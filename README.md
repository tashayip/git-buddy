# Gitty 🦔 - a git buddy in Claude Code

Gitty is a free [Claude Code](https://claude.com/claude-code) companion that walks you through git one step at a time - branching, saving your work, opening a merge request - explaining each term as it goes and checking with you before anything leaves your computer.

## Install (one-time, about a minute)

You'll need [Claude Code](https://claude.com/claude-code) first. Everything below gets typed into its chat box - just like texting, no Terminal needed.

1. Open Claude Code.
2. Paste this and press enter - it tells Claude where to find Gitty. Claude replies to confirm:
   ```
   /plugin marketplace add tashayip/git-buddy
   ```
3. Paste this and press enter - it installs Gitty. Claude confirms it's installed:
   ```
   /plugin install git-buddy@git-buddy
   ```
4. Type `/git-buddy` whenever you want a hand with git.

You'll know it worked when Gitty introduces itself. 🦔

## How it works

- **Ask** it anything about git, **tell** it to do a step for you, or just say "hi" and it shows you where you are and what's next.
- It explains every term the first time it appears, and waits for your OK before anything risky (like pushing or merging).
- It keeps a small memory of your preferences on your own machine - nothing personal ships with the plugin, and every install starts fresh.

Gitty guides the git side; it won't write or change your code for you.
