# Best Practices

This document provides operational guidelines for editors and developers working in the Wix (non-Studio) editor on the OGH website.

---

## Table of Contents

- [Wix Editor Workflow](#wix-editor-workflow)
- [Images & Media](#images--media)
- [Performance](#performance)
- [Accessibility](#accessibility)
- [Content Management](#content-management)
- [Publishing & QA Checklist](#publishing--qa-checklist)

---

## Wix Editor Workflow

### Making Changes

1. **Do not edit the live site directly** without reviewing the change in the Wix preview first.
2. Use the **Wix Editor Undo** (Ctrl/Cmd + Z) generously; save often with Ctrl/Cmd + S.
3. For larger structural changes, duplicate the page before editing so you have a fallback.
4. Preview on both desktop and mobile before publishing any change.

### Saving vs. Publishing

| Action | What it does |
|--------|--------------|
| **Save** | Saves a draft in the editor; visitors still see the previously published version. |
| **Publish** | Makes all saved changes live immediately. |

- Always save first, preview the page, and only publish when satisfied.
- Communicate with the team before publishing changes that affect shared elements (header, footer, navigation).

### Shared Elements (Header & Footer)

- The header and footer are **site-wide**. Editing them changes every page simultaneously.
- Treat header/footer changes as high-risk; test on at least three representative pages before publishing.

---

## Images & Media

### Uploading Images

| Rule | Guideline |
|------|-----------|
| File format | JPEG for photos; PNG for images requiring transparency; WebP if supported |
| Max file size | 500 KB for gallery images; 200 KB for banner images |
| Dimensions | See component-specific guidance in [Components](components.md) |
| File naming | Use descriptive, lowercase, hyphenated names: `event-2024-summer.jpg` |

### Alt Text

- Every image must have descriptive alt text set in the **Wix Media Manager**.
- Alt text should describe the image content, not say "image" or the file name.
- Decorative images (spacers, backgrounds) may use empty alt text.

### Wix Media Manager

- Organize media into folders by year or category (e.g., `Events/2024`, `Team`).
- Delete unused media periodically to keep the library manageable.
- Do not upload media with personally identifiable information in file names.

---

## Performance

### Page Load Speed

Slow pages reduce visitor engagement. Follow these rules to keep load times low:

- Compress all images before uploading (use a tool such as Squoosh or TinyPNG).
- Limit the number of apps and widgets on a single page to **5 or fewer**.
- Avoid using auto-playing video as a page background.
- Do not embed more than **one** third-party map or video per page.
- Use Wix's built-in **Page Speed** dashboard (Marketing & SEO → SEO Tools) to monitor scores.

### Mobile Performance

- Wix serves a separate mobile layout; hide elements on mobile that are not needed.
- Test the site on a real mobile device (not just the Wix mobile preview) before each major publish.

---

## Accessibility

### Color & Contrast

- Maintain WCAG AA contrast ratios (see [Colors & Typography](colors-and-typography.md#accessibility-notes)).
- Never rely on color alone to convey meaning.

### Text & Navigation

- Use proper heading hierarchy on every page (H1 → H2 → H3); do not skip levels.
- All links must have descriptive text; avoid "click here" or "read more" without context.
- Interactive elements (buttons, links) must be reachable and operable via keyboard in all supported browsers.

### Forms

- Every form field must have a visible label.
- Required fields must be clearly marked.
- Provide clear error messages when validation fails.

### Images

- Provide meaningful alt text for all informational images.
- Transcripts or captions must be provided for video and audio content.

---

## Content Management

### Writing Guidelines

- Write in a clear, friendly, and professional tone consistent with the OGH brand.
- Keep sentences short (aim for 20 words or fewer on average).
- Use active voice.
- Proofread all content before publishing; use the built-in Wix spell check or a tool like Grammarly.

### Updating Existing Pages

- When updating text only, use the **Wix Text Editor** on the element directly.
- When restructuring a page (moving/adding strips), duplicate the page first.
- Update the page's meta description if the content changes significantly (see [Pages → SEO Settings](pages.md#seo-settings)).

### Archiving Content

- Outdated events, news items, or pages should be **unpublished** (hidden from navigation and search) rather than deleted.
- Retain all content for at least **12 months** before permanently deleting.

---

## Publishing & QA Checklist

Run through this checklist before every publish:

### Content

- [ ] All text has been proofread.
- [ ] All images have descriptive alt text.
- [ ] No placeholder text (e.g., "Lorem Ipsum") is present.
- [ ] All links are working and point to the correct destination.

### Design

- [ ] Page matches the style guide (colors, fonts, spacing).
- [ ] Desktop layout has been reviewed in the Wix editor preview.
- [ ] Mobile layout has been reviewed in the Wix mobile editor.

### SEO

- [ ] Page title is set and under 60 characters.
- [ ] Meta description is set and under 155 characters.
- [ ] Social share image is uploaded.

### Functionality

- [ ] All forms submit correctly and trigger confirmation messages.
- [ ] Navigation menu reflects the current page structure.
- [ ] No broken images or missing media.

### Accessibility

- [ ] Heading hierarchy is correct (H1 → H2 → H3).
- [ ] Color contrast meets WCAG AA for all text.
- [ ] All interactive elements have clear labels.

After completing this checklist, click **Publish** in the Wix editor.
