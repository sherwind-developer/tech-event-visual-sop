---
name: tech-event-visual-sop
description: Use this skill to create a high-quality visual material system for technical events, robotics events, embodied AI forums, open-source community activities, hackathons, Demo Days, exhibitions, research talks, media/community invitations, WeChat article covers, speaker cards, agenda graphics, and social media assets. It is especially useful when a team needs consistent event visuals but does not have enough senior design capacity.
---

# Technical Event Visual SOP

## Goal

Create a coherent visual material system for technical events. The skill should not only make one poster; it should turn a structured event brief and a main visual direction into a scalable set of consistent assets.

This workflow is best for:

- Robotics and embodied AI forums
- Open-source community events
- Hackathons and Demo Days
- Product or research showcases
- Exhibitions and booth invitations
- Media/community invitation campaigns
- WeChat article covers and social media posts

## Core Principle

The main visual is not decoration. It is the metaphor container for the event.

Use a design-led, AI-assisted workflow:

1. Designer or brand owner defines the main visual direction when possible.
2. Planner structures the event, speaker, agenda, audience, CTA, and channel information.
3. AI extends the approved direction into posters, invitations, agenda graphics, speaker cards, WeChat covers, and social media assets.
4. Figma or another collaborative design tool is used for final alignment, typography, logo placement, and review.

AI should not replace the main visual decision when a strong designer is available. AI should scale the system.

## Step 1: Intake Gate

Before visual decisions, check whether the event information is structured enough to support design.

If the organizer has not clearly defined the event, audience, message, visual state, output channels, agenda, CTA, and review process, use `assets/brief-template/technical-event-visual-brief-template.md` first.

The intake template is mandatory when:

- The request is vague or only says "make a poster" / "make materials".
- The event has multiple audiences or channels.
- The main visual state is unclear.
- The agenda, speakers, CTA, or sponsor/logo order is not finalized.
- The output includes WeChat covers, speaker cards, or multiple derivative assets.

Collect or infer:

- Event name
- Event type
- Hosts and partners
- Target audience
- Core topics and technical keywords
- Brand positioning
- Required information
- Deadline and CTA
- Venue / booth / livestream info
- Existing assets: logo, product image, robot image, speaker photos, agenda, reference visual
- Output channels: WeChat, Xiaohongshu, community group, media, poster, Figma, print

If information is missing but non-blocking, make a reasonable assumption and mark it briefly. If missing information affects visual direction, ask for the brief or produce a draft brief for confirmation.

## Step 2: Main Visual Gate

Before designing anything, determine the main visual state.

### A. Existing Main Visual

Use this path if the user provides a strong poster, cover, campaign visual, brand image, or approved design direction.

Extract:

- Visual metaphor
- Color system
- Typography feel
- Composition rules
- Image treatment
- Logo placement logic
- Texture/background style
- Information hierarchy

Then extend the visual system without changing its core identity.

### B. Reference Images Only

Use this path if the user provides references but no approved main visual.

Analyze the references and propose:

- 2-3 visual directions
- What each direction communicates
- Which audience each direction fits
- Risks of each direction
- Recommended direction

Do not copy the reference directly. Derive a visual system.

### C. No Visual Reference

Use this path if the user only has event content.

Create a main visual strategy before making assets:

- Event metaphor
- Brand mood
- Color palette
- Type direction
- Image strategy
- Layout system
- Forbidden visual patterns

For technical events, prefer purposeful metaphors such as stage reveal, lab, interface, signal, system map, blueprint, data pipeline, real product detail, or open-source network.

Avoid generic AI visuals, meaningless circuit patterns, cheap blue-purple gradients, fake futuristic robots, crowded tables, and excessive glow effects.

## Step 3: Visual Strategy

Define the design system before producing derivatives:

- Main metaphor
- Primary/secondary colors
- Background treatment
- Type hierarchy
- Grid and spacing
- Logo placement rules
- CTA style
- Image cropping rules
- Mobile readability rules

The result should feel credible to researchers, developers, media, and technical partners.

If the user has no strong reference, inspect bundled assets when available. The `assets/wrc-open-source-forum/` set is a reference benchmark for a robotics/research forum campaign with main poster, WeChat cover pack, livestream visual, QR poster, and speaker cards.

## Step 4: Output Types

Create only the assets needed for the requested channel, but keep the system extensible.

### Core Event Assets

- Main poster: event identity, title, theme, time, venue, CTA
- Long image: story, value proposition, agenda, speakers, registration
- Agenda graphic: time blocks, speaker names, topics, roundtable
- Speaker card: name, title, institution, topic, technical tags
- Invitation poster: media/community/partner version
- Booth visit graphic: booth number, location, highlights, visit CTA
- Recap graphic: event photos, quotes, highlights, next steps

### WeChat Cover Pack

When the output will be used for WeChat Official Account articles, always create a cover pack:

- Top story cover: wide horizontal cover for the main article.
- Secondary story cover: square or near-square cover for secondary article placement.
- Combined upload preview: place the top story cover and secondary cover side by side in one image for backend upload checking.

Design rules:

- Top story cover carries the main visual, event title, core theme, and brand signal.
- Secondary cover is simpler, with fewer words and stronger visual recognition.
- Both covers must reuse the same color system, typography, logo placement logic, and visual metaphor.
- Do not paste the full poster into the cover. Redesign for small-card readability.
- If the article already includes detailed posters inside the body, covers should focus on attraction and recognition.

### Social Media Assets

For Xiaohongshu and other mobile feeds:

- Use strong first image.
- Keep title and hook readable on a phone.
- Split details into carousel images if needed.
- Use plain-language captions with technical credibility.
- Avoid cramming full agenda details into the cover image.

## Step 5: Content Hierarchy

Never average all information.

Use these default priorities:

Main poster:

1. Event name
2. Core theme
3. Date/time
4. Venue/booth
5. Hosts
6. CTA

Agenda graphic:

1. Date/time
2. Session type
3. Speaker name
4. Talk topic
5. Background tags

Speaker card:

1. Name
2. Strongest identity
3. Topic
4. Technical tags
5. Institution/project

WeChat cover:

1. Hook/title
2. Event identity
3. Brand signal
4. Minimal supporting text

## Step 6: Production Workflow

Recommended sequence:

1. Run the intake gate. If the brief is incomplete, use the brief template or create a structured draft brief.
2. Determine main visual state: existing visual, reference-only, or no reference.
3. Build or extract the visual strategy.
4. Structure event content into reusable fields.
5. Create or extend the main poster.
6. Generate derivative assets.
7. Import to Figma or another collaborative design tool.
8. Human review adjusts text rhythm, logo placement, image crop, and mobile readability.
9. Export final PNG/JPG files by channel.

If Figma is unavailable, still produce layered SVG, editable HTML/CSS, or clean PNGs plus layout notes.

## Step 7: Quality Gate

Before final delivery, check:

- Is the key message clear in 3 seconds?
- Is the title readable on mobile?
- Are time, location, and CTA clear?
- Does every derivative share the same visual system?
- Are technical terms accurate?
- Is the layout free of overlap and cramped text?
- Does it avoid generic AI poster aesthetics?
- Does it feel credible to researchers and developers?
- Are WeChat covers readable as small cards?
- Are social images optimized for feed scrolling?

If a design fails the quality gate, simplify information before adding decoration.

## Output Behavior

When asked for strategy, provide:

- Intake status and missing information
- Main visual state diagnosis
- Recommended visual direction
- Asset list
- Production steps
- Risks and quality checks

When asked to create assets, provide:

- Final files
- Editable source when possible
- Channel usage notes
- Short captions if useful
- Suggestions for Figma adjustment
