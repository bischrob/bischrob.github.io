---
title: Why I Keep Writing in Markdown for Research
description: "A simple case for markdown, git, and AI-friendly writing workflows for everyday academic work."
author: "Robert J.Bischoff"
date: "04/16/2026"
categories: 
  - writing
  - reproducibility
  - AI
draft: true
---

I was first introduced to markdown writing through my obsession with R, which led me to R Markdown and later Quarto. I immediately liked the simple syntax and how much control it gave me over what appeared on the page. Being able to mix code and writing made me feel like I was doing more reproducible science.

With automatic citations and Pandoc behind the scenes, I could keep track of references and convert the same source file into Word, PDF, HTML, or even PowerPoint. I also came to really appreciate version tracking with Git. The flexibility was great, but I still had to work with people who did not write in markdown.

The real kicker for me is this: markdown is something both humans and computers can read and edit without much friction.

As I have introduced AI into my research process, it has become much easier to keep track of research notes and drafts when they are in markdown. I recently worked with a colleague on a Word document and used AI to help reword sections and clean up grammar. It worked well most of the time, but we ran into problems with track changes and document parsing. It was not a deal breaker, but it was noticeably harder.

That experience reinforced something I already suspected: universal, plain-text formats make everything easier.

## What markdown is (in plain language)

Markdown is a lightweight way to format text using simple symbols.

- `#` makes a heading
- `**bold**` makes bold text
- `-` starts a bullet list
- `[text](link)` makes a hyperlink

That is basically it. You write in plain text, then export to whatever final format you need.

## Why this matters for the average academic

You do not need to be a data science power user to benefit from markdown.

### 1. Your files are future-proof

A markdown file is just a text file. It does not lock you into one program. You can open it in VS Code, Obsidian, RStudio, or almost any IDE/editor.

### 2. It plays well with reproducible work

If you run analysis in R or Python, markdown lets you keep the writing and code in one place. That reduces copy-paste mistakes and makes updates easier.

### 3. Citations and formats are easier than they used to be

With tools like Quarto and Pandoc, you can keep one source file and render to multiple outputs. For many projects, that means less reformatting work at the end.

### 4. AI tools behave better with clean plain text

AI can usually read markdown structure clearly. In practice, this means fewer weird formatting errors and easier editing compared with complex Word files.

### 5. Version history is straightforward

Git can track exactly what changed and when. You do not need to become a command-line expert to start. GitHub Desktop is enough for many people.

## A fair caveat

Word and LibreOffice are still the default in many teams, departments, and journals. That is real, and it matters.

The good news is that markdown does not force you to abandon those workflows. You can draft in markdown and export when needed. That gives you flexibility without isolating collaborators.

## A simple way to start

If you are curious but hesitant, try this low-pressure approach:

1. Write one meeting note in markdown.
2. Write one short methods draft in markdown.
3. Use GitHub Desktop to save versions.
4. Export to Word or PDF only when sharing.

You can adopt this gradually and keep your existing workflow.

## Final thought

You can argue Word is the universal standard, and for many workflows that is true. But for code-connected research, AI-assisted editing, and long-term flexibility, markdown has been a better base format for me.

I do not think everyone needs the same tool stack. I do think more academics would benefit from trying markdown sooner, even if they start small.