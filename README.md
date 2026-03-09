# Mistral Vibe Configs

A reusable configuration for Mistral Vibe with enhanced system prompts and integrated tools for complex task planning.

## Features

- **Better System Prompt**: Optimized for clarity and efficiency in task execution.
- **Integrated MCP Server**: Uses [mcp-complex_plans](https://github.com/TuchSoft/mcp-complex_plans/) for advanced thinking and complex task management.
- **Forbidden Git Commands**: Prevents accidental git operations to ensure safety.

## Installation

1. Clone this repository or copy the configs to your `.vibe` directory:

```bash
git clone https://github.com/TuchSoft/mistral-vibe-cli-config ~/.vibe
```



## Configuration Details

### System Prompt
The system prompt is optimized for:
- Clear and concise task execution
- Efficient use of tools and resources
- Minimal verbosity

### Addressing Common Issues
This configuration aims to resolve the following issues:
- **Overconfidence**: Ensures thorough verification before proceeding with tasks.
- **Stale File Content**: Always re-reads files from disk to avoid using outdated in-memory content.
- **Generic Responses**: Avoids repetitive phrases like "I have understood the issue now" and focuses on actionable steps.
- **Git Interactions**: Prevents unauthorized git operations unless explicitly requested.
- **Duplicate Logic**: Checks for existing logic or files before creating new ones to avoid redundancy.
- **Task Efficiency**: Reduces trial and error by leveraging the right tools, libraries, or components for the environment (e.g., React-based solutions for React projects).
- **Chain of Thought**: Uses an internal chain of thought for better reasoning and problem-solving.
- **Multi-File Edits**: Ensures all parts of a task are addressed and verified before completion.
- **File Reading**: Reads entire files or relevant portions to avoid missing context, especially in cases like mismatched tags.
- **Concise Responses**: Provides brief and direct answers for simple questions in chat mode.

### MCP Server Integration
The [mcp-complex_plans](https://github.com/TuchSoft/mcp-complex_plans/) server is integrated for:
- Complex task planning
- Sequential thinking and reasoning
- Dynamic problem-solving

### Forbidden Git Commands
To prevent accidental operations, the following git commands are forbidden:
- `git commit`
- `git push`
- `git reset`
- `git checkout`

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
