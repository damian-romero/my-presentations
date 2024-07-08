# Marp Themes

## Overview

Welcome to the `marp-themes` directory! This repository contains custom themes created by Damian Romero for use with Marp, a Markdown presentation ecosystem. These themes are based on the core themes provided by Marp but have been customized to better fit specific presentation needs and styles.

If you want to see a presentation guide for each custom theme, visit:

`presentations.d-romero.com/marp-themes/THEME-NAME/index.html`

## Contents

The current structure of the `marp-themes` directory is as follows:

```
.
└── damian-romero
    ├── damian-romero-marp.css
    ├── index.html
    └── slides.md
```

### damian-romero

- `damian-romero-marp.css`: This is a custom CSS file that styles the presentations based on Damian Romero's preferences.
- `index.html`: A sample HTML file demonstrating the use of the custom theme.
- `slides.md`: A Markdown file with example slides that utilize the custom theme.

## Usage

To use these custom themes in your Marp presentations, you can link the CSS file in your Markdown file as follows:

```markdown
---
marp: true
theme: damian-romero
---

Then in your terminal (assuming you have the marp cli):
`marp --html --theme-set /YOUR-PATH/marp_themes/damian-romero/damian-romero-marp.css --output index.html slides.md`

# Your Presentation Title

Your content here...
```

Make sure to adjust the path to `damian-romero-marp.css` based on your directory structure.

## License

These custom themes are based on the Marp core themes. Please make sure to check out the [MIT license](https://github.com/marp-team/marp-core) for more information on usage and distribution.

## Future Themes

More themes will be added to this directory over time. Stay tuned for updates and new styles to enhance your Marp presentations!

For any questions or suggestions, feel free to reach out.

