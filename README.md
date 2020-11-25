# WDD01 Client-Side - Orientation Week Pre-Course Setup

Welcome to the `Developers Institute`. We will be starting our first semester with the `Client-side course`. But for us to truly get stuck into building great websites we need to prepare and sharpen our tools. So the first week we will be running through a `pre-course setup`. This will entail setting up our hardware (Apple Mac), installing required software and getting to grips with how to use our software tools. At any point if you get stuck don't hesitate to ask in your Cohort `Slack channel` for help. Our instructors and teaching assistance monitors those channels and will be more than happy to help you resolve your issue.

## Effective communication in the workplace

Communication will be key to your growth into the workplace and becoming a great developer. We prefer you to over communicate (tell everybody about how scary your cat is or how often you drink coffee) then to under communicate. At Developers Institute we employ 3 main channels of communication: slack and email.

- Slack is a real time messaging tool to help you stay connected to your team (your cohort) and all the support staff at Developers Institute. Use this to ask programming questions, talk about anime, share funny memes or see what others are up to. This is the playground where you will absorb our culture and become a fellow developer.
- Email is for formal communication between yourself, the outside world and Developers Institute itself. Please check your email regularly as we will be sending you emails on important events, happenings and dates. This is a vital skill to build as it will be an expected skill in your future workplace environment and thus an expected skill in our workplace. Please make sure your Developers Institute email is working including the associated cohort calendar.
- Your calendar will play a vital roll in organising your day and helping others to know your availability. Your daily meetings and project deadlines will be communicated to you via your calendar and will fall on you to follow and update your calendar on a regular basis. Integration tools for slack exists and is highly recommend: [Google calendar for slack](https://slack.com/app-pages/google-calendar)

<details>
<summary>Day 1 - Getting Started with macOS</summary>
<br>

## Day 1 - Getting Started with macOS

### Update Mac

First things first. Let us update our Mac to the latest software release:

- [How to update the software on your Mac](https://support.apple.com/en-us/HT201541).

### Get to know your Mac

This section is for anyone new to using macOS, or are returning to macOS from a much earlier version. Here is a collection of suggested resources to get the ball rolling with the latest version of MacOS:

- [Mac Basics animated walkthrough](https://help.apple.com/macos/catalina/mac-basics).
- [Mac tips for Windows switchers](https://support.apple.com/en-us/HT204216).

### Set up an Apple ID

You are also required to register your iMac with an Apple ID as soon as you receive it.

This is a mandatory step for you.

A few simple steps to follow and make this all happen:

- Register your iMac with an Apple ID. Please use your student email, in case you have not been provided with your login data to your new student email, please use your personal email in the meantime.
- Send a screenshot of the successfully registered/signed in user to [recruitment@developersinstitute.ac.nz](mailto:recruitment@developersinstitute.ac.nz)
- Do not disconnect your Apple ID under any circumstance

### Some suggested tweaks for your Mac

- [Enable your home folder in finder](https://vimeo.com/431692277/670a619782)
- [Enable right mouse click](enable-right-mouse-click-in-macos.md)

## Software

**Important:** Watch [Installing applications on your Mac](https://www.loom.com/share/1325f420d7aa4871ac5fba2e721b4422?from_recorder=1) before completing the following. This will help you learn how mac's work when installing software.

Install the following software:

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

#### Loom

We share a lot of videos in Loom. Create a Loom account so you can leave comments and feedback on videos that we share.

- [Loom](https://www.loom.com) - create an account on Loom with your Developers Institute email address. Try and stay logged in when you are watching videos.

### Programming tools

[Node.js](https://nodejs.org/en/) is a JavaScript runtime, meaning you can run JavaScript outside of a web browser. It's used extensively in web development to both build web-servers, and to run tools on your mac computer to help with web development. You can run local servers, automate annoying tasks and a bunch of other helpful things. You need to install it, as we use a lot of tools that depend on Node.js.

Watch the [installing Node.js video tutorial](https://www.loom.com/share/d77560e0e43f4a6d87c88f6d8e408811?from_recorder=1). You install Node.js using Node Version manager.

Ensure you have a `.zshrc` file:

```sh
touch ~/.zshrc
```

Install NVM from the instructions on the [NVM repository](https://github.com/nvm-sh/nvm)

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

### freeCodeCamp

We will be using freeCodeCamp to practice and learn a lot of our web development. Visit [freeCodeCamp](https://www.freecodecamp.org/) and sign up for an account by clicking the big yellow `Get Started` button. Create an account and sign-in. Once you are signed-in, update your [profile settings](https://www.freecodecamp.org/settings) so the instructors can see your progress. You will need to switch on the following settings from `Private` to `Public`:

- My profile
- My points
- My heat map
- My certification
- My time line

You can also update the `Username` to something more memorable than the [UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier) placeholder.

Once you have updated the settings, copy the URL to your freeCodeCamp profile and post it in Slack (in your cohort channel). To get the URL to your profile from the settings page, click the `Show me my public portfolio` button, and copy the URL from the browser address bar.

### Frontend Masters

You will need a Frontend Masters account from week 2. However it's good to sign up and have a look around before then, as there are other courses that might interest you.

1. Go to [Getting Started with JavaScript, v2](https://frontendmasters.com/courses/getting-started-javascript-v2/), and click the red _Get Free Access Now_ button
2. Create an account, using your `@developersinstitute.co.nz` email address

</details>

<details>
<summary>Day 2 - Git and GitHub setup</summary>
<br>

## Day 2 - Git and GitHub setup

### Setup GitHub Account

[GitHub](https://github.com/) is a hugely popular cloud-hosted version of Git used by millions of software teams. The majority of courseware and projects are hosted in GitHub code repositories so you will need a GitHub account to access the course materials.

To be able to access the material you will need to setup a GitHub account:

- We will be sending you your GitHub invite via your Developers institute email account.
- You can use your Developers Institute account to start with, and add your personal email at https://github.com/settings/emails if you want to add your own email address, or vice versa.

### Sign up for the GitHub Student Developer Pack

GitHub provides a Student Developer Pack, where you can score heaps of freebies.

Sign up here: [GitHub Student Developer Pack](https://education.github.com/pack)

Some of our favourite tools:

- Frontend Masters - A great online tutorial website with all kinds of topics related to web development
- Canva - Software to make web page designs. It runs in your browser.
- PomoDone - A productivity tool to help you power through tasks and focus by using the Pomodoro technique

There are a bunch of others, including tutorial websites. Have a look through and sign up for ones that interest you.

### Setting up an SSH key

When working with a GitHub repository, you'll often need to identify yourself to GitHub using your username and password. An SSH key is an alternate way to identify yourself that doesn't require you to enter you username and password every time.

SSH keys come in pairs, a public key that gets shared with services like GitHub, and a private key that is stored only on your computer. If the keys match, you're granted access.

The cryptography behind SSH keys ensures that no one can reverse engineer your private key from the public one.

Let us create and add your public key to GitHub:

1. Run the following script in your terminal:

   ```bash
   echo -e $(bash <(curl -s https://raw.githubusercontent.com/Developers-Institute/WDD01-Client-Side-Pre-Course-Setup/master/setup-ssh.sh) YOUR_EMAIL_HERE)
   ```

   `Note:` Remember to replace "`YOUR_EMAIL_HERE`" with your GitHub email address.

2. The script will automatically copy your public key to your clipboard and open GitHub in your browser. All you need to do is `paste` (cmd + v) the public key into GitHub and provide it with a title of your choice.

3. There after you need to test the key by running:
   ```bash
   ssh -T git@github.com
   ```
4. If you receive a "You've successfully authenticated, but GitHub does not provide shell access." message then you have successfully added a SSH key to GitHub

![Adding SSH key to GitHub](img/ssh_key_script.gif)

### Learn the basics of Git

Git is one of the core tools that developers use daily. Watch the [Git Basics](https://git-scm.com/videos) introductory video series on the Git version control system. There is loads of information to absorb, but we only need to know a small amount of it for now. The main thing to learn is how to `git clone`, `git add`, `git commit` and `git push`.

#### Video tutorial of a GitHub workflow using Visual Studio Code:

[![Git example](img/git_example_video.jpg)](https://vimeo.com/433825571/bc1830fb90)

### Self-learning exercise

Work through the [Quick Start tutorial](https://help.github.com/en/github/getting-started-with-github/quickstart) to get familiar with common GitHub tasks.

At this stage you should have the basic understanding of how to `git clone`, `git add`, `git commit`, `git push`.

`Note:` getting to grips with git is a marathon and not a sprint. So take it easy.

### Set up your git config

Let git know what your user name and email address are.

1. Open your terminal. You can do this by typing `cmd-space`, then typing `Terminal` and pushing enter
2. In your terminal, copy and paste the below code snippet. Replace `"[YOUR NAME]"` and `user@developersinstitute.co.nz` with your name and email. Note that the name has quotes, and the email does not.

   ```bash
   git config --global user.name "Bill Murray"
   ```

   and then

   ```bash
   git config --global user.email user@developersinstitute.co.nz
   ```

### Optional Content

Get to know git and GitHub better:

- [GitHub Guides](https://guides.github.com/)
- [GitHub Training & Guides YouTube channel](https://www.youtube.com/user/GitHubGuides/featured)

</details>

<details>
<summary>Day 3 - Git and the Command Line</summary>
<br>

## Day 3

### Get to know your accountability buddy with git

Complete today's Git exercise: [Get to know your accountability buddy](git-exercise/README.md)

### Screen sharing

During the course you will need to share your screen on video calls. This might be for an instructor to help you with your code, or for you to demo your work to other students. Make sure you have you screen sharing working in both Slack and your web browser.

To enable screen sharing, you will need to update some mac security settings. Watch the [video tutorial for enabling screen sharing permissions](https://www.loom.com/share/fead2612994348a6a9d7839fcac49656?sharedAppSource=personal_library) on your mac.

When you are talking to your accountability buddy or another student, test your screen sharing setup with them.

### Password management

As a future web developer security needs to always be in the front of your mind. Not just when developing websites but, also while managing your own online security.

`Password managers` are one of our frontline security tools. Password managers store your login information for all the websites you use and help you log into them automatically. They encrypt your password database with a master password (the master password is the only one you have to remember).It also generates them for you, so that each website has a strong unique password. You only have to remember your master password

Please check all the email addresses you use with a website called [Have I Been PWNED](https://haveibeenpwned.com/) to see if any of your online accounts associated with your emails accounts have been compromised.
If you have been using the internet for some time, there is an unfortunately high chance the password has been compromised.

If your email is compromised, you need to fix that by:

1. Resetting your passwords (unless you already have since the breach date). Any account where you used the same password is potentially compromised.
1. Stop using the same 3 passwords for everything
   - How... Sticky notes? Add a number on the end? No 🤦 ! Time to use a password manager 😎 ...
1. Use a password manager to generate and remember all your passwords
   - Choose a good master password. Consider a phrase instead of a word. Don't use an old compromised password for this. Don't make it too hard to remember, as forgetting would be a disaster.
   - Us instructors, use [KeePassXC](https://keepassxc.org/) and [LastPass](https://www.lastpass.com/) and other staff use [Dashlane](https://www.dashlane.com/)
   - All three options are plenty secure. KeePassXC is the most secure option, but unfortunately it's not hosted online (passwords saved to your disk, encrypted with your master password)
   - LastPass and Dashlane store passwords on their online server, encrypted with your master password. This allows them to be easily used between multiple computers.

### Learn about the command line

You will be using the command line (aka Terminal) every day as a developer, so it's worth spending some time to learn what it is, and how to use it.

- [ ] Start working on the [Learn the Command Line in Terminal](https://openclassrooms.com/en/courses/4614926-learn-the-command-line-in-terminal) course on Open Classrooms. You don't have complete the entire course today, but try and get through as much as you can. You can keep re-visiting this tutorial as you like.

### Customise VS Code

<details>
   <summary>Disable VS-Code from auto-accepting code suggestions</summary>

Disable VS-Code from auto-accepting code suggestions (as it's suggestions are often wrong):

![Disable VS-Code from auto-accepting code suggestions](img/vscode%20tips%20-%20disable%20auto-accept%20suggestions.png)

</details>

<details>
   <summary>Set Visual Studio Code as Gits' default merge editor</summary>

Save yourself the hassle of having to learn terminal text editors (like vim) by running these 4 commands:

```bash
git config --global merge.tool vscode
git config --global mergetool.vscode.cmd "code --wait $MERGED"
git config --global diff.tool vscode
git config --global difftool.vscode.cmd "code --wait --diff $LOCAL $REMOTE"
```

`Note:` copy, paste and run the commands inside your terminal.

![Copy past terminal commands](/img/copy_past_terminal.gif)

</details>

<details>
   <summary>Launching Visual Studio Code from the command line</summary>

You can also run VS Code from the terminal by typing 'code' after adding it to the path:

- Launch VS Code.
- Open the Command Palette (⇧⌘P) and type `shell command` to find the Shell Command: `Install 'code' command in PATH` command.

  ![shell command](img/shell-command.png)

- Restart the terminal for the new \$PATH value to take effect. You'll be able to type 'code .' in any folder to start editing files in that folder.

</details>

</details>

<details>
<summary>Day 4 - Preparing for Study, How the Internet Works, and HTML</summary>
<br>

## Day 4 - Preparing for Study, How the Internet Works, and HTML

### Prepare for study

#### Progress check

Go through the following list and see how you're going. Focus on completing the list if you haven't already. If you need help with anything, let your instrutor know.

- [ ] I have a GitHub account
- [ ] I have emailed my Apple ID to [recruitment@developersinstitute.ac.nz](mailto:recruitment@developersinstitute.ac.nz)
- [ ] I can `clone`, `add`, `commit`, and `push` to and from Github, using the Terminal in VS Code
- [ ] I have set my default browser to Chrome, Brave or Firefox
- [ ] I can confidently do a standup with my accountability buddy

#### Getting ready to learn

Learning is hard work. Take some time today to think about how you are going to make the most of your time. Below are some helpful tools and links to get you started

- **[Trello](https://trello.com)** - This is a great tool for task management. Create columns such as "To Do", "Today", "Done", then create tasks and drag them between columns. You could use this to keep on top of your workload, and help you focus on one thing at a time

  ![trello](img/trello.gif)

- **[Notion](https://www.notion.so/personal)** - This is like having a second brain. Capture all your notes in one place so you can easily refer back to them. Even if you don't use Notion, make sure you have some tool for capturing notes as you learn.

- **[RunJS](https://runjs.dev/)** - A tool for quickly writing and running JavaScript. Great for practicising or coding along with tutorials

#### Practice using design software

There will be opportunities to design user interfaces throughout the course. Spend time today getting familiar with some design software, so when you have the urge to design you know where to start.

We recommend [Adobe XD](https://www.adobe.com/products/xd.html), as it's free and used widely in the industry. You can start by watching [How to design a simple website in Adobe Xd for beginners](https://youtu.be/jHBMjjLY0Dw) on YouTube (20mins), and then try designing a website or a small part of an interface.

Keep focusing on the progress check from Day 4, only continue if you have completed that checklist. Today's material is extra content that will give you a head start, rather than required.

### How the Internet Works, and HTML

As a web developer, you should have at least a basic understanding of the internet, networks and servers. So, have a read through [Mozilla's article on how the internet works](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)

Start learning about how HTML works by watching a course on Frontend Masters, then practice writing HTML on freeCodeCamp.

- [ ] Complete [Intro to Web Development, v2: Learning HTML](https://frontendmasters.com/courses/web-development-v2/) on Frontend Masters. You only need to focus on the Learning HTML section.
- [ ] Exercises for [Basic HTML & HTML5](https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/) on freeCodeCamp

Another excellent resource is [Getting started with the Web
](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web) on MDN.

If you have finished everything, take a look at the [course schedule](https://github.com/Developers-Institute/WDD01-Intro-Client-Side-Web-Development) and work your way through the material outlined there.

</details>
