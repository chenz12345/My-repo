# Git Hooks

These hooks are used to protect the repository:

- **pre-commit**: Blocks temp/log files and debug comments.
- **prepare-commit-msg**: Adds the Linux username to commit messages.
- **pre-push**: Prevents pushing large files >1MB.
- **post-merge**: Runs system health checks after merges.

To activate:
Copy files into `.git/hooks/` and make them executable.
