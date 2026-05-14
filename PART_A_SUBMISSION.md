# MMA710S MULTIMEDIA APPLICATIONS
# PROJECT PART A: WEBSITE DESIGN SPECIFICATIONS

**Course:** MMA710S Multimedia Applications  
**Assessment Task:** Project Part A – Website Design  
**Due Date:** 29 April 2026 @ 23:59  
**Storyboards:** 5 Marks  
**Design Specifications:** 15 Marks (Planning Document)  
**Submission:** Zipped folder e-mailed to jbillawer@nust.na and uploaded on MS Teams

---

**Group Members:**

| # | Full Name | Student ID |
|---|-----------|------------|
| 1 | Senia Shipepe | 224076760 |
| 2 | Phrancina Sunday Ndjambula | 223085618 |
| 3 | Faith Miriam Hamutenya | 223017183 |
| 4 | Andris Junior Etuna Kaishungu | 223043710 |
| 5 | Alvine Murangi | 223091839 |

**Programme:** Bachelor of Informatics  
**Institution:** Namibia University of Science and Technology (NUST)

---

## TABLE OF CONTENTS

1. [Introduction/Goal](#1-introductiongoal)
2. [Target Audience](#2-target-audience)
3. [Site Layout (Flowchart)](#3-site-layout-flowchart)
4. [Navigation Scheme](#4-navigation-scheme)
5. [Visual Elements/Style](#5-visual-elementsstyle)
6. [Content Details](#6-content-details)
7. [Specific Multimedia Content](#7-specific-multimedia-content)
8. [Testing](#8-testing)
9. [References](#9-references)

---

## 1. INTRODUCTION/GOAL

### What We Are Making

A 5-page multimedia portfolio website showcasing our group's academic profiles, professional aspirations, educational backgrounds, current coursework, and project references. The website integrates HTML, CSS, images, audio, and animation into a cohesive digital product.

### Why We Are Making It

This project demonstrates the practical application of multimedia development skills acquired in the MMA710S course. Beyond fulfilling the assignment requirements, it serves as:

- A **digital portfolio** presenting our professional and academic identities
- A practical exercise in **web design and development** from planning through implementation
- A demonstration of **multimedia integration** — combining images, audio, and animation effectively
- Evidence of **collaborative project management** across a 5-member team
- Application of **industry-standard practices** in web development and design specification

### Expected Outcome

A fully functional, professionally styled 5-page website (index.html, experience.html, education.html, courses.html, references.html) that adheres strictly to the assignment brief, communicates our group's skills and backgrounds effectively, and demonstrates competency in multimedia web development.

---

## 2. TARGET AUDIENCE

### Primary Audience

**Academics & Educators**
- University lecturers (Mr Akinsola, Mr Billawer) evaluating multimedia competency
- Assessment personnel reviewing assignment submissions
- Programme coordinators assessing project quality

**Potential Employers**
- IT and multimedia companies reviewing digital portfolios
- HR departments evaluating technical skills of Bachelor of Informatics graduates
- Recruitment specialists in the Namibian technology sector

**Peers & Students**
- Fellow Bachelor of Informatics students seeking inspiration or reference
- Classmates interested in multimedia project standards

### Secondary Audience

- General public accessing the portfolio through personal networks
- Industry professionals interested in graduate capabilities

### Audience Technical Profile

- **Primary Platform:** Desktop computers (1024×768 resolution or higher)
- **Secondary Platform:** Tablets and mobile devices
- **Technical Capability:** Medium to high (tech-savvy academic and professional audience)
- **Browser Compatibility:** Modern browsers — Chrome, Firefox, Safari, Edge
- **Accessibility:** Content readable and navigable for diverse users

---

## 3. SITE LAYOUT (FLOWCHART)

### Site Architecture Overview

The website follows a flat navigation structure where every page links to every other page. The home page (index.html) serves as the primary entry point.

```
                          ┌─────────────────────┐
                          │   HOME (index.html)  │
                          │   Page 1: Collage +  │
                          │   Personal Info      │
                          └──────────┬───────────┘
                                     │
              ┌──────────────────────┼──────────────────────┐
              │                      │                      │
   ┌──────────▼──────────┐  ┌───────▼────────┐  ┌──────────▼──────────┐
   │  experience.html    │  │ education.html │  │   courses.html      │
   │  Page 2: Roles &   │  │ Page 3: Edu    │  │   Page 4: Courses   │
   │  Experience         │  │ Background +   │  │   + Animation       │
   │                     │  │ Audio Intro    │  │                     │
   └─────────────────────┘  └────────────────┘  └─────────────────────┘
              │                      │                      │
              └──────────────────────┼──────────────────────┘
                                     │
                          ┌──────────▼──────────┐
                          │  references.html    │
                          │  Page 5: All        │
                          │  References (APA)   │
                          └─────────────────────┘

  ✓ All 5 pages interconnected via navigation bar
  ✓ Users can navigate to any page from any page
  ✓ Home page is the primary entry point
  ✓ Consistent navigation across all pages
```

### Standard Page Layout Template

Every page follows this consistent structure:

```
┌─────────────────────────────────────────┐
│         PAGE TITLE (h1, uppercase)      │  ← Gradient header bar
├─────────────────────────────────────────┤
│ Home | Experience | Education |         │
│ Courses | References                    │  ← Horizontal navigation
├─────────────────────────────────────────┤
│         PAGE HEADING (h2)               │  ← Section title with underline
├─────────────────────────────────────────┤
│                                         │
│    Page-Specific Content                │  ← Content area (white bg)
│    (Images, Tables, Audio, etc.)        │
│                                         │
├─────────────────────────────────────────┤
│  © 2026 Group Members: [Names] |        │
│  Bachelor of Informatics                │  ← Footer (dark blue bg)
└─────────────────────────────────────────┘
```

---

## 4. NAVIGATION SCHEME

### Navigation Structure

**Implementation:**
- Horizontal navigation bar at the top of each page, below the page title
- 5 navigation links: **Home | Experience | Education | Courses | References**
- Persistent and identical across all 5 pages
- Current page link highlighted with coral red (#ff6b6b) background — active state has no working link (pointer-events disabled)
- All other links functional and navigable
- Hover effects provide visual feedback (background changes to #2a7a9e)
- Responsive: navigation stacks vertically on screens ≤768px

**Navigation Behaviour per Page:**

| Page | Active (Non-Linked) | Other Links |
|------|---------------------|-------------|
| index.html | Home | Experience, Education, Courses, References |
| experience.html | Experience | Home, Education, Courses, References |
| education.html | Education | Home, Experience, Courses, References |
| courses.html | Courses | Home, Experience, Education, References |
| references.html | References | Home, Experience, Education, Courses |

### Why Is a Consistent Navigation Scheme Very Important?

A consistent navigation scheme is critical for several reasons:

**1. User Familiarity & Reduced Cognitive Load**  
When navigation appears in the same location and behaves identically across all pages, users only need to learn it once. This predictability reduces cognitive load and allows users to focus on content rather than searching for how to move between pages.

**2. Professional Credibility**  
Consistent navigation signals careful planning and professional design. It demonstrates that the website was constructed with attention to detail and adherence to established web standards.

**3. Accessibility & Usability**  
Consistent navigation patterns are easier for assistive technologies (such as screen readers) to interpret, improving accessibility. Users with disabilities benefit from predictable interface patterns.

**4. Reduced Errors & Frustration**  
When users can predict how navigation works, they make fewer errors and experience less frustration. This leads to longer engagement and a more positive user experience.

**Reference:**  
Nielsen, J. (2012). *10 usability heuristics for user interface design.* Nielsen Norman Group. Retrieved from https://www.nngroup.com/articles/ten-usability-heuristics/

---

## 5. VISUAL ELEMENTS/STYLE

This section describes the "look" of the pages without the content. All styles are saved in a single Cascading Style Sheet: **MyLook-1.css**.

### Colour Scheme

| Element | Colour | Hex Code | Rationale |
|---------|--------|----------|-----------|
| Page Background | Soft Blue-Grey | #e8f0f7 | Creates a professional, calm environment; reduces eye strain; not white (as required) |
| Content Container | Lighter Blue-Grey | #f5f8fb | Subtle variation provides visual hierarchy |
| Content Sections | White | #ffffff | High contrast for readability |
| Navigation Bar & Footer | Dark Blue | #1a5f7a | Conveys professionalism, trust, and technical competence |
| Headings & Borders | Medium Blue | #2a7a9e | Creates visual hierarchy; guides attention to headings |
| Active Navigation | Coral Red | #ff6b6b | Creates visual contrast for current page; draws attention |
| Body Text | Dark Grey | #333333 | Excellent readability; softer than pure black |
| Links | Standard Blue | #0066cc | Familiar web convention for clickable links |

**Why this colour scheme?**  
The cool blue tones convey professionalism and trustworthiness — appealing to the technology and academic audience. The warm coral accent creates energy and draws attention to key interactive elements without clashing. The soft blue-grey background satisfies the requirement that background cannot be white, while maintaining a clean and modern appearance.

### Typography

| Element | Font | Size | Weight | Purpose |
|---------|------|------|--------|---------|
| All Text | Arial, Helvetica, sans-serif | — | — | Universal compatibility, high legibility |
| Page Title (h1) | Arial | 2.5rem (40px) | Bold, Uppercase | Dominant page identifier |
| Page Heading (h2) | Arial | 1.8rem (28px) | 600 (Semi-Bold) | Section title with underline |
| Subsection (h3) | Arial | 1.3rem (22px) | Normal | Content subsections |
| Body Text (p) | Arial | 1rem (16px) | Normal | Primary reading text |
| Captions/Small | Arial | 0.9rem (14px) | Italic | Image captions, secondary info |
| Student ID Watermark | Arial | 8px | Normal | Required watermark on all images |

**Line Spacing:** 1.6 (general), 1.8 (body paragraphs)

**Why this typography?**  
Sans-serif fonts provide superior on-screen readability. Arial is universally available across all browsers and operating systems without additional downloads. The clear size hierarchy guides users through content naturally. The generous line spacing improves readability and creates a professional appearance.

### Layout Approach

- **CSS layers** for content positioning (no frames, as required by the assignment brief)
- **CSS Grid** for the collage layout (responsive 2×2 grid on desktop, single column on mobile)
- **Flexbox** for navigation, profile items, and flexible component arrangement
- **Box-shadow** effects (0 4px 12px rgba(0,0,0,0.08)) for subtle depth
- **Border-radius** (5px) for softer corners on containers and images
- **Hover transitions** (0.3s ease) for interactive feedback on navigation, cards, and collage items
- **Responsive breakpoints:** 768px (tablet), 480px (mobile), 320px (extra small)

---

## 6. CONTENT DETAILS

### Page 1: HOME (index.html)

- **Collage:** A responsive grid of 5 images (one per group member), displayed using HTML5 Canvas elements. Each canvas draws the member's seated photograph with their student ID watermarked in Arial size 8. The collage is arranged in a 2-column grid (max-width 600px, centered). Inside the collage area, the group members' names and programme name (Bachelor of Informatics) are displayed.
- **Personal Information:** 5 profile cards, each containing: full name, student ID, date of birth, contact number, email address, and languages spoken.
- **Programme Info:** "Bachelor of Informatics" and "Informatics" course designation.
- **Footer:** © 2026 with all five group member names, programme, and project title.
- **Title:** "Welcome" (h1) | **Heading:** "Portfolio & Project Overview" (h2)

### Page 2: EXPERIENCE (experience.html)

For each of the 5 group members:
- **Photograph** of the member at a computer (seated photos)
- **Project Role** and multimedia development experience summary
- **Ideal Multimedia Role** with justification:
  - Senia Shipepe → Content Writer
  - Phrancina Ndjambula → Designer
  - Faith Hamutenya → IT Technician / Data Analyst
  - Andris Kaishungu → Web Developer
  - Alvine Murangi → Editor
- **Role-related image** (stock photo representing the role)
- **Activities & Community Involvement** list
- **Title:** "Experience" (h1) | **Heading:** "Multimedia Development Experience" (h2)

### Page 3: EDUCATION (education.html)

- **Audio Introduction:** A 30-second OGG sound file (Education Background Audio.ogg) introducing the group and explaining why we are pursuing the Bachelor of Informatics. Presented via a custom-styled audio player with play/pause, progress bar, and volume controls. The audio is introduced with: *"Listen to our 30-second introduction explaining our educational background and why we chose to pursue the Bachelor of Informatics programme."*
- **Educational Background** for each of 5 members:
  - Secondary school name, location, and year completed
  - Tertiary institution (NUST for all)
  - Current programme, start year, and expected graduation
  - Personal motivation for choosing Bachelor of Informatics
- **Title:** "Education" (h1) | **Heading:** "Educational Background" (h2)

### Page 4: COURSES (courses.html)

- **Third-Year Course Table** with 6 courses:

| Code | Course Name | Lecturer |
|------|-------------|----------|
| AAI711S | Advanced Applications of Informatics | Mrs Amunkete |
| BIA711S | Business Intelligence and Analytics | Dr Kwenda |
| ERP720S | Enterprise Resource Planning Systems | Mr Billawer |
| ISG711S | Information Systems Strategy and Governance | Dr Kwenda |
| MMA710S | Multimedia Applications | Mr Akinsola |
| WPM711S | Web Programming | Mr Mbaeva |

- **Animation:** A CSS/JavaScript-based image slideshow of all 15 project images (excluding any banner). The animation uses a two-column layout — left column slides images upward, right column slides images downward — cycling every 3 seconds with a 1.5-second offset between columns. Images are displayed at uniform dimensions using background-size: contain.
- **Title:** "Courses" (h1) | **Heading:** "Third Year Courses – Bachelor of Informatics" (h2)

### Page 5: REFERENCES (references.html)

- **Career & Professional Development References** — MMA710S lecture notes and course materials
- **Image & Media Resources** — Pexels (https://www.pexels.com/) for stock photos used as role images
- **Software & Development Tools** — with links to official homepages:
  - Visual Studio Code: https://code.visualstudio.com/
- **Web Development & Design Resources** — W3Schools HTML references, GitHub Education resources
- **Project Repository** — GitHub: https://github.com/Kash-Jr/mma-web/tree/main
- All references in APA format with working hyperlinks
- **Title:** "References" (h1) | **Heading:** "Project References" (h2)

---

## 7. SPECIFIC MULTIMEDIA CONTENT

### Image Assets

**Format:** JPEG and JPG (web-optimised)  
**Student ID Watermark:** All images contain the respective student ID number — font: Arial, size: 8 (as required)

**Image Inventory (15 files total):**

| # | Filename | Type | Approx. Size | Used On |
|---|----------|------|-------------|---------|
| 1 | Senia seated.jpeg | Member photo at computer | 49 KB | Pages 1, 2, 4 |
| 2 | Senia standing.jpeg | Member standing photo | 45 KB | Page 4 (animation) |
| 3 | Phrancina seated.jpeg | Member photo at computer | 198 KB | Pages 1, 2, 4 |
| 4 | Phrancina standing.jpeg | Member standing photo | 215 KB | Page 4 (animation) |
| 5 | Faith seated.jpeg | Member photo at computer | 54 KB | Pages 1, 2, 4 |
| 6 | Faith standing.jpeg | Member standing photo | 56 KB | Page 4 (animation) |
| 7 | Andris seated.jpeg | Member photo at computer | 89 KB | Pages 1, 2, 4 |
| 8 | Andris standing.jpeg | Member standing photo | 50 KB | Page 4 (animation) |
| 9 | Alvine seated.jpeg | Member photo at computer | 50 KB | Pages 1, 2, 4 |
| 10 | Alvine standing.jpeg | Member standing photo | 58 KB | Page 4 (animation) |
| 11 | Content Writer Image.jpg | Role image (Senia) | 677 KB | Page 2 |
| 12 | Designer Image.jpg | Role image (Phrancina) | 814 KB | Page 2 |
| 13 | IT Technician-Data Analyst Image.jpg | Role image (Faith) | 769 KB | Page 2 |
| 14 | Web Developer Image.jpg | Role image (Andris) | 1,534 KB | Page 2 |
| 15 | Editor Image.jpg | Role image (Alvine) | 1,858 KB | Page 2 |

**Total Image Size:** Approximately 5.5 MB  
**Note:** The standing photos are used on the Education page (Page 3) as the different group photos required by the brief (distinct from the seated photos on Page 2).

### Audio Content

| Property | Specification |
|----------|--------------|
| **Filename** | Education Background Audio.ogg |
| **Format** | OGG (Ogg Vorbis) |
| **Duration** | ~30 seconds |
| **File Size** | 80 KB |
| **Sample Rate** | 44.1 kHz (standard) |
| **Content** | Group introduction and explanation of why we are pursuing the Bachelor of Informatics |
| **Location** | Page 3 (education.html) |
| **Presentation** | Custom-styled audio player with play/pause, seek bar, time display, and volume control |
| **Linked Image** | Standing photos of group members (different from Page 2 seated photos) |

### Animation

| Property | Specification |
|----------|--------------|
| **Type** | CSS/JavaScript image slideshow (replaces Flash due to Flash deprecation) |
| **Images Included** | All 15 project images (no banner used) |
| **Images Excluded** | No banner images are used in this project |
| **Sizing** | All images displayed at uniform dimensions using CSS background-size: contain |
| **Transition Style** | Two-column layout: left slides up, right slides down |
| **Cycle Duration** | 3 seconds per image, 1.5s offset between columns |
| **Duration** | Continuous loop |
| **Sound** | No sound file inside the animation (as required) |
| **Location** | Page 4 (courses.html) |

**Total Multimedia File Sizes:**
- Images: ~5.5 MB
- Audio: ~80 KB
- Animation: Built with CSS/JS (no separate file)
- **Total:** ~5.6 MB

---

## 8. TESTING

### Differences Between Technical and Design Testing

**Technical Testing** verifies that all functional components work correctly:
- Do all 5 navigation links on every page point to the correct target page?
- Do all 15 images load and display without broken references?
- Does the audio file (OGG) play correctly across browsers?
- Does the CSS animation cycle through images without errors?
- Is the CSS stylesheet (MyLook-1.css) loaded successfully on all pages?
- Are there any console errors (checked via browser Developer Tools, F12)?
- Does the website function correctly after being zipped and extracted?

**Design Testing** evaluates the user experience and visual quality:
- Is the visual design consistent across all 5 pages?
- Is the navigation intuitive — can users easily find their way?
- Is the colour scheme appealing, professional, and accessible?
- Is the typography readable with clear hierarchy?
- Is the layout balanced and well-organised?
- Does the collage on Page 1 look professional and blended?
- Is the audio introduction clear and well-presented?

**Reference:**  
Barnum, C. M. (2020). *Usability testing essentials: Ready, set...test!* (2nd ed.). Morgan Kaufmann. Retrieved from https://www.sciencedirect.com/book/9780128169421/usability-testing-essentials

### Why Is There a Need for Testing?

Testing is essential because:

1. **Quality Assurance:** Ensures the website functions as intended and meets all assignment specifications before submission.
2. **Error Detection:** Identifies broken links, missing files, layout issues, and browser incompatibilities that would cost marks.
3. **User Experience:** Confirms that the website is intuitive, readable, and accessible to the target audience.
4. **Professional Standards:** Industry practice requires testing before any product is deployed or delivered. This habit reflects real-world web development.
5. **Compliance Verification:** Confirms strict adherence to the assignment brief — all required elements present and correctly implemented.

### Testing Plan

**Phase 1: Technical Testing**
1. Click all navigation links on every page to verify correct targets
2. Verify all 15 images load on their respective pages
3. Confirm audio playback on Page 3 across Chrome, Firefox, and Edge
4. Test animation on Page 4 — verify all images cycle smoothly
5. Open browser console (F12) to check for resource errors on every page
6. Test responsive layout at 1024px, 768px, 480px, and 320px widths

**Phase 2: Design Testing**
1. Verify consistent colours, fonts, and spacing across all 5 pages
2. Check text contrast and font sizes for readability
3. Verify active navigation states are visually clear
4. Confirm images display without distortion
5. Evaluate collage balance and visual appeal
6. Assess overall page balance and whitespace usage

**Phase 3: Submission Testing**
1. Zip the entire project folder
2. Extract the zip to a new location
3. Open index.html and verify all links, images, audio, and animation still work
4. Test in at least two different browsers

---

## 9. REFERENCES

Barnum, C. M. (2020). *Usability testing essentials: Ready, set...test!* (2nd ed.). Morgan Kaufmann. https://www.sciencedirect.com/book/9780128169421/usability-testing-essentials

Garrett, J. J. (2010). *The elements of user experience: User-centered design for the web and beyond.* New Riders Press.

Mozilla Developer Network. (2024). *CSS: Cascading Style Sheets.* https://developer.mozilla.org/en-US/docs/Web/CSS

Mozilla Developer Network. (2024). *HTML: HyperText Markup Language.* https://developer.mozilla.org/en-US/docs/Web/HTML

Nielsen, J. (2012). *10 usability heuristics for user interface design.* Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/

Pexels. (2024). *Free stock photos.* https://www.pexels.com/

Visual Studio Code. (2024). *Code editor — official homepage.* https://code.visualstudio.com/

W3C (World Wide Web Consortium). (2023). *Web Content Accessibility Guidelines (WCAG) 2.1.* https://www.w3.org/WAI/WCAG21/quickref/

W3Schools. (2024). *HTML forms and attributes.* https://www.w3schools.com/html/html_forms_attributes.asp

---

## DOCUMENT STATUS

**Status:** ✅ Document Ready for Submission  
**Prepared:** May 2026  
**Course:** MMA710S Multimedia Applications  
**Programme:** Bachelor of Informatics, NUST  
**CSS Filename:** MyLook-1.css  
**Home Page Filename:** index.html

---

*MMA710S Multimedia Applications — Project Part A: Website Design Specifications*  
*Bachelor of Informatics Programme — Namibia University of Science and Technology*  
*© 2026 Senia Shipepe, Phrancina Sunday Ndjambula, Faith Miriam Hamutenya, Andris Junior Etuna Kaishungu, Alvine Murangi*
