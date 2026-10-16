# Technical architecture

## Phase 0
Next.js App Router + TypeScript + CSS, local chapter data. Deployable as a static website.

```text
existing manuscript -> human editorial approval -> public teaser manifest
                                            -> chapter page + visual + optional media
```

**Source of truth:** existing manuscript files remain untouched. Stable chapter slugs decouple URL identifiers from changing editorial numbering.

## Future
- Approved Markdown excerpts with source and rights metadata.
- Original artwork, subtitle files and accessible audio/video.
- QR codes printed in the book pointing to stable chapter pages.
- Optional order flow only after validation, legal review and consent-based data handling.

## Quality gates
Mobile-first, semantic headings, readable contrast, keyboard links, reduced-motion support. No broken promises: missing artifacts must display as planned, not available.

## Commands
`npm install`, `npm run typecheck`, `npm run build`.

## Security
No private source letters, identifiable third-party information, secret URLs, unpublished manuscripts or credentials in public bundles.
