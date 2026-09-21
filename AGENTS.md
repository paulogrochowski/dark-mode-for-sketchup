# AGENTS.md — Dark Mode for SketchUp

## Project identity
- Product name: **Dark Mode for SketchUp**
- Repository: `paulogrochowski/dark-mode-for-sketchup`
- Platform: SketchUp for Windows
- Supported versions: SketchUp 2024, 2025 and 2026
- Primary language: Ruby / SketchUp Ruby API
- Native integrations may use Qt 6, Win32/DWM and Ruby Fiddle.

## Non-negotiable behavior
1. Do not rename the product without an explicit request.
2. Preserve the extension ID/folder compatibility when updating an existing installed version unless a migration is intentionally planned.
3. Dark viewport changes must not be permanently written into the user's SKP file. Restore original rendering options before save and reapply the dark appearance afterward.
4. A light-theme/disable path must remain available.
5. Theme preference should persist across SketchUp restarts.
6. Do not modify third-party extension files.
7. Any periodic theme reapplication must run only while dark mode is active and must remain lightweight.
8. Handle missing Qt/DWM symbols defensively. A failed native integration must not crash SketchUp.
9. Never commit secrets, tokens, local machine paths or generated user data.

## UI scope
The dark theme may cover:
- Qt menus
- toolbars
- trays
- widgets
- tooltips
- Windows title bars
- 3D viewport

Third-party HTML/WebView/custom UIs may remain partially unaffected; do not patch those extensions directly.

## Development workflow
- Keep source files in the repository; generated `.rbz` packages belong in `dist/` and should be published as release artifacts rather than committed.
- Keep changes focused and reversible.
- Update `CHANGELOG.md` for user-visible changes.
- Before packaging, verify Ruby syntax and check that enabling/disabling the extension is safe.
- Prefer small commits with descriptive messages.

## Codex guidance
When asked to change the extension:
1. Inspect the current implementation before editing.
2. Preserve working native integration and viewport-save safeguards.
3. Make the smallest change that solves the request.
4. Explain any Windows/Qt-specific risk.
5. Do not replace working code with a simplified rewrite unless explicitly requested.
