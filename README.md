# Prompt Coach

A free skill for Claude that grades any prompt before you use it.

Paste a prompt you're about to give Claude, ChatGPT, Gemini or Copilot and get:

- a **score out of 100** on six habits: goal, context, audience, format, constraints and a quality bar
- a one-line note on each habit, pointing at your own words
- **the one fix** that would help most
- **a stronger version** of your prompt, with [brackets] where only you know the details
- a free 5-minute exercise to practice the habit on a real task

It reviews your prompt; it never runs it.

## Example

> **You:** grade this prompt: "make me a study plan for finals"
>
> **Prompt Coach:** **Score: 0/100.** Warm-up. Let's fix it.
> ✗ Goal: "a study plan" doesn't say what kind or how long...
> **The one fix:** add your subjects, exam dates and hours a day, and ask for a day-by-day table...

## Install

**Claude (claude.ai or the desktop app):**
1. Download `prompt-coach-claude-skill.zip` from the [latest release](https://github.com/aiexercises/prompt-coach/releases/latest).
2. In Claude: **Settings → Capabilities → Skills → Upload skill**, and choose that ZIP.
3. In any chat, paste a prompt and say "grade this prompt".

**Claude Code:**
```
/plugin marketplace add aiexercises/prompt-coach
/plugin install prompt-coach@aiexercises
```
Or copy `skills/prompt-coach` into `~/.claude/skills/`.

## Practice for real

The coach grades the prompt. To see what the AI actually does with it, practice on [AI Exercises](https://aiexercises.ai/?utm_source=github&utm_medium=referral&utm_campaign=prompt-coach): thousands of 5-minute tasks from work, school and everyday life, where you write the prompt, the AI runs it, and the answer gets graded. There's also a free [Prompt Grader](https://aiexercises.ai/prompt-grader/?utm_source=github&utm_medium=referral&utm_campaign=prompt-coach) on the web, no sign-up.

Made by the AI Exercises team. MIT license.
