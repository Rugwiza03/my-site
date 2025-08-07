 # Git Integration & Wix CLI <img align="left" src="https://user-images.githubusercontent.com/89579857/185785022-cab37bf5-26be-4f11-85f0-1fac63c07d3b.png">

This repository is part of the Git Integration & Wix CLI workflow—a set of tools that allow you to develop, test, and deploy Wix site code locally on your machine.

Easily connect your Wix site to GitHub, code in your favorite IDE, preview changes in real-time, and publish your site directly from the command line.

## Set Up This Repository in Your IDE

This repository is linked to a Wix site, which tracks changes on its default branch. Any code pushed to that branch appears on the connected site.

### Prerequisites

Before getting started, ensure the following are installed:

* [Git](https://git-scm.com/download)  
* [Node.js](https://nodejs.org/en/download/) (version 14.8 or later)  
* [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) or [Yarn](https://yarnpkg.com/getting-started/install)  
* An [SSH key added to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

### Setup Steps

1. Open your terminal and navigate to the directory where you want to store the repository.  
2. Clone the repository:
   ```bash
   git clone <your-repository-url>
   ```
3. Navigate into the project directory:
   ```bash
   cd <directory-name>
   ```
4. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```
5. Install the Wix CLI globally:
   ```bash
   npm install -g @wix/cli
   ```
   or
   ```bash
   yarn global add @wix/cli
   ```

Once installed, the CLI can be used with any Wix-connected repository.

🔗 Learn more in the [Wix CLI Setup Guide](https://support.wix.com/en/article/velo-setting-up-git-integration-wix-cli-beta).

## Write Velo Code in Your IDE

After setup, you can start writing code as you would in any standard development environment. The folder structure mirrors the [Public](https://support.wix.com/en/article/velo-working-with-the-velo-sidebar#public), [Backend](https://support.wix.com/en/article/velo-working-with-the-velo-sidebar#backend), and [Page Code](https://support.wix.com/en/article/velo-working-with-the-velo-sidebar#page-code) sections in the Wix Editor.

📁 Learn more about the [repository structure](https://support.wix.com/en/article/velo-understanding-your-sites-github-repository-beta).

## Test Your Code with the Local Editor

Use the Local Editor to test your site in real time. It keeps your local code and site in sync, allowing you to preview changes before committing.

To start the Local Editor, run the following command in your project directory:

```bash
wix dev
```

🔍 Learn more about [using the Local Editor](https://support.wix.com/en/article/velo-working-with-the-local-editor-beta).

## Preview and Publish Using Wix CLI

The Wix CLI lets you control your site directly from the terminal. With it, you can:

- Build and preview your site  
- Publish updates  
- Install [approved npm packages](https://support.wix.com/en/article/velo-working-with-npm-packages)

📘 More info: [Working with the Wix CLI](https://support.wix.com/en/article/velo-working-with-the-wix-cli-beta)

## Collaborate with Other Developers

Wix Git Integration supports [concurrent editing](https://support.wix.com/en/article/editor-x-about-concurrent-editing), allowing multiple developers to work together.

- Invite collaborators to your [Wix site](https://support.wix.com/en/article/inviting-people-to-contribute-to-your-site)  
- Invite contributors to your [GitHub repository](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)

Collaborate seamlessly and build your site as a team.

