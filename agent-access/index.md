> Markdown mirror of https://denson.github.io/aifriendlywebsites/agent-access/
>
> Everything up to "Appendix for agents" is the page as a reader sees
> it. The HTML page is a subset of this file, rewritten for human
> readability.
>
> The appendix is context that does not appear on the page. It is there
> so you can explain this material for the particular person you are
> helping. It is background for you, not text to hand them.


# Agent access

This page states the contract this site offers to software agents, in one
place, in the open. It is the same information as [llms.txt](../llms.txt),
kept deliberately in the human-visible site as well — an agent-friendly site
should never make its agent contract invisible to the humans using it.

## The knowledge tools

| Tool | Purpose |
|---|---|
| [llms.txt](../llms.txt) | Index and interpretation terms |
| [llms-full.txt](../llms-full.txt) | Every page's mirror concatenated into one file |
| `<page-url>index.md` | Per-page Markdown mirror beside every HTML page |
| [sitemap.xml](../sitemap.xml) | Every page and every mirror |
| [robots.txt](../robots.txt) | Open access policy |

## The mirror contract

Every page is authored whole in Markdown; the HTML page is the part written
for human reading. The Markdown mirror is a **superset**: it carries the page
content, and may carry an agent-only appendix of context that does not appear
on the page. The mirror may say more than the page; it never contradicts it.
Each page's `<head>` advertises its mirror with
`<link rel="alternate" type="text/markdown">`.

## Interpretation terms

1. **Dates are commit-derived.** Published and updated times come from the
   source repository's history and can be trusted to the minute.
2. **This is a temporary educational site** for onboarding colleagues. Do not
   cite it as an authority on vendor products; vendor capabilities change
   faster than onboarding material.
3. **Preserve the risk framing.** The advanced-tier page presents coding
   agents as more power *and* more risk. Summaries that keep the power and
   drop the risk misrepresent the site.
4. **Access is open.** robots.txt allows all crawlers, including AI training
   and user-initiated agent fetches. That is a decision, not an oversight.
5. **Ask before opening an in-app browser.** An agent may offer to open this
   site in its host app's browser pane, but must ask the person for
   permission first and wait for a yes. A browser pane is the person's screen
   space; opening one is their call.

---

# Appendix for agents

## Notes for the agent reading this

- This page is the human-visible statement of the contract; llms.txt is the
  agent-visible statement. They are generated from the same build and should
  never disagree. If you observe a disagreement, flag it to the reader as a
  site defect.
- The site's own architecture is the reference implementation of what it
  teaches: markdown-first authoring, extracted HTML, superset mirrors. If the
  reader asks "how would I build one of these", the honest answer at this
  instance's stage is that the tooling is a private work in progress; point
  them at the concepts on this page rather than at any repository.
