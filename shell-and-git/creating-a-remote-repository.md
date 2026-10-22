# Creating a Remote Repository

## 1. Create a repository on GitHub

- Create a new repository.
- Choose a repository name.
- Select Public.
- Leave the README option unchecked if one already exists locally.

## 2. Connect the local repository to GitHub

Run `git remote add origin git@github.com:USERNAME/REPOSITORY.git` to connect the local repository.

## 3. Verify the remote

Run `git remote -v` to check the remote address.

## 4. Push the local branch

Run `git push -u origin main` to push the branch and set its upstream.
