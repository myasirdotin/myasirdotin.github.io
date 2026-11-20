# myasirdotin.github.io

Yasir Rasool's personal site. Not a portfolio: a hobby notebook of the things I have built so far, and a way to say hello.

- **Plain static site:** `index.html`, `style.css` and the "YR" icon (`favicon.svg` is the original drawing; `favicon.ico`,
  `apple-touch-icon.png` and `icon-512.png` are made from it). No build step, no tracking; the only scripts are a few lines that close the menu and switch light/dark (the choice is saved in the visitor's own browser). After changing `style.css`, raise the number in `style.css?v=…` in `index.html` so browsers load the new styles.
- **On this PC:** start Apache in XAMPP and open `http://localhost/myasirdotin.github.io/`.
- **Live:** `https://myasirdotin.github.io` once this folder is pushed to the GitHub repository
  `myasirdotin/myasirdotin.github.io` (GitHub Pages, branch `main`, root folder).
- **Adding a project:** copy one `<article class="card">` block in `index.html`. Link only to public pages
  (a live site, a public repository, or a store listing that opens without signing in).
- **Wording: aims, not promises.** The site says what I try to follow, never what is guaranteed, because my projects
  differ. I write as a learner ("we learn"), not as a teacher. After changing any text, run the `wording-checker`
  agent (`.claude/agents/wording-checker.md`): it flags promises and cross-checks facts against the real projects.
- **Never** put keys, passwords or private repository links here: the whole site is public.
