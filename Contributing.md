# Contributing to the project
Please make sure to read the relevant section before making your contributions, it will make it a lot easier for maintainers to make the most of it and smooth out the experience for everyone involved. 🚀

The structure below explains the atomic design principle. NOTE: before creating any new compnent, please check if it exists already to avoid duplicate components.

assets:contains CSS, Javascript, Images and Icons

src: contains all html pages

## Submit Changes

### fork the repo

### Clone the forked repo 
You can do that on your github account
or in your terminal using git clone https://github.com/your_username/Team_Raccoon_qr_gen.git

### Create a new branch
You can do that on your github account
or git checkout -b <new-branch-you-created>
ensure you are in your new branch, you can type <git branch> in your terminal to confirm

### Make your changes, 
git remote add origin <https://github.com/your_github_username/Team_Raccoon_qr_gen.git>

When you are done making changes, run the following
Pull chages from the repo to avoid conlicts
git pull

You may need to accept incoming or both changes before going to the next step

Then add your changes
git add . 
git commit (Use a descriptive commit message)

### Push changes
git push origin -u <your_new_branch> 

### Pull request
Head over to the main repo (https://github.com/zuri-training/Team_Raccoon_qr_gen) on github click "Compare and pull request"
In your description part, add this closes #Your_Issue_Number e.g this closes issue #45
Then wait till your PR is merged
When your PR is merged, always make sure your forked repository is in sync with the Zuri-training main branch by clicking Sync fork and updating your branch.

### More notes
Please avoid working directly on the exisiting branches.
In your forked repository, create a branch for your upcoming patch.
Assure nothing is broken by running all the tests.
Push your changes to the your branch in your forked repository.
Open a pull request to the original repository and choose the right original branch you want to patch.
Do NOT commit to other contributor's codebase/issue without their consent.
Even if you have write access to the repository, do not directly push or merge pull-requests. Let another team member review your pull request and approve.
Important notes before pushing codes:
Always make sure your forked repository is in sync with the Zuri-trainingbranch by clicking Sync fork and updating branch.
On your local machine do a git pull to your feature branch for a local update.
If any merge conflicts occurs locally, make a fix and drop a merge commit message on conflicts fixed to help maintainers know what changes were made while making sure your change works.
With all these done you are good to go and ready to push your code and make a pull request, if met with further conflicts repeat the process or leave a comment in your PR tagging a maintainer.