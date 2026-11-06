# lean-sdd-probe

Throwaway probe for the Claude Code plugin directory. It is not a real plugin.

The plugin lives in `plugin/` and holds only JSON, Markdown and a PNG icon.
`scripts/outside.sh` and `assets/outside.svg` sit outside `plugin/` on purpose.
The probe answers one question: does the directory scan only the plugin folder, or the whole repo?

Install:

```bash
/plugin install lean-sdd-probe --marketplace alchristleo/lean-sdd-probe
```
