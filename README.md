# New Project Setup Guide

This guide will walk you through the process of setting up a new GitHub repository for 'new-project' with a development branch.

## Steps

1. **Create a new repository on GitHub**
   - Go to [GitHub](https://github.com) and sign in to your account.
   - Click the '+' icon in the top-right corner and select 'New repository'.
   - Name your repository 'new-project'.
   - Choose to make it public.
   - Click 'Create repository'.

2. **Repository to your local machine**
   ``` 
   echo "# new-project" >> README.md
   git init
   git add README.md
   git commit -m "init"
   git branch -M main
   git remote add origin https://github.com/{your-account}/new-project.git
   git push -u origin main
   ```

3. **Create a development branch**
   ``` 
   git checkout -b development
   ```
   - make new changes

4. **Push the development branch to GitHub**
   ```
   git push -u origin development
   ```