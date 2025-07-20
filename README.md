# Introduction

TODO: This project is aimed at developing a merged an very simplified CBS

## Getting Started

TODO: Prerequisites:

1. Business Central (Saas)
2. VS Code

## Build and Test

TODO: Publish to your local system for testing, Only Project Technical Lead will publish to the server.

## Contribute

TODO: In case of any updates create a pull request and send the request to Project Technical Lead for approval before merging the changes.

If you want to learn more about Github Commands then refer the following [guidelines](https://education.github.com/git-cheat-sheet-education.pdf). You can also learn more about Azure Devops and AL Development:

- [Introduction to Azure DevOps](https://learn.microsoft.com/en-us/training/modules/get-started-with-devops)
- [DevOps tutorial—an introduction](https://azure.microsoft.com/en-us/solutions/devops/tutorial/#understanding)
- [AL Development Environment](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-reference-overview)

## GIT COMMANDSpull

1. Always work from development branch.
     After changes checkout to a new branch. [git checkout -b "new-branch-name"]
     Stage your changes. [git add .]
     Commit the changes with a message [git commit -m "new-branch-name"]
     Rebase from the development branch. [git pull --rebase origin development]
    **In case of Conflict**

## Solve the conflict

        I.  [git add .]
        II.  [git commit -m "commit message"]
        III. [git rebase --continue]
     Pushing the changes to DevOps. [git push --set-upstream origin <new-branch-name>]
2). Creating a pull request from Azure DevOps site to merge the changes.
     Click the Azure DevOps link to complete the pull request.
3. After a successful push check back to development.
     [git checkout development]
     [git pull]
