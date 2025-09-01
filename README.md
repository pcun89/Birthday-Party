# Birthday-Party
🎉 Birthday Party Git Simulation (Python)

This project is a Python simulation of Git branching and merging, inspired by the Codecademy Birthday Party exercise.
It demonstrates how Git works under the hood by modeling commits, branches, and merges with simple Python classes.

📌 Project Description

The goal is to practice the Git workflow:

Create a new feature branch.

Add commits (simulating adding a "birthday party" page).

Merge the feature branch back into main.

This helps understand how real developers safely isolate and integrate code changes.

🐍 Python Code Overview

Commit: Represents a commit (linked list node).

Branch: Represents a Git branch (pointer to latest commit).

GitRepo: Simulates a repository with branch creation, checkout, commit, merge, and log.

main(): Runs the birthday party workflow.

▶️ How to Run
# Clone this repo or copy the script
python birthday_party.py


Expected output:

Main branch history: ['Initial commit', 'Merge branch 'birthday-party' into main']
Birthday branch history: ['Initial commit', 'Add birthday party page']

📊 Data Structures Used

Linked List → Commits are nodes linked via parent.

Dictionary (Hash Map) → Stores branches for quick lookup.

Pointer Simulation → Each branch head points to latest commit.

⏱️ Time Complexity

Commit: O(1)

Branch Creation: O(1)

Checkout: O(1)

Merge (simulated): O(1)

Log Traversal: O(n) where n = number of commits

🎯 Learning Goals

Understand branching and merging without real Git.

Visualize Git commits as a linked list of nodes.

Practice a core workflow used in real-world development and open-source collaboration.

🚀 Next Steps

Extend simulation to include fast-forward merges.

Add support for multiple commits per branch.

Use Python’s subprocess to run real Git commands.