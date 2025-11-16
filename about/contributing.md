---
layout: page
title: "Contributing"
parent: "About"
nav_order: 4
description: "How to contribute to the course materials and site"
permalink: /about/contributing/
---

## Contributing

Since this is just a one-person thing, Contributions to **How to Make** are welcome! Whether you're fixing typos, improving explanations, adding new information, or sharing resources, your help makes this course better for everyone.

### How to Contribute

#### 1. **Fork and Clone**
```bash
git clone https://github.com/YOUR-USERNAME/how-to-make.git
cd how-to-make
```

#### 2. **Create a Branch**
Use a clear, descriptive branch name:
```bash
git checkout -b fix/typo-in-week-1
git checkout -b feature/add-soldering-guide
```

#### 3. **Make Your Changes**
- Edit markdown files in the appropriate folder (`about/`, `curriculum/`, etc.)
- If adding a new week or section, use the existing structure and front matter format
- Keep files organized and well-named

#### 4. **Test Locally**
```bash
bundle exec jekyll serve --livereload
# Open http://127.0.0.1:4000/how-to-make/ in your browser
```

#### 5. **Commit and Push**
```bash
git add .
git commit -m "Clear description of your changes"
git push origin your-branch-name
```

#### 6. **Open a Pull Request**
Go to [GitHub](https://github.com/VaaneeTripathi/how-to-make) and open a PR with:
- A clear title summarizing your changes
- A description of what you added/fixed
- Any relevant context

---

### Contribution Guidelines

**Content**
- Write clearly and concisely
- Use the existing tone and style (conversational, beginner-friendly)
- Include examples and images when helpful
- Credit sources and external resources
- Be respectful, and aware of diverse learning styles and faculties
- Write accessible content

**Markdown & Front Matter**
- Use proper front matter for new pages:
  ```yaml
  ---
  layout: page
  title: "Your Title"
  parent: "Parent Page Name"  # if applicable
  nav_order: 1
  description: "Brief description"
  permalink: /path/to/page/
  ---
  ```
- Format lists and code blocks clearly
- Use headings appropriately (`##`, `###`, etc.)

**Images**
- Place images in `assets/images/`
- Use descriptive filenames
- Include alt text in markdown: `![Description](path/to/image.jpg)`

**Licensing**
- All contributions are licensed under the same license as the repository
- By submitting a PR, you agree to these terms

---

### What You can you do

- **Bug fixes** — typos, broken links, incorrect information
- **Content improvements** — clearer explanations, better organization
- **New resources** — tutorials, guides, exercise ideas
- **Accessibility** — alt text, better formatting, inclusive language
- **Translations** — community-driven translations welcome

---

### Questions?

- Open an [issue](https://github.com/VaaneeTripathi/how-to-make/issues) to discuss ideas before starting
- Check existing issues and PRs to avoid duplicates
- Be respectful and constructive in discussions

**Thank you for contributing!**