# DooLox Templates

This folder contains reusable website templates for the DooLox project. Each template is designed to help you quickly build a modern landing page or marketing website using a consistent structure and clean HTML/CSS assets.

## Available templates

### 1. Simple
The `simple` template is a minimal and lightweight option for a clean startup or personal brand website.

Features:
- Simple layout and modern typography
- Clean landing page structure
- Bootstrap-based styling
- Easy to edit and customize

### 2. Append
The `append` template is a more feature-rich option with a polished business-style design.

Features:
- Multi-section landing page layout
- Portfolio, pricing, and about pages
- Enhanced visual styling and section components
- More advanced marketing website structure

## Folder structure

```text
templates/
├── README.md
├── LICENSE
├── simple/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── assets/
├── append/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── assets/
└── ...
```

## How to use

1. Choose a template folder: `simple` or `append`.
2. Copy the selected template folder into the `websites` directory.
3. Rename the copied folder to match your site name or project name.
4. Open the project `config.json` file and set the `website` value to the same name used for the copied folder.
5. Customize the page files and component files in the copied website folder to match your business or project.
6. Update assets such as CSS, images, and JavaScript in the `assets` folder.
7. Publish the generated static website or use the copied output as your live site.

Example:

```json
{
  "theme": "default",
  "url": "https://example.com",
  "website": "my-site"
}
```

This should match the folder name inside `websites/`, such as `websites/my-site/`.

## Customization

You can customize each template by editing:

- `src/layout.html` and `src/layout_home.html` for page layout
- `components/header.html`, `footer.html`, and `main_menu.html` for shared site sections
- `pages/*.html` for specific website pages such as home, about, and pricing
- `assets/css/*.css` for styling
- `assets/js/*.js` for interactivity and scripts

## Notes

These templates are intended as a starting point for static website development. They are best suited for landing pages, product sites, agencies, and small business websites.

## License

This project is distributed under the license included in this folder. See `LICENSE` for details.
