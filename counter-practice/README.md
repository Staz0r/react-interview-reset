# React Counter Practice

A single-page, GitHub Pages-ready React and JavaScript refresher for a small coding interview exercise. It includes an editable counter, a JavaScript syntax decoder, and quick recall prompts.

## Run it

- For local practice, run python -m http.server 8000 in this folder, then open http://localhost:8000.
- Or publish it with GitHub Pages.
- The page loads React 18 and Babel Standalone from public CDNs so editable JSX runs without a build step.
- The editor accepts a component named `CounterApp`. Choose Run code and use the steps to change and rebuild it. The challenge ladder then adds a zero guard, a +5 button, an even/odd label, and a disabled boundary control.
- Use **Use scaffold** for a guided rebuild, then **Clear editor** for a harder blank-page attempt.

The editor and preview run in separate browser contexts. Practice code stays in the page and is not uploaded by this app. The checklist is saved locally in the browser. An internet connection is needed for the React and JSX libraries.

## Publish with GitHub Pages

Put index.html and runner.html at the repository root, then enable GitHub Pages in the repository settings. No package install or build is required.

The playground runs only the component code you write; it handles `createRoot` and rendering behind the scenes. In a typical small React project, `src/main.jsx` connects React to `<div id="root">` once, and `src/App.jsx` exports the app component. The exact files vary by starter and framework, so inspect the project before adding setup code.
