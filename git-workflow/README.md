# Git & GitHub Workflow Tips

## Basic Commands
- `git init` - Initialize a new Git repository
- `git clone [url]` - Clone a repository
- `git status` - Check the status of your working directory
- `git add [file]` - Stage changes
- `git commit -m "message"` - Commit changes with a descriptive message
- `git push` - Push changes to remote
- `git pull` - Fetch and merge changes from remote

## Branching Strategy
- Create feature branches for new features: `git checkout -b feature/name`
- Keep your `main` branch stable and production-ready
- Use pull requests for code reviews
- Delete merged branches to keep the repository clean

## Best Practices
- Write clear, descriptive commit messages
- Make small, focused commits
- Use `.gitignore` to exclude unnecessary files
- Never commit sensitive information (passwords, API keys)
- Use meaningful branch names (e.g., `feature/user-authentication`)
