# Git Commands Reference

##  Setup & Config

### git --version
**What it does:** Checks if Git is installed and shows the version  
**Example:**
git --version

### git config --global user.name
**What it does:** Sets your name for all Git commits  
**Example:**
git config --global user.name "Your Name"

### git config --global user.email
**What it does:** Sets your email for all Git commits  
**Example:**
git config --global user.email "you@example.com"

Changes Made to understand pull requests

### git config --global --list
**What it does:** Shows your Git configuration  
**Example:**
git config --global --list


##  Basic Workflow

### git init
**What it does:** Creates a new Git repository in the current folder  
**Example:**
git init

### git status
**What it does:** Shows the current state of your files (tracked/untracked/staged)  
**Example:**
git status

### git add
**What it does:** Adds files to the staging area  
**Example:**
git add README.md

### git commit -m
**What it does:** Saves staged changes as a commit  
**Example:**
git commit -m "Add README file"


## Viewing Changes

### git diff
**What it does:** Shows what has changed but not yet staged  
**Example:**
git diff

### git log
**What it does:** Shows commit history  
**Example:**
git log

### git log --oneline
**What it does:** Shows commit history in short form  
**Example:**
git log --oneline

## Branching

### git branch
**What it does:** Lists or creates branches  
**Example:**
git branch

### git switch
**What it does:** Switches to another branch  
**Example:**
git switch main

## git pull
**What it does:**Fetches changes from the remote repository and merges them into your current branch.
**Example:**
git pull

## git push
**What it does:**Uploads your local commits to the remote repository.
**Example:**
git push

## git merge
**What it does:**Combines another branch into your current branch.
**Example:**
git merge feature-branch
