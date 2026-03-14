# Apers Documentation

This repo contains the source for **[docs.apers.app](https://docs.apers.app)** — the official documentation for [Apers](https://apers.app), the AI-powered platform for real estate investment professionals.

Built with [Mintlify](https://mintlify.com).

---

## What's covered

| Section | Description |
|---|---|
| **Quickstart** | Get up and running in five steps |
| **AI Excel Modeling** | Build, edit, and interact with spreadsheet models in real time |
| **Deal Management** | Organize deals, run chats, manage your pipeline |
| **Playbook** | Codify your investment thesis; let Apers evaluate deals against it |
| **Workflows** | Automate repetitive deal tasks with custom or template workflows |
| **Library** | Store templates, crystallize learnings, reuse across future deals |

---

## Local development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the local preview server (from the repo root, where `docs.json` lives):

```bash
mint dev
```

Preview at `http://localhost:3000`. If the server doesn't start, run `mint update` first.

---

## Deploying

This repo is connected to Mintlify's GitHub app. Every push to `main` deploys automatically to [docs.apers.app](https://docs.apers.app).

---

## Structure

```
docs.json               # Mintlify config — navigation, theme, branding
index.mdx               # Introduction / landing page
quickstart.mdx          # Quickstart guide
ai-excel-modeling/      # Excel Modeling AI section
deals/                  # Deal Management section
playbook/               # Playbook section
workflows/              # Workflows section
library/                # Library section
images/                 # Screenshots and diagrams
logo/                   # Brand assets
snippets/               # Reusable MDX snippets
api-reference/          # API reference pages
```

---

## Resources

- **Product:** [ai.apers.app](https://ai.apers.app)
- **Website:** [apers.app](https://apers.app)
- **YouTube:** [@ApersAI](https://www.youtube.com/@ApersAI)
- **Mintlify docs:** [mintlify.com/docs](https://mintlify.com/docs)
