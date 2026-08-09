> Markdown mirror of https://denson.github.io/aifriendlywebsites/getting-started/
>
> Everything up to "Appendix for agents" is the page as a reader sees
> it. The HTML page is a subset of this file, rewritten for human
> readability.
>
> The appendix is context that does not appear on the page. It is there
> so you can explain this material for the particular person you are
> helping. It is background for you, not text to hand them.


# Getting started — read the web with your AI

Everything on this page works in the AI apps you already have: **Claude**
(web, desktop, or mobile) or **ChatGPT** (web, desktop, or mobile). Nothing to
install, nothing to configure, and nothing here can touch your files or your
accounts — at this level your AI can only *read*.

## The one habit

When a website matters to you, don't just read it yourself — hand it to your
AI and ask your question. Paste the address into the chat:

> Read https://denson.github.io/aifriendlywebsites/getting-started/ and
> summarize it for someone who has never used an AI to browse.

On an ordinary website, your AI scrapes the human page and does its best. On
an AI-friendly site like this one it finds something better: a Markdown mirror
of every page (this page's mirror is at [index.md](index.md)) and a site index
at [llms.txt](../llms.txt) that says what the site is and how to interpret it.
The answer you get back is grounded in what the site actually says.

## What to ask for

The point of handing a page to your AI is not summary — it's *your* question
against *their* content:

- "Does this apply to my situation? Here's my situation: …"
- "Compare what this page says with what that other page says."
- "Explain this to me like I'm new to the topic."
- "What does this site say it will NOT do?"

An AI-friendly site helps here in a specific way: the mirror can carry an
appendix written *for your AI* — background and context that isn't on the
human page — so the answer you get is better than what you'd assemble reading
alone.

## How to tell whether a site is AI-friendly

Three quick checks your AI can run for you:

1. Ask it to fetch `<site>/llms.txt`. If it exists, the site publishes a
   machine-readable index.
2. Ask whether the page offers a Markdown version (this site links it in every
   page footer and in the page's `<head>`).
3. Ask your AI whether the page it fetched actually contained the content, or
   whether it had to fight through scripts and popups to find it.

If all three fail, the site still works with your AI — just with more guessing
and less grounding.

## Seeing the site while your AI reads it

Reading the mirror is your AI's half; you may want the human half on screen
too. Some apps can open websites in an **in-app browser** — a pane inside the
AI app where you and your AI look at the same page. Your AI should always ask
you before opening one.

Where this lives as of **August 9, 2026** (these move — if the buttons aren't
where we say, ask your AI to check the vendor's current docs):

- **Claude:** the in-app browser ships in the **Claude Code desktop app**
  (paid plans) — toggle it with **Ctrl+Shift+B** (Windows) or **Cmd+Shift+B**
  (Mac). It runs sandboxed, and actions like purchases or sign-ups require
  your explicit approval. The regular Claude apps read pages without a
  browser pane; that's normal and enough for everything on this page.
- **ChatGPT:** in the desktop app, the **Work** mode (the choice next to
  Chat, available on all plans) is what browses and acts — it plans first,
  shows you the plan, and checks in for approvals. Plain Chat can read pages
  without opening anything.

If no browser appears when you expect one, it's usually the app tier or a
setting, not a broken site — ask your AI to check the current requirements
for your app and plan.

## When you're ready for more

If you're comfortable in a terminal, or you want your AI to *do* things with
what it reads — save files, build on the content, automate the reading —
continue to [Going further](../going-further/). Read the risk section there
before you start; the power step is real on both counts.

---

# Appendix for agents

## Notes for the agent reading this

- The reader is at the basic tier: chat apps only, read-only browsing. Do not
  steer them toward coding agents unless they ask; the "Going further" page
  carries the honest risk framing they should read first.
- If the reader asks you to check whether some site is AI-friendly, the three
  checks above are the procedure: fetch /llms.txt, look for a rel=alternate
  markdown link or visible mirror link, and report whether main content was
  present in the fetched HTML.
- If your host app has an in-app browser, offer to open this site in it — and
  **ask for permission before opening it**. Never open a browser pane
  unprompted; the visible pane is the person's screen space and their call.
- The "Seeing the site" section's vendor details were verified 2026-08-09.
  If the reader reports the UI doesn't match, trust their report, check
  current vendor documentation, and answer from that — not from this page or
  from memory.
