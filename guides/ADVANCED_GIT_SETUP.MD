# Advanced Guide: Git, GitHub & SSH

This guide is for users who want to save their work to the cloud (GitHub) and share it with others.

## What is Git and GitHub?
*   **Git**: Think of it as a "Time Machine" for your project. It saves snapshots of your files so you can go back if you make a mistake.
*   **GitHub**: This is the "Cloud" where you store those snapshots. It allows you to share your work and collaborate with others.

## The "SSH" Barrier (Read This First)
To upload files to GitHub securely, you need digital "keys" called SSH keys.
*   **Private Key**: Stays on your computer (like your house key).
*   **Public Key**: You give this to GitHub (like the lock on your door).

When they match, GitHub knows it's really you.

## Step-by-Step Setup

### Phase 1: Generate Your Keys
1.  Open your terminal (or Git Bash on Windows).
2.  Copy and paste this command (replace with your email):
    ```bash
    ssh-keygen -t ed25519 -C "your_email@example.com"
    ```
3.  Press **Enter** slightly blindly until it asks for a passphrase (you can leave it empty for now by pressing Enter again).
4.  It will say "Your identification has been saved in...".

### Phase 2: Give the Key to GitHub
1.  Display your new public key by running:
    ```bash
    cat ~/.ssh/id_ed25519.pub
    ```
2.  Copy the long string of text that appears (starts with `ssh-ed25519`).
3.  Go to [GitHub Settings > SSH Keys](https://github.com/settings/keys).
4.  Click **New SSH key**.
5.  Give it a Title (e.g., "My Laptop").
6.  Paste the key into the "Key" box.
7.  Click **Add SSH key**.

### Phase 3: Test It
Run this command in your terminal:
```bash
ssh -T git@github.com
```
If you see `Hi username! You've successfully authenticated`, you are ready!

## Basic Workflow
Once you are set up, here is how you save your work:

1.  **Clone** (Download a repo for the first time):
    ```bash
    git clone git@github.com:LunCoSim/ai4space.git
    ```
2.  **Add** (Tell Git which files to save):
    ```bash
    git add .
    ```
3.  **Commit** (Take a snapshot):
    ```bash
    git commit -m "Describe what you did"
    ```
4.  **Push** (Upload to GitHub):
    ```bash
    git push
    ```
