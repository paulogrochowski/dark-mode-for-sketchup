# Dark Mode for SketchUp

A professional dark mode extension for SketchUp on Windows, designed to provide a modern, comfortable and visually consistent dark interface while preserving the native SketchUp experience.

## Features

- Dark styling for native Qt menus, toolbars, trays, widgets and tooltips.
- Dark Windows title bars through DWM integration.
- Optional dark 3D viewport.
- Preserves the model's original viewport settings when saving.
- Reapplies the theme to UI elements created after startup, including some floating extension toolbars.
- Includes additional handling for native Win32 tooltips.
- Theme preference is restored automatically when SketchUp starts.

## Compatibility

- SketchUp 2024
- SketchUp 2025
- SketchUp 2026
- Windows

The extension integrates with the Qt 6 UI used by current Windows versions of SketchUp.

## Notes

Some third-party extensions use their own HTML/WebView interfaces or custom styling. Those interfaces may keep some of their original colors.

## Development

This repository is the source of truth for **Dark Mode for SketchUp**. Development should preserve the extension's existing SketchUp behavior and avoid permanently changing model viewport settings.

See [AGENTS.md](AGENTS.md) for project-specific instructions for Codex and other coding agents.

---

# Português

Extensão profissional de modo escuro para SketchUp no Windows, criada para oferecer uma interface moderna, confortável e visualmente consistente, preservando a experiência nativa do SketchUp.

## Recursos

- Tema escuro para menus, barras de ferramentas, bandejas, widgets e tooltips nativos do Qt.
- Barra de título escura do Windows por integração com DWM.
- Viewport 3D escuro opcional.
- Preserva as configurações originais do viewport do modelo ao salvar.
- Reaplica o tema a elementos de interface criados depois da inicialização.
- Tratamento adicional para tooltips Win32 nativos.
- A preferência do tema é restaurada automaticamente ao iniciar o SketchUp.

## Compatibilidade

SketchUp 2024, 2025 e 2026 no Windows.
