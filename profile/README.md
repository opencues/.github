<div align="center">
  <!-- Hero is theme-aware. It must be a <picture> with two flat files, not a
       single SVG carrying @media (prefers-color-scheme: dark): Safari does not
       propagate the page colour scheme into an SVG loaded through <img>, so the
       in-file query never matches there (WebKit bug 199134). Pin tracks
       opencues/opencues assets/. -->
  <a href="https://opencues.com"><picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://cdn.jsdelivr.net/gh/opencues/opencues@e440d5098423d496ea4ff4007db04a048b3898bb/assets/Hero-dark.svg">
    <img width="600" alt="OpenCues" src="https://cdn.jsdelivr.net/gh/opencues/opencues@e440d5098423d496ea4ff4007db04a048b3898bb/assets/Hero-light.svg">
  </picture></a>
</div>

<br>

<div align="center">

**AI anywhere you type. Just type `_` and an LLM fills in the blank.**

Platform, model, and provider agnostic. Fully open source.

</div>

<br>

| You type | You get |
|---|---|
| `hey can u send me that report make this formal _` | Could you please send me that report at your earliest convenience? |
| `4 + 4 = _` | `4 + 4 = 8` |
| `hello world translate to japanese _` | こんにちは世界 |
| `draft an email to my landlord asking for a rent reduction _` | *(the email, written)* |

<br>

## Quickstart

```bash
npm install -g opencues
opencues set-key cerebras csk-...     # free tier, lowest latency
opencues install claude-code          # or: opencode | gemini-cli | chrome | shell
```

Runs on **Claude Code, OpenCode, Gemini CLI, Chrome, and your shell** — each pins its own fork and never touches your native install.

<br>

## Explore

- **Website** — [opencues.com](https://opencues.com)
- **Main repo** — [opencues/opencues](https://github.com/opencues/opencues)
- **Features** — [docs/features](https://github.com/opencues/opencues/tree/master/docs/features) (40+ concepts)
- **Install guide** — [docs/install.md](https://github.com/opencues/opencues/blob/master/docs/install.md)
- **Open standard** — [the Cues spec](https://github.com/opencues/opencues/tree/master/spec)
- **FAQ** — [opencues.com/faqs](https://opencues.com/faqs)

<br>

<div align="center">
<sub>Apache-2.0 · an open standard for inline AI</sub>
</div>
