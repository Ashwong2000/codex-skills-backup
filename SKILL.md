---
name: marketing-intelligence-html-report
description: Create reusable marketing intelligence reports for any brand, industry, competitors, market, social/community platforms, campaign monitoring, case opportunities, and visual inspiration sources. Use when the user asks for competitor/social/community monitoring, weekly intelligence, campaign insights, Pinterest/Etsy/visual material research, case-line recommendations, or dual HTML reports for operators and leaders.
---

# Marketing Intelligence HTML Report

## Purpose

Produce two reusable HTML report files for brand/social/media operations:

1. A full operator version with source links, evidence, detailed insights, case opportunities, material inspiration, and next actions.
2. A concise leader version with conclusions, selected visuals/screenshots, key links, and a short action list.

Do not send email by default. Save HTML files in the user's current workspace unless the user asks otherwise.

## Inputs To Capture

Use the user's brief or infer from context:

- Brand and product lines
- Target market and report period
- Competitors and owned accounts
- Platforms to monitor, such as TikTok, Instagram, YouTube, Facebook, Reddit, Pinterest, Etsy, Amazon, official sites, communities, newsletters, PR/news, forums, and industry media
- Case line owner needs, such as case ideas, materials, use scenes, visual hooks, and priority
- Output language, file location, naming convention, and whether a leader version is needed

If a required input is missing, make a reasonable assumption and state it in the report. Ask only when the missing input changes the whole report.

## Research Rules

- Browse for all current weekly, recent, latest, or platform-dynamic facts.
- Use primary links whenever possible: original posts, official pages, platform pages, community pages, product pages, or creator/listing pages.
- Use secondary media only when the original platform is inaccessible or to validate industry context.
- For every key fact, include the original link or the closest available source link.
- Clearly label access limits, such as login walls, unavailable engagement counts, or search-index-only evidence.
- Use image search for visual inspiration. Include Pinterest or other visual platforms when requested. Visual inspiration can be outside the product category if it helps social composition, product display, gifting, color, props, or campaign mood.
- Do not over-quote sources. Summarize and link.

## Report Workflow

1. Read any user-provided product, campaign, PRD, case, or audience files first.
2. Build a monitoring brief:
   - brand
   - market
   - period
   - product lines
   - competitors
   - platforms
   - output files
3. Research four lanes:
   - Competitor and market lane: platform updates, launches, campaigns, offers, PR, community programs.
   - Content and campaign lane: formats, hooks, trend adaptations, audience insight, channel tactics.
   - Case lane: case ideas for the case owner, with product fit, materials, user scenes, visual hooks, source links, and priority.
   - Visual inspiration lane: Pinterest/Etsy/marketplace/IG-style references, not limited to the category.
4. Convert findings into two HTML files.
5. Verify the files open locally and contain useful links/images.

## Output Files

Default naming:

- `{Brand}_第{N}周周报_完整版_给{UserName}.html`
- `{Brand}_第{N}周周报_领导简版.html`

Use Chinese filenames if the workspace and user context are Chinese. Otherwise use ASCII names:

- `{brand}_week-{n}_full.html`
- `{brand}_week-{n}_leader.html`

## Full Version Structure

Use this structure unless the user requests another:

1. Title, period, market, products, competitors, platform scope, caveats
2. Executive conclusions
3. Competitor dynamics table:
   - item
   - platform/date
   - insight
   - original link
   - visual/screenshot if available
   - implication for the brand
4. Market and content insights
5. Trend watch and cross-industry hooks
6. Pinterest / visual inspiration line:
   - image
   - source link
   - visual takeaway
   - how to adapt
7. Case line:
   - priority
   - case direction
   - matching product/material
   - user scene
   - source/reference
   - social packaging angle
8. Recommended content/campaign actions
9. Next-week tracking list

## Leader Version Structure

Keep it short and image-led:

1. Title, period, market, products
2. 3-5 conclusions
3. 3-4 key competitor updates with links
4. 2-4 visual references or screenshots
5. 3-5 recommended actions

Avoid long explanations. Use tables, short bullets, and direct links.

## HTML Requirements

- Produce standalone HTML with inline CSS.
- Use remote image URLs only when they are stable enough for email/browser rendering. If direct image URLs are unavailable, include the page link and a text note.
- Keep images moderate in size with `max-width` styling.
- Use plain tables and simple CSS so the file works in browsers and email clients.
- Put source links directly beside the information they support.
- Do not depend on JavaScript.

For detailed field schemas and checklist, see `references/report-spec.md`.
Use `assets/full-report-template.html` and `assets/leader-report-template.html` as optional starting points.
