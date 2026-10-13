# NextEdge handbook instructions

## Project

This repository contains the NextEdge company handbook on Mintlify. Pages use MDX with YAML frontmatter; navigation and branding live in docs.json.

Use the official Mintlify authoring skill for component and configuration changes. The official source is https://mintlify.com/docs. Follow the existing Git-based workflow when editing locally.

## Content and terminology

- Use NextEdge for the company, Food and beverages ERP for that business domain, and Pharma ERP for the pharma business domain.
- Membership, milestone programs, and spin-the-wheel loyalty belong under Pharma ERP. Core banking is a separate domain; workforce operations are shared supporting capabilities.
- Write practical guidance for new joiners and existing teammates.
- Use Senior Manager, Technical/Operations as the full title and Senior Manager (Tech/Ops) as the short form. Product Owner/Manager and UI/UX/Product Designer are peers; both, Senior Developer, and Developer report directly to this manager. Technical Operations and the Senior Manager report directly to the designated Founder/CEO, SVP, or VP. Only Founder/CEO, SVP, and VP finalize requirements and approve out-of-scope finance/billing.
- Tech Ops owns testing/UAT and release/recovery sign-off; Senior Developer/Senior Manager (Tech/Ops) provide technical help. Exceptions require owner/authority permission and a named alternate.
- Workday: 9 AM–6 PM; lunch: 2–3 PM. Calendar-time SLAs remain active through assigned coverage; do not invent working days or individual on-call assignments.
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
