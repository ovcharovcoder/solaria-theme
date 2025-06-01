# Changelog

All notable changes to the Solaria Theme for VS Code will be documented in this file.
The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.
Unreleased

## [1.0.3] - 2025-06-01

### Added
- Syntax highlighting support for Go, including keywords (`func`, `struct`, `interface`), strings, numbers, functions, and types.
- Semantic highlighting for Go-specific token `struct` in both Solaria Light and Solaria Dark.
- Story page (`STORY.md`) with the inspiration and journey behind Solaria Theme.
- Banners in `README.md` and `STORY.md` to enhance visual appeal and branding.
- Author photo in `STORY.md` for a personal touch.
- Theme icon in `STORY.md` to reinforce branding (if added).

### Changed
- Updated `README.md` with a link to `STORY.md` and added Go to supported languages.
- Improved color consistency in `semanticTokenColors` for Solaria Dark.

### Fixed
- Corrected potential color typos in `semanticTokenColors` (e.g., `regexp`, `namespace`).

## [1.0.2] - 2025-06-01

**Added**

Semantic highlighting support for parameter, decorator, class, and other tokens in both Solaria Light and Solaria Dark themes.
Support for WCAG 2.1 accessibility standards with improved color contrast (≥4.5:1 for text, ≥3:1 for UI elements).
New screenshots for JavaScript, Python, and CSS in README to showcase syntax highlighting.
CHANGELOG.md and CONTRIBUTING.md files for better documentation and community contributions.

**Changed**

Harmonized color palettes between Solaria Light and Solaria Dark for consistent syntax associations:
Keywords: #9F7AEA (Light) and #C4A1F8 (Dark).
Strings: #38A169 (Light) and #68D391 (Dark).
Functions: #4299E1 (Light) and #7BB8F0 (Dark).
Numbers: #D69E2E (Light) and #F6AD55 (Dark).


Updated UI elements for smoother transitions between themes:
Sidebar: #EDF2F7 (Light) and #2A3344 (Dark).
Active tab: #F7FAFC (Light) and #4A5568 (Dark).


Improved contrast for error and warning indicators in both themes to meet accessibility standards.
Updated README with badges, customization guide, and FAQ section.

**Fixed**

Fixed inconsistent coloring for SCSS/JSX tokens in Solaria Light.
Corrected low-contrast issues for editorWarning.foreground in Solaria Light (#B7791F).
Resolved minor UI inconsistencies in tab and sidebar backgrounds for both themes.

## [1.0.1] - 2025-05-31

**Added**

Enhanced syntax highlighting for Tailwind CSS utility classes, SCSS variables, and DOM API methods.
Improved UI customization for VS Code (sidebar, tabs, editor, terminal).

**Changed**

Refined color palette for better readability and Nordic minimalist aesthetic.
Optimized initial theme configurations for JavaScript, TypeScript, HTML, CSS/SCSS/SASS, PHP, Python, Java, C/C++, Ruby, JSX/TSX, JSON, YAML, and Markdown.

**Fixed**

Fixed minor color inconsistencies in Python and Ruby syntax highlighting.

## [1.0.0] - 2025-05-30

**Added**

Initial release of Solaria Theme, combining the previously separate Solaria Light Theme and Solaria Dark Theme into a unified theme pack.
Syntax highlighting for JavaScript, TypeScript, HTML, CSS/SCSS/SASS, PHP, Python, Java, C/C++, Ruby, JSX/TSX, JSON, YAML, and Markdown.
Tailwind CSS-inspired color palette with Nordic minimalist design.

**Changed**

None (initial release).

Fixed

None (initial release).
