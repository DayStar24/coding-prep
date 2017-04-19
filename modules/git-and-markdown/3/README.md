---
title: Make a Resume!
currentMenu: modules
---

## Introduction  

Let's start putting together our knowledge of Git, Markdown, and the command line in order to make a tech resume that will help you stand out!  

## Exercise: Make a Resume!  

### Step 1: Create Content  

1. Open a Git Bash or Terminal window and make sure you are in your home directory: `cd ~`  
2. Using the command line, create a new directory called my-resume: `mkdir my-resume`  
3. Navigate to that directory and create a new file called "resume.md": `cd my-resume` and `touch resume.md`  
4. Open that file in your text editor: `open resume.md` or `start resume.md`  
5. Type your name using a level 1 Header and save the file: `# LaunchCode Jones`  

### Step 2: Make a Git Repository  

1. Make sure you are in the directory you just created and initialize it as a Git repository: `pwd` and `git init`  
2. Check that the file you just made will be in this repo: `git status`  
3. Add and commit this file to your repo with the message "First Commit": `git add .` and `git commit -m "First Commit"`  

### Step 3: Put it on GitHub   

1. Go to your profile page on GitHub and click Repositories, then click the green `New` button at the top right  
2. Enter the repository name `my-resume`, and leave the default settings as they are, then click `Create Repository`  
3. In the `Quick setup` panel click `Https` and copy the address shown.  
4. Back on the command line, type `git remote add origin <paste the address you just copied>`  
5. Next on the command line, type `git push -u origin master`  
6. Go back to your repositories page on GitHub and find `my-resume` then take a look at `resume.md`  
7. You should see your name formatted in Header style  

### Step 4: Use GitHub Pages to Host Your Resume  

1. While in your `my-resume` repo, click the `Settings` tab at the top  
2. Scroll down to `GitHub Pages` and choose a theme  
3. Notice that now the `Source` section right above `Theme chooser` should now show `Master` as selected. If it doesn't, select `Master` from the dropdown  
4. Visit your new web page by opening up a browser window and typing (replace your username for 'username'): `http://username.github.io/my-resume/resume.html` (note the `.html` extension instead of `.md`)

### Step 5: Spruce Up Your Resume!  

1. Now it's time to fill in your resume with your information! For tips on what to include and how to order the information, see [this LaunchCode guide](../../../resources/LaunchCodeResumeTemplateGuide.pdf)  
2. As you add content to your `resume.md` file, play around with the Markdown syntax you've learned to make your resume look catchy and professional  
3. Remember that each time you make a change on your computer to the `resume.md` file, you'll need to repeat the steps to add and commit your changes, as well as to push them to your remote (GitHub) using `git push origin master` for your GitHub Pages site to reflect the changes you've made  

## Congratulations!  

Way to go on completing this module and getting your resume live on the web! You've come a long way and are now ready to build more complex and stylish web pages by learning HTML and CSS!  

[Start HTML and CSS Module](../../html-and-css-intro/)