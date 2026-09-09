# Install your RAJU.OS profile

1. Open your `rajureddi/rajureddi` GitHub repository.
2. Replace its root `README.md` with the included `README.md`.
3. Upload the entire `assets` folder alongside it, preserving the folder name.
4. Commit the files, then open your GitHub profile.

Required layout:

```text
rajureddi/
├── README.md
└── assets/
    ├── header.svg
    └── system-core.svg
```

The ZIP contains this exact structure plus this guide. You do not need to upload this guide. No dependencies, API keys, website deployment, or GitHub Actions are required.

## Design notes

- The header has one slow rotating orbital element and a subtle status pulse. Both use SVG-contained CSS; no JavaScript, foreign objects, external fonts, or remote artwork.
- Reduced-motion preferences disable animation. The static SVG remains complete when motion is disabled.
- The architecture has an accessible image description and a collapsible ASCII version.
- Project descriptions remain selectable Markdown rather than being flattened into images. A separate project-grid image would duplicate that content and shrink it on phones, so it is intentionally omitted.
- GitHub controls the surrounding page background. The bundled graphics retain their dark backgrounds in either GitHub theme.
- Three optional telemetry cards are grouped inside a disclosure. Direct GitHub links remain available when remote cards fail. The public [GitHub Readme Stats service](https://github.com/anuraghazra/github-readme-stats) is best-effort and can be rate-limited; the [streak service](https://github.com/DenverCoder1/github-readme-streak-stats) is also an external dependency.

## Verification

- Matched all four project URLs against the public GitHub repository listing; the portfolio URL comes from the public profile.
- Checked SVG XML, local image paths, Markdown fences, and disclosure tags.
- Visually inspected a local Markdown preview at desktop and 390-pixel phone widths. Both SVGs loaded; the phone preview had no page-wide horizontal overflow.
- Uses standard GitHub Markdown, image tags, tables, and disclosures. The SVG assets use browser-supported animation with static fallbacks.
- This package has not been uploaded to GitHub. The local preview approximates GitHub styling; final GitHub image-proxy rendering and continued external-card availability cannot be guaranteed by a local check.

All project and education descriptions are based on your supplied brief. No project performance metrics, usage counts, or deployment claims have been added.
