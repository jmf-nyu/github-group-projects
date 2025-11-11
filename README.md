# GitHub Group Projects Guide


## Introduction
So, you want to work on a project on GitHub, but want to do it as a group. Here are some workflows for different scenarios. Whether you are contributing to an existing repository or creating a new repository makes a big difference in how you should go about things.

In every case, communication is key, make sure all group members are clear on what they are working on, otherwise you risk overwriting other peole's code or creating conflicts. It is also important to make commit messages that clearly describe the changes that were made and pull request messages that describe the changes as well.

## Creating a New Repository as a Group Project
If you are creating a new repository, you can choose one of the workflows below:

### Simpler, Less GitHub Practice
1. Designate one group member to be the "Repository Manager"
2. Repository Manager creates a new repository for the project.
3. Other group members communicate additions and edits to the repository to the Manager through means outside GitHub (Google Docs, emails, text messages, etc.).
4. Repository Manager makes these changes as commits.
5. Other group members review these commits by looking at the repository, either by looking at the code or looking at the GitHub pages site.
6. Work continues until everyone is happy with the repository.

### More Complicated, More GitHub Practice
1. Designate one group member to create/initialize the repository. We'll call this person the "Repository Manager"
2. The other group members [fork the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).
3. The other group members [create a branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) within their fork. It's probably best to name the fork with your first name. The other group members will keep their forks up to date with the original (upstream) respoitory by [synching](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) and always getting the latest changes before starting any new work.
4. Other group members will make commits to their branch of the fork.
5. When they are ready, other group members will [submit a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to the original repository. The Repository Manager will examine the pull requests and approve the ones that are ok and ask for changes for ones that are not. The Repository Manager then merges pull requests into their repository. 

**Warning**: Group members should try not to work on the same sections of files, this can cause conflicts within Git that it may not be able to resolve. 

**Note**: If the project uses GitHub Pages, make sure the settings for pages are displaying the correct fork and branch so you can actually see your changes as you make them.


## Contributing to an Existing Repository as a Group Project
There are several possible workflows for doing this. Before starting work, you'll want to look at the existing project's guidelines for contribution. For example, [the guidelines for the FFmprovisr project](https://github.com/amiaopensource/ffmprovisr?tab=readme-ov-file#how-do-i-contribute).

### Simpler, Less GitHub Practice
1. Designate one group member as the "Repository Manager"
2. Repository Manager [forks the existing repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) and [creates a new branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository). It is best practice to create a new branch when contributing to an existing project.
4. Manager keeps their fork up to date with the original (upstream) repository by [synching with it](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) before any new work is started.
5. Other group members communicate additions and edits to the repository to the Manager through means outside GitHub (Google Docs, emails, text messages, etc.).
6. Repository Manager makes these changes as commits in their branch of their fork.
7. Other group members review these commits by looking at the code or GitHub pages of the fork.
8. Work continues until everyone is happy with the changes.
9. When the changes are ready, the repository manager [submits a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) to the original (upstream) repository.

### More Complicated, More GitHub Practice
1. Each member of the group [forks the original repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).
2. Each group member [creates a branch](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) within their fork. They should name the branch with their first name.
3. Each group member makes sure to update their branch with the latest changes before they start new work.
4. Each group member works on their branch separately, making commits as they need to. This will work fine if the group is only working on existing files within the respoistory. Group members should try not to work on the same sections of files, this can cause conflicts within Git that it may not be able to resolve. If group members need to add new files, things might get more complicated.
5. When each group member is satisfied with their contribution, they make a pull request to the original repository. This will result in multiple pull requests for the repository, which is totally fine.

**Warning**: Group members should try not to work on the same sections of files, this can cause conflicts within Git that it may not be able to resolve. 

**Note**: If the project uses GitHub Pages, make sure the settings for pages are displaying the correct fork and branch so you can actually see your changes as you make them.

## Further Reading
[GitHub Guide to Contributing to Open Source](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-open-source) - has some helpful info but instructions use command line for Git.
