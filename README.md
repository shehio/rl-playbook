# rl-playbook

Source for [rlplaybook.com](https://rlplaybook.com) — a visual timeline of reinforcement learning breakthroughs, from DQN playing Atari (2013) to AlphaZero, Pluribus, OpenAI Five, and AlphaStar (2019). Each entry summarizes a landmark paper and links to the original publication. See the [About](https://rlplaybook.com/about/) page for background.

Built with [Hugo](https://gohugo.io/) and the [hugo-theme-timeline](https://github.com/shehio/hugo-theme-timeline) theme, deployed to GitHub Pages via GitHub Actions.

## Local development

Requires Hugo **extended** (the theme compiles SCSS). CI builds with Hugo 0.139.0.

```sh
git clone --recurse-submodules https://github.com/shehio/rl-playbook
cd rl-playbook
hugo server
```

If you already cloned without submodules, run `git submodule update --init`.

## Layout

- `content/timeline/` — one Markdown file per paper
- `content/about.md` — the About page
- `layouts/` — site-level overrides of the theme's templates
- `static/images/` — figures referenced by timeline entries
- `.github/workflows/hugo.yml` — build and deploy to GitHub Pages

## Adding a paper

Create `content/timeline/<Name>-<year>.md` with `title`, `date`, and an optional `img` in the frontmatter, followed by the abstract and a link to the paper. The timeline is ordered by `date`.
