# Barbara Franks — Voice & Communication Knowledge Base

Canonical source for how Claude should write on behalf of Dr. Barbara Franks in
professional communications: tone, sentence construction, formality, word choice,
email and Slack style, leadership communication, feedback, requests, updates, and
strategic recommendations.

**The file:** [`barbara-voice-communication-kb.md`](barbara-voice-communication-kb.md)

Raw URL (stable, fetchable):

```
https://raw.githubusercontent.com/bzafranks/claude-voice-kb/main/barbara-voice-communication-kb.md
```

---

## How this gets referenced

### Claude Code (terminal / desktop app Code tab)

The global user memory at `~/.claude/CLAUDE.md` imports the local clone of this
file, so it loads into every Claude Code session automatically:

```
@C:/Users/barba/.claude/claude-voice-kb/barbara-voice-communication-kb.md
```

### Claude app (claude.ai / desktop chat)

Add the knowledge base to a Project so it is in context for every conversation in
that Project:

1. Open the Project, then **Add content → Add text or file**.
2. Upload `barbara-voice-communication-kb.md`, or paste the raw URL above and ask
   Claude to fetch it.

For one-off chats outside a Project, paste the raw URL and ask Claude to read it
before drafting.

---

## Updating

This repo is the single source of truth. Edit
`barbara-voice-communication-kb.md` here and commit:

```bash
git add -A && git commit -m "Update voice knowledge base"
```

The two remotes belong to different GitHub accounts, so each push needs its own
active `gh` account:

```bash
gh auth switch -u bzafranks && git push origin main
gh auth switch -u barbarafranks-alpha && git push alpha main
```

`origin` -> `bzafranks/claude-voice-kb`
`alpha`  -> `barbarafranks-alpha/claude-voice-kb`

After pushing, re-upload the file to any Claude Project that holds a copy —
uploaded Project files do not track the repo. Claude Code picks up edits to the
local file immediately, with no push required.
