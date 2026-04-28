# Repo Visual Assets

Drop-in graphics for the Crowd-Sourced Truth repo, matched to the talk's gold-on-navy aesthetic.

## Logos

| File | Use |
|------|-----|
| `logo-banner.png` / `.svg` | 1280x320 landscape banner. Use at the top of the README. |
| `logo-square.png` / `.svg` | 512x512 square. Use for GitHub's social preview image (Settings → General → Social preview) and as a profile/avatar option. |

## Section Icons

256x256 PNG and SVG pairs. SVG is preferred for crisp scaling; PNG for places that don't render SVG.

| File | Suggested section |
|------|-------------------|
| `icon-checklist.*` | Planning Checklist |
| `icon-crisis-mapping.*` | Crisis Mapping & Data Collection |
| `icon-osint.*` | OSINT & Verification |
| `icon-secure-comm.*` | Secure Communication & Submission |
| `icon-archiving.*` | Archiving & Preservation |
| `icon-metadata-privacy.*` | Metadata & Privacy |
| `icon-civic-tech.*` | Civic Tech & Data Governance |
| `icon-people-orgs.*` | People & Organizations to Follow |
| `icon-case-studies.*` | Case Study Reading List |
| `icon-academic.*` | Academic & Framework References |
| `icon-decision-matrix.*` | Quick-Start Decision Matrix |

## Using Icons in the README

GitHub markdown supports inline images with sizing via HTML. Drop an icon next to a section header like this:

```markdown
## <img src="assets/icon-checklist.svg" width="32" align="center"> The Planning Checklist
```

Or as a section divider:

```markdown
<p align="center">
  <img src="assets/icon-osint.svg" width="64" />
</p>

## OSINT & Verification
```

## Color Reference

If you ever need to extend the set, the palette is:

| Color | Hex | Use |
|-------|-----|-----|
| Background (deep) | `#12121A` | Page/canvas background |
| Background (card) | `#1E1E2E` | Icon tile backgrounds |
| Gold | `#D4A843` | Primary accent, glyphs |
| Gold (bright) | `#F0C75E` | Emphasis, highlights |
| Text (light) | `#E8E8EC` | Headings, primary text |
| Text (muted) | `#8B8DA0` | Secondary text |
| Teal (positive) | `#3AAFA9` | "Good" examples (color-blind safe alt to green) |
| Red (warning) | `#C94040` | "Bad" examples, warnings |
