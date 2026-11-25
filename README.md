# Seadon handover documentation

Operator documentation for the Seadon Shopify storefront and the Seadon Backer
Program, published so the incoming team can read it without an account.

Published 25 November 2026. This is the public edition: internal identifiers,
trading figures and the exploit-level detail of two security findings are held
back. The internal edition is the master copy.

## Read it

Open `index.html`, or browse the pages in this order:

| Page | Contents |
|---|---|
| `00-start-here.html` | The absolute basics: what the site is, logging in, the admin map, a glossary |
| `01-shopify-maintenance.html` | Nine procedures: theme publishing, homepage, products, collections, bundle pricing, discount codes, gifts, checkout checks, troubleshooting |
| `02-backer-program-operations.html` | Dashboard, campaigns, claim states, pricing configuration, imports, maintenance, troubleshooting |
| `03-access-and-code.html` | Access inventory, both repositories, test state, deploy procedures, transfer checklist |
| `04-knowledge-transfer.html` | Five session agendas with artefacts and a sign-off log |
| `05-progress.html` | Status by responsibility, defects found, decisions needed, sign-off |

Everything is static HTML with one stylesheet, no JavaScript, and no build step.
Open the files directly, or serve the folder with `python3 -m http.server`.

## What is in the pages, and what is not

Every procedure carries a status tag: verified (run and read back on 25 November
2026), described (written from the live UI or the code, not run), blocked (needs
a decision or an access grant from someone else). Claims follow the same rule:
a number is measured, traced to a file and line, or labelled a proposal.

Not here: credentials of any kind, passwords, tokens, connection strings, sales
figures, customer records. Page 3 says where each credential lives and who holds
it, never its value.

## Editing

Plain HTML and CSS. Keep the house rules: sentence-case headings, no em or en
dashes, one fact in one home, a status tag on every procedure, and a caption on
every screenshot. Screenshots belong in `images/` at 1600 px wide.

## Rights

Written for Seadon. No licence is granted for reuse outside the company.
