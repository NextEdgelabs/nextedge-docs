# NextEdge handbook

Company, onboarding, delivery, business-domain, and engineering guidelines for NextEdge. Built with Mintlify and maintained as MDX.

## Read the handbook

- Published site: https://nextedge.mintlify.site
- Local preview: http://localhost:3333
- Connected repository: https://github.com/nextedgelabs/nextedge-docs

The site contains three tabs: Company handbook, Engineering, and Reference. Begin with index.mdx. Adoption status, ownership gaps, and the edition history are recorded in reference/handbook-governance.mdx.

## Run locally

Requires Node.js 20.17 or newer, below version 25, and npm.

```bash
npm ci
npm run dev
```

Use the fallback port printed by the CLI if 3333 is occupied.

## Content structure

| Directory | Content |
| --- | --- |
| company/ | Company context, organization, working practices, everyday operations |
| onboarding/ | Joiner journey, access, role-specific learning |
| delivery/ | Project lifecycle, requirements, quality |
| support/ | Support cycle, P0–P4 SLA targets, recovery, escalation, closure |
| domains/ | Sustainability, pharma, Hoisst ERP, workforce, loyalty |
| engineering/ | Architecture, stack, data, APIs, web/mobile, security, releases |
| reference/ | Templates, glossary, handbook ownership |
| guides/ | Writing and publishing instructions |

## Verify changes

```bash
npm run validate
npm run check:links
```

Preview pages and Mermaid diagrams before publishing. Every content page should appear in docs.json navigation. Keep confidential records and credentials out of this site.

## Publish

Mintlify is connected to this repository's main branch. Push reviewed changes through the repository's configured rules. Check deployment status in the Mintlify dashboard and verify the live site.

The CLI is pinned in package-lock.json. This documentation repository does not define runtime versions or startup commands for customer applications.
