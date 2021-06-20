# Install Node on a Mac with NVM

[Node.js](https://nodejs.org/en/) is a JavaScript runtime, meaning you can run JavaScript outside of a web browser. It's used extensively in web development to both build web-servers, and to run tools on your mac computer to help with web development. You can run local servers, automate annoying tasks and a bunch of other helpful things. You need to install it, as we use a lot of tools that depend on Node.js.

Watch the [installing Node.js video tutorial](https://www.loom.com/share/d77560e0e43f4a6d87c88f6d8e408811?from_recorder=1). You install Node.js using Node Version manager.

Ensure you have a `.zshrc` file:

```sh
touch ~/.zshrc
```

Install NVM from the "Install & Update Script" instructions on the [NVM repository](https://github.com/nvm-sh/nvm#install--update-script)

Once NVM is installed, type the following:

```sh
nvm install --lts
```