Disclaimer -Okay so whosoever is reading this first of thanks for this opportunity it was actually fun to do and I wish I can be a part of your team as I myself prefers the actual skills
this file might be lengthy but I can confidentially say that I did what you wanted as first while doing the task I did mention my thoughts in raw format in broken English and so on, I know it might sound unprofessional but your task is makes you think like a developer not like an interview so I hope you won't mind, but just in case you ant professionalism I also put my raw thoughts about the steps issues to chatgpt to create this professional summary, but in case if you want to actually want to know what I went through i want you to please scroll down a bit and you will find the messy thoughts
Thank You
Divyam Jain(J.D.)




# 100Hires Portfolio Project

## Objective

This repository documents the setup process required for the 100Hires portfolio project. The goal was to install the required development tools, configure them, connect GitHub, and document both the successful steps and the issues encountered along the way.

---

# Step 1: Install Cursor IDE

- Visited the Cursor website.
- Downloaded the Windows x64 version.
- Ran the installer.
- Accepted the license agreement.
- Chose the installation directory.
- Created desktop shortcuts.
- During installation I searched whether I needed to add Cursor to the PATH.
- Learned that PATH allows Windows to locate installed programs from the command line.
- Completed the installation.
- Launched Cursor.

---

# Step 2: Create a Cursor Account

Since this was my first time using Cursor:

- Clicked **Sign Up**.
- Browser opened automatically.
- Chose to sign up using email.
- Completed CAPTCHA verification.
- Verified the account using the email verification code.
- Selected:
  - Personal account
  - Profession: Other
- Skipped the Individual Plan setup.
- Disabled optional usage data sharing.
- Skipped GitHub connection for later.
- Logged into the Cursor desktop application.

---

# Step 3: Install Claude Code Extension

## Initial Problem

I couldn't find the Extensions tab.

I tried:

- Searching inside Customize
- Ctrl + Shift + X
- View → Extensions
- Ctrl + Shift + P → "Extensions: Show Extensions"

None of these worked.

## Troubleshooting

I searched YouTube for tutorials.

The videos showed an Extensions tab that did not exist in my Cursor window.

I then asked ChatGPT.

It suggested:

1. Opening a folder.
2. Creating a source code file.
3. Opening the Editor workspace.

I first created a folder.

That did not work.

Next I accidentally created:

```
test.py.txt
```

instead of

```
test.py
```

This also did not work.

Eventually ChatGPT explained that I was still on Cursor's Home/Agent dashboard rather than the actual code editor.

I opened the Editor window.

After renaming:

```
test.py.txt
```

to

```
test.py
```

the full VS Code interface appeared.

The Extensions tab became available.

## Installing Claude

- Opened Extensions.
- Searched **Claude Code**.
- Installed the extension.
- Trusted the publisher.
- Opened Claude.
- Selected login using Anthropic Console.
- Browser opened.
- Logged in using Google.
- Selected Individual account.
- Skipped API key creation.
- Authorized Cursor.
- Successfully connected Claude.

---

# Step 4: Install Codex Extension

Opened Extensions.

Searching "Codex" returned nothing.

Searching "OpenAI" displayed the Codex extension.

Steps:

- Installed Codex.
- Trusted publisher.
- Selected **Sign in with ChatGPT**.
- Browser opened.
- Logged in using Google.
- Authorization completed successfully.
- Returned to Cursor.

Codex was now connected.

---

# Step 5: Create GitHub Repository

I already had a GitHub account.

Created a new repository:

```
100hires
```

Visibility:

```
Public
```

Copied the repository URL.

---

# Step 6: Clone Repository

Initially I tried using:

```
Git: Clone
```

through the Command Palette.

The command was unavailable.

Instead I opened the terminal and ran:

```bash
git clone https://github.com/unknown1234509876/100hires
```

This produced the error:

```
git is not recognized as an internal or external command
```

---

# Step 7: Install Git

Installed Git for Windows.

During installation I selected:

```
Git from the command line and also from 3rd-party software
```

Verified installation:

```bash
git --version
```

Output:

```
git version 2.54.0.windows.1
```

Configured Git:

```bash
git config --global user.name "unknown1234509876"

git config --global user.email "divyamjain2409@gmail.com"
```

---

# Step 8: Clone Repository Again

Ran:

```bash
git clone https://github.com/unknown1234509876/100hires
```

Repository cloned successfully.

Git displayed that the repository was empty, which was expected.

Opened the repository:

```bash
cd 100hires

cursor .
```

Cursor opened the repository in a new window.

---

# Step 9: Create README

Created:

```
README.md
```

Started documenting the complete setup process.

---

# Step 10: First Commit

Added files:

```bash
git add .
```

Created the first commit:

```bash
git commit -m "Initial commit"
```

Pushed to GitHub:

```bash
git push
```

---

# Step 11: Updating the README

After making changes to README.md, I attempted:

```bash
git commit -m "change 2"
```

Git returned:

```
Changes not staged for commit
```

## Issue

I had modified the README but forgot two important steps:

1. Save the file.
2. Stage the changes.

## Solution

Saved the file in Cursor.

Ran:

```bash
git add .
```

Then:

```bash
git commit -m "change 2"

git push
```

The changes were successfully uploaded to GitHub.

---

# Tools Installed

- Cursor IDE
- Git
- Claude Code Extension
- OpenAI Codex Extension

---

# Skills Demonstrated

- Installing development tools
- Setting up Git
- Configuring GitHub
- Repository creation
- Cloning repositories
- Using Git commands
- Installing Cursor extensions
- Troubleshooting installation issues
- Research using documentation, YouTube, and AI tools
- Problem-solving through iterative debugging

---

# Challenges Faced

- Could not locate the Extensions tab in Cursor.
- Accidentally created a `.py.txt` file instead of a `.py` file.
- Git was not installed initially.
- Repository cloning initially failed because Git was missing.
- Forgot to stage modified files before committing.

Each issue was resolved through documentation, YouTube tutorials, ChatGPT guidance, and testing different approaches until the correct solution was found.

---

# Outcome

Successfully completed all required tasks:

- Cursor installed
- Claude installed and authenticated
- Codex installed and authenticated
- Git installed and configured
- Public GitHub repository created
- Repository opened in Cursor
- README created
- Changes committed
- Repository pushed to GitHub









---------------------------------------------------------------------RAW Thoughts below -----------------------------------------------------






go to cursor website
click download 
choose your operating system and version I did x64 system windows you may choose mac if you use macos, Linux verion based upon distro
now click yes to install the setup
run the setup(
agree terms-select destination- create shortcut
i used chatgpt coz do I need to add to PATH
it told me PATH tells where to find installed programs
hit install it will extract files and will install the cursor files to the destined folder, you have to be patient yeah it does takes some time. 
launch cursor
if you are first time user like me you need to sign up, hit signup a brower window will open continue
you may choose signup with google/apple/GitHub or signin with email(i did that the email one)
verify you are a human(obviously)
verify with password or code on email(i did code on email)
after verification it asks personal/team your profession i did personal and other because mine wasn't lister 
it asks setup individual plan which I skipped
I turned off share data because why not
i skipped connect GitHub will do it later coz follow the instructions in email 
then click login to cursor desktop
you may close the tab and return to cursor desktop
okay I liked the animation when you login and gets you to the homepage

now next step is to add claude extention but I couldn't find that I thought in customize you search for claude but nope it wasn't there maybe in settings there will be an option but nah I couldn't find that
now let's ask chatgpt where can I find extentions in cursor like where am I supposed to add
chatgpt gave me 2 option either use claude models inside cursor and other claude code extentions
the first method yeah go to settings models enable sonnet opus model which were already enabled but you have to add the api keys but that was not the task so 
let's go to 2nd option the shortcut ctrl+shift+X didn't work and I could not find claude code in customize section so both methods failed because I couldn't find where is the extentions tab
now I opened the old is gold youtube and searched on how to install claude extention on cursor i find a video https://youtu.be/5E5ByxaOKuo but there was a difference my cursor was a bit different from his because it was having extentions under view options but mine didn't so I youtube again but unfortunately the videos were about how to install extention not actually why extentions options was missing in the first place
so I chatgppt gave 3 options when I said ctrl+shift+X not working 
method 1left sidebar click extentions icon which is not visible
method 2 Ctrl + Shift + P then type Extensions: Show Extensions again not working
method 3 view-extentions again extentions is missing
so i screenshot the cursor home to chatgpt
so it gave me 3 options it asked me to open any folder i created a test folder it didn't work
option 2 create.py file I created a test.py and it worked 
so i created a file test.py.txt actually i want to create a .py file but didn't realize that time I by mistake created test.py.txt which didn't work again
so it gave me last option Click the gear icon next to your name (Divyam Jain) in the bottom-left.
Look for Open Editor, Workbench, or Settings.
I searched and somehow I saw a editor window button and clicked that and it worked
then I realized the first line chatgpt said You're not in the code editor/workspace. You're on Cursor's Home / Agent dashboard, which hides the normal VS Code interface, including Extensions.
then I renamed the test.py.txt file to test.py file and I was now in editor window and I followed the step to now view-extentions-search claude went back to the first youtube video installed claude for vs code-hit install-trust publisher and installed claude
then I followed the video open claude code in and it gave options how do you want to login claude.ai subscription/anthropic console/ or api keys I chose the console option, it opened a browser window I logged in using my google account as I had an account earlier
it asked individual or organization i chose individual then skipped get api keys and the authorized the connection and yeah I logged in with claude, closed the tab as it was asking to purchase credits
now next step was to install codex
view-extentions- searched for codex clouldn't found tried searching openAI as codex is by chatgpt which is by openAI and yeah it worked hit install trust publisher then again drop down hit codex use api key or signin with chatgpt I chose signin with chatgpt- a browser window open I signed in with google-continue-you may close this tab, I was signed in with codex

next step to create a public repositpry on GitHub I already had an account- I chatgpt to open repository in cursor
first I sign in github on browser created a repository named as 100hires - public- create
copied the url of repository here comes the role of chatgpt "https://github.com/unknown1234509876/100hires"
chatgpt said ctrl+shift+P 
the search Git:Clone but couldn't find the command
then I opened terminal in cursor git clone https://github.com/unknown1234509876/100hires ran this 
but got error git: The term 'git' is not recognized as a name of a cmdlet, function, script file, or executable program.
Check the spelling of the name, or if a path was included, verify that the path is correct and try again.
then I installed git didn't change any selections this one I made sure worked
Most options can be left at their defaults. The important one is:

When you see "Adjusting your PATH environment", choose:

✅ Git from the command line and also from 3rd-party software (Recommended)

I checked if installed using git --version and it gave the output git version 2.54.0.windows.1
then I ran
git config --global user.name "unknown1234509876"
git config --global user.email "divyamjain2409@gmail.com"

then I again cloned my repository git clone https://github.com/unknown1234509876/100hires
gave error repository empty
cd 100hires
cursor .
a new cursor window opened with my repository
created README.md file
I then pasted all this data in this file and pushed as of here the file you will be receiving will be updated to below 
git add .
git commit -m "Initial commit"
git push

i accidentally typed unprofessiona commit and it worked but I could not find the text inside the file
tried ctrl + S then this
git commit -m "change 2" got error        
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed) 
  (use "git restore <file>..." to discard changes in workingdirectory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit-a")
realized 2 things to be done first save the file in cursor 
then also run git add .
then same commit and then git push

