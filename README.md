# Quode Palette MD Preview

A fast, reliable Markdown preview for VS Code. It opens beside your editor, updates as you type, and keeps both sides scrolled to the same spot.

![Quode Palette MD Preview showing a README next to its source](docs/screenshot.png)

*The preview beside the editor, with images, tables and code blocks rendered as you type.*

## Features

- **Live preview.** Changes show up in the preview as you type.
- **Synced scrolling.** Scroll the editor and the preview follows. Scroll the preview and the editor follows.
- **Three themes.** Right-click inside the preview and pick Light, Dark or VS Code. The VS Code option matches whatever theme you are using, and your choice is remembered.
- **Images that just work.** Relative paths, paths from the workspace root, and images placed with HTML tags (for example a centered paragraph with a full width image inside) all load.

- **The basics, done well.** Syntax highlighted code blocks, tables, task lists, heading links, and relative links to other Markdown files.

## Install

1. Download the latest `.vsix` file from the Releases page of this repository.
2. In VS Code, open the Extensions view.
3. Click the `...` menu at the top and choose **Install from VSIX...**
4. Select the downloaded file and reload VS Code if asked.

You can also install from a terminal:

```
code --install-extension quode-palette-md-preview-1.0.0.vsix
```

## Use

Open a Markdown file, right-click in the editor and choose **Open Quode Palette Preview to the Side**.

The same command is available from the button in the editor title bar, from the right-click menu on a file in the Explorer, and from the Command Palette (search for "Quode Palette").

To change the theme, right-click anywhere in the preview.

## Good to know

- Images need to live inside your workspace folder or next to the Markdown file. VS Code does not let previews read files from other places.
- Remote images only load from `http` and `https` addresses.
- The preview is not restored after VS Code restarts. Just open it again.
- Mermaid diagrams and math are not supported yet.

## License

MIT. See the LICENSE file.
