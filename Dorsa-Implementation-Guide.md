# Kitchen Sink Implementation Guide

## How to Build Each Block Type

This guide provides specific instructions for building each priority block with exact specifications based on SCS Group branding guidelines.

---

## 1. Hero – Service Landing

**Template Name:** `Hero – Service Landing – Kitchen Sink`

**Structure:**
```
Container (Full Width)
├── Section (2 Columns, 50/50 split on desktop)
    ├── Column 1 (Text Content)
    │   ├── Heading (H1): {{H1_SERVICE_TITLE}}
    │   ├── Text Editor: {{SERVICE_INTRO}}
    │   └── Buttons Row
    │       ├── Button 1: {{CTA_PRIMARY_TEXT}} → {{CTA_PRIMARY_LINK}}
    │       └── Button 2: {{CTA_SECONDARY_TEXT}} → {{CTA_SECONDARY_LINK}}
    └── Column 2 (Image)
        └── Image: {{SERVICE_IMAGE_URL}}
```

**Styling:**
- Background: Global Color → Background Grey (#F2F2F2) OR White
- Padding: 80px top/bottom, 40px left/right (desktop), 40px top/bottom (mobile)
- H1: Global Font → H1 (53px, 600 weight, SCS Blue)
- Intro Text: Global Font → Body 2 (19px, 400 weight, Headings Black)
- Button 1: Background → SCS Blue, Text → White, Font → Button Text (16px, 500 weight)
- Button 2: Background → Ocean Blue, Text → White, Font → Button Text (16px, 500 weight)
- Mobile: Stack columns vertically, image below text

**Placeholders:**
- {{H1_SERVICE_TITLE}}: "Commercial Cleaning Services"
- {{SERVICE_INTRO}}: "Professional commercial cleaning solutions tailored to your business needs across Australia."
- {{CTA_PRIMARY_TEXT}}: "Get A Quote Now"
- {{CTA_PRIMARY_LINK}}: "#contact"
- {{CTA_SECONDARY_TEXT}}: "Call Us Now"
- {{CTA_SECONDARY_LINK}}: "tel:1300664647"
- {{SERVICE_IMAGE_URL}}: Placeholder image 800x600px

---

## 2. Hero – Homepage

**Template Name:** `Hero – Homepage – Kitchen Sink`

**Structure:**
```
Container (Full Width)
├── Section (Background Image Overlay)
    └── Column (Centered Content)
        ├── Heading (H1): {{H1_HOMEPAGE_TITLE}}
        ├── Text Editor: {{HOMEPAGE_INTRO}}
        └── Buttons Row
            ├── Button 1: {{CTA_PRIMARY_TEXT}} → {{CTA_PRIMARY_LINK}}
            └── Button 2: {{CTA_SECONDARY_TEXT}} → {{CTA_SECONDARY_LINK}}
```

**Styling:**
- Background: {{IMAGE_BACKGROUND_URL}} with dark overlay (50% opacity)
- Min-Height: 600px (desktop), 400px (mobile)
- Content Alignment: Center center
- H1: Global Font → H1 (53px, 600 weight, White)
- Intro Text: Global Font → Body 1 (16px, 500 weight, White)
- Buttons: Same as Service Landing hero
- Mobile: Reduce min-height, adjust font sizes

**Placeholders:**
- {{H1_HOMEPAGE_TITLE}}: "Creating Positive & Motivated Environments So Our People & Customers Thrive"
- {{HOMEPAGE_INTRO}}: "Professional commercial cleaning service that Really CARES"
- {{IMAGE_BACKGROUND_URL}}: Full-width background image 1920x800px

---

## 3. Service Grid – 3 Column

**Template Name:** `Service – Icon Grid 3 Col – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
├── Text Editor (Optional): {{SECTION_INTRO}}
└── Section (3 Columns on desktop, 1 on mobile)
    ├── Column 1
    │   ├── Icon: {{ICON_1}}
    │   ├── Heading (H3): {{H3_SERVICE_1_TITLE}}
    │   ├── Text Editor: {{SERVICE_1_DESC}}
    │   └── Button/Link: {{CTA_1_TEXT}} → {{CTA_1_LINK}}
    ├── Column 2
    │   ├── Icon: {{ICON_2}}
    │   ├── Heading (H3): {{H3_SERVICE_2_TITLE}}
    │   ├── Text Editor: {{SERVICE_2_DESC}}
    │   └── Button/Link: {{CTA_2_TEXT}} → {{CTA_2_LINK}}
    └── Column 3
        ├── Icon: {{ICON_3}}
        ├── Heading (H3): {{H3_SERVICE_3_TITLE}}
        ├── Text Editor: {{SERVICE_3_DESC}}
        └── Button/Link: {{CTA_3_TEXT}} → {{CTA_3_LINK}}
```

**Styling:**
- Background: White or Background Grey
- Padding: 80px top/bottom, 24px left/right
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Section Intro: Global Font → Body 2 (19px, 400 weight) - Centered
- Column Gap: 40px
- Icon: 64px size, SCS Blue color
- H3: Global Font → H3 (19px, 500 weight, Headings Black)
- Description: Global Font → Body 2 (19px, 400 weight, Body Text Black)
- CTA: Text link or button (Ocean Blue color)
- Hover: Icon scales to 1.1, H3 changes to SCS Blue

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Our Cleaning Services"
- {{SECTION_INTRO}}: "Comprehensive cleaning solutions for every industry"
- {{ICON_1}}: Icon library icon (cleaning related)
- {{H3_SERVICE_1_TITLE}}: "Commercial Cleaning"
- {{SERVICE_1_DESC}}: "Professional office and commercial space cleaning"
- {{CTA_1_TEXT}}: "Learn More"
- {{CTA_1_LINK}}: "#"
- (Repeat for services 2 and 3)

---

## 4. CTA – Quote Form Banner

**Template Name:** `CTA – Quote Banner – Kitchen Sink`

**Structure:**
```
Container (Full Width)
├── Section (Background Color: SCS Blue)
    └── Column (Centered Content)
        ├── Heading (H2): {{H2_CTA_TITLE}}
        ├── Text Editor: {{CTA_DESCRIPTION}}
        └── Buttons Row
            ├── Button 1: {{CTA_PRIMARY_TEXT}} → {{CTA_PRIMARY_LINK}}
            └── Button 2: {{CTA_SECONDARY_TEXT}} → {{CTA_SECONDARY_LINK}}
```

**Styling:**
- Background: Global Color → SCS Blue
- Padding: 60px top/bottom, 40px left/right
- Content Alignment: Center
- H2: Global Font → H2 (37px, 600 weight, White)
- Description: Global Font → Body 1 (16px, 500 weight, White)
- Button 1: Background → White, Text → SCS Blue, Font → Button Text
- Button 2: Background → Ocean Blue, Text → White, Font → Button Text
- Mobile: Stack buttons vertically

**Placeholders:**
- {{H2_CTA_TITLE}}: "Looking for a professional commercial cleaning service?"
- {{CTA_DESCRIPTION}}: "Contact The SCS Group today for a personalised cleaning proposal"
- {{CTA_PRIMARY_TEXT}}: "Get A Quote Now"
- {{CTA_PRIMARY_LINK}}: "/contact-us/"
- {{CTA_SECONDARY_TEXT}}: "1300 66 46 47"
- {{CTA_SECONDARY_LINK}}: "tel:1300664647"

---

## 5. Client Logos Grid

**Template Name:** `Content – Client Logos Grid – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
├── Text Editor (Optional): {{SECTION_INTRO}}
└── Section (Gallery or Custom Grid)
    └── Logo Images (6 columns on desktop, 3 on tablet, 2 on mobile)
        - {{LOGO_1_URL}} through {{LOGO_16_URL}}
```

**Styling:**
- Background: White or Light Grey
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Logo Size: Max-height 80px, auto-width
- Column Gap: 40px (desktop), 20px (mobile)
- Logo Filter: Grayscale(100%) - Hover: Grayscale(0%)
- Logo Alignment: Center center

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Many of our clients are trusted National Brands"
- {{SECTION_INTRO}}: ""
- {{LOGO_1_URL}} through {{LOGO_16_URL}}: 16 placeholder logo images

---

## 6. Statistics/Counters

**Template Name:** `Content – Statistics Counter – Kitchen Sink`

**Structure:**
```
Container (Full Width or Boxed)
└── Section (3 Columns on desktop, 1 on mobile)
    ├── Column 1
    │   ├── Counter: {{COUNTER_1_NUMBER}}
    │   ├── Heading (H2): {{COUNTER_1_LABEL}}
    │   └── Text: {{COUNTER_1_DESC}}
    ├── Column 2
    │   ├── Counter: {{COUNTER_2_NUMBER}}
    │   ├── Heading (H2): {{COUNTER_2_LABEL}}
    │   └── Text: {{COUNTER_2_DESC}}
    └── Column 3
        ├── Counter: {{COUNTER_3_NUMBER}}
        ├── Heading (H2): {{COUNTER_3_LABEL}}
        └── Text: {{COUNTER_3_DESC}}
```

**Styling:**
- Background: Background Grey or SCS Blue
- Padding: 80px top/bottom
- Column Gap: 40px
- Counter Number: Font size 60px, 700 weight, SCS Blue (or White if on SCS Blue background)
- Counter Label (H2): Global Font → H2 (37px, 600 weight), same color as counter
- Description: Global Font → Body 2 (19px, 400 weight)
- Animation: Counter animates from 0 to target number on scroll
- Alignment: Center

**Placeholders:**
- {{COUNTER_1_NUMBER}}: "975,000"
- {{COUNTER_1_LABEL}}: "+"
- {{COUNTER_1_DESC}}: "Square Meters Cleaned Daily"
- {{COUNTER_2_NUMBER}}: "2,000"
- {{COUNTER_2_LABEL}}: "+"
- {{COUNTER_2_DESC}}: "Locations Cleaned Daily"
- {{COUNTER_3_NUMBER}}: "3,000"
- {{COUNTER_3_LABEL}}: "+"
- {{COUNTER_3_DESC}}: "Cleaning Personnel Deployed Daily"

---

## 7. FAQ – Accordion

**Template Name:** `FAQ – Accordion – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
├── Text Editor (Optional): {{SECTION_INTRO}}
└── Toggle/Accordion Widget
    ├── Item 1
    │   ├── Title (H4): {{H4_QUESTION_1}}
    │   └── Content: {{ANSWER_1}}
    ├── Item 2
    │   ├── Title (H4): {{H4_QUESTION_2}}
    │   └── Content: {{ANSWER_2}}
    └── (Repeat for 6-10 items)
```

**Styling:**
- Background: White or Light Grey
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Accordion Border: Seal Grey, 1px
- Question (H4): Global Font → H4 Option B (16px, 600 weight, SCS Blue)
- Answer Text: Global Font → Body 2 (19px, 400 weight, Body Text Black)
- Icon: Plus/Minus or Chevron (SCS Blue)
- Spacing: 16px between items

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Frequently Asked Questions"
- {{H4_QUESTION_1}}: "What services does SCS Group provide?"
- {{ANSWER_1}}: "SCS Group provides comprehensive commercial cleaning services including office cleaning, industrial cleaning, medical facility cleaning, and more."
- (Repeat for additional FAQ items)

---

## 8. Blog – Archive Grid

**Template Name:** `Blog – Archive Grid 3 Col – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
└── Section (3 Columns on desktop, 1 on mobile)
    └── Post Cards (Loop/Manual)
        ├── Card 1
        │   ├── Featured Image: {{POST_1_IMAGE}}
        │   ├── Category Badge: {{POST_1_CATEGORY}}
        │   ├── Heading (H5): {{H5_POST_1_TITLE}}
        │   ├── Excerpt: {{POST_1_EXCERPT}}
        │   ├── Meta Row (Author, Date)
        │   │   ├── Author: {{POST_1_AUTHOR}}
        │   │   └── Date: {{POST_1_DATE}}
        │   └── Read More Link: {{POST_1_LINK}}
        └── (Repeat for additional posts)
```

**Styling:**
- Background: White or Light Grey
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue)
- Column Gap: 40px
- Card Background: White with subtle shadow
- Card Padding: 0 (image full-width), 24px padding on text area
- Featured Image: Aspect ratio 16:9, object-fit cover
- Category Badge: Background → Ocean Blue, Text → White, Font 14px, Padding 4px 12px
- H5: Global Font → H5 Blogs (24-27px, 700 weight, SCS Blue)
- Excerpt: Global Font → Body 2 (19px, 400 weight), max 2-3 lines
- Author/Date: Global Font → Caption (19px, 500 weight, Seal Grey)
- Read More: Text link (Ocean Blue)
- Hover: Card lifts slightly (box-shadow), H5 underlines

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Our Blog"
- {{POST_1_IMAGE}}: 800x450px placeholder image
- {{POST_1_CATEGORY}}: "Integrated Facility Management"
- {{H5_POST_1_TITLE}}: "How Often Should Hotels Clean Carpets?"
- {{POST_1_EXCERPT}}: "Hotels rely on spotless rooms to create strong first impressions..."
- {{POST_1_AUTHOR}}: "Jono"
- {{POST_1_DATE}}: "January 23, 2026"
- {{POST_1_LINK}}: "#"
- (Repeat for 3, 6, or 9 posts)

---

## 9. Blog – Single Post Layout

**Template Name:** `Blog – Single Post – Kitchen Sink`

**Structure:**
```
Container (Boxed, max-width 900px for readability)
├── Breadcrumbs (Optional)
├── Article Header
│   ├── Category Badge: {{POST_CATEGORY}}
│   ├── Heading (H1): {{H1_POST_TITLE}}
│   └── Meta Row
│       ├── Author: {{POST_AUTHOR}}
│       └── Date: {{POST_DATE}}
├── Featured Image: {{POST_FEATURED_IMAGE}}
├── Content Area
│   └── Post Content: {{POST_CONTENT}}
├── Tags/Share Section
│   ├── Tags: {{POST_TAGS}}
│   └── Social Share Buttons
├── Author Bio (Optional): {{AUTHOR_BIO}}
├── Related Posts Section
│   └── 3 Related Post Cards
└── CTA Section
    └── Quote/Contact CTA
```

**Styling:**
- Background: White
- Padding: 80px top/bottom
- Category Badge: Same as archive
- H1: Global Font → H1 (53px, 600 weight, SCS Blue)
- Meta: Global Font → Caption (19px, 500 weight, Seal Grey)
- Featured Image: Full-width within container, aspect ratio 16:9
- Content: Global Font → Body 2 (19px, 400 weight), line-height 1.8
- Headings within content: H2, H3, H4 per global styles
- Tags: Pills with border (Seal Grey), text (SCS Blue)
- Social Share: Icon buttons (Ocean Blue)
- Related Posts: Same style as archive grid (3 columns)

**Placeholders:**
- {{POST_CATEGORY}}: "Integrated Facility Management"
- {{H1_POST_TITLE}}: "How Often Should Hotels Clean Carpets, Upholstery & Curtains?"
- {{POST_AUTHOR}}: "Jono"
- {{POST_DATE}}: "January 23, 2026"
- {{POST_FEATURED_IMAGE}}: 1200x675px image
- {{POST_CONTENT}}: Full blog post content with headings, paragraphs, lists, images
- {{POST_TAGS}}: "Hotel Cleaning, Carpet Cleaning, Upholstery"
- {{AUTHOR_BIO}}: Author name, photo, short bio

---

## 10. Content – 2 Column Text + Image

**Template Name:** `Content – Text Image 2 Col – Kitchen Sink`

**Structure:**
```
Container (Boxed)
└── Section (2 Columns, 50/50 or 60/40 split)
    ├── Column 1 (Text)
    │   ├── Heading (H2): {{H2_CONTENT_TITLE}}
    │   └── Text Editor: {{CONTENT_BODY}}
    └── Column 2 (Image)
        └── Image: {{CONTENT_IMAGE_URL}}
```

**Styling:**
- Background: White or Background Grey
- Padding: 80px top/bottom, 40px left/right
- Column Gap: 40px
- H2: Global Font → H2 (37px, 600 weight, SCS Blue)
- Body Text: Global Font → Body 2 (19px, 400 weight, Body Text Black)
- Image: Object-fit cover, border-radius optional
- Mobile: Stack columns, image below text
- Variation: Swap column order (image left, text right)

**Placeholders:**
- {{H2_CONTENT_TITLE}}: "Why Choose SCS Group?"
- {{CONTENT_BODY}}: Multi-paragraph content with lists, bolded text, etc.
- {{CONTENT_IMAGE_URL}}: 800x600px image

---

## 11. Content – EPIC Values

**Template Name:** `Content – EPIC Values – Kitchen Sink`

**Structure:**
```
Container (Boxed or Full Width)
├── Heading (H2): "Our 'EPIC' Values"
└── Section (2 Columns on desktop)
    ├── Column 1 (Text Content)
    │   ├── Value 1
    │   │   ├── Icon/Letter: E
    │   │   ├── Heading (H3): "Enterprising"
    │   │   └── Text: {{VALUE_1_DESC}}
    │   ├── Value 2
    │   │   ├── Icon/Letter: P
    │   │   ├── Heading (H3): "Passion"
    │   │   └── Text: {{VALUE_2_DESC}}
    │   ├── Value 3
    │   │   ├── Icon/Letter: I
    │   │   ├── Heading (H3): "Integrity"
    │   │   └── Text: {{VALUE_3_DESC}}
    │   ├── Value 4
    │   │   ├── Icon/Letter: C
    │   │   ├── Heading (H3): "Collaboration"
    │   │   └── Text: {{VALUE_4_DESC}}
    │   └── Button: {{CTA_TEXT}} → {{CTA_LINK}}
    └── Column 2 (Image)
        └── Image: {{EPIC_VALUES_IMAGE_URL}}
```

**Styling:**
- Background: Background Grey or White
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Letter/Icon: Large font (48px), SCS Blue, bold
- H3: Global Font → H3 (19px, 500 weight, Headings Black)
- Description: Global Font → Body 2 (19px, 400 weight)
- Button: SCS Blue background, White text
- Image: Full-height within column

**Placeholders:**
- {{VALUE_1_DESC}}: "We live by our entrepreneurial spirit, taking risks and learning from them..."
- {{VALUE_2_DESC}}: "We show up every day motivated to make a difference..."
- {{VALUE_3_DESC}}: "We lead by example, act with integrity..."
- {{VALUE_4_DESC}}: "We work in collaboration with our clients..."
- {{CTA_TEXT}}: "Find Out More Here"
- {{CTA_LINK}}: "/about-us/"
- {{EPIC_VALUES_IMAGE_URL}}: 800x800px graphic

---

## 12. Content – Certifications 3 Column

**Template Name:** `Content – Certifications 3 Col – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
├── Text Editor: {{SECTION_INTRO}}
└── Section (3 Columns)
    ├── Column 1
    │   ├── Icon/Image: {{CERT_1_ICON}}
    │   ├── Heading (H4): {{H4_CERT_1_TITLE}}
    │   ├── Text: {{CERT_1_DESC}}
    │   └── Button: {{CERT_1_CTA_TEXT}} → {{CERT_1_LINK}}
    ├── Column 2
    │   └── (Same structure)
    └── Column 3
        └── (Same structure)
```

**Styling:**
- Background: White or Light Grey
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Section Intro: Global Font → Body 2 (19px, 400 weight) - Centered
- Column Gap: 40px
- Icon/Image: 120x120px, centered
- H4: Global Font → H4 Option A (21px, 400 weight, SCS Blue)
- Description: Global Font → Body 2 (19px, 400 weight)
- Button: Text link or button (Ocean Blue)

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Quality, Safety & Environmental Standards"
- {{SECTION_INTRO}}: "We take Quality Customer Service, Safety, and Environmental standards very seriously..."
- {{CERT_1_ICON}}: ISO 9001 certification logo
- {{H4_CERT_1_TITLE}}: "Quality Certified System"
- {{CERT_1_DESC}}: "Our commitment with high-quality standards are end to end..."
- {{CERT_1_CTA_TEXT}}: "Find Out More Here"
- {{CERT_1_LINK}}: "/quality-policy/"
- (Repeat for certifications 2 and 3: ISO 14001, ISO 45001)

---

## 13. Location – City Cards Grid

**Template Name:** `Location – City Cards Grid – Kitchen Sink`

**Structure:**
```
Container (Boxed)
├── Heading (H2): {{H2_SECTION_TITLE}}
└── Section (3 or 4 Columns on desktop, 1 on mobile)
    └── City Cards
        ├── Card 1
        │   ├── Heading (H5): {{H5_CITY_1_NAME}}
        │   └── Button/Link: {{CITY_1_LINK}}
        └── (Repeat for 9 cities)
```

**Styling:**
- Background: White or SCS Blue
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, White if on SCS Blue background)
- Column Gap: 24px
- Card Background: White (if section is SCS Blue) or SCS Blue (if section is white)
- Card Padding: 40px
- H5: Global Font → H5 Locations (24-27px, 600 weight, SCS Blue or White depending on card background)
- Button: Text link or icon link
- Hover: Card background changes to Ocean Blue, text to White

**Placeholders:**
- {{H2_SECTION_TITLE}}: "Commercial Cleaning services made easier for you. Find SCS Group in your closest city."
- {{H5_CITY_1_NAME}}: "SCS Group Melbourne"
- {{CITY_1_LINK}}: "/commercial-cleaning-melbourne/"
- (Repeat for Sydney, Brisbane, Adelaide, Perth, Canberra, Darwin, Hobart, New Zealand)

---

## 14. Contact Form – Standard

**Template Name:** `Contact – Form Standard – Kitchen Sink`

**Structure:**
```
Container (Boxed, max-width 800px)
├── Heading (H2): {{H2_FORM_TITLE}}
├── Text Editor: {{FORM_INTRO}}
└── Form Widget (Elementor Pro Form or Contact Form 7)
    ├── Field 1: Name (Required)
    ├── Field 2: Email (Required)
    ├── Field 3: Phone (Required)
    ├── Field 4: Company
    ├── Field 5: Service Type (Dropdown - Required)
    ├── Field 6: Message (Textarea - Required)
    └── Submit Button: {{SUBMIT_BUTTON_TEXT}}
```

**Styling:**
- Background: White or Light Grey
- Padding: 80px top/bottom
- H2: Global Font → H2 (37px, 600 weight, SCS Blue) - Centered
- Form Intro: Global Font → Body 2 (19px, 400 weight) - Centered
- Field Labels: Global Font → Body 2 (19px, 500 weight, Headings Black)
- Field Inputs: Border 1px Seal Grey, Padding 12px, Font 16px
- Field Focus: Border SCS Blue
- Submit Button: Background → SCS Blue, Text → White, Font → Button Text (16px, 500 weight)
- Error Messages: Red text
- Success Message: Green background, White text

**Placeholders:**
- {{H2_FORM_TITLE}}: "Get A Quote Now"
- {{FORM_INTRO}}: "Contact us today to get a personalised cleaning proposal."
- {{SUBMIT_BUTTON_TEXT}}: "Submit"
- Service Type Options: Commercial Cleaning, Industrial Cleaning, Medical Cleaning, etc.

---

## 15. Footer – Standard

**Template Name:** `Footer – Standard – Kitchen Sink`

**Structure:**
```
Container (Full Width)
├── Section 1 (4 Columns on desktop, 1 on mobile)
│   ├── Column 1 - Company
│   │   ├── Heading (H4): "Company"
│   │   └── Nav Menu: {{COMPANY_MENU_LINKS}}
│   ├── Column 2 - Locations
│   │   ├── Heading (H4): "Locations"
│   │   └── Nav Menu: {{LOCATIONS_MENU_LINKS}}
│   ├── Column 3 - Resources
│   │   ├── Heading (H4): "Resources"
│   │   └── Nav Menu: {{RESOURCES_MENU_LINKS}}
│   └── Column 4 - Contact/Logo
│       ├── Logo: {{FOOTER_LOGO_URL}}
│       └── CTA Button: {{FOOTER_CTA_TEXT}} → {{FOOTER_CTA_LINK}}
├── Section 2 (Copyright & Social)
│   ├── Copyright Text: {{COPYRIGHT_TEXT}}
│   └── Social Media Icons: {{SOCIAL_LINKS}}
```

**Styling:**
- Background: Dark Grey (#555555) or Headings Black (#1A1A1A)
- Padding: 60px top/bottom
- H4: Global Font → H4 Option B (16px, 600 weight, White)
- Menu Links: Global Font → Body 2 (19px, 400 weight, White), no underline
- Link Hover: Color → Ocean Blue
- Copyright: Global Font → Caption (19px, 500 weight, Seal Grey)
- Social Icons: 32px size, White color, Ocean Blue on hover
- Footer CTA Button: Background → White, Text → SCS Blue

**Placeholders:**
- {{COMPANY_MENU_LINKS}}: Work With Us, About Us, SCS Group Indigenous, Services/Industries, Locations, Sponsorships, Awards
- {{LOCATIONS_MENU_LINKS}}: Melbourne, Sydney, Brisbane, Adelaide, Perth, Canberra, Darwin, Hobart, New Zealand
- {{RESOURCES_MENU_LINKS}}: Quality Policy, OH&S Policy, Environmental Policy, Privacy Policy, Sitemap
- {{FOOTER_LOGO_URL}}: Footer logo (white version)
- {{FOOTER_CTA_TEXT}}: "Request A Quote"
- {{FOOTER_CTA_LINK}}: "/contact-us/"
- {{COPYRIGHT_TEXT}}: "© 2026 Commercial & Office Cleaning Service Australia | SCS Group. All Rights Reserved"
- {{SOCIAL_LINKS}}: Facebook, LinkedIn, YouTube, Instagram

---

## Global Settings Reference

### Colors (Site Settings > Global Colors)
1. **SCS Blue (Primary)**: #124CA1
2. **Ocean Blue**: #5795CE
3. **Seal Grey**: #919294
4. **Dark Grey**: #555555
5. **Light Grey (Tint 1)**: #D9D9D9
6. **Headings Black**: #1A1A1A
7. **Body Text Black**: #222222
8. **Background Grey**: #F2F2F2

### Typography (Site Settings > Global Fonts)

| Element | Weight | Size | Color |
|---------|--------|------|-------|
| H1 | 600 | 53px | SCS Blue/White |
| H2 | 600 | 37px | SCS Blue/White |
| H3 | 500 | 19px | Headings Black |
| H4 Opt A | 400 | 21px | SCS Blue |
| H4 Opt B | 600 | 16px | SCS Blue |
| H5 Locations | 600 | 24-27px | SCS Blue |
| H5 Blogs | 700 | 24-27px | SCS Blue |
| H6 Blog Title | 400 | 32px | White |
| Body 1 | 500 | 16px | SCS Blue/White |
| Body 2 | 400 | 19px | Headings Black |
| Body 2 Bold | 600 | 19px | Headings Black |
| Button | 500 | 16px | White |
| Caption | 500 | 19-21px | White/Seal Grey |

---

## Implementation Checklist for Each Block

Before marking a block as complete, verify:

- [ ] All global colors used (no hardcoded hex)
- [ ] All global fonts used (no custom sizes)
- [ ] Responsive on mobile, tablet, desktop
- [ ] All placeholders clearly labeled
- [ ] Hover states defined
- [ ] Animation/transitions are subtle
- [ ] Accessibility: proper heading hierarchy, contrast
- [ ] Documented with screenshots
- [ ] Saved as template in Elementor
- [ ] Named correctly with Kitchen Sink suffix

---

## Next Steps

1. **Set up Global Colors and Fonts** in Elementor Site Settings first
2. **Build Priority 1 blocks** (Hero, Service Grid, CTA, Client Logos, Stats)
3. **Test each block** on a test page before saving as template
4. **Document each block** with screenshots and notes
5. **Build Priority 2 and 3 blocks** once core blocks are complete
6. **Assemble test pages** using combinations of blocks
7. **Final QA** on all blocks and page assemblies
