# GDPVal Bench · Qwen 3.6 27B — golden-sample showcase

Static site. No build step. To publish on GitHub Pages:

1. Create a repo (e.g. `gdpval-bench-qwen`) and push these files to the root
   (or a `/docs` folder).
2. Settings → Pages → Source = your branch, folder = root (or `/docs`).
3. `index.html` is the home page; the six `task_*.html` pages link from it.

`.nojekyll` is included so GitHub serves the files verbatim.
All links are relative, so it works at any path.
