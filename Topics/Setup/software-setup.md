# Install software

### Homebrew

Homebrew is a command-line tool that lets you install software. It's useful for installing tools that are needed during development.

Watch the tutorial for [Installing Homebrew](https://www.loom.com/share/6d675407abf54da5b4cf93d257fcc1ab?from_recorder=1) to install [Homebrew](https://brew.sh).

### Version Control

Now you have Homebrew installed, you can use it to install Git.

Git is an industry-standard tool for tracking changes to files, and allowing developers to collaborate on code together. It's like a shared Google Doc for code.

Watch the [installing git video tutorial](https://www.loom.com/share/494e9d716a2948768e19248317650406?from_recorder=1).

Install Git by opening your Terminal, and typing the following:

```sh
brew install git
```

If after installing Homebrew you start seeing an error on your command line:

```shell
zsh compinit: insecure directories, run compaudit for list.
Ignore insecure directories and continue [y] or abort compinit [n]?
```

Watch the following video on how to fix this issue: [Compaudit fix](https://www.loom.com/share/327e2e694840467eb89271ec25f34aee)

### Web-browser

Install a modern web browser, preferably [Google Chrome](https://www.google.com/chrome/index.html), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), or [Brave Browser](https://brave.com/).

We like to use modern web browsers because they have excellent developer tools built in, which make your life as a developer much easier.

- Set your new browser as the default browser for your computer: [Google Chrome](https://support.google.com/chrome/answer/95417?co=GENIE.Platform%3DDesktop&hl=en), [Mozilla Firefox](https://support.mozilla.org/en-US/kb/make-firefox-your-default-browser), or [Brave Browser](https://support.brave.com/hc/en-us/articles/360020406572-How-do-I-set-Brave-to-be-my-Default-Browser-)
- `Note:` You will need Chrome or the Brave browser to use the Whereby conferencing tool.

### Communication

#### Slack

Slack is our main communication hub, where you and your class will talk with each other using text and video chat. You have access to all the instructions and other students, and a lot of chat rooms where different content is shared.

Install the Slack desktop app. Using the desktop app allows you to make video calls to instructors and other students, which can be handy when you want a 1:1.

- [Slack](https://slack.com/intl/en-nz/) messaging app. Ensure you install the desktop app as this will enable you the ability to make video calls to fellow students and instructors.
- Watch [Getting Started with Slack at Developers Institute](https://www.loom.com/share/a3b3687160364ce8aa9d19e452826736?from_recorder=1)
- Watch [Making calls in Slack](https://www.loom.com/share/67c6ec6d949641e9b84c106493616c76?from_recorder=1)

### Programming tools

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

### Visual Studio Code

Visual Studio Code is a text editor with developer super powers. We use it to write our code, and it provides a lot of helpful features that make our lives much easier as a developer. You will be writing all of your code into Visual Studio Code (VS Code)

- Download and install [Visual Studio Code](https://code.visualstudio.com/), the open-source code editor.
- Make sure it's installed to your Applications folder
- Customize VS-Code by installing the following extensions:
  - [ ] [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
  - [ ] [Code Runner extension](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  - [ ] [Prettier extension](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [ ] [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)

### Design

- [Adobe XD](https://www.adobe.com/products/xd.html), free software to create designs for websites and mobile apps.
