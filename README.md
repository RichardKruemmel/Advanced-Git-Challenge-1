Advanced Git Challenge #1
Merging / Rebasing
Complete the following steps:

Create a new repository (each individually): either on GitHub or locally
Create a single commit in that repo (for example by adding a Readme.md)
Clone the GitHub repo or push your local repository to GitHub
Create a new branch locally
Change your Readme.md in your local branch and commit it
Push your local branch to GitHub
Create a pull request for your new branch on GitHub
Merge your pull request
Inspect your history: Post a screenshot of your commit history on slack. The history should include your merged pull request (if you take it locally you need to update your main branch first)

Part 2:
Create a local branch (featureB) based off of your initial commit
Look at the history of the featureB branch (git log) to ensure that it only contains a single commit. It shouldn’t contain anything from featureA (that you merged via GitHub)
Commit something in the featureB branch (ideally in a new file, to avoid conflicts)
Checkout your main / master branch and pull to get the merged PR from GitHub. Verify using the log that the GitHub merge commit is part of your history
Merge the featureB branch into your main / master (locally, e.g. from the command line)
What is the automatically generated commit message for the merge commit?
Post a screenshot in Slack of the full history graph. Note: this should include the merged pull request as well as your local merge. You might have to run git pull on your local main / master branch to update it. You can get a nice graph using:
git log --oneline --decorate --graph --all
If you leave out the --oneline argument you get more info per commit (such as the author and the date).
