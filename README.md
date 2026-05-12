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

## Quick Start

```bash
# Clone the repo
git clone https://github.com/YourOrg/recognize-exclusion-windows-agent.git
cd recognize-exclusion-windows-agent

# Launch Copilot CLI
copilot

# Select the model (recommended: Opus 4.6)
/model
# Choose claude-opus-4.6

# Start a conversation
# Example: "I want to analyze the Windows 11 Snap Layouts feature"
```

The agent automatically loads its instructions from `CLAUDE.md` and `.github/copilot-instructions.md`.

## Repository Structure

```
├── CLAUDE.md                           # Agent identity and core instructions
├── README.md                           # This file
├── .github/
│   └── copilot-instructions.md         # Copilot CLI-specific configuration
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
