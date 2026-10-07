# Student Task Manager

A collaborative web-based task tracking application built to demonstrate professional Git workflows, branch strategies, conflict resolution, and GitHub-based team collaboration.

---

## Table of Contents
- [Project Description](#project-description)
- [Team Members](#team-members)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Git Workflow](#git-workflow)
- [Branches](#branches)
- [Git Commands Demonstrated](#git-commands-demonstrated)
- [GitHub Features Demonstrated](#github-features-demonstrated)
- [How to Run](#how-to-run)
- [Screenshots](#screenshots)
- [Version History](#version-history)
- [Contributors](#contributors)

---

## Project Description
Student Task Manager is an intuitive front-end web utility engineered to help students manage academic deadlines, tasks, and daily schedules efficiently. Developed as part of a 5-day pair-based collaborative engineering assignment, this repository highlights structured Git version control, GitHub collaboration mechanisms, pull request reviews, issue tracking, and production release management.

---

## Team Members
* **Ayesha Javed** (`ayeshajaved-ds`) — Core Logic, Git Strategy, Conflict Resolution & Documentation
* **Sumaya Zahid** (`SumayaZahid`) — Repository Host, UI/UX Layout Styling, Feature Integration & Release Management

---

## Features
* **Interactive Task Creation:** Add tasks dynamically with title input validation.
* **Responsive Task List:** View pending and completed tasks with distinct status indicators.
* **Search & Filter:** Easily filter through existing tasks using the integrated search feature.
* **Clean Modern UI:** Responsive, minimalist card layout styled with contemporary UI design patterns.

---

## Technologies Used
* **HTML5:** Semantic markup and component structuring.
* **CSS3:** Modern flexbox styling, custom properties, and responsive layout design.
* **JavaScript (ES6):** Client-side DOM manipulation, event listeners, and dynamic state filtering.
* **Git:** Distributed version control, branch isolation, merge workflows, and local history tracking.
* **GitHub:** Remote repository hosting, issue management, code reviews, PR lifecycles, and releases.

---

## Git Workflow
This project strictly implemented the Feature Branch Workflow alongside pair collaboration:
1. **Repository Setup:** Origin repository initialized with main branch protection and shared collaborator access.
2. **Feature Branching:** Developers created isolated feature branches (`feature/task-form`, `feature/task-style`, `feature/task-search`) for every modular update.
3. **Commit Best Practices:** Concise, imperative commit messages outlining specific code increments.
4. **Pull Requests & Code Reviews:** Code changes were reviewed and discussed via Pull Requests before merging into `main`.
5. **Conflict Simulation & Resolution:** Handled 3-way merge conflicts manually via terminal, staged resolved states, and completed clean merges.
6. **Tagging & Releases:** Clean semantic version tagging on stable main builds.

---

## Branches
* `main`: Production-ready branch containing stable releases and merged features.
* `feature/task-form`: Form input structures and base task creation logic.
* `feature/task-style`: Visual layout enhancements, card designs, and CSS responsiveness.
* `feature/task-search`: Live task search and filtering scripts.
* `conflict-student2`: Branch configured for simulating and resolving merge conflicts on common files.
* `management`: Administrative and documentation refinement updates.

---

## Git Commands Demonstrated
* **Repository & Branch Setup:** `git clone`, `git branch`, `git switch`, `git checkout -b`
* **Staging & History:** `git add .`, `git commit -m`, `git status`, `git diff`
* **Log & Inspection:** `git log --oneline --graph --all`, `git shortlog`, `git branch -a`, `git remote -v`
* **Synchronization & Merge:** `git fetch`, `git pull origin main`, `git push origin <branch>`, `git merge`
* **Tagging:** `git tag v1.0.0`, `git push --tags`

---

## GitHub Features Demonstrated
* **Collaborator Access Management:** Fine-grained repository invite and pair access settings.
* **Issue Tracking:** Logging task requirements, assigning team members, and labeling issues.
* **Pull Requests (PRs):** Cross-branch reviews, line-by-line inspection, and PR approvals.
* **Issue Linking:** Automatically closing issues via keywords in commit messages and PR bodies (`Closes #3`).
* **Release Management:** Packaging version `v1.0.0` with tagged release assets and detailed release changelogs.
* **Repository Insights:** Visual inspection using Pulse, Contributors Graph, and Network commit trees.

---

## How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SumayaZahid/student-task-manager.git](https://github.com/SumayaZahid/student-task-manager.git)
