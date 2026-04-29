# Handoff Wizard — Public Release Host

Distribution channel for **Handoff Wizard** desktop installers.

Source code: <https://github.com/jacobcini911/handoff> (private).

## Latest release

See **[Releases](https://github.com/jacobcini911/handoff-releases/releases)** for downloads.

| Platform | Direct link |
|---|---|
| Windows (.msi) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard_0.0.1_x64_en-US.msi |
| Windows (.exe) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard_0.0.1_x64-setup.exe |
| macOS (Apple Silicon .dmg) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard_0.0.1_aarch64.dmg |
| macOS (.app.tar.gz) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard.app.tar.gz |
| Linux (AppImage) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard_0.0.1_amd64.AppImage |
| Linux (.deb) | https://github.com/jacobcini911/handoff-releases/releases/latest/download/Handoff.Wizard_0.0.1_amd64.deb |

## Unsigned alpha — installation notes

Builds are intentionally unsigned during alpha. Code-signing cert + macOS notarization land before v1.0 (tracked in INF-006/INF-007 of the source repo).

- **Windows:** SmartScreen warns "Windows protected your PC" → click **More info** → **Run anyway**
- **macOS:** Right-click the `.app` (after extracting `.dmg` or `.app.tar.gz`) → **Open** → confirm the Gatekeeper prompt
- **Linux AppImage:** `chmod +x Handoff.Wizard_0.0.1_amd64.AppImage && ./Handoff.Wizard_0.0.1_amd64.AppImage`

## Issues

Bug reports + tester feedback: <https://github.com/jacobcini911/handoff-releases/issues>

The signing roadmap, source code, and architecture documentation are tracked in the private source repo.
