---
created: Apr 02, 2025 4:29 pm
modified: Apr 03, 2025 12:17 pm
---

# Starship Odyssey Development Note

Welcome to the Starship Odyssey. This readme should give you information on how to contribute.

## Tag Explanations

For this project, writing status is tracked in the Markdown files via tags in combination with [GitHub Issues](https://github.com/ChaseTramel/starship-odyssey/issues). Here's an explanation of each of the tags.

`needsWriting` : The note or portions of it include **significant gaps** that are not at all written or just bullet points.

`needsDetail` : The note or portions of it is **partially written**, but needs more information, sometimes general information, other times specific details.

`needsRevision` : The note or portions of it are **written and complete**, but may need spelling, grammar, and wordsmithing review.

`firstDraftComplete` : The note is **complete for initial use**. Distribute in iterative ways and see how it is received.

`publicationReady` : The note is **ready to be used in final materials.**

## How to Contribute

### 1. Clone the Repo

First, fork the repository to your own GitHub account, then clone it to your local machine:
```bash
git clone https://github.com/your-username/your-fork.git
```

For **GitHub Desktop**:
1. Go to the main repo page on GitHub.
2. Click the “Fork” button in the top-right corner to create your own copy.
3. Once you're on your fork’s page, click the green “Code” button.
4. Select “Open with GitHub Desktop.”
5. Choose a local folder to clone the project into.
6. Click "Clone."

### 2. Open the Files in Your Markdown Editor

Use whatever Markdown editor you're comfortable with: [Typora](https://typora.io/), [VSCode](https://code.visualstudio.com/), [Zettlr](https://www.zettlr.com/), etc. I (and others in this project) use **[Obsidian](https://obsidian.md/)** to manage and write these files. So you might run into things like callouts (`> [!note]`) and canvases. These are Obsidian-specific features. They won’t break anything if you're not using Obsidian, but they probably won't make sense.

### 3. Make Your Changes

Write away. Use the tagging system described above to indicate the current status of a file.

Keep your edits focused and super clear. If you're fixing a small thing, that’s cool. If you're doing a big rewrite, keep track of what you did so you can drop a comment in the pull request so we know what changed and why.

### 4. Commit Your Changes

```bash
git add .
git commit -m "Example example example (needsRevision > firstDraftComplete)"
```

Then push your changes to your fork:
```bash
git push origin main
```

For **GitHub Desktop**:
1. After saving your changes in your editor, go back to GitHub Desktop.
2. You'll see your changed files listed until the "Changes" tab.
3. At the bottom left, write a very short summary of what you did.
4. Press the "Commit to Main" button

### 5. Open a Pull Request

Once you’re ready, open a pull request (PR) on GitHub. Make sure that:
- You briefly explain what you changed and why.
- You note the status tag, if relevant.
- You’re not breaking anything obvious

For **GitHub Desktop**:
1. Click the blue "Push Origin" button at the top to sync your commit to GitHub.
2. Next, GitHub will show a "Create a Pull Request" button for you to click.
3. This opens GitHub in your browser. Here you can:
	- Add a title and a description.
	- Explain what you changed, why, and what tag you used.
	- Submit the PR

### 6. I'll Review & Merge (with Comments)

I’ll read through your PR, leave any comments if needed, and then merge it into the main branch. If it needs changes, I’ll let you know what to tweak. No pressure whatsoever! We’re here to build something cool together.

## Conclusion

Let me know in Discord if you'd like a GitHub template for new pull requests.