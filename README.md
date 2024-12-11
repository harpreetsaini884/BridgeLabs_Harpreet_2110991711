# Monday

# Setup
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Initialize and clone repositories
git init
git clone <repo-url>

# Status, add, commit
git status
git add <file-name>
git commit -m "Your message"

# Branching
git branch <branch-name>
git checkout <branch-name>
git checkout -b <new-branch-name>

# Push and pull
git push origin <branch-name>
git pull origin <branch-name>

# View commits
git log
git log --oneline

# Undo changes
git reset <file-name>
git checkout -- <file-name>

# Delete files
git rm <file-name>
git rm --cached <file-name>

# Remotes
git remote add origin <repo-url>
git remote -v

