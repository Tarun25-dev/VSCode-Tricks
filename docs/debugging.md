# VS Code Debugging 

## 1. Set Up the Debugger
- Press `F5` → Start debugging your program.
- Choose the correct environment/runtime (Python, Node.js, Java, etc.) when prompted.
- Use `.vscode/launch.json` to **customize debug configurations** for different projects.

---

## 2. Breakpoints
- **Set breakpoints** by clicking in the left margin of the editor.
- **Conditional breakpoints**: Right-click → *Edit Breakpoint* → add condition (e.g., `i === 5`). Only stops when the condition is true.
- **Logpoints**: Right-click → *Add Logpoint* → prints variables/messages to Debug Console without stopping execution.

---

## 3. Step Through Code
- `F10` → Step Over: Runs the next line, skips function internals.
- `F11` → Step Into: Enters the function call.
- `Shift + F11` → Step Out: Exits the current function.
- `F5` → Continue: Resume until next breakpoint.

---

## 4. Watch Variables
- Use the **Watch panel** to monitor variable values in real-time.
- Hover over a variable in code → see its current value.
- Use **DataTips** to expand objects or arrays in the editor.

---

## 5. Debug Console Tricks
- Type expressions in **Debug Console** to evaluate variables or run commands live.
- Combine with breakpoints or logpoints for **interactive debugging**.

---

## 6. Inline Values & Hover
- Turn on **Inline Values**: `Settings → Debug: Inline Values` → shows variable values next to code while debugging.
- Hover over variables to see real-time values without adding to Watch panel.

---

## 7. Multi-Thread / Async Debugging
- For Node.js or Python async code: check **Call Stack panel** to track async calls.
- Use breakpoints in Promises or async functions to catch tricky issues.

---

## 8. Shortcuts Summary

| Shortcut | Action |
|----------|--------|
| `F5` | Start/Continue debugging |
| `F9` | Toggle breakpoint |
| `F10` | Step Over |
| `F11` | Step Into |
| `Shift+F11` | Step Out |
| `Ctrl+Shift+D` | Open debug panel |
| `Ctrl+K Ctrl+I` | Show hover tooltip (variable info) |

---

## 9. Extra Tricks
- **Attach debugger to running process** → Useful for backend servers or web apps.
- **Debug tests** → Run individual unit tests in debug mode (Python `pytest`, Node.js `Jest`).
- **Compound launch configurations** → Debug multiple services simultaneously (frontend + backend).
- **Use `Debug: Open Link`** → Open URLs printed in console directly in browser while debugging web apps.

