# Agent Ready Doc Intake

Turn messy documents into agent-ready intake flows.

This repository is a static-first starter for teams that already have PDFs, scans, proposal folders, and attachments, but do **not** want to begin with a heavyweight parser, queue, storage layer, or RAG stack.

It gives you the first layer that usually gets skipped:
- a clear intake page
- a believable output preview
- an agent handoff structure
- a clean starting point that can later grow into Docling, MarkItDown, OCR, MCP, or private knowledge workflows

## Why This Exists

Many teams are not blocked by model quality. They are blocked by the lack of a clear, forkable, trustworthy starting point for document intake.

This project is intentionally:
- static first
- backend later
- easy to fork
- easy to deploy

It does not pretend to be a full parser or a complete AI platform. It makes the first public-facing layer usable today.

## What Is Included

- `index.html`
  - intake landing page for an agent-ready document workflow
- `samples/output-preview.html`
  - sample delivery showing manifest and markdown handoff structure
- `assets/styles.css`
  - standalone styling with no build step

## Before / After

Before:
- raw PDFs
- scans
- proposal attachments
- folder chaos

After:
- manifest preview
- normalized markdown delivery
- clearer handoff to agents and private AI tools
- a front-end wedge you can extend later

## Good First Use Cases

- `docs.example.com`
- `kb.example.com`
- a public intake demo before backend work exists
- a service landing page that can later evolve into a product
- a starter shell for private document workflow experiments

## What This Is Not

- not a parser
- not a RAG backend
- not an MCP server
- not a file processing pipeline

This is the **front-end wedge**: the part that proves demand and communicates the workflow before the heavier system exists.

## Deploy

### Vercel

1. Create a clean public repository from this folder only.
2. Import that repository into Vercel.
3. Deploy as a static site.
4. Bind a production subdomain such as `docs.example.com`.

### Local Preview

Open `index.html` directly in a browser, or serve the folder with any static file server.

## Why It Can Earn Attention

The repo is narrow and legible:
- one clear document workflow
- one believable preview
- one easy deployment path
- no setup pain

That makes it more shareable than a half-finished full-stack app.

## Suggested Next Steps

- add a real intake form
- add vertical variants for legal, consulting, and research teams
- connect Docling or MarkItDown for actual document conversion
- add storage, queueing, and MCP integration later

## License

MIT
