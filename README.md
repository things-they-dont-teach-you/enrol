# Things They Don't Teach You in School

Free courses on the practical things school skipped: tax, money, investing, your rights, wellbeing and more.
An AI assistant asks what you need, downloads only the courses that apply to you and your
country, then tutors you through them.

> [!WARNING]
> **Beta.** Each course has a status: `planned` (not written yet), `draft` (written, not yet
> reviewed by a qualified professional, so may contain mistakes; don't rely on it for real
> decisions) or `published` (reviewed).
>
> **Are you a tax practitioner, financial adviser, dietitian, doctor or other professional?**
> We're looking for people to review lessons in their field.
> [Offer to review](https://github.com/things-they-dont-teach-you/enrol/issues/new?template=volunteer-reviewer.yml)
> or use the [contact form](https://things-they-dont-teach-you.github.io/#contact).

## Easiest start: any AI chat app

No downloads needed. Paste this into Claude, ChatGPT, Gemini or a similar app, on your phone or
computer:

```
Be my tutor. Please read https://things-they-dont-teach-you.github.io/start.html and follow its instructions.
```

When you stop, the tutor gives you a progress card. Save it, and paste it into a new chat next
time to carry on.

## Start on your computer, with files

This repository is for learners who'd rather keep courses and progress as files on their
computer. You need [git](https://git-scm.com/downloads) and an AI command-line tool, such as
[Claude Code](https://claude.com/claude-code), Codex or Gemini CLI.

```sh
git clone https://github.com/things-they-dont-teach-you/enrol.git school
cd school
claude
```

Then say hello. The assistant runs a short survey and downloads your courses into this folder:

```
school/
  profile.md           your survey answers, kept on your computer only
  south-african-tax/
  money-basics/
```

To start a course, open its folder and run your AI tool there: `cd south-african-tax && claude`.

Run the AI tool in `school/` again any time to add courses or update the ones you have.

## Your privacy

Your answers and your course work stay on your computer. Nothing you write is committed or
uploaded. Your AI tool's provider does see your conversation, so don't share ID numbers,
account details or anything else you would not put in an email.

## This is not advice

The courses explain how things work and point you to official sources. They are not tax,
legal, financial or medical advice. Rules change; check the official source before you act.

## Missing a course?

[Request a course](https://github.com/things-they-dont-teach-you/enrol/issues/new?template=request-course.yml),
or [build one](https://github.com/things-they-dont-teach-you/staff-room).
