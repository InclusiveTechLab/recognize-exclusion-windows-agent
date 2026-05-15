# Recognize Exclusion — Windows 11 Agent

A GitHub Copilot CLI agent that applies Microsoft Inclusive Design's **"Recognize Exclusion"** principle to Windows 11 features. Given a Windows feature description, it produces at least 28 structured exclusions across disability categories and assistive technology mismatches.

## What It Does

This agent guides you through a 3-step conversation:

1. **Describe** — You describe a Windows 11 feature you want to analyze
2. **Clarify** — The agent asks up to 3 clarifying questions
3. **Generate** — The agent produces 28+ exclusions covering vision, hearing, motor, cognition, and assistive technology mismatches

Each exclusion follows a structured format:
- **Pattern** — The UI pattern or interaction being analyzed
- **User action** — What the user is trying to do
- **Exclusion type** — Perceivable, Operable, Understandable, or Robust
- **Explanation** — The specific disability or assistive technology mismatch

## Prerequisites

- [GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli) installed
- An active [Copilot subscription](https://github.com/features/copilot/plans)
- Access to Claude Opus 4.6 model (recommended)

## Getting Access

This is a private repository. To get access:

1. **Request an invitation** — Ask the repo owner to add you as a collaborator.
2. **Accept the invitation** — Check your email or visit [github.com/notifications](https://github.com/notifications) and accept the repository invitation.
3. **Clone the repo** — Once accepted, you can clone and use the agent (see Quick Start below).

If you need access, contact the repo owner on Teams or email.

## Quick Start

### 1. Install GitHub Copilot CLI

If you haven't installed it yet, pick the method for your platform:

**Windows (WinGet):**
```bash
winget install GitHub.Copilot
```

**macOS / Linux (Homebrew):**
```bash
brew install copilot-cli
```

**Any platform (npm):**
```bash
npm install -g @github/copilot
```

> **Requirement:** You need an active [GitHub Copilot subscription](https://github.com/features/copilot/plans). If your organization provides Copilot, check with your admin that CLI access is enabled.

### 2. Clone this repo and open a terminal in it

```bash
git clone https://github.com/InclusiveTechLab/recognize-exclusion-windows-agent.git
cd recognize-exclusion-windows-agent
```

### 3. Launch the CLI

```bash
copilot
```

On first launch you'll see an animated banner. If you're not already logged in to GitHub, the CLI will prompt you to run `/login` — follow the on-screen instructions to authenticate with your GitHub account.

### 4. Select the model

Once you're inside the CLI, type:

```
/model
```

Use the arrow keys to select **claude-opus-4.6** and press Enter. This is the recommended model for this agent. If Opus 4.6 isn't available to you, any Claude model will work.

### 5. Select the agent

Type `/agent` and select **recognize-exclusion** from the list. This loads the agent with its specialized instructions and tools.

Alternatively, you can reference the agent directly in a prompt:

```
Use the recognize-exclusion agent to analyze the Windows 11 Snap Layouts feature
```

Or launch it from the command line:

```bash
copilot --agent=recognize-exclusion
```

### 6. Start a conversation

Just type a message describing the Windows 11 feature you want to analyze. For example:

```
I want to analyze the Windows 11 Snap Layouts feature
```

The agent will walk you through its 3-step workflow:
1. It will ask you to describe the feature in more detail
2. It will ask up to 3 clarifying questions
3. It will produce 28+ structured exclusions

### How it works

When you launch `copilot` inside this repo, it automatically reads the instruction files and reference data. There are two ways the agent loads:

- **Via `/agent`** — Selects the custom agent profile in `.github/agents/recognize-exclusion.agent.md`, which specifies the model, tools, and behavior.
- **Via direct chat** — The CLI reads `CLAUDE.md` and `.github/copilot-instructions.md` from the current directory, giving the same behavior without explicit agent selection.

Both paths use the same reference data in `reference/`. You don't need to configure anything beyond cloning the repo.

### Tips

- **Stay in the repo directory** — the CLI loads instructions from the current working directory.
- **Use `/agent`** to select the Recognize Exclusion agent explicitly.
- **Use `/model`** at any time to switch models (Claude Opus 4.6 is recommended).
- **Say "start over"** to reset and analyze a different feature.
- **Use `/help`** to see all available commands.
- **Use `/diff`** if the agent makes any file changes you want to review.

## Repository Structure

```
├── CLAUDE.md                           # Agent identity and core instructions
├── README.md                           # This file
├── .github/
│   ├── copilot-instructions.md         # Copilot CLI-specific configuration
│   └── agents/
│       └── recognize-exclusion.agent.md # Custom agent profile (selectable via /agent)
└── reference/
    ├── windows-exclusions.md           # 144 Windows 11 UI pattern exclusions
    └── icf-exclusions-windows.md       # 153 ICF functional classification exclusions
```

## Reference Data

The `reference/` directory contains the agent's knowledge base, converted from the Inclusive Tech Lab's HTML reference material:

- **windows-exclusions.md** — Exclusion patterns organized by Windows 11 UI feature (Taskbar, File Explorer, Settings, Snap Layouts, Start Menu, etc.)
- **icf-exclusions-windows.md** — Exclusion patterns organized by ICF (International Classification of Functioning) body function and activity/participation categories

## Contributing

To add or update exclusion patterns:

1. Edit the relevant file in `reference/`
2. Follow the existing Markdown structure (## heading for pattern, ### for exclusion type, bullet list for items)
3. Submit a pull request

## Background

This agent is part of the [Inclusive Tech Lab](https://www.microsoft.com/inclusive-tech-lab)'s inclusive design toolkit. It operationalizes the "Recognize Exclusion" principle from [Microsoft Inclusive Design](https://inclusive.microsoft.design/) for Windows product teams.
