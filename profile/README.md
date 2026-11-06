# Moraph — Expert Network Sales

Moraph builds and runs secure, audit-ready technology for financial services, healthcare and government. This organisation holds the tooling that writes the replies Moraph's experts send back to expert networks.

- Website: [www.moraph.com](https://www.moraph.com)
- Portfolio project: TODO(confirm) — link to the "Moraph (Expert Networks)" portfolio project once it exists
- Sister organisation: [expertnetwork-operations](https://github.com/expertnetwork-operations) (the expertnetworks pre-chew pipeline)

## What we build

| Product | What it does | Repository |
| --- | --- | --- |
| Expert network sales (`answer`) | A Cloudflare Worker that writes the final text of expert-network replies (email bodies, or one answer per question for web-form networks) from the expertnetworks pre-chew, in the expert's own voice, with an independent reviewer and learning from the owner's edits | [expertnetwork-sales/expertnetwork-sales](https://github.com/expertnetwork-sales/expertnetwork-sales) (private) |
| Community health files | Default issue forms and pull request template for every repository in this organisation | [expertnetwork-sales/.github](https://github.com/expertnetwork-sales/.github) |

## How we work

- **Issue forms.** New issues start from the org-wide forms: Bug, Feature, Task, Epic and Initiative. Bugs and feature requests are labelled `needs-triage` until reviewed.
- **Hierarchy.** Work is tracked as Initiative > Epic > Feature / Task / Bug, using GitHub issue types and sub-issues. Blocking relationships are recorded as issue dependencies.
- **Project boards.** Each product has a GitHub Project ("Moraph · <Product>") with Status (Backlog, Ready, In progress, In review, Done), Priority (P0–P3), Size (XS–XL) and two-week iterations.
- **Pull requests.** Every PR uses the template, links its issue with `Closes #<n>`, and states its test plan.

## Contact

Get in touch through [www.moraph.com/contact](https://www.moraph.com/contact). Please report security vulnerabilities privately through the same page, not in a public issue.
