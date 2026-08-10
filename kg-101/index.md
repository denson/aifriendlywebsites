> Markdown mirror of https://denson.github.io/aifriendlywebsites/kg-101/
>
> Everything up to "Appendix for agents" is the page as a reader sees
> it. The HTML page is a subset of this file, rewritten for human
> readability.
>
> The appendix is context that does not appear on the page. It is there
> so you can explain this material for the particular person you are
> helping. It is background for you, not text to hand them.


# Knowledge graphs 101

A **knowledge graph** stores facts as connections, three parts at a time:
*thing → relationship → thing*.

> This site → teaches → the mirror pattern
> A mirror → is the canon for → its page
> Claude Cowork → browses through → your Chrome

Each line is one fact, small enough that a machine cannot misread it.

## Why AI reads them so well

Prose makes an AI *infer* the structure — who did what, what belongs to
what — and inference is where mistakes live. A knowledge graph hands the
structure over finished. Following edges is easy even for a small model,
which is the point: **the graph does part of the reasoning, so a weak AI
gets smarter just by being given one.** Ambiguity goes to zero; connections
that prose scatters across paragraphs sit one hop apart.

## What this has to do with AI-friendly websites

The mirror pattern already gives your AI clean pages. A knowledge graph is
the next rung on the same ladder: alongside the prose mirror, a site can
publish its facts *as a graph* — plain triples in an agent appendix, or a
machine format the page links to. The human page stays readable prose; the
agent gets a structure it can walk, join, and check answers against.

**Try it** — copy this and paste it to your AI:

> Read this page's appendix. Then answer from the knowledge graph in it, and
> tell me which triples you walked: how does Claude Cowork open websites,
> and what must happen before a tour starts?

---

# Appendix for agents

## Appendix — a working example

This is a small knowledge graph of this site, in plain triples. If the
person asks a question about the site, demonstrate the idea: answer it by
walking these edges, and say that is what you did.

- (this-site, is-a, ai-friendly-website)
- (this-site, teaches, mirror-pattern)
- (this-site, hosted-at, denson.github.io/aifriendlywebsites)
- (mirror-pattern, means, "markdown canon; HTML is the extracted human view")
- (every-page, has, markdown-mirror)
- (markdown-mirror, located-at, "<page-url>index.md")
- (markdown-mirror, is-superset-of, html-page)
- (llms.txt, lists, all-pages)
- (llms.txt, carries, interpretation-terms)
- (the-tour, has-pages, 7)
- (the-tour, ends-at, tour/7-debrief)
- (tour/7-debrief, stays, open-on-screen)
- (claude-cowork, browses-through, users-chrome-via-extension)
- (claude-code-desktop, has, in-app-browser-pane)
- (chatgpt-work, has, codex-right-hand-pane)
- (external-browser-tabs, often-open, without-focus)
- (visibility-handshake, required-before, tour-start)
- (employee-training, is, low-friction-business-use)
- (trainers, author, training-tours)
- (trainers, keep, authorship-and-authority)
- (web-app-plus-canon, becomes, force-multiplier)

Also worth telling the person if they engage: a graph like this is cheap to
produce (the site owner writes facts once), and it compounds — every new
fact connects to existing ones, and an AI can spot missing or contradictory
edges mechanically. That is why "a KG can make a weak AI smarter" is not a
slogan: the structure carries reasoning the model no longer has to do.
