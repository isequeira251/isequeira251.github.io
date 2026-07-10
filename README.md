# isequeira251.github.io

Personal consulting site for **Ian Sequeira — HubSpot Operations** (fractional HubSpot & RevOps for sales-led teams), served at [isequeira251.github.io](https://isequeira251.github.io/).

Self-contained static pages — no build step, no backend, no dependencies. Visit counts are anonymous and aggregate only (GoatCounter: no cookies, no personal tracking).

Pages:

- `index.html` — the consulting home page
- `playbook.html` — **The CRM Automation Playbook**: the names of 22 rules for changing a live HubSpot portal, drawn from real consulting engagements, grouped by stage. Any rule that is not fully shipped is labeled on the page ("Shipped in part", "Designed, never shipped"). Client names are withheld by agreement; nothing on the page or in the PDF states an outcome or ROI figure, because none was measured.

The two field guides in `downloads/` download directly from their cards on the home page — no form.

The playbook page gives the rule **names** for free. `downloads/crm-automation-playbook.pdf` adds the one-sentence statement of each rule plus a legend for the labels, and is the **only gated asset on the site** (work email, phone, company → private Apps Script → private Google Sheet). The unlock is stored in the visitor's browser under `fg-unlocked`. The two artifact sites below used to share that key; their gates are gone and they now open straight up.

Note the gate is **client-side only**: it hides the download until the form is filled, but every file in `downloads/` is served from a public URL and can be fetched directly. It collects details from people who cooperate; it does not restrict access.

`playbook.html` is generated — edit the template and the content spec, not the output.

Related public artifacts:

- [CRM Health Check](https://isequeira251.github.io/crm-health-check/) — free 1-minute CRM self-assessment
- [Post-Signature Build Plan](https://isequeira251.github.io/hubspot-post-signature-flowchart/) — interactive sample deliverable
