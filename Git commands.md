# Basic Git Commands

## check status of current branch

`git status`

## Create & Clone

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **create new** repository                         | `git init`                                 |
| **clone local** repository                        | `git clone /path/to/repository`            |
| **clone remote** repository                       | `username@host:/path/to/repository`        |

### Example:
> `git clone https://github.com/OWNER/REPOSITORY.git`

## Add & Remove

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **add** changes to INDEX                          | `git add <filename>`                       |
| **add all** changes to INDEX                      | `git add *`                                |
| **remove/delete**                                 | `git rm <filename>`                        |

### Example:
> `git add .`

## Commit & Sync

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| commit changes                                    | `git commit -m "commit message"`           |
| push changes to remote repository                 | `git push origin main"`                    |
| **connect** local repository to remote repository | `git remote add origin <server>`           |
| **update** local repository with remote changes   | `git pull`                                 |

## Branches

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **create** new branch                             | `git checkout -b <branch>`                 |
| **switch to** main branch                         | `git checkout main`                        |
| **delete** branch                                 | `git branch -d <branch>`                   |
| **push branch** to remote repository              | `git push origin <branch>`                 |


## Merge

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **merge changes** from another branch             | `git merge <branch>`                       |
| **view changes** between two branches             | `git diff <source_branch> <target_branch>` |

### Example:
> `git diff main header`

## Tagging

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **create tag**                                    | `git tag <tag> <commit ID>`                |
| **get commit IDs**                                | `git log`                                  |


## Restore

| Description                                       | Command                                    |
| :------------------------------------------------ | :----------------------------------------- |
| **replace** working copy with latest from HEAD    | `git checkout -- <filename>`               |


git remote -v

git remote set-url origin https://github.com/OWNER/REPOSITORY.git