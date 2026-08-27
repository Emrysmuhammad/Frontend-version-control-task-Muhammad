# Frontend Version Control Task

## Project Purpose
This project demonstrates Git and GitHub workflows including:
- Repository initialization and management
- Creating and working with branches
- Making meaningful commits
- Creating and reviewing pull requests
- Merging changes
- Reverting commits
- Branch renaming and fetching

## Project Structure

### Branches
- **main** - Production branch with final, reviewed code
- **feature-header** - Feature branch for header component
- **feature-footer** - Feature branch for footer component
- **feature-cards** (renamed) - Feature branch for card components

### Files
- `index.html` - Main HTML page
- `styles.css` - Styling for the project
- `README.md` - Project documentation

## Commits Made

### Feature-Header Branch
1. "Add basic HTML structure for header"
2. "Style header with CSS"
3. "Add responsive design to header"

### Feature-Footer Branch
1. "Create footer HTML structure"
2. "Add footer styling"
3. "Add social media links to footer"

### Feature-Cards Branch
1. "Create card component HTML"
2. "Style card component"
3. "Add hover effects to cards"

## Pull Requests & Merging
- PR #1: Merged feature-header → main
- PR #2: Merged feature-footer → main
- PR #3: Merged feature-cards → main

## Git Commands Used
- `git clone` - Clone repository
- `git checkout -b` - Create and switch branches
- `git add .` - Stage changes
- `git commit -m` - Create commits
- `git push origin` - Push to GitHub
- `git pull origin` - Pull from GitHub
- `git merge` - Merge branches
- `git revert` - Revert commits
- `git branch -m` - Rename branches
- `git fetch` - Fetch updates

## Commit History & Reversion
- Created intentional error commit
- Demonstrated reversion using `git revert`
- Showed how to undo changes while maintaining history

## Lessons Learned
1. **Branching is essential** - Keeps main branch clean and allows parallel work
2. **Commit messages matter** - Clear messages help team understand changes
3. **Pull requests enable review** - Quality control through code review
4. **Git history is valuable** - Can revert errors and understand project evolution
5. **Collaboration workflow** - Fetch, branch, commit, push, review, merge

## How to Use This Repository
1. Clone the repository
2. Explore different branches with `git checkout branch-name`
3. View commit history with `git log`
4. Check pull request history in GitHub interface

## Screenshots
[Will add merged PR screenshots]

**Created:** August 2024  
**By:** [Muhammad Rabiu]  
**Internship:** FlexiSAF Frontend Development