# 🤝 Contributing to KnowGrow Roadmaps

First off, thank you for taking the time to contribute! 🎉 Every contribution — big or small — makes this project better for learners around the world.

---

## 📋 Table of Contents

- [Code of Conduct](#-code-of-conduct)
- [What Can I Contribute?](#-what-can-i-contribute)
- [Getting Started](#-getting-started)
- [How to Submit Changes](#-how-to-submit-changes)
- [Style Guide](#-style-guide)
- [Adding a New Roadmap](#-adding-a-new-roadmap)

---

## 🧭 Code of Conduct

By contributing, you agree to be respectful and inclusive. We welcome learners and contributors from all backgrounds. Be kind, be helpful, be constructive.

---

## 💡 What Can I Contribute?

Here are some ways you can help:

- ✏️ **Fix typos or grammar** — Small fixes are always welcome!
- 📚 **Add learning resources** — Books, courses, tutorials, tools.
- 🗺️ **Improve existing roadmaps** — Add missing topics or better descriptions.
- 🆕 **Create a new roadmap** — Use the [roadmap template](templates/roadmap-template.md).
- 🛠️ **Add project ideas** — Add to [beginner](projects/beginner-projects.md) or [advanced](projects/advanced-projects.md) projects.
- 🐛 **Report issues** — Open a GitHub Issue if you find something wrong.

---

## 🚀 Getting Started

1. **Fork** the repository by clicking the "Fork" button on GitHub.

2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/roadmap-repo.git
   cd roadmap-repo
   ```

3. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```
   Use a descriptive branch name, e.g.:
   - `feature/add-rust-roadmap`
   - `fix/python-typos`
   - `update/web-dev-resources`

---

## 📤 How to Submit Changes

1. **Make your changes** to the relevant files.

2. **Stage and commit** your changes:
   ```bash
   git add .
   git commit -m "feat: add Rust learning roadmap"
   ```
   Use clear, descriptive commit messages. Follow this format:
   - `feat:` for new features or content
   - `fix:` for corrections
   - `update:` for improvements to existing content
   - `docs:` for documentation changes

3. **Push** your branch to GitHub:
   ```bash
   git push origin feature/your-feature-name
   ```

4. **Open a Pull Request**:
   - Go to your fork on GitHub.
   - Click "Compare & pull request".
   - Write a clear title and description of your changes.
   - Reference any related issues (e.g., `Closes #12`).

5. **Wait for review** — A maintainer will review your PR and may suggest changes.

---

## 🎨 Style Guide

To keep the repo consistent and beautiful:

- Use **emojis** for section headers and lists (they improve readability).
- Use `##` for main sections and `###` for sub-sections.
- Keep descriptions **clear and beginner-friendly** — avoid jargon where possible.
- Always add a **navigation link** back to the main README at the bottom of each file.
- Use **bullet points** for lists rather than dense paragraphs.
- For resource links, use this format:
  ```markdown
  - 🔗 [Resource Name](URL) — Short description of what it is.
  ```

---

## 🗺️ Adding a New Roadmap

If you want to add a brand new roadmap:

1. Copy the template from [`templates/roadmap-template.md`](templates/roadmap-template.md).
2. Create a new folder under `roadmaps/` with the domain name (e.g., `roadmaps/rust/`).
3. Save your content as `README.md` inside that folder.
4. Add a link to the new roadmap in the root [`README.md`](README.md) table.
5. Submit a Pull Request!

---

## 🙏 Thank You!

Every contribution matters. Whether it's a typo fix or a brand-new roadmap, you're helping learners worldwide grow their skills. Thank you for being part of **KnowGrow Roadmaps**! 🌱

---

[⬅️ Back to Main README](README.md)
