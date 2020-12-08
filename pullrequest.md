# STEPS TO CREATE A PULL REQUEST #

## Step 1 - FORKING ##

To Fork a GitHub Repository Click on the `Fork` button On the Right top corner.

## Step 2 - CREATE A LOCAL CLONE OF YOUR FORK ##

On GitHub navigate to your Fork Repository, Click on `Code` button to copy the URL of HTTPS.

## Step 3 - CLONE FORKED REPOSITORY IN LOCAL TERMINAL ##

On your local machine open a terminal. Use the command:

`git clone <copied url>`

## Step 5 - MAKE CHANGES AND PUSH IT TO THE REPOSITORY ##

After making your desired changes use these commands:

`git add --all`

`git commit -m <"Your-commit-name">`     (`Note` : `-m` tells git that you are comming the changes with a message to tell people what the commit is about)

`git push origin <your-branch-name>`

## Step 6 - CREATE A PULL REQUEST ##

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

Now submit the Pull Request.

### NOW WAIT FOR THE APPROVAL FROM THE REPOSITORY ADMIN TO ACCEPT YOUR PULL REQUEST ###