# SUTD_CTD_1D
# README: Getting Started with GitHub

Welcome to this quick guide on using GitHub! This README will cover the basics of committing changes, a fundamental aspect of version control with GitHub.

## Basic Terms

- **Repository (Repo)**: A directory or storage space where your projects can live. It can be local to your computer or hosted on GitHub.
- **Commit**: Recording changes to the repository. Think of it as a snapshot of your current project.

## Step-by-Step Instructions

### 1. Create a Repository

- **On GitHub**: Click the "+" icon in the top right and select "New repository". Name your repository, choose public/private, and initialize with a README if you like.

### 2. Clone the Repository

- **On your computer**: Open a terminal or command prompt.
- Use `git clone` followed by the URL of your repository:

  ```bash
  git clone https://github.com/username/repository.git
  ```

### 3. Make Changes

- Edit files in your local repository using your preferred text editor or IDE.
- You can add new files or modify existing ones.

### 4. Stage Your Changes

- From your terminal/command prompt, change to the repository directory.
- To stage changes (prepare them for a commit), use:

  ```bash
  git add .
  ```

  or specify individual files with `git add <filename>`.

### 5. Commit Your Changes

- Commit your staged changes with:

  ```bash
  git commit -m "Your commit message"
  ```

  Write a meaningful message to describe what changes you've made.

### 6. Push Your Changes

- Upload your commits to GitHub with:

  ```bash
  git push origin main
  ```

  Replace `main` with the branch name, if different.

### 7. Check Your Repository on GitHub

- Go to your GitHub repository in a web browser to see your changes.

## Additional Tips

- **Branches**: Before making changes, consider creating a new branch. This keeps the main project stable.
- **Pull Requests**: If you're working with others, use pull requests to merge changes from different branches.
- **Stay Updated**: Regularly pull changes from the origin to keep your local repo up-to-date.

## Conclusion

That's it! You've learned the basics of committing changes on GitHub. As you get more comfortable, explore more advanced features of Git and GitHub. Happy coding!
