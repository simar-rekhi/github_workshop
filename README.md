# GitHub x The Society of Women Engineers

## Prerequisites!
* GitHub account signed up: https://github.com/
* GitHub Desktop installed and set up: https://github.com/apps/desktop
* A code editor installed on your PC (preferably, VS Code)


## creating your first repo!
1. Click "Create New Repository"
2. Name it: `swe-match`. _Heads Up!_ Make sure your repo does not share the same name as your username
3. If you want, change the `repo visibility` to private (by default, this is public)
4. Select   `Add README`
5. Hit `Create repository`

You just created your very first repo over GitHub i.e., remote. Now, how do we make it available locally?

## forks
forking is the act of creating a personal copy of someone else's repository on YOUR GitHub account. For the purpose of understanding, you can fork this repo.
1. Navigate to the public repo you wish to fork
2. Click on the `fork` button at the top-right corner
3. GitHub will now create a fork of the original repo in your account. <br> Notice how the link changed from `github.com/simar-rekhi/github_workshop` to `github.com/your-username/github-workshop`
4. Now this is your independent copy to experiment with!
5. If you wish to work on it locally, follow the procedure listed below under `clone` to clone YOUR fork

## clone
cloning is the act of downloading the latest version of repository from your GitHub page to your PC. This allows you to work on the project locally via a code editor. <br>
You will be cloning the recently forked repository through some Terminal commands!
1. Navigate to the repo you wish to clone
2. Click the green `Code` button
3. Copy the `HTTPS` URL. This looks somewhat like https://github.com/username/repo-name.git
4. Navigate to the location where you want to clone this repository
5. Once found, right click, and open "Terminal" from this location
6. Run the following command: `git clone <url you just copied>` eg: `git clone https://github.com/username/repo-name.git`
7. Type: `cd <repo-name>` This will bring you in the project folder
8. Open your code editor:<br>
  * Mac users: `open .`
  * Windows users: `code .`

## add. commit. push.
This trio of commands will rule your time working on projects with Git/GitHub. Whenever you wish to add a new file to your source code or edit an existing one, you will make use **ACP: Add. Commit. Push.**<br>
For the purpose of this demo, start by modifying the file `demo.py`. Replace `Hello, World` to `Hello, GitHub`, and save it as you would usually do.
1. Open Terminal, this time via your code editor
2. Run: `git add .`
3. Run: `got commit -m "short description of your work"`. _Heads Up!_ Make sure to not leave the message section blank. Leaving it blank can cause vim to launch.
4. Before we push our staged commits, it is pertinent to understand the difference between _first push command_ vs _usual push command_<br>
 * First time: run `git push -u origin main` (this sets the upstream)
 * Otherwise: run `git push`


## pull & pull requests
Pulling is the act of getting the latest changes from GitHub. The command to follow: `git pull` <br>
Pull Requests (aka PRs) are made when you work on a common project, and you wish to merge your changes (worked on a different branch) to the main branch <br>

## creating your first repo!
1. Click "Create New Repository"
2. Name it: `swe-match`. _Heads Up!_ Make sure your repo does not share the same name as your username
3. If you want, change the `repo visibility` to private (by default, this is public)
4. Select   `Add README`
5. Hit `Create repository`

You just created your very first repo over GitHub i.e., remote. Now, how do we make it available locally?

## resources 
* GitHub Documentation: https://docs.github.com/en
* GitHub command cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
* Git Tutorial For Dummies by Nick White: https://youtu.be/mJ-qvsxPHpY?si=jsToKY9UsKkR-PzZ
* Sign up for GitHub Student Developer Pack: https://education.github.com/pack
