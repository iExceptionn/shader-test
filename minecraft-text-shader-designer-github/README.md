# Minecraft Text Shader Designer

A small static HTML tool for designing Minecraft text shader effects and generating copy-paste GLSL snippets for `rendertype_text.fsh` / text shader workflows.

## Features

- Live preview for text effects
- Gradient and diagonal-style preview support
- Effect library with requirements labels
- Shows whether an effect is FSH-only, VSH-required, or VSH + FSH
- RGB trigger controls for main and shadow colors
- Copy-paste shader output
- Works as a single static `index.html` file

## Use locally

Open `index.html` directly in your browser.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload the files from this folder.
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root`
5. Save.
6. GitHub will give you a Pages URL after it finishes deploying.

## Notes

Some effects can be generated for `rendertype_text.fsh` only. Effects that move, rotate, scale, bounce, shake, or create true per-glyph diagonal vertex gradients usually require `rendertype_text.vsh` as well.
