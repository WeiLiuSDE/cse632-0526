# Assignment 07: Git Workflow
# Assignment 07: Git Workflow

## Student Name
Wei Liu

## Repository
cse632-0526

## Branch Name
feature/wei-liu-assignment-07

## Commands Practiced
- git clone
- git remote -v
- git config user.name
- git config user.email
- git checkout -b
- git status
- git add
- git diff --staged
- git commit
- git push
- git fetch
- git merge
- git log
- git rev-parse HEAD

## Directories Created
- assignment-07/
- assignment-08/
- final_project/

## Git Remote Output
origin	https://github.com/WeiLiuSDE/cse632-0526.git (fetch)
origin	https://github.com/WeiLiuSDE/cse632-0526.git (push)

## Git Status Output
On branch feature/wei-liu-assignment-07
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   assignment-07/wei-liu-git-workflow.md

## Pull Request URL
https://github.com/WeiLiuSDE/cse632-0526/pull/1

## Latest Commit Hash
0988f0153d874e14175a08b15afa9548835b6d0a

## Merge Conflict Summary
I created the merge conflict by creating two separate branches, feature/readme-conflict-a and feature/readme-conflict-b, and editing the exact same first line of the README.md file in both. After pushing and merging Branch A into main via a pull request, I fetched those updates and attempted to merge them into my local Branch B. Because both branches altered the same line differently, Git could not automatically reconcile the changes, which triggered the conflict. To resolve it, I opened the file in my text editor, deleted the Git conflict markers (<<<<<<<, =======, >>>>>>>), and updated the line to the required text: # CSE632 Assignment 07 Git Practice. I then staged the file and committed the resolution to complete the merge.

## Reflection
This assignment provided valuable hands-on experience with a complete Git workflow, reinforcing how each command contributes to safe version control. I learned that branches are essential for isolating new work, ensuring the main codebase remains stable while features are developed. Opening a pull request highlighted the collaborative aspect of Git, demonstrating how code can be formally reviewed and discussed before it is integrated. Additionally, intentionally causing and fixing a merge conflict demystified a very common developer hurdle. It showed that when Git cannot automatically merge files, it clearly marks the overlapping code and relies on the developer to manually dictate the final outcome. Overall, walking through these steps sequentially has given me practical experience in managing repositories, tracking changes, and resolving integration issues.