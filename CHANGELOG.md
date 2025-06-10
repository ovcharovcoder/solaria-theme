# Changelog

All notable changes to the Solaria Theme for VS Code will be documented in this file.
The format is based on Keep a Changelog, and this project adheres to Semantic Versioning.

## [1.0.6] - 2025-06-10

### Changed
- **Solaria Dark**:
- "statusBar.noFolderBackground": "#2A3344": Fix light #CBD5E0 to dark #2A3344 so that the Status Bar remains dark when there is no folder open.

## [1.0.5] - 2025-06-03
### Added
- Language-specific syntax accents for Go (`#2B6CB0` in Light, `#C4A1F8` in Dark), JavaScript (`#B45309` in Light, `#7BB8F0` in Dark), and Python (`#2F855A` in Light, `#7BB8F0` in Dark) in `tokenColors`.
- Subtle gradient highlight for active line in Solaria Light (`#7BB8F033`) and Solaria Dark (`#7BB8F026`).
- Custom terminal cursor color in Solaria Light (`#63B3ED`) and Solaria Dark (`#7BB8F0`).

### Changed
- **Solaria Light**:
  - Editor line numbers: Changed from `#a7b7c7` (~3.5:1) to `#8B99AD` (~4.5:1) for WCAG 2.1 compliance.
  - Terminal cursor: Changed from `#378cd1` (~5.8:1) to `#63B3ED` (~4.6:1) for lighter appearance.
  - Comments: Changed from `#A0AEC0` to `#718096`.
  - Strings: Changed from `#38A169` to `#2F855A`.
  - Numbers, parameters: Changed from `#D69E2E` to `#B45309`.
  - Functions, tags: Changed from `#4299E1` to `#2B6CB0`.
  - Control keywords: Changed from `#E53E3E` to `#C53030`.
  - Errors, Git deletions: Changed from `#E53E3E` to `#C53030`.
  - Warnings: Changed from `#B7791F` to `#975F00`.
  - Git untracked, terminal ANSI green: Changed from `#38A169` to `#2F855A`.
- **Solaria Dark**:
  - Editor line numbers: Changed from `#6B7280` (~3.5:1) to `#8798A8` (~5.2:1) for WCAG 2.1 compliance.
  - Active line highlight: Changed from `#4A5568` to `#7BB8F026` for consistency with Solaria Light.
  - Added terminal cursor color `#7BB8F0` (~7.3:1) for lighter appearance.

### Fixed
- Corrected transparent color for `diffEditor.removedTextBackground` to `#C5303033` in Solaria Light and `#F5656533` in Solaria Dark.
- Ensured consistent string color (`#2F855A` in Light, `#68D391` in Dark) across all languages.

## [1.0.4] - 2025-06-02
### Changed
- Improved color contrast in Solaria Light for code and UI clarity:
  - Comments: Changed from `#A0AEC0` to `#718096`.
  - Strings: Changed from `#38A169` to `#2F855A` for consistency.
  - Numbers, parameters, attributes: Changed from `#D69E2E` to `#B45309`.
  - Functions, tags, namespaces: Changed from `#4299E1` to `#2B6CB0`.
  - Control keywords: Changed from `#E53E3E` to `#C53030`.
  - Editor line numbers: Changed from `#718096` to `#a7b7c7` for a lighter, elegant appearance (note: contrast ~3.5:1, may not meet WCAG 2.1).
  - Editor cursor, list highlights, borders: Changed from `#4299E1` to `#2B6CB0`.
  - Errors, Git deletions, diff removed: Changed from `#E53E3E` to `#C53030`.
  - Warnings: Changed from `#B7791F` to `#975F00`.
  - Git modifications, terminal ANSI yellow: Changed from `#D69E2E` to `#B45309`.
  - Git untracked, terminal ANSI green: Changed from `#38A169` to `#2F855A`.

### Fixed
- Corrected transparent color for `diffEditor.removedTextBackground` to `#C5303033`.
- Ensured consistent string color (`#2F855A`) across all languages.
- Improved readability for UI elements on `#FBFBFB` background.

## [1.0.3] - 2025-06-01
### Added
- Syntax highlighting support for Go, including keywords (`func`, `struct`, `interface`), strings, numbers, functions, and types.
- Semantic highlighting for Go-specific token `struct` in both Solaria Light and Solaria Dark.
- Story page (`STORY.md`) with the inspiration and journey behind Solaria Theme.
- Banners in `README.md` and `STORY.md` to enhance visual appeal and branding.
- Author photo in `STORY.md` for a personal touch.

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
