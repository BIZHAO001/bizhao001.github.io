# Bizhao Pang - Academic Homepage

Personal academic website for **Bizhao Pang**, tenure-track Assistant Professor at The Hong Kong University of Science and Technology (Guangzhou).

Based on [AcadHomepage](https://github.com/georgeliu233/georgeliu233.github.io) template.

## 🚀 Quick Start - Deploy to GitHub Pages

### 1. Create a new GitHub repository

- Go to [GitHub](https://github.com/new)
- Repository name: **`YOUR_USERNAME.github.io`** (e.g., `bizhaopang.github.io`)
- Make it public, then Create repository

### 2. Push this website to your repo

```bash
cd bizhao-pang-website
git remote set-url origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git add .
git commit -m "Initial commit: Bizhao Pang academic website"
git push -u origin main
```

### 3. Configure GitHub Pages

- In your repo: **Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main** (or master), folder: **/ (root)**
- Save — Your site will be live at `https://YOUR_USERNAME.github.io` in 1–2 minutes

### 4. Update `_config.yml` before pushing

Edit `_config.yml` and set:

- **`repository`**: `YOUR_USERNAME.github.io`
- **`googlescholar`**: Your Google Scholar URL (optional, for citation stats)
- **`github`**: Your GitHub username
- **`linkedin`**, **`researchgate`**: Add if desired

## 📂 Add Videos and Figures (Showcase Section)

### Add a YouTube video

In `_pages/about.md`, find the Showcase section and add:

```html
<div class="showcase-item">
  <h4>Your Project Title</h4>
  <p>Brief description.</p>
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
  </div>
</div>
```

### Add a figure/image

1. Save your image to `images/` (e.g., `images/my-figure.png`)
2. In the Showcase section, add:

```markdown
![Caption](images/my-figure.png)
*Figure: Description of your work.*
```

## 🔧 Run Locally (Optional)

Requires [Ruby](https://www.ruby-lang.org/) and [Jekyll](https://jekyllrb.com/).

```bash
cd bizhao-pang-website
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000 in your browser.

## 📁 Project Structure

- `_config.yml` — Site configuration
- `_pages/about.md` — Main content (About, News, Publications, etc.)
- `_data/navigation.yml` — Navigation menu
- `images/` — Photos and figures
- `assets/css/main.scss` — Styles (including video showcase)

## 📧 Contact

Bizhao Pang — bizhaopang@hkust-gz.edu.cn
