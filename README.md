## Learning Git

![Git](https://user-images.githubusercontent.com/26144363/178100171-b0e774a4-1c7a-419d-a0ea-1d523a3929d8.png)

## Git Workflow
![git working](https://user-images.githubusercontent.com/26144363/179404381-b1c60216-36e5-4aeb-9311-2102723206c8.jpg)


## What is Gitflow and how it Works?
The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects. Gitflow is ideally suited for projects that have a scheduled release cycle.

![git-flow1](https://user-images.githubusercontent.com/26144363/179404550-d4f7c353-c061-4d63-9cb8-1d5914bde450.jpg)


## Some key takeaways to know about Gitflow are:
The workflow is great for a release-based software workflow.
Gitflow offers a dedicated channel for hotfixes to production.
The overall flow of Gitflow is:
A develop branch is created from master.
A release branch is created from develop.
Feature branches are created from develop.
When a feature is complete it is merged into the develop branch.
When the release branch is done it is merged into develop and master.
If an issue in master is detected a hotfix branch is created from master.
Once the hotfix is complete it is merged to both develop and master
Gitflow with pull request:
Pull requests let you tell others about changes you’ve pushed to a branch in a repository. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.



## How the pull request works with Gitflow?
Adding pull requests to the Gitflow Workflow gives developers a convenient place to talk about a release branch or a maintenance branch while they’re working on it.

![pull-request](https://user-images.githubusercontent.com/26144363/179404620-ca12aec3-10fb-4e82-8f82-c14e68d4db86.jpg)


A developer simply files a pull request when a feature, release, or hotfix branch needs to be reviewed, and the rest of the team will be notified.

Features are generally merged into the develop branch, while release and hotfix branches are merged into both develop and master. Pull requests can be used to formally manage all of these merges.

The overall flow of Gitflow with Pull Request is:
A developer creates the feature, release or hotfix in a dedicated branch in their local repo.
The developer pushes the branch to a public remote repository.
The developer files a pull request via remote server.
The rest of the team reviews the code, discusses it, and alters it.
The project maintainer merges the feature, release or hotfix into the official repository and closes the pull request.

## Diffrence between the pull request fetch?
