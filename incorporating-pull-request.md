# How to incorporate code from a pull request that hasn't been accepted by the main project yet

**Scenario:** You want to contribute to a project on GitHub. You see that a pending pull request has some excellent code that you want to use. However, that pull request has not been accepted into the original project.

Assuming the contributor created a new branch for their changes and their fork is public, here's how to get that code into your fork of the repository. 

## Using GitHub.com Web User Interface to Get Changes from a Branch

1. Create a fork of the original repository by navigating to it and clicking the "Fork" button. **DO NOT fork the other contributor's repository.**
2. Now find the pull request for the contributor whose code you want to pull into your fork, click on the branch that originated the pull request.
3. Click "New Pull Request".
4. Change the "base repository" to your fork. Maybe sure "Head" is set to the contributor's fork and the correct branch is selected.
5. Write a pull request statement
6. Submit the pull request.
7. Scroll down on the page and make sure the pull request can be merged. The changes will be merged into your main branch. But you want to work outside the main branch.  
8. Go back to the page for your fork. Create a new branch. Name this branch with the name of the new feature. The new branch should copy all code from your main branch. 
9. You can edit the code within the branch. Always work within the branch. Keep your fork and branch up to date with the original repository by synching before starting any new work. 
10. Set up GitHub pages to work with your new branch. Go the GitHub pages settings and change the source for the pages to your new branch.
11. On the main page for your repository, click the gear near the URL. Check the box that says "Use your GitHub pages site"
12. When you are ready, you can submit a pull request to the original repository.

## Worse Option: Manually Copy in Web Interface from Changes Made to a Branch
1. Fork original repository
2. Create new branch
3. Look at changes made in pull request
4. Manually copy them to your new branch.

## Acknowledgements
Some initial advice for these instructions was provided by Microsoft Copilot. All steps were edited and tested by Jonathan Farbowitz.
