# Employee Management System

A Git and GitHub assignment demonstrating repo creation, version control, branching, merging, remote repo management, and merge conflict resolution.

---

## Features

- Employee Registration
- Employee Dashboard
- Git Branching Workflow
- Merge Conflict Resolution

---

## Branch Structure

```
main
├── feature/employee-registration
├── feature/employee-dashboard
├── feature/login
└── feature/dashboard-conflict
```

---

## Screenshots

### Commit History
![Commit History](./public/image.png)

### All Branches
![All Branches](./public/branches.png)

### Successful Merge
![Successful Merge](./public/successfulMerge.png)

### Merge Conflict Resolution
![Merge Conflict](./public/mergeConflict.png)

![Add & Commit](./public/addCommit.png)

---

## Task-wise Screenshots

### Task 3 — Initialize Repository
![Init](./public/init.png)
![Screenshot](./public/Screenshot%202026-06-24%20102645.png)

### Task 4 — First Commit
![Initialise](./public/initialise.png)

### Task 5 — View Log
![Log](./public/image.png)

### Task 8 — View Diff
![Diff](./public/diff.png)

### Task 9 — Merge
![Merge](./public/merge.png)

### Task 13 — Pull from Remote
![Pull](./public/pull.png)

### Task 14 — Merge
![Merge](./public/merge.png)

### Task 15 — All Branches
![Branches](./public/branches.png)

### Task 16 — Merge & Push
![Merge 2](./public/merge2.png)
![Push](./public/push.png)

---

## Branching Strategy

A feature-based branching strategy suitable for a team of multiple developers.

### Main Branches

| Branch | Purpose |
|--------|---------|
| `main` | Stable, production-ready code |
| `develop` | Integration branch where completed features are merged before release |

### Supporting Branches

- **`feature/*`** — Created for new features.
  - e.g. `feature/employee-registration`, `feature/employee-dashboard`
- **`bugfix/*`** — Used to fix defects found during development.
  - e.g. `bugfix/login-validation`
- **`release/*`** — Created when preparing a production release.
  - e.g. `release/v1.0`

### Workflow

1. Developers create `feature` branches from `develop`.
2. Features are developed and committed independently.
3. Completed features are merged back to `develop`.
4. Bugfixes are handled through dedicated `bugfix` branches.
5. Release branches are created from `develop` for final testing.
6. Stable releases are merged into `main`.

### Benefits

- Supports parallel development by multiple developers.
- Keeps production code stable.
- Simplifies bug fixing and feature tracking.
- Reduces merge conflicts through isolated development.
