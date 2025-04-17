# GitHub MCP Demo

This repository demonstrates how to initialize a local project and sync it with a new GitHub repository.

## User Prompt

> create a public repo named github mcp demo
> and sync local project (current folder)
> and write all step in README.md
> include my prompt
> than add a commit and push to repo
> before do this, also add into .md

## Steps to Sync Local Project with GitHub

1. **Initialize a Git repository in your project folder:**
   ```zsh
   git init
   ```

2. **Add the remote repository:**
   ```zsh
   git remote add origin https://github.com/AdemKao/github-mcp-demo.git
   ```

3. **Add all files to the staging area:**
   ```zsh
   git add .
   ```

4. **Commit the files:**
   ```zsh
   git commit -m "Initial commit"
   ```

5. **Rename the default branch to `main`:**
   ```zsh
   git branch -M main
   ```

6. **Push to GitHub:**
   ```zsh
   git push -u origin main
   ```

## Notes
- Make sure you have files in your project directory before running `git add .` and `git commit`.
- You need to have git installed and be authenticated with GitHub to push changes.
