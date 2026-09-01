---
name: evepupil GitHub Profile
description: An airy light-blue developer portfolio built within GitHub README constraints.
colors:
  wave-mist: "#EAF7FF"
  wave-light: "#BFE6F8"
  wave-sky: "#86C9E8"
  badge-blue: "#72B9DE"
  deep-blue-gray: "#17324D"
typography:
  display:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "78px"
    fontWeight: 700
  title:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "18px"
    fontWeight: 500
---

# Design System: evepupil GitHub Profile

## Overview

**Creative North Star: "Airy Blue Developer Portfolio"**

The profile is a concise, evidence-led developer portfolio shaped for GitHub's README canvas. A pale-blue waving banner introduces evepupil at display scale, then the interface recedes so the About copy, representative projects, and current work can carry the story.

The visual world is light, open, and restrained: airy blues provide identity, dark blue-gray keeps the banner legible, and GitHub's native content surface handles the reading experience. The waving hero, chapter hierarchy, and emoji chapter markers are adapted from the user-pinned `epicsagas/epicsagas` reference.

**Key Characteristics:**

- One full-width light-blue waving banner before the content.
- GitHub-native reading surfaces with one bounded project matrix and no custom chrome.
- A two-column project matrix with a full-width final row for the third project.
- Compact blue evidence badges and responsive media.
- Generous separation without decorative containers.

## Colors

The palette moves from near-white blue through clear sky tones, anchored by dark blue-gray; GitHub supplies the surrounding white and light surfaces.

### Primary

- **Clear Sky** (`wave-sky`): The strongest wave field and the footer's leading tone.
- **Badge Blue** (`badge-blue`): The restrained accent used by project and external-link badges.

### Secondary

- **Wave Mist** (`wave-mist`): The palest edge of the hero and footer waves.
- **Wave Light** (`wave-light`): The transition tone that keeps the wave soft and open.

### Neutral

- **Deep Blue-Gray** (`deep-blue-gray`): Banner text and dark badge fields that need dependable contrast.
- **GitHub Light Surfaces**: Platform-controlled page backgrounds, content surfaces, links, and dividers. They are context, not repository-owned color tokens.

### Named Rules

**The Five-Color Rule.** Use the five recorded blue tokens for repository-controlled artwork and badges; let GitHub supply white and light content surfaces.

## Typography

**Banner Display Font:** capsule-render's system stack.

**Page Font:** GitHub's native system stack for headings and body copy.

**Character:** The banner is confident and direct, while the page remains familiar and easy to scan. Custom type styling stops at the hosted banner; the Markdown content follows GitHub's established hierarchy.

### Hierarchy

- **Banner Name** (700, 78px): The public name `evepupil`, centered in the hero as the only display-scale text.
- **Banner Subtitle** (500, 18px): The confirmed role line beneath the name.
- **Chapter Heading** (platform-controlled): Standard level-two Markdown headings with one emoji marker.
- **Project Title** (platform-controlled): Standard linked level-three Markdown headings.
- **Body** (platform-controlled): Standard Markdown paragraphs and lists without repository-defined font sizes or weights.

### Named Rules

**The Platform Type Rule.** Use standard Markdown hierarchy for page content; only the banner sets explicit type sizes and weights.

## Layout

The profile follows a single reading column. The 854x280 hero SVG scales to the available GitHub content width, and the About chapter begins immediately below it without an intermediate card. Sections proceed in a linear story: identity, focus, tools, selected projects, evidence, and external destinations.

Selected projects sit inside one GitHub-native HTML table. NextDevTpl and CloudMind share the first row as equal 50% cells, while CCSM spans both columns in the second row. Each cell contains a linked title, one concise description, and a compact evidence row. External badges wrap naturally when the available width narrows. The GitHub activity graphic and AI-usage graphic scale down with the README content; the AI-usage image is requested at up to 700px wide. The footer closes the page with a shallow 100px wave.

No repository-owned breakpoint system exists. Responsive behavior comes from fluid images, natural badge wrapping, source-order table content, and GitHub's own page chrome. GitHub may compress or horizontally scroll the project table on narrow screens; the repository does not add unsupported custom CSS to change that behavior.

### Named Rules

**The Project Matrix Rule.** Pair projects in equal 50% cells and let the final unpaired project span the complete row; preserve source reading order from left to right, then top to bottom.

## Elevation & Depth

The system is flat. It uses no custom shadows or raised panels. Depth comes from the ordered pale-blue fields inside the wave artwork, GitHub's native content hierarchy, and the project table's platform-owned borders and alternating row surface.

### Named Rules

**The Native Frame Rule.** Let GitHub supply the project matrix border and alternating row surface; do not add custom borders, backgrounds, or shadows.

## Shapes

The defining silhouette is the soft wave used by the full-width header and shallow footer. Compact external badges use their hosted flat-square style. The project matrix uses GitHub's square native table cells and one platform-owned dividing line between columns and rows.

Emoji chapter markers are an intentional exception to an otherwise restrained form language. They remain because the user-pinned reference uses them to make a long profile easier to scan.

### Named Rules

**The Reference Marker Rule.** Retain one relevant emoji marker on each level-two chapter heading; do not extend emoji decoration into project titles or body copy.

## Components

### Waving Banner

- **Header:** A full-width 854x280 hosted SVG with three pale-blue wave fields, the name at 78px/700, and the role at 18px/500.
- **Footer:** A shallow 100px hosted wave that reverses the light-blue progression and contains no text.
- **Role:** Establish identity once, then yield to the GitHub-native content surface.

### Chapter Heading

- **Structure:** A standard level-two Markdown heading led by one relevant emoji marker.
- **Role:** Separate the profile into scannable chapters without adding navigation or custom containers.

### Project Matrix

- **Structure:** One HTML table containing linked level-three titles, descriptive paragraphs, compact evidence badges, and an optional direct website link.
- **Layout:** Two equal cells in the first row; one cell spanning both columns in the second row.
- **Separation:** GitHub's native table border and alternating row surface group each project without repository-owned CSS.

### Evidence Media

- **GitHub Activity:** A theme-aware picture that selects GitHub light or dark artwork.
- **AI Usage:** A centered public graphic requested at up to 700px wide.
- **Fallback:** Meaningful nearby text, links, and alternative text keep the profile useful if a hosted image fails.

### External Badges

- **Style:** Compact hosted shields using the flat-square preset and the recorded blue palette.
- **Behavior:** Inline links that wrap naturally; they do not become custom buttons or navigation.

## Do's and Don'ts

### Do:

- **Do** lead with the single light-blue waving banner and place About directly after it.
- **Do** use only the recorded five-color palette for repository-controlled banner and badge accents.
- **Do** keep the selected projects in the documented two-column GitHub table with compact evidence badges.
- **Do** retain one relevant emoji marker for each level-two chapter heading.
- **Do** preserve useful text, links, and alternative text around hosted images.

### Don't:

- **Don't** wrap About, activity, or external links in custom cards, and don't replace the project table with custom card styling.
- **Don't** add custom shadows, raised surfaces, or decorative depth effects.
- **Don't** override GitHub's body typography, standard headings, links, tables, or responsive chrome.
- **Don't** invent navigation, buttons, inputs, motion rules, or breakpoints that the README does not own.
- **Don't** add unsupported responsive CSS to the project matrix or replace the restrained palette with saturated accents.
