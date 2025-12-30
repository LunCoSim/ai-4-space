# Using Workspaces

When working on LunCoSim, you need **two repositories** open at the same time:
- **ai4space**: Guides, skills, and tutorials
- **lunco-sim**: The actual simulation code

A **workspace** lets you open both folders in one window so the AI can see and work with both.

---

## Quick Setup

### VS Code / Cursor

1. **File → Open Folder** → Select `ai4space`
2. **File → Add Folder to Workspace** → Select `lunco-sim`
3. **File → Save Workspace As** → Save as `lunco-project.code-workspace`

Done! Next time, just open the `.code-workspace` file.

### IDEs (Antigravity / Cursor / VS Code)

IDEs detect workspaces automatically when you have multiple folders open. Just use "Add Folder to Workspace" and it handles the rest.

---

## Tips

**Tell the AI which repository:**
- ❌ "Add a new guide about rovers"
- ✅ "Add a new guide about rovers to ai4space"

**Each repository has its own Git:**
- Commit changes to each repository separately
- Check which folder you're in before running git commands

**That's it!** You're ready to work with both repositories.
