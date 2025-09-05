# Aperture Viewer Project - Media Assets

## 1. Overview

This is the official repository for all public-facing media assets of The Aperture Viewer Project. This includes images, GIFs, and other visual materials used in our official documentation, release notes, and project communications.

> [!WARNING]
> This repository is for asset storage only. **No code is contained herein.** For the main Aperture Viewer software project, please visit our primary repository:
> **[https://github.com/ApertureViewer/Aperture-Viewer](https://github.com/ApertureViewer/Aperture-Viewer)**

---

## 2. Asset Management Protocol

To ensure long-term consistency and maintainability, all assets in this repository **must** adhere to the following structure and naming conventions.

### 2.1. Directory Structure: A Purpose-Driven Hierarchy

The repository is organized by the **context in which an asset is used.** To find or place an asset, determine its primary purpose.

```bash

├── branding/ # Official, context-agnostic project logos and icons.
├── github/ # Assets used on our main GitHub Organization profile page.
├── releases/ # Media used exclusively within release notes, organized by version.
│ └── v3.0.0/
│ └── v4.0.0/
├── wiki/ # All images and GIFs for the project's GitHub Wiki.
│ │ # Subdirectories should mirror the page names on the Wiki.
│ ├── downloads/
│ ├── post-processing-suite/
│ └── troubleshooting/
└── website/ # (Future Use) Assets for the apertureviewer.com website.
```

### 2.2. File Naming Convention

All filenames must be **lowercase** and use **hyphens** to separate words (`kebab-case`). The name should be descriptive and follow this structure:

**`[subject-or-type]-[descriptor].[ext]`**

*   **`[subject-or-type]`:** The primary subject of the image or its type.
    *   Examples: `ui-panel`, `color-balance-slider`, `diagram`, `screenshot`.
*   **`[descriptor]` (Optional):** Other clarifying details.
    *   Examples: `highlighted`, `before-after`, `error-message`.

#### Example

A screenshot of the download options for the "Downloads" wiki page would be located at:
`wiki/downloads/screenshot-installer-options.png`

An animated GIF demonstrating the color balance tool for the "Post-Processing Suite" wiki page would be located at:
`wiki/post-processing-suite/demo-color-balance.gif`

---

## 3. Usage & Licensing

All creative works and media assets contained in this repository are the property of The Aperture Viewer Project and are licensed under the **[Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/)**.

You are free to share these assets for non-commercial purposes, provided you give appropriate credit and a link to our main project. You may **not** use these materials for commercial purposes or modify them in any way.

Hotlinking to these assets is not permitted.

For more information, visit our official project website:
**https://apertureviewer.com**
