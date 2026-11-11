# Claude Browser Extension Builder Skill

A development skill for building browser extensions for Chrome, Firefox, and other supported browsers. It covers extension architecture, Manifest V3, content scripts, background service workers, popup interfaces, storage, permissions, and publishing considerations.

## What It Covers

- **Extension architecture:** Organize manifests, popup UI, content scripts, background workers, options pages, and icons.
- **Manifest V3:** Configure modern Chrome extensions with service workers and declared permissions.
- **Content scripts:** Read and modify page content and communicate with extension components.
- **Messaging:** Structure communication between popup, background service worker, and content scripts.
- **Storage:** Use browser storage APIs for settings and persistent extension state.
- **Permissions:** Request only the permissions required, including optional permissions when appropriate.
- **Publishing:** Consider store policies, cross-browser support, maintenance, and monetization.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-browser-extension-builder-skill.git ~/.claude/skills/browser-extension-builder
```

## Using the Skill

Example request:

```text
Use the browser-extension-builder skill to design a Manifest V3
Chrome extension with a popup, content script, and background worker.
```

The skill includes an example project structure and manifest template. Read [SKILL.md](SKILL.md) for the detailed architecture patterns and implementation examples.

## Recommended Practices

Follow least-privilege permission design, explain permission needs to users, keep background workers lightweight, handle messaging failures, and test extension behavior across supported browsers. Check current Chrome Web Store and browser-specific policies before publishing.
