# Gitty 🦔 - a git buddy for designers

Gitty is a free companion for [Claude Code](https://claude.com/claude-code) that helps you use **git** - the tool code projects use to save and share changes. It walks you through everything one step at a time, explains each word as it comes up, and checks with you before anything risky. If git has always felt confusing, Gitty is the friend who does it with you.

## What it does

- **Walks you through the whole flow** - starting a branch, saving your work (a *commit*), and putting it up for review (a *pull* or *merge request*) - always telling you where you are and what's next.
- **Explains as it goes** - every git word is defined the first time it appears, in plain language. No prior git knowledge needed.
- **Keeps you safe** - it says what each step does and waits for your "yes" before anything leaves your computer. It won't push or merge behind your back.
- **Answers questions** - ask it anything ("what's a merge conflict?", "did I break something?") and it explains, then helps you fix it.
- **Remembers you** - your setup and preferences, saved only on your own machine.

## How to install (one-time, about a minute)

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

You'll know it worked when you can run `/git-buddy`.

## How to use it

Any time you want a hand with git, type:

```
/git-buddy
```

Gitty says hi and shows you where you are. Then just talk to it in plain words - you don't need to know the right git terms. For example:

- "I want to start on a new feature"
- "save my work"  *(it makes a commit for you)*
- "put this up for review"  *(it walks you through pushing and opening a request)*
- "what's a branch?"  /  "what's a merge conflict?"
- "I think I broke something"  /  "how do I undo that?"
- "remember I'm on GitLab"

Describe what you want, and Gitty figures out the git part - explaining each step and checking with you before anything risky.

## Good to know

- Gitty keeps a small memory of your preferences on your own machine. Nothing personal ships with the plugin, and every install starts fresh.
- Gitty guides the *git* side; it won't write or change your code for you.
