<div align="center">
  <!-- Hero is theme-aware. It must be a <picture> with two flat files, not a
       single SVG carrying @media (prefers-color-scheme: dark): Safari does not
       propagate the page colour scheme into an SVG loaded through <img>, so the
       in-file query never matches there (WebKit bug 199134).
       Assets are read from opencues/opencues master, not a pinned commit, so
       this page always shows what the main README shows: a commit-pinned URL
       twice sat stale behind an asset edit (#412, #415). -->
  <a href="https://opencues.com"><picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/opencues/opencues/master/assets/Hero-dark.svg">
    <img width="600" alt="OpenCues" src="https://raw.githubusercontent.com/opencues/opencues/master/assets/Hero-light.svg">
  </picture></a>
</div>

<br>

**Turn any text field into a two-way LLM channel.** It reads what you write and fills what you ask: catching a slip as you type, or answering the moment you end a line with `_`. A drop-in for Claude Code, OpenCode, Gemini CLI, DeepSeek Harness, your shell, and Chrome. Model-agnostic, output you review before it sends, an open standard with no chat window.

<a href="https://github.com/opencues/opencues"><img width="100%" alt="A Claude Code tip that knows the situation you are in, underscore makes the draft the command; then Slack catching a date that does not exist" src="https://raw.githubusercontent.com/opencues/opencues/master/assets/readme-2-cues.webp"></a>

| You type | You get |
|---|---|
| i keep having to approve every single git command | ↳ 💡 Tired of approving? /permissions allow rules like Bash(git *), or Shift+Tab to auto mode |
| ok this is a mess, let's start over on the auth stuff | ↳ 💡 Starting over? /clear wipes the conversation, CLAUDE.md stays |
| let's ship it Thursday the 19th | ↳ ⚠ the 19th is a Friday |
| we should probably go ahead and refactor this | ↳ we should refactor this |
| hey can u send me that report when u get a sec make this formal _ | Could you please send me that report at your earliest convenience? |
| hello world translate to japanese _ | こんにちは世界 |
| draft an email to my landlord asking for a rent reduction _ | (the email, written) |
| ffmpeg command to convert a video to web-ready mp4 _ | ffmpeg -i input.mov -vcodec libx264 -crf 23 -pix_fmt yuv420p -acodec aac output.mp4 |

Rows with `_` are **blanks**: you ask, the model fills in. Rows without are **cues**: the model speaks up on what you wrote, no prompt. A 💡 cue knows the situation you are in and `_` makes the draft the command.

<br>

## Quickstart

```bash
npm install -g opencues              # needs Node 22+ and git
opencues set-key cerebras csk-...    # cerebras.ai — free tier, lowest latency
opencues install claude-code         # or: opencode | gemini-cli | chrome | shell | dsh
claude-cues                          # launch — native `claude` is untouched
```

Every host pins its own fork and never touches your native install. `opencues doctor` diagnoses anything that looks wrong.

<br>

## Explore

- **Main repo** — [opencues/opencues](https://github.com/opencues/opencues)
- **Website** — [opencues.com](https://opencues.com)
- **Install guide** — [docs/install.md](https://github.com/opencues/opencues/blob/master/docs/install.md)
- **Features** — [docs/features](https://github.com/opencues/opencues/tree/master/docs/features)
- **Open standard** — [the Cues spec](https://github.com/opencues/opencues/tree/master/spec)
- **Releases** — [what changed, per version](https://github.com/opencues/opencues/releases)
- **FAQ** — [opencues.com/faqs](https://opencues.com/faqs)

<br>

<div align="center">
<sub>Apache-2.0 · an open standard for inline AI</sub>
</div>
