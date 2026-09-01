Nice, that's the main piece done. Once students accept, they'll have push access to the repo.

Next: update the README so it matches the branch-per-student flow instead of the fork instructions. Go to `README.md` → click the pencil (edit) icon → replace the content with this → commit:

```markdown
# class-27a-backspace

**redAcademy Class 27A — Backspace Technologies Python Track**

This repo is where Class 27A submits Python assignments.

## Setup (do this once)

1. Accept the collaborator invite (check your email or github.com/notifications).
2. Clone the repo:
   ```
   git clone https://github.com/cam-redacademy/class-27a-backspace.git
   cd class-27a-backspace
   ```

## Submitting an assignment

1. Make sure you're up to date:
   ```
   git checkout main
   git pull
   ```
2. Create your own branch, named after yourself:
   ```
   git checkout -b student/your-name-assignment1
   ```
3. Add your code, then commit:
   ```
   git add .
   git commit -m "Assignment 1: short description"
   ```
4. Push your branch directly to this repo:
   ```
   git push origin student/your-name-assignment1
   ```
5. On GitHub, open a **Pull Request** from your branch into `main`.
6. Wait for feedback/merge from the instructor.

## Rules
- One branch per assignment, named `student/your-name-assignmentX`.
- Do not push directly to `main` — it's protected and will be rejected.
- Do not push to another student's branch.
```


