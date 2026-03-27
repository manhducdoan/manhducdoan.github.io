# Manh-Duc Doan — Personal Academic Website

Personal academic website of Manh-Duc Doan.

**Live site:** [https://manhducdoan.github.io](https://manhducdoan.github.io)

---

## Pages

| Page | Description |
|------|-------------|
| `/home` | Home — bio, news timeline, contact |
| `/research` | Publications and working papers |
| `/cv` | Links to full CV PDF |
| `/blog` | Blog posts |

---

## Tech Stack

- **Framework:** [Jekyll](https://jekyllrb.com/) with `jekyll-theme-minimal`
- **Hosting:** GitHub Pages
- **Fonts:** Playfair Display · Libre Baskerville · Source Sans 3 (Google Fonts)
- **Icons:** Font Awesome 6

## Features

- Responsive layout with fixed top navigation bar
- Dark mode toggle (persists via `localStorage`, respects system preference)
- Social icon sidebar (Email, Google Scholar, GitHub)
- Academic paper cards with DOI links
- News timeline

---

## Local Development

**Requirements:** Ruby 3.x via [chruby](https://github.com/postmodern/chruby) + Bundler

```bash
# Install dependencies
bundle install

# Serve locally with live reload
bundle exec jekyll serve --livereload
```

Open [http://localhost:4000](http://localhost:4000).

---

## Updating Content

| File | What to edit |
|------|-------------|
| `_config.yml` | Name, email, social links |
| `index.md` | About Me, News, Contact |
| `research.md` | Papers and working papers |
| `cv.md` | CV page content |
| `_posts/` | Blog posts (filename: `YYYY-MM-DD-title.md`) |
| `assets/img/profile.jpeg` | Profile photo |

---

## Deploy

Push to `master` — GitHub Pages builds and deploys automatically.

```bash
git add .
git commit -m "feat: update content"
git push origin master
```
