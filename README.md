# github-group-projects
A Guide to Group Projects on GitHub

## Introduction
So, you want to work on a project on GitHub, but want to do it as a group. Here are some workflows for different scenarios. Whether you are contributing to an existing repository or creating a new repository makes a big difference in how you should go about things.

### Creating a New Repository

#### Simple, Less GitHub Practice
1. Designate one group member to be the "Repository Manager"
2. Repository Manager creates a new repository for the project.
3. Other group members communicate additions and edits to the repository to the Manager through means outside GitHub (Google Docs, emails, text messages, etc.).
4. Repository Manager makes these changes as commits.
5. Other group members review these commits by looking at the repository.
6. Work continues until everyone is happy with the repository. 

#### More Complicated, More GitHub Practice
If you are creating a new repository, you will do the following
1. Designate one group member to create/initialize the repository. We'll call this person the "Repository Manager"
2. Other group members fork the repository.
3. Other group members create a branch within their fork. It's probably best to name the fork with your first name. They will keep that fork up to date with the original (upstream) respoitory, always getting the latest changes before starting any new work.
4. Other group members will make committs to their branch of the fork.
5. When they are ready, other group members will submit a pull request to the original repository. The Repository Manager will examine the pull requests and approve the ones that are ok. The Repository Manager then merges pull requests into their repository. 
Note: Group members should try not to work on the same sections of files, this can cause conflicts within Git that it may not be able to resolve.


### Contributing to an Existing Repository
There are several possible workflows for doing this.

#### Simple, Less GitHub Practice
1. Designate one group member as the "Repository Manager"
2. Repository Manager forks the existing repository and creates a new branch.
4. Other group members communicate additions and edits to the repository to the Manager through means outside GitHub (Google Docs, emails, text messages, etc.).
5. Repository Manager makes these changes as commits in the branch of their fork.
6. Other group members review these commits by looking at the fork.
7. Work continues until everyone is happy with the changes.
8. When the changes are ready, the repository manager submits a pull request to the original (upstream) repository.

#### More Complicated, More GitHub Practice
1. Each member of the group forks the original repository
2. Each group member creates a branch within their fork. They should name the branch with their first name.
3. Each group member makes sure to update their branch with the latest changes before they start new work.
4. Each group member works on their branch separately, making commits as they need to. This will work fine if the group is only working on existing files within the respoistory. Group members should try not to work on the same sections of files, this can cause conflicts within Git that it may not be able to resolve. If group members need to add new files, things might get more complicated.
5. When each group member is satisfied with their contribution, they make a pull request to the original repository. This will result in multiple pull requests for the repository, which is totally fine. 
