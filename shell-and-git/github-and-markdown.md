# GitHub and Markdown

## Markdown basics

# Heading 1

## Heading 2

**Bold text**
_Italic text_

- List item

1. Numbered item

[Link text](https://example.com)
`inline code`

## Git basics

```bash
git status
git branch
git switch main
git switch -c feature/name
git add filename
git diff --staged
git commit -m "Add session notes"
git log --oneline
```

- `git status` checks the working tree.
- `git branch` lists local branches.
- `git switch` changes branches.
- `git switch -c` creates and switches to a new branch.
- `git add` stages changes for a commit.
- `git diff --staged` reviews staged changes.
- `git commit` saves staged changes in the local repository.
- `git log --oneline` shows a compact commit history.

## GitHub: branches and pull requests

```bash
git switch -c notes/github-and-markdown
git add shell-and-git/github-and-markdown.md
git commit -m "Add GitHub and Markdown session notes"
git push -u origin notes/github-and-markdown
```

- **Branch:** An independent line of work.
- **Commit:** A snapshot of staged changes.
- **Push:** Uploads local commits to a remote repository.
- **Pull request (PR):** Proposes changes for review and merging.
- **Merge:** Integrates changes from one branch into another.

## Typical workflow

1. Start from an up-to-date `main` branch.
2. Create a new branch for the task.
3. Make changes and review them with `git diff`.
4. Stage the relevant files and commit with a descriptive message.
5. Push the branch to GitHub.
6. Open a pull request targeting `main`.
7. Review feedback, make changes if necessary, and push again.
8. Merge the approved pull request.
9. Switch back to `main` and run `git pull`.
10. Delete the feature branch when it is no longer needed.

## Useful reminders

- Run `git status` before and after important operations.
- Stage only the files relevant to the task.
- Use commit messages that describe the changes.
- Local and remote branches are separate.
- `git push -u origin branch-name` sets the upstream branch for future pushes.
