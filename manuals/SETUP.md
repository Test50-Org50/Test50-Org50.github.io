# Setup Guide

This guide explains how to fork the CS50 AP course site template, run it locally, and deploy it to GitHub Pages.

## Prerequisites

- Git installed
- Ruby 3.2+ installed
- A GitHub account

## Step 1: Fork & Clone

1. Go to the original CS50 AP repository: **https://github.com/cs50/ap**
2. Click the **Fork** button in the top right corner
3. **Important:** Name your fork appropriately (see [Deploy to GitHub Pages](#step-4-deploy-to-github-pages) section)
4. **Clone** your fork locally:
   ```bash
   git clone git@github.com:YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
   ```

## Step 2: Install Dependencies

### On Ubuntu/Debian:
```bash
# Install Ruby bundler and development headers
sudo apt install -y ruby-bundler ruby-dev

# Install gems locally
bundle config set --local path 'vendor/bundle'
bundle install
```

### On macOS:
```bash
# Install bundler
gem install bundler

# Install gems locally
bundle config set --local path 'vendor/bundle'
bundle install
```

> **Note:** The first `bundle install` may take a few minutes as it downloads ~100 gems.

## Step 3: Run Locally

```bash
bundle exec jekyll serve --host 0.0.0.0 --port 4000
```

Your site will be available at: **http://localhost:4000**

The server has auto-regeneration enabled - any changes you make to files will automatically rebuild the site.

## Step 4: Deploy to GitHub Pages

### Important: Repository Naming

The CS50 theme uses **absolute asset paths** (e.g., `/assets/page.css`), which means your repository **must be served from the root URL**.

**Choose ONE option:**

| Option | Repository Name | Site URL |
|--------|-----------------|----------|
| **Organization site** | `YOUR-ORG.github.io` | `https://your-org.github.io/` |
| **User site** | `YOUR-USERNAME.github.io` | `https://your-username.github.io/` |
| **Custom domain** | Any name | `https://your-custom-domain.com/` |

> ⚠️ **If you keep a repository name like `my-course`**, the site will be at `your-username.github.io/my-course/` and **CSS will NOT load**. You must either rename the repository or use a custom domain.

### Enable GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Select **main** branch and **/ (root)** folder
4. Click **Save**

Your site will be live in a few minutes!

## Customizing Your Course

| File | Purpose |
|------|---------|
| `_includes/header.md` | Course title and subtitle |
| `_includes/nav.md` | Navigation sidebar menu |
| `index.md` | Homepage content |
| `curriculum/` | Course materials and chapters |
| `syllabus.md` | Course syllabus |
| `tools.md` | Tools and resources page |
| `_config.yml` | Site configuration (title, etc.) |

## Troubleshooting

### CSS not loading on GitHub Pages?
Your repository is probably named something other than `username.github.io`. Either:
- Rename the repository to `YOUR-USERNAME.github.io`, or
- Set up a custom domain in repository Settings → Pages

### Bundle install fails with permission errors?
Make sure to configure bundle to install locally:
```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

### Changes not showing up locally?
- Make sure the Jekyll server is running
- For `_config.yml` changes, you must **restart** the server (Ctrl+C then run again)
- For other files, just refresh your browser

## Project Structure

```
├── _config.yml          # Jekyll configuration
├── _includes/           # Shared components (header, nav)
├── assets/              # Static files (PDFs, CSS)
├── curriculum/          # Course content by chapter
├── periods/             # Per-class-period content
├── index.md             # Homepage
├── syllabus.md          # Course syllabus
├── tools.md             # Tools page
├── Gemfile              # Ruby dependencies
└── vendor/              # Installed gems (gitignored)
```

## License

Based on [CS50's Teacher Site](https://cs50.readthedocs.io/site/) template.
