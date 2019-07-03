# How to contribute my source code
This document describes the composition and operation of the hit-1163710211 team, what benefits your submitted code will bring to the hit-1163710211 project, and how we can join us.
# Contributing code via Github
ThinkPHP currently uses Git to control the version of the program. If you want to contribute source code to hit-1163710211, first get an idea of how to use Git. We currently host the project on GitHub, and any GitHub user can contribute code to us.

The way to participate is very simple, `fork` a hit-1163710211 code into your warehouse, modify it and submit it, and send us a `pull request`, we will review the code and process your application in time. After the review, your code will be `merge`d into our repository, so you will automatically appear on the contributor list, very convenient.

We hope that the code you contributed will be:
+ hit-1163710211 coding specification
+ Appropriate comments that others can read
+ Follow the Apache2 open source protocol

# GitHub Issue
GitHub provides the Issue feature, which can be used to:
+ Raise a bug
+ Proposed functional improvement
+ Feedback experience

This feature should not be used for:
+ Suggestions for revision (involving code signature and revision traceability issues)
+ Unfriendly speech

# Quick modification
**GitHub provides the ability to quickly edit files**
+ Log in to your GitHub account;
+ Browse the project file and find the file to be modified;
+ Click the pencil icon in the upper right corner to modify it;
+ Fill in `Commit changes` related content (Title is required);
+ Submit your changes and wait for CI verification and administrator merge.

 **If you need to submit a large number of edits at once, please continue reading the following**

# Complete process
1. `Fork` this project;
2. `Clone` your `fork` project locally;
3. Create a new `branch` and `checkout` the new branch;
4. Add this project to your local git repository as an `upstream` ;
5. Make changes. If your changes include additions or subtractions of methods or functions, please remember to modify the unit test file;
6. `Rebase` your branch to the upstream master branch;
7. `Push` your local repository to GitHub;
8. Submit a `pull request`;
9. Wait for CI verification (if you don't pass, repeat 5~7, GitHub will automatically update your `pull request`);
10. Wait for the administrator to handle and `rebase` your branch to the upstream master branch (if the upstream master branch has modifications).

If necessary, you can `git push -f` to force the rebase branch to its own `fork`

Never use `git push -f` to force push changes to the upstream

## Precautions
+ If you have any questions about the above process, please check out the GIT tutorial, such as [this](https://backlog.com/git-tutorial/cn/);
+ For changes to **different aspects** of the code, **create different branches** in your own `fork` project (for reasons see section 9 of the `full process`);
+ For rebase and interactive rebase operations, see [Git Interactive Rebase](http://pakchoi.me/2015/03/17/git-interactive-rebase/)

# Development environment
+ jdk：1.7/1.8 
+ eclipse 
