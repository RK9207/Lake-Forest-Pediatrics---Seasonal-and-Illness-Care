# Design system · Seasonal and Illness Care

## Design direction

Use a warm editorial style with the clarity of a practical clinic page. The first screen must communicate pediatric sick visits, the Illinois office city, qualified same-day availability, on-site flu/RSV/strep testing, and tap-to-call. Give the headline and decision-making information priority over photography and ratings.

## Color and typography

| Color | Use |
| --- | --- |
| Brand green `#1a8362` | Primary call buttons and the mobile call bar, with white text and phone icon |
| Brand blue `#1b67b2` | Links, focus on light surfaces, secondary CTA border and text, directions |
| Pale blue `#daf5fe` | Access panel and an optional proof accent |
| Plum `#5d3148` | Select editorial accents and a distinct emergency guidance label |
| White `#ffffff` | Primary page canvas and text on green primary CTAs |
| Suggested dark neutral `#182824` | Headings, body text and a possible closing panel |

Use white on green for the mobile sticky call control. It has a calculated contrast ratio of 4.70:1. The blue-on-green pairing in the brief has a ratio of 1.23:1. Use visible focus on every interactive state, including controls over tinted or dark surfaces. Give links and emergency guidance identifiable text and cues as well as color.

Verify the current practice website's computed heading and body fonts when access permits. For a first draft that needs a provisional typography choice, use a humanist sans such as Source Sans 3, with a system sans fallback. Use semibold headings and regular body copy. Favor clear type over decorative pediatric fonts.

| Role | Suggested size and line height |
| --- | --- |
| H1 | 34–40 px on mobile and 48–60 px on desktop, roughly 1.1 line height |
| H2 | 28–32 px on mobile and 36–42 px on desktop, roughly 1.2 line height |
| H3 and component titles | 20–24 px, roughly 1.25 line height |
| Body and hero lead | 16–18 px body and 18–21 px hero lead, roughly 1.5–1.6 line height |
| Labels and secondary metadata | 14–16 px, with a comfortable line height |

## Grid, spacing, and responsive layout

- Use a maximum content width of roughly 1,200 px. Keep long copy at 56–68 characters per line and the FAQ column near 760 px.
- Start with 16–20 px side gutters, increase to 28–32 px on tablets, and use 40–48 px at wide sizes. Use a 4 px spacing base and repeat common steps of 8, 12, 16, 24, 32, 48, 64, and 80 px.
- Design single-column first. Treat roughly 640 px as a tablet layout check and 960 px as the point to consider a desktop grid, balanced desktop navigation, and two-column layouts. Let the layout change where the actual content fits.
- Use a 12-column grid on wide screens. Start the hero near a 7/5 text-to-image split. Two equal columns work for the access routes and a 5/7 split works for office details and map. Keep the FAQ contained and single-column.
- Aim for 44–56 px vertical section padding on mobile and 64–96 px on desktop. Decrease padding between related blocks and leave more space around shifts in topic.
- Use 1 px borders and modest 8–12 px radii. Reserve cards for grouped actions or proof. Keep icons simple, consistent and accompanied by labels. Use subtle state transitions and respect reduced motion.

## Components

| Component | Guidance |
| --- | --- |
| Header | Sticky desktop header with left logo, balanced in-page navigation, call with number, and secondary request button. Use a shorter mobile header with logo and the brief's Book Appointment entry to the request popup. Link the approved logo to the practice website. Account for header height in anchor scrolling and focus. |
| Primary and secondary CTA | Solid green and white for calls. Use a quiet outlined blue treatment for the secondary action on light surfaces and a contrast-tested variant on dark surfaces. Use a phone icon with the call label and a minimum 44 px target. |
| Hero credential and review badge | Use one concise credential near the decision area. Once Google rating and count are verified per office, add the brief's badge as a compact, readable trust element with the correct source. |
| Access panel and emergency callout | Use two routes with clear time and action labels, and a restrained border or heading for emergency guidance. Keep the callout visible without expanding a control and make its action visually distinct from routine scheduling. |
| Testing and cards | Use one compact list or comparison and put label, benefit, and any qualifier together. Keep the access pair and review cards visually recognizable without repeating their layout elsewhere. |
| Reviews | Use the matching office's verified rating and total, an approved selection, and “Read all our Google reviews.” Show a maximum of six reviews on desktop and three on mobile. Keep quotes legible and avoid requiring interaction to read the core proof. |
| FAQ | Use accessible disclosure controls with visible focus and clear expanded states. Keep answers short. The emergency callout and key hours should remain visible in their earlier sections. |
| Appointment popup | Use an accessible dialog with a title, short explanatory intro, selected office, and accessible close control. Support Escape, keep focus inside while open, and return focus to the trigger on close. Keep the GHL iframe title meaningful, allow vertical scrolling on small screens, and retain the supplied embed unless integration requires a change. Keep the practice's phone available if the form is unavailable. Verify office routing in the received submission before going live. |
| Map and directions | Use the map for the selected office with a readable address and hours outside the embed. Lazy-load the responsive map and position Get Directions below it. Give the directions button an icon and readable label. Keep the address and directions link usable if Maps fails to load. |
| Mobile sticky call | Use a full-width green call control with white text and icon. Include bottom safe-area padding and reserve equivalent document space. Check that the bar, keyboard, navigation, and popup never cover the active form field, critical copy, or footer links. |
| Footer | List all three offices, relevant contact information, Privacy Policy, Visit Our Website, and the brief's copyright treatment with the current year and location name where applicable. |

## Visual storytelling system

The page moves from **finding care → choosing an access route → learning what the visit can clarify → seeing who provides care → knowing where to go → acting**. Vary the section width, density, and image roles to support that order.

| Moment | Treatment and image role |
| --- | --- |
| Hero | Strongest headline, ample whitespace and a clear green call CTA on white. Use one authentic or approved illustrative image if it supports reassurance. An image should never push testing, city, or the call below the first useful mobile screen. |
| Getting seen | Establish a distinct pale-blue visual block. Use a simple route layout with hours and actions. Keep this section text-led. A simple process cue can help with parking-lot check-in if it adds clarity. |
| Common illness and testing | Return to white and a quieter rhythm. Use a small test comparison or short list. Keep the explanation text-led, with no generic lab imagery. |
| Team and reviews | Introduce a real practice portrait or team photo as the next visual high point. Follow with subdued review styling and verified proof. A narrow heading and compact quotes give the section room to breathe. |
| Office and directions | Use address, hours, and map as practical proof. Add a genuine exterior photo only when it helps families recognize the correct building. |
| FAQs and close | Use a quiet contained FAQ followed by a high-contrast close with a dominant call button. Keep both text-led. |

### Image selection and crops

- **Practice and Google Business Profile (GBP)** · Prefer approved provider headshots or a real team photo for credibility. Use office-specific GBP or clinic imagery with permission and verify that it matches the selected location. Keep practice-wide team images labeled as such. Verify rights before reusing any imagery from the practice site.
- **Lifestyle and outcome imagery** · An approved, licensed or clearly illustrative caregiver-and-child scene can make the hero feel familiar. Use calm, everyday expressions. Avoid imagery that implies an actual patient experience or a guaranteed clinical outcome.
- **AI imagery** · If an authentic or licensed lifestyle photo is unavailable, use generated imagery only as generic illustration. Use captions or adjacent context if needed to prevent it from being read as an actual clinician, patient, review, or clinic. Real photos and verified records carry practice proof.
- **Crop and density** · Start with a 4:3 hero crop on desktop and 3:2 or no crop module on mobile depending on fold space. Use 4:5 for provider portraits and 3:2 for exterior photos. Select crops with room around faces and reserve enough space for mobile cropping. Limit the main narrative to the hero, trust focal point, and optional office image.

## Handoff checks

- Read the headlines and scan the page at mobile and desktop widths. The scan should tell a parent the service, city, access options, testing scope, practice credibility, and next action.
- Test Lake Bluff, Lindenhurst, Vernon Hills, and missing or unknown location values. Confirm hero, hours, review data, map, call link, and appointment destination agree. Check Saturday handling and use the Lake County overview for missing or invalid values.
- With campaign assets available, test the actual call numbers, matching form submissions, Google profile links, and map directions. Check tap targets, focus order, popup behavior on small phones, and sticky controls while navigating and entering information.

See [Page strategy](PAGE_STRATEGY.md) and [Content direction](CONTENT_DIRECTION.md) for the approved message and sequence.
