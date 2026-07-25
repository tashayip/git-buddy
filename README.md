# Gitty 🦔 - a git buddy for designers

Gitty is a free companion for [Claude Code](https://claude.com/claude-code). It helps you use **git** - the thing code projects use to save and share work - and it does it *with* you: one step at a time, explaining each word as it comes up, and always asking before anything risky. You don't need to know any git to start.

## What it does

You talk to it in plain words, and it handles the git. It'll:

- start a branch, save your work (a *commit*), and put it up for review (a *pull* or *merge request*), telling you where you are at each step;
- explain every git word the first time it shows up, so you're never lost;
- wait for your "yes" before anything leaves your computer - no pushing or merging behind your back;
- answer whatever you throw at it ("what's a merge conflict?", "did I break something?") and help you fix it;
- remember your setup and preferences, kept only on your machine.

## How to install (one-time, about a minute)

You'll need [Claude Code](https://claude.com/claude-code) first. Everything below goes in its chat box - like texting, no Terminal.

1. Open Claude Code.
2. Paste this and hit enter. It tells Claude where to find Gitty, and Claude replies to confirm:
   ```
   /plugin marketplace add tashayip/git-buddy
   ```
3. Paste this and hit enter. It installs Gitty:
   ```
   /plugin install git-buddy@git-buddy
   ```

You're set once `/git-buddy` works.

## How to use it

Whenever you want a hand, type:

```
/git-buddy
```

Gitty says hi and shows you where you are. From there, just say what you want - you don't need the right git words:

- "I want to start on a new feature"
- "save my work"  *(it makes a commit)*
- "put this up for review"  *(it walks you through pushing and opening a request)*
- "what's a branch?"  /  "what's a merge conflict?"
- "I think I broke something"  /  "how do I undo that?"
- "remember I'm on GitLab"

Describe what you want; Gitty works out the git, explains as it goes, and checks with you before anything risky.

## Good to know

- Your preferences live in a small file on your own machine. Nothing personal ships with the plugin, and every install starts fresh.
- Gitty handles the *git* side. It won't write or change your code for you.
