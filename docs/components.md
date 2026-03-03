# Components

This document describes the reusable components used across the OGH Wix website, including their purpose, settings, and usage rules.

---

## Table of Contents

- [Buttons](#buttons)
- [Navigation Menu](#navigation-menu)
- [Header / Banner](#header--banner)
- [Image Gallery](#image-gallery)
- [Text Box](#text-box)
- [Divider](#divider)
- [Strip / Section](#strip--section)
- [Contact Form](#contact-form)
- [Slideshow](#slideshow)
- [Video Player](#video-player)
- [Social Bar](#social-bar)
- [Footer](#footer)

---

## Buttons

### Primary Button

Used for main calls to action (e.g., "Contact Us", "Learn More", "Register").

| Property | Value |
|----------|-------|
| Background | Brand Primary (`#1A1A2E`) |
| Text color | Text Light (`#FFFFFF`) |
| Font | Montserrat Bold, 14 px |
| Border radius | 4 px |
| Padding | 14 px top/bottom, 28 px left/right |
| Hover background | Brand Accent (`#E94560`) |

### Secondary Button

Used for lower-priority actions (e.g., "Back", "See All").

| Property | Value |
|----------|-------|
| Background | Transparent |
| Border | 2 px solid Brand Primary |
| Text color | Brand Primary (`#1A1A2E`) |
| Hover background | Brand Primary |
| Hover text | Text Light (`#FFFFFF`) |

### Rules

- Every page must have at most **one** primary CTA button in the viewport.
- Button labels must be action-oriented (verb + object), e.g., "Download Guide" not just "Download".
- Avoid disabling buttons; instead, hide unavailable actions.

---

## Navigation Menu

### Settings

| Property | Value |
|----------|-------|
| Orientation | Horizontal |
| Font | Montserrat Semi-Bold, 14 px |
| Text color (default) | Text Primary (`#212121`) |
| Text color (hover / active) | Brand Accent (`#E94560`) |
| Background | Background Light (`#F5F5F5`) |
| Sticky | Yes (scrolls with the page) |

### Mobile Menu

- Wix auto-generates a hamburger menu for mobile; use the default Wix mobile menu behavior.
- Ensure all top-level pages are represented in the menu.
- Limit top-level menu items to **7 or fewer**.

### Dropdown Submenus

- Submenus are permitted for sections with 3 or more child pages.
- Use the same font and color settings as the top-level menu.

---

## Header / Banner

### Full-Width Banner Strip

Used at the top of most pages to introduce the page topic.

| Property | Value |
|----------|-------|
| Height (desktop) | 500 px |
| Height (mobile) | 280 px |
| Background | Full-width image or Brand Secondary color |
| Overlay opacity | 40% dark overlay on images |
| Title | H1 style, Text Light, centered |
| Subtitle | Body style, Text Light, centered |

### Rules

- Every page must have a banner strip at the top.
- Banner images should be **1920 × 800 px** minimum.
- Compress banner images to **200 KB or less** before uploading.

---

## Image Gallery

Use the **Wix Pro Gallery** widget for all multi-image displays.

| Property | Value |
|----------|-------|
| Layout | Grid (default) |
| Columns (desktop) | 3 |
| Columns (mobile) | 1 |
| Image ratio | 3:2 |
| Spacing between images | 16 px |
| Hover effect | Expand title |

### Rules

- All gallery images must have a meaningful **title** and **alt text** set in the media manager.
- Images should be resized to **1200 × 800 px** before uploading.
- Maximum file size: **500 KB** per image.

---

## Text Box

Standard text containers for body content on pages.

| Property | Value |
|----------|-------|
| Font | See [Typography](colors-and-typography.md#typography) |
| Max width | 780 px (centered) |
| Padding | 40 px top/bottom, 24 px left/right |
| Alignment | Left for body text; Center for short intro text |

### Rules

- Do not place raw text directly on page backgrounds; always use a text box element.
- Use Wix's built-in heading styles (H1–H6) rather than manual font overrides.

---

## Divider

Thin horizontal lines used to separate content sections.

| Property | Value |
|----------|-------|
| Color | Neutral (`#CCCCCC`) |
| Width | 100% of container |
| Thickness | 1 px |
| Top/bottom margin | 32 px |

---

## Strip / Section

Full-width horizontal sections that group related content.

| Light strip | Value |
|-------------|-------|
| Background | Background Light (`#F5F5F5`) |
| Padding | 80 px top/bottom |
| Content max width | 1200 px, centered |

| Dark strip | Value |
|------------|-------|
| Background | Background Dark (`#0F3460`) |
| Text color | Text Light (`#FFFFFF`) |
| Padding | 80 px top/bottom |
| Content max width | 1200 px, centered |

### Rules

- Alternate light and dark strips to create visual rhythm.
- Every strip must have at least 60 px of vertical padding on desktop.
- Mobile padding may reduce to 40 px.

---

## Contact Form

Use the **Wix Forms** app for all contact and registration forms.

| Property | Value |
|----------|-------|
| Input border | 1 px solid Neutral (`#CCCCCC`) |
| Input border (focus) | 2 px solid Brand Primary |
| Input background | `#FFFFFF` |
| Label font | Montserrat Medium, 13 px |
| Submit button | Primary button style |

### Required Fields (Contact Form)

- Name (text)
- Email (email, validated)
- Message (multi-line text)

### Rules

- Always include a **confirmation message** after successful form submission.
- Connect Wix Forms to an email notification so submissions are not missed.
- Do not collect sensitive personal data beyond what is necessary.

---

## Slideshow

Used for featured content carousels.

| Property | Value |
|----------|-------|
| Transition | Slide (not fade) |
| Auto-play | Yes, 5-second interval |
| Navigation arrows | Visible, white |
| Dot indicators | Visible, white |
| Height (desktop) | 600 px |
| Height (mobile) | 300 px |

### Rules

- Limit slides to **5 or fewer** to keep load times reasonable.
- Every slide must include alt text on the background image.
- Do not use a slideshow and a full-width banner on the same page section.

---

## Video Player

Use the **Wix Video** widget or embed YouTube/Vimeo for video content.

| Property | Value |
|----------|-------|
| Aspect ratio | 16:9 |
| Max width | 800 px |
| Alignment | Centered |
| Autoplay | Off (user-initiated only) |
| Mute on load | Yes if autoplay is ever enabled |

### Rules

- Always provide a text description or transcript near each video for accessibility.
- Prefer YouTube/Vimeo embeds over Wix Video for large files to reduce bandwidth costs.

---

## Social Bar

Used in the footer and optionally in page content to link to social media profiles.

| Property | Value |
|----------|-------|
| Icon style | Filled circle |
| Icon size | 32 px |
| Color | Text Light on dark backgrounds; Brand Primary on light backgrounds |
| Spacing between icons | 12 px |

### Platforms to Include

- Facebook
- Instagram
- Twitter / X
- LinkedIn *(if applicable)*

---

## Footer

### Layout

The footer is divided into **three columns** on desktop and stacks to a single column on mobile.

| Column | Content |
|--------|---------|
| Left | Logo + short tagline |
| Center | Quick links (main navigation pages) |
| Right | Contact info + social bar |

### Settings

| Property | Value |
|----------|-------|
| Background | Brand Secondary (`#16213E`) |
| Text color | Text Light (`#FFFFFF`) |
| Link color | Brand Accent (`#E94560`) on hover |
| Font | Montserrat Regular, 13 px |
| Padding | 60 px top, 40 px bottom |

### Rules

- The footer must appear on every page.
- Include a copyright line at the very bottom: `© [Year] OGH. All rights reserved.`
- Link to the Privacy Policy page if one exists.
