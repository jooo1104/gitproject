# pygit

**Just enough of a Git client to create a repo, commit, and push itself to GitHub.**

This project is a minimal Git client written in Python, inspired by [Ben Hoyt’s pygit](https://benhoyt.com/writings/pygit/). It demonstrates how to build a tiny version of Git from scratch with just enough functionality to:

- Initialize a repository
- Commit changes
- Push commits to GitHub

This is ideal for learning how Git works under the hood and for experimenting with Python’s file I/O and subprocesses.

---

## 🚀 Features

- Create a `.git` directory and set up the repository
- Add files to the staging area
- Commit changes with a message
- Push commits directly to a remote GitHub repository

---

## 📦 Installation


Clone this repository:

```bash
git clone https://github.com/<your-username>/pygit.git
cd pygit



"""
python pygit.py init        # Initialize a new repo
python pygit.py add <file>  # Add a file to staging
python pygit.py commit -m "Your commit message"
python pygit.py push        # Push to GitHub
"""
