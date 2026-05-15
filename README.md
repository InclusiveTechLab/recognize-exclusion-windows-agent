# Recognize Exclusion — Windows 11 Agent

An AI-powered tool that helps you find accessibility gaps in Windows 11 features. You describe a feature, and it identifies 28+ ways that feature might exclude people with disabilities.

## What Is This?

This is a **custom agent** for [GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) — a terminal-based AI assistant made by GitHub. When you run this agent, it becomes a specialist in inclusive design, helping you think through how a Windows 11 feature might unintentionally exclude people who use assistive technologies, have limited motor control, are blind or deaf, or experience cognitive differences.

### What it does in practice

You have a conversation with the agent. It works in 3 steps:

1. **You describe a feature** — for example, "the Windows 11 Snap Layouts feature"
2. **It asks clarifying questions** — up to 3 questions to understand the feature better
3. **It produces a structured report** — at least 28 specific exclusions, each explaining who is excluded, what they're trying to do, and why the feature fails them

Each exclusion looks like this:

> **Pattern:** Hover-triggered layout grid  
> **User action:** Trying to choose a window layout  
> **Exclusion type:** Operable  
> **Explanation:** Someone using eye-gaze input cannot reliably hover over a small target long enough to trigger the layout options, because the hover zone is too small and the dwell time too short.

## What You Need Before Starting

Before you can use this agent, you need three things:

### 1. A GitHub account with Copilot access

You need a [GitHub Copilot subscription](https://github.com/features/copilot/plans). If your organization provides Copilot, ask your admin to confirm that **CLI access** is turned on for your account.

### 2. GitHub Copilot CLI installed on your computer

This is a program you install once. Here's how:

**On Windows** — Open PowerShell or Terminal and run:
```
winget install GitHub.Copilot
```

**On macOS or Linux** — Open Terminal and run:
```
brew install copilot-cli
```

**If neither works** — You can also install it with npm (requires Node.js):
```
npm install -g @github/copilot
```

> 💡 **Not sure if it worked?** After installing, type `copilot --version` in your terminal. If you see a version number, you're good.

### 3. Git installed on your computer

You need Git to download this agent. Most computers have it already. To check, type `git --version` in your terminal. If you see a version number, you have it. If not:

- **Windows:** Download from [git-scm.com](https://git-scm.com/download/win) or run `winget install Git.Git`
- **macOS:** It's included with Xcode Command Line Tools. Run `xcode-select --install`
- **Linux:** Run `sudo apt install git` (Ubuntu/Debian) or `sudo dnf install git` (Fedora)

## How to Set Up the Agent (One-Time Steps)

You only need to do these steps once.

### Step 1: Download the agent to your computer

Open a terminal and run these two commands:

```
git clone https://github.com/InclusiveTechLab/recognize-exclusion-windows-agent.git
cd recognize-exclusion-windows-agent
```

The first command downloads the agent files. The second command moves you into the agent's folder.

> 💡 **Where does it go?** It creates a folder called `recognize-exclusion-windows-agent` wherever your terminal is currently pointing (usually your home directory or Documents).

### Step 2: Log in to GitHub (first time only)

Launch the CLI and log in:

```
copilot
```

If this is your first time, it will ask you to run `/login`. Type that command and follow the on-screen instructions — it will open a browser window where you authenticate with your GitHub account.

## How to Use the Agent (Every Time)

### Step 1: Open a terminal in the agent folder

Navigate to where you downloaded the agent:

```
cd recognize-exclusion-windows-agent
```

> 💡 **Why do I need to be in this folder?** The agent's instructions and knowledge base are stored here. Copilot CLI reads them automatically when you're in this folder.

### Step 2: Start the CLI

```
copilot
```

### Step 3: Select the agent

Type this command inside the CLI:

```
/agent
```

Use your arrow keys to highlight **recognize-exclusion** and press Enter.

> 💡 **Shortcut:** You can skip steps 2-3 by running `copilot --agent=recognize-exclusion` directly from your terminal.

### Step 4: Select the best model (recommended)

Type this command inside the CLI:

```
/model
```

Use your arrow keys to select **claude-opus-4.6** and press Enter. This model produces the best results for this agent. If it's not available, any Claude model will work.

### Step 5: Start your analysis

Type a message describing the Windows 11 feature you want to analyze:

```
I want to analyze the Windows 11 Start Menu
```

The agent will guide you through the rest — asking questions, then producing the exclusion report.

## Tips

- **Say "start over"** at any time to analyze a different feature
- **You must be in the agent's folder** for it to work — if you get generic Copilot responses instead of inclusive design analysis, you're probably in the wrong directory
- **Use `/help`** inside the CLI to see all available commands
- **Copy the output** — the exclusion report is designed to be pasted into documents, tickets, or design reviews

## How the Agent Is Structured

You don't need to understand this to use the agent, but if you're curious:

```
recognize-exclusion-windows-agent/
├── CLAUDE.md                              ← The agent's core instructions
├── README.md                              ← This file
├── .github/
│   ├── copilot-instructions.md            ← Tells the CLI which model to use
│   └── agents/
│       └── recognize-exclusion.agent.md   ← Agent profile (makes it show up in /agent)
└── reference/
    ├── windows-exclusions.md              ← 144 exclusion patterns by Windows feature
    └── icf-exclusions-windows.md          ← 153 exclusion patterns by disability category
```

The `reference/` files are the agent's knowledge base — curated exclusion patterns from the Inclusive Tech Lab that it draws on when generating your report.

## Troubleshooting

| Problem | Solution |
|---------|----------|
| `copilot` command not found | Reinstall Copilot CLI (see installation steps above) |
| Agent gives generic responses, not exclusion analysis | Make sure you're in the `recognize-exclusion-windows-agent` folder |
| `/agent` doesn't show "recognize-exclusion" | Make sure you're in the agent folder, not a parent directory |
| "Not logged in" error | Run `/login` inside the CLI and follow the prompts |
| Model not available | Use `/model` and pick any available Claude model |

## Background

This agent is part of the [Inclusive Tech Lab](https://www.microsoft.com/inclusive-tech-lab)'s inclusive design toolkit. It puts the "Recognize Exclusion" principle from [Microsoft Inclusive Design](https://inclusive.microsoft.design/) into practice for Windows product teams.

## Contributing

Want to improve the exclusion patterns? Edit the files in `reference/`, keep the existing heading structure, and submit a pull request.
