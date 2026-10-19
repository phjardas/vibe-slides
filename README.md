# Vibe Slides

Dieses Projekt erzeugt Folien für Powerpoint-Karaoke mit einem KI-Coding-Agenten. Die Folien sind absurd, sarkastisch und auf Deutsch, das Format ist [Slidev](https://sli.dev/guide/syntax).

## Voraussetzungen

- Node.js (siehe `volta` in `package.json`) und pnpm
- Ein Coding-Agent, der `AGENTS.md` liest, zum Beispiel Claude Code, opencode oder Codex

Abhängigkeiten installieren:

```bash
pnpm install
```

## Ein Deck per One-Shot-Prompt erzeugen

Prompt:

```text
Erstelle ein Deck.
```

### Claude Code

```bash
claude -p "Erstelle ein Deck." --permission-mode acceptEdits
```

### opencode

```bash
opencode run "Erstelle ein Deck."
```

### Codex

```bash
codex exec "Erstelle ein Deck."
```
