

Part 1: Using VSCode with Git and GitHub
Download and install VSCode from https://code.visualstudio.com/

Install Git from https://git-scm.com/downloads

Open VSCode and create a new project folder

Initialize a Git repository by opening the terminal in VSCode (Ctrl+`) and typing:

git init

Create a new file (e.g., README.md) and add some content

Stage your changes:

git add .

Commit your changes:

git commit -m "Initial commit"

Create a new repository on GitHub

Connect your local repository to the remote GitHub repository:

git remote add origin https://github.com/yourusername/your-repo-name.git

Push your changes to GitHub:

git push -u origin main

To create a new branch:

git checkout -b new-feature

Make changes, stage, and commit them

Push the new branch to GitHub:

git push -u origin new-feature

Create a pull request on GitHub to merge your changes

To update your local repository with changes from GitHub, use:

git pull origin main

Part 2: Glossary
Branch: A parallel version of a repository that allows you to work on different parts of a project without affecting the main branch.

Clone: A copy of a repository that lives on your computer instead of on a website's server.

Commit: A record of changes to a repository.

Fetch: Downloading changes from a remote repository without merging them.

GIT: A distributed version control system for tracking changes in source code during software development.

Github: A web-based platform for version control and collaboration using Git.

Merge: The act of combining different branches into a single branch.

Merge Conflict: An event that occurs when Git is unable to automatically resolve differences in code between two commits.

Push: Sending your committed changes to a remote repository.

Pull: Fetching changes from a remote repository and merging them into your local branch.

Remote: A version of your project that is hosted on the internet or network somewhere.

Repository: A project's folder containing all files and their version history.
