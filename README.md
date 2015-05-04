---
tags: git, github, bash, command line, learn.co, tutorial
languages: bash
---

# Your First Lab

On Learn, labs are exercises you have to complete.

The goal of this lab is to practice the workflow to complete a lab and to see if you can make a new file or directory using terminal.

**Make sure you accept the invite on [Github](https://github.com/learn-co-students) to the learn.co student organization**

To complete this lab you will have to:

1. Fork the lab via github.
2. Clone your fork.
3. Solve the Lab
4. Push that commit to your fork.
5. Open a Pull Request for your fork.

## 1. Forking from Github

Forking is the process of making a personal remote copy of the Learn lab.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-1.png" alt="Git Workflow 1">

To get started, in Learn click the title of the lab to go to Flatiron School's copy of the lab on Github.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-0.jpg" alt="Ironboard Labs Step 0">

Next on Flatiron's Github page for the lab click the Fork button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1.jpg" alt="Ironboard Labs Step 1">

Then select your personal Github account as the location to fork to.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-1b.jpg" alt="Ironboard Labs Step 1B">

## 2. Clone Your Fork

Cloning is the process of making a local copy of the lab from your personal remote on Github. 

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-2.png" alt="Git Workflow 2">

To clone, click the copy button next to the Clone URL to copy it to your clipboard.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2.jpg" alt="Ironboard Labs Step 2">

Next, in Terminal navigate to the parent directory where you would like to place this lab. Then type ♥ `git clone <paste the clone URL here>`  
Note: You should replace the &lt;paste the clone URL here&gt; including the &lt; and &gt; symbols in the snippet above with your actual clone URL by pressing command+v on mac or ctrl+v on windows. Example: git clone git@github.com:jongrover/html-album-cover-fe-004.git

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-2b.png" alt="Ironboard Labs Step 2b">

## 3. Solving this Lab

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-3.png" alt="Git Workflow 3">

Now that you have forked and cloned your fork, your goal is simple. Just create a new file within this lab.

1. You should be cd'd into this lab's directory. Confirm that your working directory in terminal is this lab: `pwd`

You should see something like: `/Users/avi/first-lab`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/1-solving-the-lab.png)

2. Simply create a file. It doesn't matter what you call it.

`touch my-new-file.txt`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/2-solving-the-lab.png)

3. Once you've done that, run `learn` on your terminal, which will run one test that's in the `spec/` folder. This test is looking to see that you've added a new file. If you have the test passing on your computer, you should see something like this on Learn, indicating the local build is passing:

![Local Build](https://s3-us-west-2.amazonaws.com/readme-photos/ib-3.png)

4. Add it to the repo, staging it for commit.

`git add my-new-file.txt`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/3-solving-the-lab.png)

5. Confirm that the file is staged for commit with `git status`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/4-solving-the-lab.png)

6. Commit the file.

`git commit -am "My first commit"`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/5-solving-the-lab.png)

## 4. Push Your Code to Github

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-4.png" alt="Git Workflow 4">

After adding and commiting your most recent work next we want to push our work up to our personal Github remote (origin). 

`git push origin master`

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/6-solving-the-lab.png)

Go to github and confirm the push.

![1](http://flatiron-videos.s3.amazonaws.com/ironboard/ironboard-tutorial/7-solving-the-lab.png)

## 5. Opening a Pull Request

Submitting a pull request can be described as the process of asking the maintainer of the Learn lab (upstream remote) to consider pulling (fetching & merging) in your work from your personal remote copy (origin remote). This enables your instructor to see your solution for the lab.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/git-workflow-5.png" alt="Git Workflow 5">

To do so, in Learn click the title of the lab to go to Flatiron Schools copy.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-0b.jpg" alt="Ironboard Labs Step 0b">

This will take you back to the Learn copy you originally forked from. Then click the Pull Requests link from the right sidebar.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4.jpg" alt="Ironboard Labs Step 4">

Next, click the New pull request button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4b.jpg" alt="Ironboard Labs Step 4b">

Then click the compare across forks link.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4c.jpg" alt="Ironboard Labs Step 4c">

Then click the drop down menu for the head fork and select yourself from the list.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4d.jpg" alt="Ironboard Labs Step 4d">

After reviewing the comparison code and making sure it shows your solution, click the Create pull request button.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4e.jpg" alt="Ironboard Labs Step 4e">

Then click Create pull request button again.

<img width="100%" height="auto" src="http://ironboard-curriculum-content.s3.amazonaws.com/front-end/lab-assets/ironboard-labs-step-4f.jpg" alt="Ironboard Labs Step 4f">

That's it your done! Now go back to Learn and you should be able to proceed.