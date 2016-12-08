# Setting up your cloud9 workspace

## Objectives

1. Create a Ruby workspace
2. Get workspace ready for Ruby

## Creating your workspace

* Login to cloud9 ([c9.io](http://c9.io)).
* Create a new workspace
* Name: **ruby** (yes, lowercase)
* Description: *whatever you want*
* Visibility: leave as **Public**
* Template: select **Ruby**
* **Create workspace**

## Getting your workspace ready

Close the README.  You won't be needing that.

#### Delete the file/folder structure
The easiest way to do this is to type: `rm -rf *`

#### Turn on auto-save
Top-left menu > Cloud9 > Preferences > Experimental > Files > Auto-Save > **switch to ON**

You will be prompted to restart the workspace.  Go ahead and **do that**.

#### Verifying your connection to Github
Type `git config --list`.  You should see your name and email.  ONLY IF you don't, type these two commands with your information:
```bash
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```

#### Make the directories where your labs will live
So far, there are 6 units planned.  Here's a quick way to make all 6 folders at once:  
```bash
mkdir 00-intro 01-variables-methods 02-conditionals 03-loops 04-arrays-hashes 05-applications 06-oo
```

### Now you're ready!
Just make sure you stay organized! 