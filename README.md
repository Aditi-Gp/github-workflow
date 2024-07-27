# github-workflow

## Steps to Push Changes

### 1. Navigate to Your Local Repository

Open your terminal (or command prompt) and navigate to the directory of your local repository:

```bash
cd path/to/your/repository
```

### 2. Check the Remote Configuration

Verify that the remote repository is set up correctly:

```bash
git remote -v
```

If the remote named `origin` does not exist, add it using:

```bash
git remote add origin https://github.com/your-username/your-repository.git
```

### 3. Stage Your Changes

Stage the files you want to commit:

- To stage specific files:

  ```bash
  git add filename1 filename2
  ```

- To stage all changes:

  ```bash
  git add .
  ```

### 4. Commit Your Changes

Commit your staged changes with a descriptive message:

```bash
git commit -m "Your descriptive commit message"
```

### 5. Push Your Changes to GitHub

Push your changes to the remote repository. If you are pushing to the `main` branch, use:

```bash
git push -u origin main
```

Replace `main` with the name of your branch if you are working on a different one.

### 6. Authentication

If prompted for your username and password:

- Enter your GitHub username.
- For the password, use a **personal access token** instead of your GitHub password. 

To generate a personal access token:

1. Go to your GitHub account settings.
2. Navigate to **Developer settings**.
3. Click on **Personal access tokens** and then **Generate new token**.
4. Select the appropriate scopes and generate the token.
5. Copy the token and use it as your password when prompted.

### 7. Verify the Push

To confirm that your changes have been pushed successfully, visit your GitHub repository in a web browser.
