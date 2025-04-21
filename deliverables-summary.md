# Project Summary – Version Control Simulation

## Repository & Branch Setup

Set the repo `version-control-simulation-Paul-Tunda` and successfully cloned it locally. Encountered a misstep where `feature/header` became the default branch due to lack of initial commits on `main`.

### ✅ Resolution:

Committed and pushed `index.html` immediately after cloning to lock in `main` as the default branch before branching off.

---

## ⚔️ Merge Conflict Simulation

Created `feature/footer` to add a `<footer>` element in `index.html`. Switched to `feature/header` and added conflicting code to the same section to simulate a merge conflict.

### ⚠️ Conflict Details:

- `feature/footer`:
  ```html
  <footer>
    <p>&copy; 2025 My website</p>
  </footer>
  ```
- `feature/header`:
  ```html
  <footer>
    <p>copyright</p>
  </footer>
  ```

### ✅ Resolution:

Committed changes in `feature/header`, removed `.DS_Store` using `git rm .DS_Store`, and added it to the global `.gitignore` to avoid future noise across projects.

---

## Pull Requests & Code Reviews

- Received a peer review from Meron on my PR.
  ![Image](Screenshot%202025-04-19%20134541.png)
- Provided a code review on Meron’s repository through GitHub’s pull request interface.
  ![Image](Screenshot%202025-04-19%20041724.png)
