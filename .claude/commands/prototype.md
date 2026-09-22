The Salesforce token bundle lives at:
https://sfdc-ui-documentation-667d4c5e8394.herokuapp.com/dms-design-tokens/

The agent skill is at SKILL.md in that folder. Read it first; it tells you
how to use the rest of the bundle.

$ARGUMENTS

---

## Additional context — read these before generating

### WES (Website Experience Subsystem)
- WES Figma shortlink: https://sfdc.co/wes-figma
- WES Agentic Experience Pattern Library (Figma, WIP): https://www.figma.com/design/dFGCbhfF9UoJnsx2yBEbOT/WES-Agentic-Experience-Pattern-Library-(WIP)?m=auto&node-id=0-1&t=UnXFCy2q6trNArVV-1
- WES Library (Figma): https://www.figma.com/design/DN3YozSYLe50fn3BFLUrKM/Website-Experience-Subsystem--WES--Library?m=auto&node-id=0-1&t=wAntDxlcVbD8yQNU-1
- WES Documentation (Zeroheight, password: adm0n!t!0n): https://zeroheight.com/7dcc358f4/p/14d134-roadmap
- WES GitHub repo: https://github.com/salesforce-ux/website-experience-subsystem

### SFDC Page Builder Guidelines (Figma)
- Base Styles & Atoms: https://www.figma.com/design/WTdx6FjsSfc0piE8RBHxtq/SFDC-Page-Builder-Guidelines--Base-Styles---Atoms?m=auto
- Molecules: https://www.figma.com/design/p0g5rwu90BpYQw72t7fDHO/SFDC-Page-Builder-Guidelines%3A-Molecules?node-id=17912-47503&t=cxvGzbOTEKkKfsDP-4
- Blades & Containers: https://www.figma.com/design/b3JPljcZ4eRRGlRoIJeBpr/SFDC-Page-Builder-Guidelines--Blades---Containers?node-id=1-6487&t=2kdJYELTBNNA1Ly2-4
- Templates: https://www.figma.com/design/NWxXRWu7rMT08FCHJVtnGJ/SFDC-Page-Builder-Guidelines--Templates?m=auto&t=hK0j2u20u1Oxvf6j-6
- X-Site Framework: https://www.figma.com/design/wzbU65i2IDINfGbdJq3HJ3/SFDC-Page-Builder-Guidelines--X-Site-Framework?m=auto
- Forms UI Library & Documentation: https://www.figma.com/design/5diyDMmssSNQ4XPaPwZG16/SFDC-Page-Builder---TBID---Forms-UI-Library---Documentation--Guidelines-?m=auto

### SFDC UI & MuleSoft (Figma)
- SFDC UI Library 2.0 Brand Refreshed: https://www.figma.com/design/gtNa7k7Q1BXro4LnQEuOHU/SFDC-%E2%80%A8UI-Library-2.0-Brand-Refreshed?m=auto
- MuleSoft Page Builder Template Specs: https://www.figma.com/design/OExAhZRwsG0KXqsnAW1uv6/MuleSoft-Pagebuilder-Template-Specs?m=auto&t=hK0j2u20u1Oxvf6j-7
- MuleSoft Grab & Go 2.0: https://www.figma.com/design/Vrk94bQCjKVMrRWf5BpxUB/MuleSoft---Platform-%7C-Brand-Evolution-Guidelines---Resources?node-id=376-11422

### Editorial guidelines — apply to all placeholder and generated copy

**Headlines**
- Sentence case always; no period for a single sentence or fragment
- Period if two or more sentences
- Subheads: sentence case with a period

**Punctuation**
- Always use the Oxford/serial comma
- Em dash (—) with spaces on both sides, never --
- "a.m." and "p.m." (lowercase, with periods)
- No ordinals in dates: April 15, not April 15th

**Product names**
- Capitalize: Workflow Builder, Slack Connect, Slack AI, Do Not Disturb
- Lowercase: huddles, channels, clips, canvases, lists, shortcuts
- Never "Slack Canvas" — always "canvases"
- Einstein is retired — use "Trust Layer"

**Spelling preferences**
- "okay" not OK or O.K.
- "email" not e-mail
- "e-book" not ebook
- "canceled" not cancelled
- "advisor" not adviser
- "toward" not towards
- "gray" not grey
- "healthcare" (one word)

**Jargon to avoid** — replace with the alternative shown
- leverage → use
- empower → help
- utilize → use
- streamline → simplify
- enable → help or turn on
- bandwidth → time or capacity
- deep dive → analysis
- ecosystem → environment

**AI writing patterns to avoid**
- Never use: delve, navigate, landscape, foster, moreover, furthermore
- Never open with "In an era of..." or "When it comes to..."
- Cut: "it's important to note," "in today's world," "This helps ensure that..."
- No triple adjective lists ("simple, intuitive, and powerful")
- Vary sentence openings — don't let every paragraph start with a topic sentence

### Page Builder image spec guidelines
Source: https://confluence.internal.salesforce.com/pages/viewpage.action?pageId=1276811733

**Global standards**
- Format: WEBP, JPG, or PNG for photos; SVG for icons
- File size target: ≤ 120kb; threshold: 300–500kb if 120kb not possible
- GIFs: preferred <500kb, max 1MB

**Image dimensions by blade/slot**

| Blade | Slot | Aspect Ratio | Dimensions |
|---|---|---|---|
| All blades | Featured image (search/social) | 16:9 | 1440 × 810 |
| All blades | Standard background | flexible | 3200 wide; height 480–976 |
| All blades | Eyebrow image/icon | 1:1 / 3:2 / 16:9 | 480×480 / 720×480 / 854×480 |
| Marquee | Background (desktop) | — | 3200 × 1000 |
| Marquee | Background (mobile) | — | 1536 × 2152 |
| Marquee | Foreground / video poster | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| 1-Up | Foreground / video poster | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| Promotion | Foreground image | 1:1 | 1440 × 1440 |
| Product Portfolio | Anchor product image | 3:2 | 1680 × 1120 |
| Product Portfolio | Category card icon | 1:1 | 48 × 48 |
| Story | Story slot card image (×4) | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| Product Features | Feature card image | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| Product Features | Video thumbnail | 16:9 | 1920 × 1080 |
| Media | Main image / video poster | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| N-Up: Resource Card | Card image | 16:9 | 1440 × 810 |
| N-Up: Headshot Card | Headshot | 1:1 | 719 × 719 |
| N-Up: Quote Card | Headshot | 16:9 / 1:1 | 2160×1215 / 1440×1440 |
| N-Up: Quote Card | Product image | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| N-Up: Quote Card | Logo image | 16:9 / 1:1 / 3:2 | 2160×1215 / 1440×1440 / 1680×1120 |
| N-Up: Events Card | Event card image | 16:9 / 1:1 | 719×404 / 156×156 |
| N-Up: Statistics Card | Top/bottom images | — | 1240 × 480 |
| N-Up Fixed: Category Cards | Card icon | 1:1 | 48 × 48 |
| Logo Grid | Logo image | 16:9 | 320 × 180 |
| Logo Grid | Product icon | 1:1 | 48 × 48 |
| Author | Headshot | 1:1 | 1440 × 1440 |
| Author | Corner image | 16:9 | 1440 × 810 |
| Summary | Industry / product icon | 1:1 | 48 × 48 |
| Agenda | Image | 3:2 | max 140 × 94 |
| Notification | Icon/image | — | 360 × 2880 |
| GIF | GIF | matches blade | matches blade |
