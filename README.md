# ESPHome Devices

[![Netlify Status](https://api.netlify.com/api/v1/badges/4cab5ac3-6466-4c05-ad3f-f5c0a62dc18c/deploy-status)](https://app.netlify.com/sites/esphome-devices/deploys)

A database of configuration files and guides for devices commonly flashed with <https://esphome.io> firmware.

Go to <https://devices.esphome.io> to view the website.

## How To Contribute

Content on devices.esphome.io is generated by [Gatsby](https://www.gatsbyjs.com/). Pages are written in Markdown which anyone can learn. How to add a new device is [documented here](https://devices.esphome.io/adding-devices).

When you create a merge request, Netlify will automatically compile your proposed changes for you to preview what gets rendered. It puts a comment in the PR on Github.

## Development of site

The site requires Node 18 to build.  Once that is running, to build locally:

```bash
# Now install gatsby as configured in the esphome-devices repository:
npm install
# Run a development gatsby server so you can see your copy of the site:
npm run start
# Open a browser to http://localhost:8000/
```

You can learn more about [Gatsby develop mode here](https://www.gatsbyjs.com/docs/reference/gatsby-cli#develop).

## Code of Conduct

When contributing to this project please abide by our [Code of Conduct](CODE-OF-CONDUCT.md)

### This is a fork, join our effort

This is a fork of [jonathanadams/esphome-configs](https://github.com/jonathanadams/esphome-configs). The goal is to involve more members of the ESPHome community to more actively update the devices! Please contact us or submit an issue if you are interested!

## Git Hub commands

```markdown
# Cloning and Pushing Code to GitHub

## Prerequisites

1. **Git Installed**: Ensure that Git is installed on your system. You can check by running the following command in your terminal:

   ```bash
   git --version
   ```

2. **GitHub Account**: Make sure you have a GitHub account and either have created a repository or have access to an existing one.

## Steps to Clone and Push Code

### 1. Clone the Repository

Open your command line interface (Terminal, Command Prompt, or Git Bash) and run the following command to clone the repository:

```bash
git clone <repository-url>
```

Replace `<repository-url>` with the URL of the GitHub repository you want to clone (you can find this URL on the repository page on GitHub).

**Example:**

```bash
git clone https://github.com/username/repository.git
```

### 2. Navigate to the Repository Directory

Change into the directory of the cloned repository:

```bash
cd repository
```

Replace `repository` with the name of the cloned repository folder.

### 3. Make Your Changes

Edit files or add new code as needed within the repository directory.

### 4. Add Your Changes

After making changes, stage the files you want to commit:

```bash
git add .
```

The `.` adds all changed files. You can also specify individual files like `git add filename`.

### 5. Commit Your Changes

Commit the changes with a descriptive message:

```bash
git commit -m "Your commit message here"
```

Replace `"Your commit message here"` with a brief description of your changes.

### 6. Push Your Changes to GitHub

Finally, push your committed changes to the GitHub repository:

```bash
git push origin main
```

Replace `main` with the name of the branch you want to push to (e.g., `master`, `develop`, etc.), if it's different.

## Summary of Commands

```bash
git clone <repository-url>
cd repository
git add .
git commit -m "Your commit message here"
git push origin main
```

## Additional Notes

- If prompted for your GitHub username and password, enter them to authenticate.
- If you have set up SSH keys, you can use the SSH URL for cloning and pushing without needing to enter your credentials each time.

These steps will help you clone a GitHub repository, make changes, and push those changes back to the repository.
```



