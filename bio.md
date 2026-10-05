# version control

version control is a system that records changes to a file over so that you can recall specific versions later. It allows multiple to work on a project simultaneously, tracks changes and help manage conflicts when merging contribution from different collaborators. Popular version control system includes Git, subversion (SVN), and mercurial.

### setup
To set up version control for your project, follow these step:
1.**Install a version control system **: choose a version control system (e.g., Git) and install it on your machine.
2.**Initialize a Repository**: Navigate to your project directory and initialize a new repository using the command `git init` (for Git).
3.**Add files**: Add files you want to track using `git add <file>` or `git add .` to add all files.
4.**Commit changes**: commit your changes with a decriptive message using `git commit -m "your commit message"`.
5.**Create a Remote Repository**: If you want to collaborate with others, create a remote repository on platforms like Github, Gitlab, or Bitbucket.
6. **Push Changes**: Push your local commit to the remote repository using `git push origin main` (replace `main` with your branch name if different).


### Branching
Braching allows you to create seperate lines of development within your project. This is useful for working on new festures or bug fixes without affecting the main codebase.

To create a new branch, use the command `git branch <branch-name>`, and switch to it using `git checkout <branch-name>`,or you create and switch to a new branch in one command using `git checkout -b <branchname>`.

After making changes, you can merge branch back into the main branch using `git merge <branch-name>`.
