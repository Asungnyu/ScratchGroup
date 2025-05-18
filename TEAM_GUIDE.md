## 👩‍💻👨‍💻 Team Workflow/Branching Guide

Welcome to the Scratch Group project!
This guide outlines how we work together using git Git branches and pull requests.

---
so far here are the branches created and the structure
## 🧱 Branch Structure

 ___________________________________________________________________________________________________________________
| Branch       | Purpose                                          | Who works/pushes to this branch?                |
|--------------|--------------------------------------------------|-------------------------------------------------|
| `main`       | all reviewed and stable codes will be here       | Lead only (via Pull Requests)                   |
| `dev`        | integration & comparison branch for all features | Every other person (PRs not necessary)          |
| `features/*` | feature specific (Tasks from a specific member)  | Each teammate individualy (e.g. features/Berti) |
 -------------------------------------------------------------------------------------------------------------------
-> 'features/Berti' branch has been created for user = Bertimondmubukwefi@gamil.com, and initial PR already.

---

## 🔐 Protected Branches

### `main` branch is protected:
 - 🚫 no direct pushes allowed
 - ✅ pull requests required
 - ✅ 1 review required
 - status checks (when implemented) must pass

 ---

## ✅ How to contribute

 - sign in with username and email from terminal (git config --global user.name "your-username" && git config --global user.email "your email" [execute one after the other] )
 - clone repository (git clone https://github.com/Asungnyu/ScratchGoup.git)
 - cd ScratchGroup
 - fetch all branches available for the repository (git fetch origin)
 - swutch into the branch created for you (git checkout features/*). replace 'features/*' with the features/* branch listing that has your name at the end.

  when you're done with your work on a feature given to you,

 - add files and commit (git add . && git commit -m "message" [execute one after the other] )
 - push to your branch (git push origin features/*)

** if a branch has not been created for you,
 -  create a new branch
 - after working, add and commit to it
 - push to the branch
 - go to github.com/Asungnyu/ScratchGroup.git
 - click on pull request tab
 - create a new pull request to compare dev and your newly created branch.