# Zendesk-like Jekyll GitHub Pages Site

## Overview
This project is a **Jekyll-based documentation site** styled like Zendesk Help Center, hosted on **GitHub Pages**. It uses the [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme for a clean, searchable knowledge base experience.

## Features
- ✅ Remote theme: Just the Docs
- ✅ Category and article structure (similar to Zendesk)
- ✅ Responsive design with custom CSS for Zendesk-like look
- ✅ GitHub Actions workflow for automated deployment
- ✅ Optional custom domain support

## How to Use
1. Clone or download this repository.
2. Update `_config.yml` with your site details:
   ```yaml
   url: "https://<your-username>.github.io"
   baseurl: "/<repo-name>"
   ```
3. Add your categories in `_categories/` and articles in `_articles/`.
4. Customize styles in `assets/css/custom.css`.

## Deployment Steps
1. Push changes to the `main` branch.
2. Enable **GitHub Pages**:
   - Go to **Settings → Pages**
   - Source: `main` → `/ (root)`
3. Access your site at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## Customization
- Modify `index.md` for the landing page.
- Update `custom.css` for branding.
- Add callouts (e.g., **Caution**, **Note**) using Markdown:
   ```markdown
   > **Caution**
   > This action is irreversible.
   {: .caution}
   ```

  
  > **Note**
  > You can restore settings from a previous export.
  {: .note}

  > **Tip**
  > Keyboard shortcut: press `?` to open the command palette.
  {: .tip}

  > **Warning**
  > Never share your API secret publicly.
  {: .warning}


## License
This project is open-source under the [MIT License](LICENSE).
