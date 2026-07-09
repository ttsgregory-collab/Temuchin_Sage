# Temuchin Sage Memoir

Your memoir is automatically built and published on every commit.

## 📖 Read the Memoir

**View Online:** [GitHub Pages link will appear after first build]

## 🏗️ Build System

This repository uses **mdBook** for automated builds:

- **HTML** — Beautiful, responsive website
- **PDF** — Downloadable book format
- **EPUB** — E-reader compatible format

### How It Works

1. Write or edit chapters in `src/` directory
2. Push to `main` branch
3. GitHub Actions automatically:
   - Builds the HTML website
   - Generates PDF and EPUB (when configured)
   - Publishes to GitHub Pages
4. Your book is live!

## 📝 Writing Guidelines

See [WRITING_GUIDE.md](./WRITING_GUIDE.md) for detailed instructions on:
- Markdown formatting
- Chapter structure
- Commit messages
- Workflow best practices

## 🔧 Local Development

### Prerequisites
- [mdBook](https://rust-lang.github.io/mdBook/)
- Rust toolchain (for mdBook installation)

### Install mdBook
```bash
cargo install mdbook
```

### Build Locally
```bash
# Build HTML
mdbook build

# Serve with live reload (open http://localhost:3000)
mdbook serve
```

### Edit & Preview
```bash
# In one terminal
mdbook serve

# In another, edit files in src/
# Changes appear automatically in browser
```

## 📂 Repository Structure

```
src/
  SUMMARY.md          Book outline & chapter order
  reference.md        Reference materials
  table-of-contents.md
  preface.md          Introduction
  temuchin.md         Main chapters
  [more chapters...]

book.toml             mdBook configuration
.github/workflows/    Automated build pipeline
```

## 📋 Project Metadata

See `metadata/book-info.md` for:
- Themes and motifs
- Timeline and era
- Key figures and relationships
- Intended audience

## 🚀 Next Steps

1. **Export your Google Docs** → Convert to Markdown
2. **Add chapters to `src/`** → Use the chapter naming convention
3. **Update SUMMARY.md** → Set reading order
4. **Push to GitHub** → Build runs automatically
5. **Share the published link** → Your memoir is live!

---

**Status:** Build system ready. Awaiting chapters from Google Docs export.
