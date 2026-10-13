# NextEdge handbook instructions

## Project

This repository contains the NextEdge company handbook on Mintlify. Pages use MDX with YAML frontmatter; navigation and branding live in docs.json.

Use the official Mintlify authoring skill for component and configuration changes. The official source is https://mintlify.com/docs. Follow the existing Git-based workflow when editing locally.

## Content and terminology

- Use NextEdge for the company, Food and beverages ERP for that business domain, and Pharma ERP for the pharma business domain.
- Membership, milestone programs, and spin-the-wheel loyalty belong under Pharma ERP. Core banking is a separate domain; workforce operations are shared supporting capabilities.
- Write practical guidance for new joiners and existing teammates.
- Separate confirmed company facts from proposed organization roles and practices.
- Do not invent employee names, reporting lines, benefit amounts, approval limits, SLAs, customer metrics, or deployed features.
- Keep employee/customer records, secrets, and environment access details out of the published site.
- Treat workflow diagrams as illustrative unless an approved project source confirms implementation.
- Update reference/handbook-governance.mdx when facts or adoption status change.

## Style

- Use active voice, second person, concise sentences, and sentence case headings.
- Explain business context before technical detail.
- Use flow diagrams for workflows and tables for responsibility and decisions.
- Link internal pages with root-relative paths without extensions.
- Give every page a title and description; register pages in docs.json.
- Use language tags for code and Mermaid fences.

## Verification

Run npm run validate and npm run check:links. Check Mermaid syntax and visually inspect representative diagrams and pages before publishing.

Respect repository branch rules. A user request to commit and push to main authorizes that workflow; do not force-push or bypass branch protection.
