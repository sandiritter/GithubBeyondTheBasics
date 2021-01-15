## Lab One - Forking a Repo

### This is an exercise in forking a repo, making a change and a pull request

#### Part I. Forking a repo

1. Log in to your personal github account, if needed.
2. In a browser, navigate to https://github.com/sandiritter/GithubBeyondTheBasics
3. In the upper right-hand corner, click on Fork:

   <img src="../images/fork.png" alt="drawing" width="400"/>

4. If you only have access to your own personal repo, this will fork VSCode into your account.  However, if you have access to multiple repos, you will have to specify where to fork it.
5. Once forking is completed, you will be on the main page of your newly forked repo.

#### Part II. Cloning your forked copy of the repo
Now that you have a repo, you will follow normal flow to make a change. 

1. Click the copy button next to the repo name
2. Open your terminal
3. Navigate to a location where you prefer to store
your code, or create a new folder
4. Clone the repository
   
   ```git clone https://github.com/<therepocloned>.git``` 
5. Change directory to the new repo
6. Create a new branch 
   
   ``` git checkout -b myBranchName```
   
7. In your favorite text editor, add a new file to the quotes directory. Name the file something unique and include a favorite quote in the file.  You can copy the existing file ```sandi.html``` as a starting point if you prefer.
8. Once done with your file, commit your changes 

   ```git commit -m "some meaningful message"```
9. Now push your changes up to your repo 

   ``` git push origin my BranchName```

 #### Part III. Pull request
Let's create a pull request to merge your changes

1. Navigate to your repo in Github
2. You should see a messge block indicating your branch was recently pushed. Click on ‘Compare & pull request’

   <img src="../images/branch.png" alt="drawing" width="400"/>

3. Verify the base repo and hed repo are accurate

   <img src="../images/base.png" alt="drawing" width="400"/>

4. Click ‘Create Pull Request’

