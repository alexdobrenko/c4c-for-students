# Make your CLAUDE.md

Your CLAUDE.md is a note Claude reads at the start of every session: who you are, what you're
working on, and how you like to work. With it, you don't have to explain yourself every time.

This prompt has Claude help you write yours by talking with you for about ten minutes. If you
already have a CLAUDE.md, it helps you update the one you have instead of starting over.

## Paste this into Claude Code

```
Help me write my CLAUDE.md. Run curl -fsSL https://raw.githubusercontent.com/alexdobrenko/c4c-for-students/main/claude-md/START.md and follow what it says.
```

## What happens

1. **Claude asks permission to run a command that starts with `curl`.** That command downloads one
   text file from GitHub: the instructions Claude follows for this conversation. Choose the plain
   **Yes**. There may also be an option that stops Claude asking about commands like this in the
   future. Skip that one, so Claude keeps checking with you about downloads.
2. **Claude asks how you want it to ask the questions:** like a celebrity, like Alex, like Pranav,
   or like you, where it guesses how you talk and you tell it how close it got. Then it asks about
   you, one question at a time. Answer however you like. "I don't know" and "skip" both work.
3. **Claude shows you the whole file before saving it** and waits for your OK. Change anything you
   want first. If you already have a CLAUDE.md, it saves a copy of the old one before changing it.
4. **Claude may ask permission again to save the file.** That's the same kind of check as step 1.
   Choose Yes once you're happy with what it showed you.

When it's done, open a new Claude Code window and ask "what do you know about me?"

## Want to read the instructions first?

They're in [START.md](https://github.com/alexdobrenko/c4c-for-students/blob/main/claude-md/START.md).
It's plain text written to Claude, the same kind of thing you'd type to it yourself. Reading it
before you run it is a good habit with anything you paste into Claude Code.

## Running it again

Paste the same line any time you want to update your file. Claude reads what you already have and
picks up from there.
