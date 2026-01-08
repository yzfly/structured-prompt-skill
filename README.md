# Structured Prompt Writer

A comprehensive prompt engineering reference library and Claude Code skill for designing high-quality AI prompts.

## Overview

This repository provides:

1. **Claude Code Skill** - A ready-to-use skill that helps you write structured, professional prompts
2. **Prompt Reference Library** - Curated collection of 300+ prompts from various AI tools and models

## Quick Start

### Install the Skill

```bash
# Download and install the skill
cp structured-prompt-writer.skill ~/.claude/skills/
```

Or manually import in Claude Code:
```
/skill import structured-prompt-writer.skill
```

### Use the Skill

Once installed, the skill provides guidance for writing prompts with:
- Structured formats (persona, context, task, output format)
- Best practices from industry-leading AI tools
- Chinese and English prompt patterns

## Repository Structure

```
.
├── structured-prompt-writer.skill  # Packaged skill file
├── skills/
│   └── structured-prompt-writer/   # Skill source files
│       ├── SKILL.md                # Main skill definition
│       ├── README.md               # Skill documentation
│       └── references/             # Reference materials
│           ├── prompt-catalog.md   # Categorized prompt index
│           ├── format-templates.md # Prompt format templates
│           ├── example-prompts.md  # Example prompts
│           └── prompts/            # Source prompt collection
├── prompts/                        # Additional prompt resources
├── CLAUDE.md                       # Claude Code configuration
└── GEMINI.md                       # Gemini configuration
```

## Prompt Collection

The reference library includes prompts from:

### System Tool Prompts
- **Anthropic**: Claude Code, Claude for Chrome, Sonnet 4.5
- **OpenAI**: VSCode Agent, Codex CLI
- **Google**: Gemini CLI, AI Studio, Antigravity
- **Development Tools**: Cursor, RooCode, Cline, Bolt
- **AI Platforms**: v0, Lovable, Leap.new, Perplexity

### Persona Prompts (Chinese)
- Historical figures and thought leaders
- Creative writing assistants
- Domain experts (palm reading, product design, etc.)

### GPT Store Collection
- 280+ leaked GPT prompts
- Various use cases and interaction patterns

## Prompt Format Patterns

### Structured Chinese Prompts
```markdown
---
needs: [requirements]
model: [recommended model]
author: [author name]
version: [version number]
---

# [Title]

## 思维内核 (Core Thinking)
[Core principles and approach]

## 审美与禁忌 (Aesthetics & Taboos)
[Style guidelines and restrictions]

## 交互逻辑 (Interaction Logic)
[Conversation flow and response patterns]

## 初始化 (Initialization)
[Opening message template]
```

### GPT-Style Prompts
```markdown
# [Name]

You are [persona description]...

## Commands
- /command1 - [description]
- /command2 - [description]

## Knowledge Files
- file1.md
- file2.json
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new prompts
- Improving existing prompts
- Reporting issues

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

## Acknowledgments

- Prompt collections from various open-source projects
- Community contributions and feedback
- Claude Code team for the skill framework

## Related Resources

- [Claude Code Documentation](https://docs.anthropic.com/claude-code)
- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/claude/docs/prompt-engineering)
- [LangGPT](https://github.com/langgptai/langgpt) - Structured prompt framework
