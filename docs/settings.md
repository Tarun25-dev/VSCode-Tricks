# VS Code Settings Guide for Students & Developers

Optimize VS Code for productivity, readability, and efficient coding.

Theme & Appearance:
- Color Theme: Ctrl+K Ctrl+T → Choose from Dark+, Dracula, One Dark Pro, etc.
- Icon Theme: File → Preferences → File Icon Theme → Material Icon Theme
- Font & Size: "editor.fontFamily": "Fira Code, Consolas, monospace", "editor.fontSize": 14, "editor.fontLigatures": true
  Improves readability and supports coding ligatures like => or ==.

Editor Settings:
- Auto Save: "files.autoSave": "onFocusChange" → Saves files automatically when switching tabs
- Word Wrap: "editor.wordWrap": "on" → Prevents horizontal scrolling for long lines
- Minimap: "editor.minimap.enabled": true → Shows overview of code on the side

Linting & Formatting:
- Format on Save: "editor.formatOnSave": true → Auto-formats code when saved
- Default Formatter: "editor.defaultFormatter": "esbenp.prettier-vscode"
- Enable Linting: Use ESLint, Pylint, or language-specific linters

Terminal Settings:
- Open terminal: Ctrl+`
- Default shell: "terminal.integrated.shell.windows": "C:\\Windows\\System32\\cmd.exe"
- Terminal font size: "terminal.integrated.fontSize": 13

Explorer & Files:
- Exclude unnecessary files/folders: "files.exclude": { "**/node_modules": true, "**/.git": true }, "search.exclude": { "**/node_modules": true }
- Auto Reveal in Explorer: "explorer.autoReveal": true

Debugging Settings:
- Inline Values: "debug.inlineValues": true
- Enable breakpoints everywhere: "debug.allowBreakpointsEverywhere": true

Productivity Features:
- Breadcrumbs: "breadcrumbs.enabled": true → Shows current file & symbol path on top
- Quick Suggestions: "editor.quickSuggestions": { "other": true, "comments": false, "strings": true } → Auto-complete without distractions
- Multi-Cursor & Selection: Alt+Click → Add multiple cursors, Ctrl+D → Select next occurrence, Ctrl+Shift+L → Select all occurrences

Extensions & Sync:
- Install productivity & dev extensions
- Enable Settings Sync: sync extensions, themes, and editor settings across devices

Pro Tips:
- Use JSON settings for full control: Ctrl+, → click {} icon
- Workspace-specific settings: .vscode/settings.json
- Keep personal vs project settings separate (workspace overrides global)
