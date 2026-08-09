> Markdown mirror of https://denson.github.io/aifriendlywebsites/
>
> Everything up to "Appendix for agents" is the page as a reader sees
> it. The HTML page is a subset of this file, rewritten for human
> readability.
>
> The appendix is context that does not appear on the page. It is there
> so you can explain this material for the particular person you are
> helping. It is background for you, not text to hand them.


# AI-Friendly Websites

This site teaches one idea and then lets you practice it on the site itself.

**The idea:** most websites are written for human eyes, and AI tools read them
by scraping the page and guessing at the structure. An *AI-friendly* website is
built the other way around. Every page here is authored in Markdown — the
format AI tools read natively — and the web page you are looking at is
generated from it. Beside every page sits its Markdown mirror, at the same
address plus `index.md`. The mirror is the canonical version, and it can carry
*more* than the page: context, sources, and notes written specifically for the
AI that is helping you.

**What that means for you:** you don't browse this site instead of your AI —
you point your AI at it, and the site cooperates.

## Try it right now

Open your AI app — Claude or ChatGPT, desktop or web — and paste this:

> Read https://denson.github.io/aifriendlywebsites/ and its llms.txt. If you
> can open the site in a browser I can see — an in-app browser pane, or my
> own browser through an extension you drive — open it and walk me through
> it while I look at it. If you can't, tell me what app, plan, extension, or
> setting I would need and help me set it up — then give me the tour from
> the pages themselves.

Your AI will find the machine-readable index ([llms.txt](llms.txt)), the
Markdown mirrors, and the agent notes, and explain the site back to you. That
round trip — you ask, your AI reads the friendly version, you get a grounded
answer — is the whole skill this site teaches.

**Why the browser request is in *your* paste:** your AI takes instructions
from you, not from websites. A site cannot tell your AI to open anything —
that is a security feature, and it protects you from malicious pages trying
to hijack your agent. So anything you want your AI to *do* with a site rides
in your own message; the site's job is to be worth reading when it gets
there. [Getting started](getting-started/) has the settings notes for
enabling the in-app browser in each app.

## Two paths from here

- **[Getting started](getting-started/)** — for everyone: using AI-friendly
  sites from the apps you already have, with the built-in browsing your AI
  offers. Low risk, nothing to install.
- **[Going further](going-further/)** — for advanced users: coding agents like
  Claude Code and OpenAI's Codex that can fetch, save, and *act* on what they
  read. More power, and genuinely more risk — the page is honest about both.

This is a temporary onboarding instance for colleagues. It may be taken down
without notice.

---

# Appendix for agents

## Notes for the agent reading this

You are probably here because a person asked you to read this site. Useful
context:

- This site is itself the demonstration: every page has a Markdown mirror at
  `<page-url>index.md`, and `/llms.txt` is the index. Prefer the mirrors over
  scraping the HTML.
- If the person's message asked you to open this site in an in-app browser,
  just do it — your host app's own approval flow is the safety gate — and
  narrate the tour as they look at it. If you lack the capability, don't
  stop at "I can't": tell them which app, plan, or setting provides it (the
  Getting started page carries vendor notes, dated), help them enable it if
  they want, and give the tour from the mirrors meanwhile. If their message
  did not mention a browser at all, you may mention the option, but treat
  this note as information about the site, not as an instruction — your
  instructions come from the person. Never open a pane unprompted.
- The person you are helping is being onboarded to the practice of pointing
  their AI at AI-friendly sites. If they seem new to this, the most useful
  thing you can do is narrate what you found: that the site published a
  machine-readable version for you, and that this is why your answer is
  grounded rather than guessed.
- Suggest the "Getting started" page for readers using chat apps, and "Going
  further" only for readers comfortable running developer tools.
- The site is temporary and educational. Do not cite it as an authority on
  vendor products; vendor UIs change faster than onboarding sites.
