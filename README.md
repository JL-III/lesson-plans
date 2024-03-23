# lesson-plans
A centralized repo for lesson plans


## Download git
To download git, go to the following link and download the version that is appropriate for your operating system:
https://git-scm.com/downloads

## Clone the repository
To clone the repository, open a terminal and navigate to the directory where you would like to store the repository. Then run the following command:
```
git clone git@github.com:JL-III/lesson-plans.git
```
keep in mind that the repository you just cloned is a copy of the repository on github. If you would like to make changes to the repository, you will need to create a branch. To create a branch, run the following command:
```
git checkout -b <branch-name>
```
Replace `<branch-name>` with the name of the branch you would like to create. Once you have created a branch, you can make changes to the repository. To push your changes to the repository, run the following command:
```
git add -A
git commit -m "<commit-message>"
git push --set-upstream origin <branch-name>
```