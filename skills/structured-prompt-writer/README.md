# Structured Prompt Writer / 结构化提示词写作器

A Claude Code skill for creating professional AI prompts with structured formats. Includes **395+ prompt templates**.

用于创建专业结构化 AI 提示词的 Claude Code 技能，内置 **395+ 提示词模板**。

## Features / 特性

- **Two Modes / 双模式支持**
  - Detailed Mode: For complex personas, expert roles, multi-turn interactions
  - Simple Mode: For single tasks, utility assistants, quick deployments
  - 详细模式：复杂角色、专家人设、多轮深度交互
  - 简单模式：单一任务、工具型助手、快速部署

- **395+ Built-in Templates / 内置模板**
  | Category | Count | Description |
  |----------|-------|-------------|
  | Structured Personas | 5 | High-quality Chinese prompts |
  | Xiaohongshu | 4 | Social commerce prompts |
  | Creative Writing | 3 | Writing templates |
  | GPT Store | 282 | OpenAI GPT Store prompts |
  | System Prompts | 101 | Claude/Cursor/Gemini tools |

- **Structured Format / 结构化格式**
  - Tree-structured knowledge frameworks (├─ └─)
  - Conditional logic flows (? triggers)
  - Visual separators and markers
  - 树形知识框架、条件逻辑流程、视觉分隔符

## Installation / 安装

### For Claude Code Users

1. Download the `.skill` file or clone this repository
2. Place in your Claude Code skills directory
3. The skill will be available when you need to create prompts

### Manual Usage

Copy the SKILL.md content as a system prompt for any LLM.

## Directory Structure / 目录结构

```
structured-prompt-writer/
├── README.md                    # This file
├── SKILL.md                     # Main skill definition
└── references/
    ├── format-templates.md      # Format templates
    ├── example-prompts.md       # Example comparisons
    ├── prompt-catalog.md        # Full prompt catalog
    └── prompts/                 # 395+ built-in prompts
        ├── personas/            # Structured personas (5)
        ├── xiaohongshu/         # Xiaohongshu series (4)
        ├── creative/            # Creative writing (3)
        ├── gpts-personas/       # GPT Store prompts (282)
        ├── system-tools/        # System prompts (101)
        │   ├── Anthropic/
        │   ├── Cursor Prompts/
        │   ├── Google/
        │   ├── Open Source prompts/
        │   └── ...
        └── awesome-chatgpt-prompts.md
```

## Quick Start / 快速开始

1. Choose a mode based on complexity
2. Reference format-templates.md for structure
3. Browse prompts/ for similar examples:
   - Learn structured format → `personas/`
   - Xiaohongshu operations → `xiaohongshu/`
   - Find specific functions → `gpts-personas/`
   - Study system prompts → `system-tools/`
4. Fill in sections following the template
5. Apply writing principles

## Writing Principles / 写作原则

| Principle | Description |
|-----------|-------------|
| 诗意开场 | Use metaphors, avoid "I am an AI assistant" |
| 人感注入 | Show personality, values, even flaws |
| 克制精准 | Concise like a manual, every word matters |
| 反AI味 | Unique voice, reject buzzwords |

## Format Symbols / 格式符号

| Symbol | Usage |
|--------|-------|
| ━━━━ | Section separator |
| ： | Requirement definition |
| ├─ └─ | Tree structure |
| ▸ | Arrow pointer |
| ▪ | List item |
| ① ② ③ | Ordered steps |
| 『』 | Emphasis title |
| 〖〗 | Protocol title |

## Included System Prompts / 包含的系统提示词

- **Anthropic**: Claude Code, Claude for Chrome
- **Code Editors**: Cursor, Windsurf, VSCode Agent
- **Open Source**: RooCode, Cline, Bolt, Codex CLI, Gemini CLI
- **AI Platforms**: Gemini, Replit, Perplexity, v0, Lovable, Devin AI

## License

MIT

## Credits

- Prompt templates inspired by [Awesome Gemini Prompts](https://github.com/langgptai/awesome-gemini-prompts)
- GPT Store prompts from community contributions
- System prompts from respective tool documentation
- Author: 云中江树 and contributors
