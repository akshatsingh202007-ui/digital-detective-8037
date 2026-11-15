# Mission 6 — Git and GitHub

## 1. Task / objective

The objective was to understand Git and GitHub, practise the basic Git workflow, create a branch, and open a Pull Request.

## 2. Work completed

- Checked repository status and reviewed commit history.
- Created a branch named `update-about`.
- Added a **My Learning** section to the root README.
- Committed and pushed the changes.
- Created Pull Request #1 from `update-about` into `master`.
- The Pull Request is open and has not been merged.

## 3. Commands / tools used

| Command | Purpose |
|---|---|
| `git status` | Checks repository status and file changes. |
| `git add README.md` | Stages the selected file. |
| `git commit -m "message"` | Saves staged changes as a commit. |
| `git log` | Displays commit history. |
| `git branch update-about` | Creates a new branch. |
| `git checkout update-about` | Switches to another branch. |
| `git push -u origin update-about` | Publishes the branch to GitHub. |

GitHub was used to create and review the Pull Request.

## 4. My understanding

Git keeps track of changes made to a project, while GitHub allows us to host and collaborate on Git repositories.

Staging and committing are different. `git add` selects changes for the next commit, whereas `git commit` saves those staged changes in the repository history.

A branch lets us work on changes separately. A Pull Request allows changes to be reviewed before they are merged.

## 5. Git command glossary

| Operation | Explanation |
|---|---|
| `git init` | Initialises a new Git repository. |
| `git status` | Shows the current state of the repository. |
| `git add` | Stages selected changes. |
| `git commit` | Saves staged changes in the repository history. |
| `git log` | Shows previous commits. |
| `git branch` | Lists branches or creates a new branch. |
| `git checkout` | Switches to another branch. |
| `git push` | Sends local commits to a remote repository. |
| `git pull` | Retrieves and integrates changes from a remote repository. |

## 6. Difficulties faced

Initially, there were no changes to stage in the root README, so Git reported that there was nothing to commit.

## 7. How I resolved them

I added the required My Learning section to the root README while on the `update-about` branch. Git then detected the change, and I was able to stage, commit and push it.

## 8. Evidence / files

- Root `README.md` — My Learning section.
- `mission-06-git-github/README.md` — Mission documentation.
- GitHub Pull Request #1 — Add my learning summary.

## 9. Commit details

- Branch: `update-about`
- Learning update commit: `0b4960c` — Add my learning summary
- Mission documentation commit: To be added.
- Pull Request: #1
- Pull Request status: Open, not merged.
