# Repo Visual Assets

Drop-in graphics for the Crowd-Sourced Truth repo, matched to the talk's gold-on-navy aesthetic. All icons have transparent backgrounds and work on both light and dark themes.

## Logos

| File | Use |
|------|-----|
| `logo-banner.png` / `.svg` | 1280x320 landscape banner. Use at the top of the README. |
| `logo-square.png` / `.svg` | 512x512 square. Use for GitHub's social preview image (Settings → General → Social preview) and as a profile/avatar option. |

## Parent Section Icons

For the six top-level sections of the resource guide. 256x256, transparent background, gold glyph.

| File | Section |
|------|---------|
| `parent-checklist.*` | The Planning Checklist |
| `parent-tools.*` | Open Source Repos & Tools |
| `parent-people.*` | People & Organizations to Follow |
| `parent-case-studies.*` | Case Study Reading List |
| `parent-academic.*` | Academic & Framework References |
| `parent-decision-matrix.*` | Quick-Start Decision Matrix |

## Subsection Icons

For the subsections under "Open Source Repos & Tools" and "People & Organizations." 256x256, transparent background.

| File | Subsection |
|------|------------|
| `icon-crisis-mapping.*` | Crisis Mapping & Data Collection |
| `icon-osint.*` | OSINT & Verification |
| `icon-secure-comm.*` | Secure Communication & Submission |
| `icon-archiving.*` | Archiving & Preservation |
| `icon-metadata-privacy.*` | Metadata & Privacy |
| `icon-civic-tech.*` | Civic Tech & Data Governance |
| `icon-organizations.*` | Organizations |
| `icon-researchers.*` | Key Researchers & Practitioners |

## Gold Dividers

Five styles, each available as SVG (scales infinitely) and PNG. All use the same gold (`#D4A843`).

| File | Style | Best for |
|------|-------|----------|
| `divider-simple.*` | Plain full-width gold line | Default, between any two sections |
| `divider-short.*` | Short centered gold bar | Subtle break within a section |
| `divider-diamond.*` | Two lines flanking a center diamond | Major section transitions |
| `divider-dots.*` | Two lines flanking three small dots | Slightly less formal than the diamond |
| `divider-tapered.*` | Single line that fades at both ends | Elegant, less heavy-handed than full-width |

## Using Icons in the README

GitHub markdown supports inline images with sizing via HTML. A few patterns:

**Icon next to a section header:**
```markdown
## <img src="assets/parent-checklist.svg" width="32" align="center"> The Planning Checklist
```

**Centered icon as a section divider:**
```markdown
<p align="center">
  <img src="assets/parent-tools.svg" width="64" />
</p>

## Open Source Repos & Tools
```

**Gold divider between sections:**
```markdown
<p align="center">
  <img src="assets/divider-diamond.svg" width="80%" />
</p>
```

## Color Reference

Palette used across the deck and these assets:

| Color | Hex | Use |
|-------|-----|-----|
| Background (deep) | `#12121A` | Page/canvas background |
| Background (card) | `#1E1E2E` | Card backgrounds in the deck |
| Gold | `#D4A843` | Primary accent, glyphs, dividers |
| Gold (bright) | `#F0C75E` | Emphasis, highlights |
| Text (light) | `#E8E8EC` | Headings, primary text on dark |
| Text (muted) | `#8B8DA0` | Secondary text |
| Teal (positive) | `#3AAFA9` | "Good" examples (color-blind safe alt to green) |
| Red (warning) | `#C94040` | "Bad" examples, warnings |
