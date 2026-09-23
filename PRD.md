# PRD: Ishan Dhodapkar Portfolio Site

## Purpose
A personal portfolio site for Ishan Dhodapkar, linked from his resume. The primary audience is recruiters, people at companies he wants to work for, and startup CEOs. The single goal for a visitor is to contact Ishan (via email or phone).

## Structure
Single scrolling page (`index.html`) with anchor-linked sections, navigated via a nav bar. No separate pages.

### Section order
1. Hero
2. About
3. Experience
4. Projects
5. Contact

### Navigation
Sticky/fixed nav bar at the top of the viewport, visible while scrolling, linking to each section anchor.

## Sections

### Hero
- Bold intro/greeting (sketch shows "HEY!!!" + "My name is Ishan Dhodapkar...")
- A photo of Ishan
- An abstract artwork/graphic element alongside the photo for visual interest
- "Built by Ishan D" attribution (per sketch)

### About
- Short bio text block (placeholder content initially, real bio added later)

### Experience
- Work experience and internships, listed (placeholder entries initially, real content added later)

### Projects
- Projects built / currently in progress (placeholder entries initially, real content added later)

### Contact
- Direct `mailto:` email link
- Direct `tel:` phone link
- No contact form (static site, no backend)

## External links
- LinkedIn profile link
- GitHub profile link

## Visual style
- Light theme, minimal, generous whitespace, restrained use of text
- Style references:
  - https://www.ishandhodapkar.space/ — minimal, less text
  - https://a24.raviklaassens.com/ — aesthetic, fresh

## Content status
Real bio, experience, and project content exists but is not yet in this repo. Build the layout first with realistic placeholder content, then swap in real content once the design is approved.

## Checks
Once the home page is built, verify:
- [ ] All 5 sections (Hero, About, Experience, Projects, Contact) are present and appear in the correct order
- [ ] Nav bar links correctly jump to each section and stays visible while scrolling

## Later (out of scope for this version)
- Dark mode / theme toggle
- Downloadable resume PDF
- Contact form (would require a backend or third-party form service)
- Mobile-responsive polish and cross-device QA
- Verifying contact links (`mailto:`/`tel:`) are correctly formatted
- Matching the minimal aesthetic of the reference sites more closely
