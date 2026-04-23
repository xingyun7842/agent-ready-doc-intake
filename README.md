# Agent Ready Docs Starter

A static starter for selling or demoing an **agent-ready document cleanup** service.

It is designed for the common situation where a team has:
- PDFs
- scanned files
- proposal archives
- legal attachments
- research folders

and wants to turn them into structured markdown, manifests, and a cleaner handoff for AI workflows.

## Why This Exists

Most AI document demos jump straight to heavyweight parsing stacks, uploads, queues, or vector infrastructure.

This project starts earlier in the funnel:
- explain the offer clearly
- show what the delivery looks like
- collect interest before building a heavy backend

It is intentionally small, static, and deployable in minutes.

## What Is Included

- `index.html`
  - public landing page for a document cleanup offer
- `samples/output-preview.html`
  - sample handoff page showing manifest and markdown output
- `assets/styles.css`
  - standalone styling with no build step

## Good First Use Cases

- `docs.xingyun10x.top`
- `kb.example.com`
- internal concept validation for a service business
- a launch page before adding upload or parsing workflows

## What This Is Not

- not a parser
- not a RAG backend
- not an MCP server
- not a file processing pipeline

This is the **front-end wedge**: the part that proves demand and communicates value before the heavier system exists.

## Deploy

### Vercel

1. Create a clean public repository from this folder only.
2. Import that repository into Vercel.
3. Deploy as a static site.
4. Bind a production subdomain such as `docs.xingyun10x.top`.

### Local Preview

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Why It Can Earn Attention

The repo is narrow and legible:
- one clear use case
- one believable offer
- one sample output
- no setup pain

That makes it more shareable than a half-finished full-stack app.

## Suggested Next Steps

- add a lead form
- add 2-3 vertical variants
- add sample manifests for legal, consulting, and research teams
- later connect a real document-processing backend

## License

MIT
