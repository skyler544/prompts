## Purpose
A lightweight collection of plain-text prompts for LLM code assistants. Store and share small, composable prompts intended to be loaded by tooling or scripts.

## Organization / Naming
- Prompts live in folders that act as namespaces.
- Files follow the namespace/preset.md convention (e.g., php/plan.md).
- Each file is written in Markdown and represents a single prompt or preset.
- The prompts are designed to be modular and potentially combinable.

## Loading convention
Treat paths as "namespace/preset.md". For example:
- php/plan.md → namespace: "php", preset: "plan"
Tooling can load prompts by combining the folder name (namespace) and filename (preset) to pick the correct prompt.

## Contributing
Add plain-text .md files under a new or existing namespace. Keep prompts focused and reusable.

## License
MIT License
