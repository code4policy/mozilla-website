# mozilla-website

This is just an empty repository containing a README and a picture of a fox. It also contains a HTML file that has a website with just a title.


## Instructions

### Step 0 - How to make a branch

To make a branch called `xyz`, cd into the git repo you'd like to branch. 

First, check which branch you're currently on (likely main)
```
git branch
```
To create a new branch (and switch to it), enter the following command into your console:
```
git checkout -b xyz
```
Now, when you run `git branch` you should see that the current branch is `xyz`. 

Note! To switch to an existing branch, you'll drop the `-b` flag from the `git checkout` command. E.g. to switch back to `main`, you'll use
```
git checkout main
```
And back to `xyz`: 
```
git checkout xyz
```

### Step 1 - HTML
1. Make a branch called `learn-html`
2. Follow this [HTML
Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics). Make sure you make a handful of commits along the way inside the `learn-html` branch.
3. Push the branch to GitHub and merge it into `main`
4. Switch to the main branch on your computer locally and pull the `main` branch

### Step 2 - CSS 
1. Make a branch called `learn-css`
2. Follow this [CSS Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics). Make sure you make a handful of commits along the way inside the `learn-css` branch.
3. Push the branch to GitHub and merge it into `main`
4. Switch to the main branch on your computer locally and pull the `main` branch

