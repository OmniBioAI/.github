# OmniBioAI/.github

This is the special organization repository for **[OmniBioAI](https://github.com/OmniBioAI)**.

GitHub uses it in two ways:

1. **Organization profile.** `profile/README.md` is rendered on the public
   [OmniBioAI organization page](https://github.com/OmniBioAI).
2. **Default community health files.** Files such as `CONTRIBUTING.md`, `SECURITY.md`,
   `CODE_OF_CONDUCT.md`, `SUPPORT.md`, issue templates and pull-request templates placed here
   apply to every OmniBioAI repository that does not define its own.

> Looking for the platform itself? Start with
> **[OmniBioAI Studio](https://github.com/OmniBioAI/omnibioai-studio)** or visit
> **[omnibioai.org](https://omnibioai.org)**.

---

## Repository layout

```text
.github/
├── README.md              ← this file (about the repository)
└── profile/
    ├── README.md          ← organization profile shown on github.com/OmniBioAI
    └── assets/            ← images used by the profile (diagrams, logos)
```

Organization-wide defaults can be added at the repository root as they are introduced:

| File / folder | Purpose |
|---|---|
| `CONTRIBUTING.md` | How to contribute to OmniBioAI repositories |
| `CODE_OF_CONDUCT.md` | Community standards |
| `SECURITY.md` | How to report vulnerabilities privately |
| `SUPPORT.md` | Where to get help |
| `ISSUE_TEMPLATE/` | Default issue forms |
| `PULL_REQUEST_TEMPLATE.md` | Default pull-request checklist |
| `workflow-templates/` | Reusable GitHub Actions starter workflows for the organization |

A repository's own copy of any of these files always takes precedence over the default here.

---

## Editing the organization profile

- Edit **`profile/README.md`**. Changes appear on the organization page as soon as they
  are merged to `main`.
- Put images in **`profile/assets/`** and reference them by their raw URL, for example:
  `https://raw.githubusercontent.com/OmniBioAI/.github/main/profile/assets/<file>.png`
- Keep the **Platform at a Glance** figures (repositories, tests, plugins, workflow bundles,
  containers, corpus and index sizes) in line with verified numbers. Live metrics are
  published at [control.omnibioai.org](https://control.omnibioai.org).
- Preview Markdown rendering on GitHub before merging; the profile page uses standard GitHub
  Flavored Markdown.

---

## Links

| Resource | Link |
|---|---|
| Website | https://omnibioai.org |
| Organization | https://github.com/OmniBioAI |
| Studio | https://github.com/OmniBioAI/omnibioai-studio |
| Documentation | https://github.com/OmniBioAI/omnibioai-docs |
| Control Center | https://control.omnibioai.org |
| Discord | https://discord.gg/Hu6vgfAFn |

---

Maintained by the OmniBioAI team.
