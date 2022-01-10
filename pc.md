# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [x] [Download gitbash]() - Windows computers speak in a language called powershell however we will be speaking to our computers in a language called unixshell, in order to all be speaking the same language if you are using a PC you will need to download gitbash and use this program instead of the native command line. Whenever you see an instruction to use the terminal that will be your queue to open up gitbash. On a PC gitbash will be your terminal. 
2. [x] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [x] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection. 
4. [x] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [x] [Download Slack](https://slack.com/intl/en-ca/help/articles/209038037-Download-Slack-for-Windows) - make sure your slack display name is your `first name` `last name` 
6. [x] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [x] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [ ] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
   Git is an Open Sourced Distributed Version Control System; while GitHub is a company that offers a cloud-based git-hosting service. GitHub allows us to access and manipulate the standard git command-line interface.
2. Why do we create a branch? 
   We create a branch because it isolates individual's work from other team members.
3. What is the purpose of a pull request? 
   The pull request is to update the local version of a repository from a remote. 
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
   The command we can use to switch between branches is git checkout 'nameofbranch' or git switch 'nameofbranch'.
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
   Git fetch is similar to pull but doesn't merge. Git pull pulls down from a remote and instantly merges.
   Git merge is putting forked history backed together again. Between the three, git pull does a git fetch followed by a git merge.
6. What is a merge conflict? How do you resolve a merge conflict? 
   Merge conflict is when a merge enters a conflicted state at two separate points. We can resolve a merge conflict by editing the conflicted file and remove all conflict dividers.