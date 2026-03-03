# Pages

This document describes the standard page templates, layouts, and structural rules for the OGH Wix website.

---

## Table of Contents

- [Page Hierarchy](#page-hierarchy)
- [Standard Page Structure](#standard-page-structure)
- [Home Page](#home-page)
- [About Page](#about-page)
- [Gallery / Portfolio Page](#gallery--portfolio-page)
- [Events Page](#events-page)
- [Contact Page](#contact-page)
- [General Page (Content)](#general-page-content)
- [SEO Settings](#seo-settings)
- [Mobile Layout](#mobile-layout)

---

## Page Hierarchy

All pages must be organized within the Wix Pages menu. The recommended site structure is:

```
Home
├── About
├── Gallery
├── Events
│   └── [Individual Event Pages] (dynamic, if needed)
├── Contact
└── [Additional Content Pages]
```

- Keep the navigation to **7 or fewer top-level pages**.
- Use subpages (children) for related content rather than adding more top-level items.
- Archive or hide pages that are no longer active rather than deleting them.

---

## Standard Page Structure

Every page on the site follows this vertical structure:

1. **Header / Navigation** – Sticky Wix header with site logo and navigation menu (shared across all pages).
2. **Page Banner Strip** – Full-width strip with page title and optional subtitle (see [Components → Header / Banner](components.md#header--banner)).
3. **Main Content** – One or more content strips specific to the page.
4. **Call-to-Action Strip** *(optional)* – A dark strip with a single primary CTA button.
5. **Footer** – Shared footer (see [Components → Footer](components.md#footer)).

---

## Home Page

### Purpose

Introduce the organization, highlight key sections, and drive visitors to the most important actions.

### Sections (in order)

| # | Section | Component | Notes |
|---|---------|-----------|-------|
| 1 | Hero Banner | Full-width strip with background image | H1 title, short tagline, one primary CTA button |
| 2 | Welcome / Intro | Light strip with centered text box | 2–3 sentences max |
| 3 | Feature Highlights | Dark strip with 3-column icon layout | 3 key features or values |
| 4 | Gallery Preview | Light strip with Pro Gallery (6 images) | Link to full Gallery page |
| 5 | Events Teaser | Dark strip with upcoming event cards | Show next 2–3 events |
| 6 | Contact CTA | Light strip | Short message + primary "Contact Us" button |

### Rules

- The home page hero banner must load **without** a preloader delay.
- Do not add more than 6 sections to the home page to keep it focused.

---

## About Page

### Purpose

Describe the organization's mission, history, and team.

### Sections (in order)

| # | Section | Component | Notes |
|---|---------|-----------|-------|
| 1 | Page Banner | Full-width strip | Title: "About Us" |
| 2 | Mission Statement | Light strip, centered text | 1–2 short paragraphs |
| 3 | Our Story | Dark strip, text + image side by side | Chronological overview |
| 4 | Team Members | Light strip, 3-column card grid | Photo, name, and role for each member |

### Rules

- Team member photos must be uniform in size (**400 × 400 px**, square crop).
- Keep mission statement to **50 words or fewer**.

---

## Gallery / Portfolio Page

### Purpose

Showcase photos, artwork, or project work.

### Sections (in order)

| # | Section | Component | Notes |
|---|---------|-----------|-------|
| 1 | Page Banner | Full-width strip | Title: "Gallery" |
| 2 | Gallery Grid | Light strip, Pro Gallery | Full grid of images |

### Rules

- Organize images into **albums** within the Wix Pro Gallery if there are more than 20 images.
- Label each album clearly (e.g., "2024 Events", "Projects").
- All images must have alt text set in the Wix media manager.

---

## Events Page

### Purpose

List upcoming and past events.

### Sections (in order)

| # | Section | Component | Notes |
|---|---------|-----------|-------|
| 1 | Page Banner | Full-width strip | Title: "Events" |
| 2 | Upcoming Events | Light strip, Wix Events app or manual cards | Date, title, brief description, CTA |
| 3 | Past Events *(optional)* | Dark strip, condensed list | Year, event name only |

### Rules

- Use the **Wix Events** app if online ticketing or RSVP is needed.
- If using manual event cards, follow the [Components → Strip / Section](components.md#strip--section) padding guidelines.
- Remove or archive past events rather than leaving them in the "upcoming" section.
- Each event card must include: date, title, location (or "Online"), and a CTA button.

---

## Contact Page

### Purpose

Allow visitors to reach the organization and find location/contact information.

### Sections (in order)

| # | Section | Component | Notes |
|---|---------|-----------|-------|
| 1 | Page Banner | Full-width strip | Title: "Contact Us" |
| 2 | Contact Form | Light strip | Required fields: Name, Email, Message |
| 3 | Contact Details | Dark strip, two-column layout | Address, phone, email + optional Google Maps embed |

### Rules

- The contact form must send submissions to an active, monitored email address.
- A confirmation message must be displayed after form submission.
- Include a **Google Maps embed** only if the organization has a physical location open to visitors.
- Do not display personal email addresses as plain text to reduce spam; use the Wix form instead.

---

## General Page (Content)

Use this template for any additional informational pages (e.g., FAQ, Privacy Policy, Blog Post).

### Structure

| # | Section | Component |
|---|---------|-----------|
| 1 | Page Banner | Full-width strip |
| 2 | Content | Light strip with centered text box (max 780 px wide) |

### Rules

- Use heading hierarchy (H2 → H3 → H4) within content; never skip levels.
- Break long content into sections using H2 headings.
- Add a divider between major sections if the page exceeds 800 words.

---

## SEO Settings

Every page must have the following SEO settings configured in **Wix SEO Settings** (Pages menu → SEO tab):

| Setting | Guidance |
|---------|----------|
| Page title | `[Page Name] | OGH` – max 60 characters |
| Meta description | Unique 1–2 sentence summary of the page – max 155 characters |
| Social share image | 1200 × 630 px image relevant to the page |
| Canonical URL | Use the default Wix canonical; do not override unless redirecting |

### Rules

- Every page must have a unique page title and meta description.
- The home page title may simply be `OGH | [Short Tagline]`.
- Use the **Wix SEO Wiz** to check for common issues before publishing.

---

## Mobile Layout

Wix provides a separate mobile editor. The following rules apply to mobile layouts:

- **Review every page in the Wix mobile editor** after making desktop changes.
- Stack multi-column layouts to single column on mobile.
- Increase touch target sizes: buttons must be at least **44 × 44 px**.
- Reduce banner height on mobile (see [Components → Header / Banner](components.md#header--banner)).
- Verify that all text is legible without zooming (minimum 15 px body text).
- Hide decorative-only elements (e.g., large background shapes) on mobile to improve performance.
