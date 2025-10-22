# Time Travel Magazine

I am learning about Git workflows, branching strategies, and collaborative development practices through creating a digital magazine (zine) about time travel concepts.

## .gitignore Patterns
- `*.log` and `target/`: Excludes logs and build artifacts that are generated during development
- `.DS_Store` and IDE files: Prevents OS-specific and editor-specific files from cluttering the repository

## Branch Strategy
- `main`: Production-ready content
- `author/idea-sprint`: For drafting and creating new content ideas
- `editor/review`: For reviewing and refining content before merging to main
