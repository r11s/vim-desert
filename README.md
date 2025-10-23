# Desert (Vim Port)

A faithful port of Vim’s classic **“desert.vim”** colorscheme — now available for Visual Studio Code.

This theme recreates the warm, balanced contrast and soft readability that made Vim’s *Desert* a community favorite since the early 2000s.

------

## 🎨 About the Theme

The original `desert.vim` by **Hans Fugal** was one of the most popular dark color schemes in Vim history — known for its gentle contrast, readable comments, and earth-toned palette that worked well across terminals and GUI Vim.

This VS Code port preserves that distinctive look and feel, matching Vim’s highlight groups as closely as possible within VS Code’s syntax system.

### ✳️ Highlights

| Group        | Color (hex)            | Description            |
| ------------ | ---------------------- | ---------------------- |
| **Normal**   | `#ffffff` on `#333333` | Subtle dark base       |
| **Comment**  | `#6dceeb`              | Soft cyan              |
| **String**   | `#ffa0a0`              | Warm pinkish tone      |
| **Keyword**  | `#f0e68c`              | Pale gold              |
| **Function** | `#89fb98`              | Vibrant green          |
| **Type**     | `#bdb76b`              | Muted khaki            |
| **Visual**   | `#f0e68c` on `#6b8e24` | Olive visual selection |

------

## 🧩 Installation

### 1️⃣ From the VS Code Marketplace

Search directly in VS Code:

> **Desert (Vim Port)** by **r11s**

or visit the Marketplace page:
 🔗 https://marketplace.visualstudio.com/items?itemName=r11s.desert-vscode-theme

Once installed, open the **Command Palette → Preferences: Color Theme**
 and select:

> ```
> Desert (Vim Port)
> ```

### 2️⃣ Manual Installation (Local VSIX)

If you built or downloaded a `.vsix` file manually:

1. Open **Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P` on macOS)
2. Run **“Extensions: Install from VSIX...”**
3. Select `desert-vscode-theme-<version>.vsix`
4. Restart VS Code ✅

------

## ⚙️ Recommended Settings

To retain Vim’s clean, focused aesthetic:

```jsonc
{
  "editor.semanticHighlighting.enabled": true,
  "editor.bracketPairColorization.enabled": false,
  "editor.guides.bracketPairs": false,
  "editor.renderWhitespace": "none",
  "editor.cursorBlinking": "solid"
}
```

These options remove unnecessary color distractions and keep the interface faithful to the Vim look.

> 💡 *Tip:*
>  If you prefer the classic Vim look, you can set `"editor.semanticHighlighting.enabled": false`.
>  Vim itself didn’t use semantic highlighting, so this makes the code appear a bit more authentic.

------

## ⚖️ License

Released under the [Vim License](https://github.com/vim/vim/blob/master/runtime/doc/uganda.txt).

This theme is based on **“desert.vim”**, originally created and maintained by **Hans Fugal** and the **Vim Project**.  All modifications and adaptations are provided under the same terms as Vim itself.

------

## 🛠 Maintainers

- **Ported by:** Rainer S. ([r11s](https://github.com/r11s))
- **Original desert.vim author:** Hans Fugal
- **Vim Project:** https://www.vim.org

------
