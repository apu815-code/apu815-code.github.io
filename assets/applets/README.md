# How to add a new applet

1. Put your applet in its own folder here, e.g. `assets/applets/my-applet/index.html`
   (a single self-contained HTML file with inline JS/CSS is easiest; it can also be a
   folder with several files, or an exported Plotly / Streamlit-static / WebAssembly build).
2. Create `_applets/my-applet.md` by copying `_applets/barrier-tunneling.md`, and change
   `title`, `description`, `tags`, `importance` (lower = earlier), `applet_src` and, optionally,
   `img: assets/img/my-preview.png` for a card thumbnail.
3. Commit and push. It appears automatically on the Applets page.

For an applet hosted elsewhere (e.g. a Hugging Face Space, Observable notebook or Streamlit app), point
`applet_src` to the full https:// URL instead.
