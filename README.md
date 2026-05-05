# Red Hat LaTeX Technical Document Template

A professional LaTeX template designed to create technical documents, whitepapers, and architectural guides that align with Red Hat's corporate brand guidelines.

## Features
- **Brand Colors:** Pre-configured with official Red Hat Red (`#EE0000`), Black, and Gray scales.
- **Typography:** Configured to use system fonts (supports Red Hat Display/Text when compiled with XeLaTeX or LuaLaTeX).
- **Structure:** Includes custom title page, headers/footers with confidentiality markers, and custom callout boxes (`rhnote`).
- **Clean Layout:** Modern, spacious design suitable for technical audiences.

## Prerequisites
To compile this document, you need a LaTeX distribution (like TeX Live or MiKTeX) and an engine that supports system fonts:
- `xelatex` (Recommended)
- `lualatex`

### Fonts
For the best experience, install the official open-source Red Hat fonts on your system:
- [Red Hat Display & Text (Google Fonts)](https://fonts.google.com/specimen/Red+Hat+Display)

If the fonts are not installed, the template will fall back to standard sans-serif fonts.

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/tavaresg/redhat-latex-template.git
   cd redhat-latex-template
   ```
2. Edit `redhat-doc.tex` with your content.
3. Compile the document:
   ```bash
   xelatex redhat-doc.tex
   ```
   *(Run it twice to ensure the table of contents is generated correctly).*

## License
This template is provided for educational and professional use. Red Hat is a trademark of Red Hat, Inc.
