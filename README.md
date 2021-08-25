# how-to-contribute
How to do a contribution to an Open Source projects
----------------------------------------------------

1. Step 1: Find a project you want to contribute to.

2. Step 2: Fork the repository. Once you’re there, click the “Fork” button.
   This will copy the whole project under your GitHub user.
   The link will look like this https://github.com/<YourUsername>/git-repo.

3. Step 3: Clone the repository. Open your terminal, and run the following command:
   git clone https://github.com/<YourUsername>/git-repo.git
   This will create a local copy of the repository.

4. Step 4: Create a new remote for the upstream repository.
   For this we will use the following command:
   git remote add upstream https://github.com/repo-owner-username/git-repo

5. Step 5: Create a new branch.
   We can do this by running the command:

   // git checkout -b my-branch

   This will create a new branch, and switch to it.

6. Step 6: Add some code.
   Now, the time has come, we actually add some code. 😊
   After adding the changes, you can check them by running git status.
   If everything is as expected, we can add the code to the staging area:

   // git add .

7. Step 7: Commit your changes.
   This is the last step before pushing the code to the repository.
   Run the command:

   // git commit -m "Adding an awesome feature to my-branch"

8. To push the current branch and set the remote as upstream, use

    git push --set-upstream origin mugisha-branch

•. Step 8: Push the changes to your repository.

   Finally, we’re ready to push the changes.
   git push is the command we need in this case. Let’s run it:

   // git push -u origin my-branch

9. Step 9: Create a pull request.

   Once we pushed the changes to our repository, we are ready to open the pull request.
   Go back to your repository and click on the “Compare and Pull Request” button.
   If everything went OK, the maintainer of the repository will merge your pull request.




Quick recap:

1. Find a project you want to contribute to.
2. Fork the repo.
3. Clone the repository.
4. Create a new remote for the upstream repository.
5. Create a new branch.
6. Add your changes.
7. Commit your changes.
8. Push the changes to your repository.
9. Create a pull request.


// Learned those steps from <a href="https://markodenic.com/make-your-first-open-source-contribution/" target="_blank">Marko Denic</a>
