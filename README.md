# Ferouz

Cursor agent skills and tooling installed from the skills/tools directory spreadsheet.

## Installed in this repo

- **Agent skills:** `.agents/skills/` (~890 skills) + `skills-lock.json`
- **Agency Agents rules:** `.cursor/rules/` (~280 `.mdc` rules)
- **Graphify:** `.cursor/rules/graphify.mdc` (run `/graphify .` to build a graph)

Install or refresh skills with:

```bash
npx skills add OWNER/REPO -y --agent cursor --skill '*'
```

## CLIs available in this Cloud Agent VM

| Tool | Notes |
| --- | --- |
| `ffmpeg` | Already present |
| `uv` / `graphify` | Graphify CLI |
| `agent-reach` | Default channels set up |
| `rtk` | Token-saving shell wrappers |
| `agent-browser` | Browser automation CLI |
| `playwright` | Playwright CLI (browsers not fully downloaded) |
| `cursor-memory` | MCP configured for this VM (`cursor-memory setup --model small`) |
| `rea` | Reverse Engineer Anything CLI + skill |

## Not installed here (and why)

- **JS/React libraries** (Anime.js, Motion, Lottie, Three.js, R3F, Remotion framework, Theatre.js, tsParticles, Matter.js, p5.js, Rapier, Motion Canvas): project libraries — add when you start an app, not as agent skills.
- **Manim:** heavy Python animation stack; install per project when needed.
- **Blender MCP:** needs a local Blender install.
- **Claude HUD:** Claude Code plugin, not Cursor.
- **Official Cursor Plugins Marketplace:** install individual plugins from Cursor’s marketplace UI on desktop.
