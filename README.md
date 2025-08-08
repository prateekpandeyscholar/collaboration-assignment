# Collaborative Development Assignment

## Overview
You and your teammate(s) will collaborate on this repository to practice:
- Creating branches
- Opening Pull Requests (PRs)
- Reviewing and approving PRs
- Merging changes
- Following a branch naming convention

This assignment will be **autograded** to verify collaboration.

---

## Instructions

### Step 1: Accept the Assignment
One team member accepts the GitHub Classroom invitation and **adds teammates**:
1. Go to **Settings → Collaborators & teams → Manage Access**.
2. Invite your teammate(s) via their GitHub username.

---

### Step 2: Create a Branch
Each member should:
1. Create a branch named `branch-rollno` (replace `rollno` with your roll number in the format 231B227).
   ```bash
   git checkout -b branch-231B227
   ```
2. Edit the `team_greetings.md` file.
3. Add your roll number and a short greeting in this format:
   ```
   231B227: Your Greeting Here
   ```

---

### Step 3: Commit and Push
```bash
git add team_greetings.md
git commit -m "Added greeting for <Roll No>"
git push origin branch-<Roll No>
```

---

### Step 4: Open a Pull Request
1. Go to your repository on GitHub.
2. Click **Compare & Pull Request**.
3. Request **review** from a teammate.
4. Teammate approves and merges your PR into `main`.

---

### Step 5: Review a Teammate’s PR
- Each member must approve at least one PR from another member.

---

## Autograding Rules
You will PASS if:
1. `team_greetings.md` exists ✅
2. At least two valid roll numbers are present ✅
3. At least two unique commit authors are found ✅
4. At least two correctly named branches (`branch-rollno`) exist ✅

---

💡 **Tip:** This assignment is about process, not coding skill. Make sure everyone participates.
