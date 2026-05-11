# MMA WEB PROJECT - PART A: WEBSITE DESIGN SPECIFICATIONS

**Project:** Multimedia Assignment - Part A  
**Date Submitted:** May 7, 2026  
**Group:** Bachelor of Informatics Programme  
**Status:** Ready for Submission

---

## TABLE OF CONTENTS

1. [Introduction/Goal](#1-introductiongoal)
2. [Target Audience](#2-target-audience)
3. [Site Layout - Flowchart](#3-site-layout--flowchart)
4. [Navigation Scheme](#4-navigation-scheme)
5. [Visual Elements/Style](#5-visual-elementsstyle--look-of-pages)
6. [Content Details](#6-content-details)
7. [Specific Multimedia Content](#7-specific-multimedia-content)
8. [Testing Plan](#8-testing-plan)
9. [References](#9-references)

---

## 1. INTRODUCTION/GOAL

### What is this project?

This MMA Web portfolio project is an educational multimedia website showcasing the academic and professional development of Bachelor of Informatics students. The website serves as a digital portfolio that integrates HTML, CSS, and multimedia elements to create a cohesive online presence.

### Why are we making it?

Beyond fulfilling an educational assignment, this project demonstrates the practical application of multimedia development skills in creating professional web content. It provides valuable experience in:

- **Web Design & Development:** Understanding the full lifecycle of website creation from planning to implementation
- **Portfolio Creation:** Building a professional online presence to attract potential employers
- **Multimedia Integration:** Combining various media types (images, audio, animation) in a coherent digital product
- **Project Management:** Collaborating as a team to deliver a complete multimedia solution
- **Industry-Standard Practices:** Applying real-world web development methodologies and design principles

### Expected Outcome

A fully functional, professionally designed 5-page website that effectively communicates the team's skills, experience, and educational background while adhering to modern web standards and best practices.

---

## 2. TARGET AUDIENCE

### Primary Audience

**Academics & Educators**
- University lecturers and academic advisors evaluating multimedia competency
- Assessment personnel reviewing assignment submissions
- Programme coordinators assessing project quality

**Potential Employers**
- IT and multimedia companies reviewing digital portfolios
- HR departments evaluating technical skills
- Recruitment specialists in the technology sector

**Peers & Students**
- Other informatics students seeking inspiration or reference material
- Classmates interested in multimedia project standards
- Student community members exploring career paths

### Secondary Audience

- General public accessing the portfolio through personal networks
- Industry professionals interested in graduate capabilities
- Family members of group participants

### Audience Expectations & Technical Capabilities

- **Expected Viewing Platform:** Desktop computers (primary), tablets (secondary), mobile devices
- **Technical Capability:** Medium to high (tech-savvy audience)
- **Browser Compatibility:** Modern browsers (Chrome, Firefox, Safari, Edge)
- **Network Speed:** Variable (should load efficiently on standard connections)
- **Accessibility:** Content should be readable and navigable for diverse users

---

## 3. SITE LAYOUT - FLOWCHART

### Navigation Architecture

```
                          ┌─────────────────┐
                          │  HOME (index)   │
                          │  Page 1: Cover  │
                          │  + Collage      │
                          └────────┬────────┘
                                   │
                    ┌──────────────┼──────────────┐
                    │              │              │
         ┌──────────▼──────────┐   │   ┌──────────▼──────────┐
         │  EXPERIENCE.html    │   │   │  EDUCATION.html     │
         │  Page 2: Roles      │   │   │  Page 3: Background │
         │  + Computer Photo   │   │   │  + Audio Intro      │
         └─────────────────────┘   │   └─────────────────────┘
                    │              │              │
                    └──────────────┼──────────────┘
                                   │
         ┌─────────────────────────┼─────────────────────────┐
         │                         │                         │
    ┌────▼────────────────┐   ┌────▼────────────────┐   
    │  COURSES.html       │   │  REFERENCES.html    │   
    │  Page 4: Courses    │   │  Page 5: Links      │   
    │  + Flash Animation  │   │  + APA References   │   
    └─────────────────────┘   └─────────────────────┘   

Key Features:
✓ All pages interconnected via navigation menu
✓ Users can navigate to any page from any page
✓ Hierarchical structure with Home as entry point
✓ Consistent navigation system across all pages
```

### Detailed Page Layout

**Page 1 - HOME (index.html)**
```
┌─────────────────────────────────────┐
│    WELCOME (Page Title)             │
├─────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ... │ ← Navigation
├─────────────────────────────────────┤
│         Page Heading                │
├─────────────────────────────────────┤
│     COLLAGE OF ALL IMAGES           │ ← 4 images arranged
│  (Grid layout, 2x2 or responsive)   │
├─────────────────────────────────────┤
│  Group Member Information (1-5)     │ ← Profile cards
│  - Names, IDs, Dates, Contact Info  │
├─────────────────────────────────────┤
│         © 2026 | Footer              │
└─────────────────────────────────────┘
```

**Pages 2-5 - Standard Layout**
```
┌─────────────────────────────────────┐
│    PAGE TITLE (Experience/Education/...)
├─────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ... │ ← Consistent Navigation
├─────────────────────────────────────┤
│         Page Heading                │
├─────────────────────────────────────┤
│                                     │
│  Page-Specific Content              │
│  (Images, Tables, Audio, etc.)      │
│                                     │
├─────────────────────────────────────┤
│         © 2026 | Footer              │
└─────────────────────────────────────┘
```

---

## 4. NAVIGATION SCHEME

### Navigation Structure

**Implementation Approach:**
- Horizontal navigation bar positioned at the top of each page
- Below the main page title
- Above the main content area
- Persistent across all pages for consistency

**Navigation Elements:**
- 5 navigation links: Home, Experience, Education, Courses, References
- Current page highlighted with active state (coral red background)
- Links styled as buttons for clear affordance
- Responsive design: stacks vertically on mobile devices

**Navigation Behavior:**
- All links functional and working
- Current page link is disabled/inactive
- Hover effects provide visual feedback
- Mobile-friendly: collapses to vertical menu on small screens

### Why is a Consistent Navigation Scheme Very Important?

A consistent navigation scheme is critical to web design and user experience for several essential reasons:

**1. User Familiarity & Predictability**

Users expect navigation to be in the same location and function the same way across all pages. Consistency reduces cognitive load and makes the website feel professional and trustworthy. When navigation is predictable, users can focus on content rather than searching for how to navigate.

*Nielsen, J. (2012). "10 Usability Heuristics for User Interface Design." Nielsen Norman Group. Accessed from: https://www.nngroup.com/articles/ten-usability-heuristics/*

**2. Reduced Learning Curve**

A consistent navigation system means users only need to learn it once. They immediately understand how to move through the site on subsequent pages, creating a seamless user experience and reducing frustration or confusion.

**3. Professional Appearance**

Consistent navigation demonstrates attention to detail and professional design practices. It indicates that the website was carefully planned and constructed according to established web standards, enhancing credibility.

**4. SEO & Accessibility Benefits**

Search engines recognize consistent site architecture and navigation patterns, which can improve search rankings. Additionally, consistent navigation patterns are easier for assistive technologies (screen readers) to interpret, improving accessibility for users with disabilities.

**5. Conversion & User Goals**

Users who understand how to navigate a website are more likely to explore it thoroughly, find what they're looking for, and accomplish their goals (whether viewing a portfolio, learning about skills, or contacting the team).

**6. Mobile Compatibility**

Consistent navigation patterns that adapt responsively to different screen sizes ensure the website functions well across all devices, which is essential given the diversity of user access methods.

---

## 5. VISUAL ELEMENTS/STYLE - "LOOK" OF PAGES

### Color Scheme

**Background Colors:**
- **Primary Background:** #e8f0f7 (Soft Blue-Grey)
  - **Why:** Creates a professional, calm environment; reduces eye strain; commonly used in corporate web design; suggests trustworthiness and stability

- **Secondary Background:** #f5f8fb (Lighter Blue-Grey)
  - **Why:** Subtle variation provides visual hierarchy without overwhelming the content area

- **Content Container:** #ffffff (White)
  - **Why:** Ensures high contrast for readability while maintaining the cool color scheme through surrounding elements

**Accent Colors:**
- **Primary Color:** #1a5f7a (Dark Blue)
  - **Why:** Conveys professionalism, trust, and technical competence; used for footer, primary navigation background

- **Secondary Accent:** #2a7a9e (Medium Blue)
  - **Why:** Creates visual hierarchy; guides user attention to important elements like headings and borders; provides continuity with primary color

- **Highlight Color:** #ff6b6b (Coral Red)
  - **Why:** Creates visual contrast for active navigation states; draws attention to the current page without clashing with the overall color scheme; energetic yet professional

- **Text Color:** #333333 (Dark Grey)
  - **Why:** Excellent contrast for readability; softer than pure black to reduce eye strain while maintaining legibility

### Typography

**Font Family:** Arial, Helvetica, sans-serif
- **Why:** Highly legible on web across all devices; professional appearance; universal compatibility across browsers and operating systems; no additional downloads required

**Font Sizes & Hierarchy:**
- **Page Title:** 2.5rem (uppercase, bold, 40px equivalent)
  - **Purpose:** Immediately identifies the page; dominant visual element
  
- **Page Heading (Section Title):** 1.8rem (bold, 28px equivalent)
  - **Purpose:** Clearly delineates major sections; maintains visual structure
  
- **Subsection Heading (h3):** 1.3rem (22px equivalent)
  - **Purpose:** Identifies content subsections; maintains hierarchy
  
- **Body Text:** 1rem (16px equivalent)
  - **Purpose:** Primary reading text; comfortable size for extended reading; accessible size for vision-impaired users
  
- **Small Text/Captions:** 0.9rem (14px equivalent)
  - **Purpose:** Image captions, footer text; secondary information

**Line Spacing:** 1.6 (default), 1.8 for body text
- **Why:** Generous line spacing improves readability; reduces eye fatigue; creates professional appearance

### Layout Approach

**Design Methodology:**
- CSS-based layer positioning (no frames - as required)
- Grid system for responsive layouts
- Flexbox for navigation and flexible component arrangement
- Mobile-first responsive design approach

**Key Design Principles Applied:**
- **Grid-Based Layout:** Ensures alignment and visual balance
- **Whitespace:** Adequate padding and margins prevent cluttered appearance
- **Responsive Columns:** Content adapts from single column (mobile) to multi-column (desktop)
- **Visual Hierarchy:** Size, color, and positioning guide user attention
- **Consistency:** Repeated patterns create familiar, predictable interface

### Design Decisions Rationale

**Why This Color Scheme?**
- The cool blue tones (professional, trustworthy) paired with warm accent (energy, attention) creates balance
- Accessible color combinations that work for color-blind users
- Appeals to technology sector professionals who value clean, modern design

**Why This Typography?**
- Sans-serif fonts are web-standard for body text (superior readability on screens)
- Clear visual hierarchy through size variation guides users through content
- Generous sizing ensures accessibility for users with vision challenges

**Why This Layout?**
- Responsive design ensures functionality across all devices (requirement compliance)
- CSS layers provide modern, valid HTML structure
- Grid-based approach creates professional, organized appearance

---

## 6. CONTENT DETAILS

### Page 1: HOME (index.html)

**Primary Content Elements:**
- **Collage:** A grid display of 4 representative images from throughout the project
  - Demonstrates visual design capability
  - Provides preview of multimedia content
  - Arranged in responsive 2x2 grid (adjusts on smaller screens)

- **Group Member Information:** Structured profile cards for 2-5 group members containing:
  - Full names
  - Student ID numbers
  - Dates of birth
  - Contact phone numbers
  - Email addresses
  - Languages spoken

**Purpose:** Introduces the team, establishes professional presence, displays multimedia competency

### Page 2: EXPERIENCE (experience.html)

**Primary Content Elements:**
- **Professional Photos:** Images of group members in front of computers
- **Role Information:** Each member's ideal multimedia development role
- **Role Justification:** Brief explanation of career interests and strengths
- **Role-Related Images:** Visual representation of chosen roles
- **Community Activities:** List of involvement in campus/community activities

**Purpose:** Demonstrates work experience, career aspirations, and professional development

### Page 3: EDUCATION (education.html)

**Primary Content Elements:**
- **Audio Introduction:** 30-second sound file introducing the group and explaining motivation for Bachelor of Informatics
- **Educational Background Photos:** Different image from Page 2 (different group photo)
- **Education History:** For each member:
  - Primary school information
  - Secondary school information
  - Current programme details
  - Expected graduation date
  - Motivation/reasoning for programme choice

**Purpose:** Provides educational context, establishes credibility, personal connection through audio

### Page 4: COURSES (courses.html)

**Primary Content Elements:**
- **Course List:** Table displaying all third-year courses with:
  - Course code
  - Course name
  - Lecturer name
  
- **Flash Animation:** Animated display of all project images (excluding banner):
  - All images resized to smallest image dimensions
  - Smooth transitions/animations
  - Professional presentation

**Purpose:** Demonstrates course knowledge, provides technical skill evidence (animation creation)

### Page 5: REFERENCES (references.html)

**Primary Content Elements:**
- **Career References:** URLs and sources used for career research
- **Image/Media Attribution:** Credits for all images and multimedia assets used
- **Software References:** Official homepages of software used (Dreamweaver, Adobe products, audio/animation tools)
- **Design Reference:** Links to web design resources and tutorials
- **All references in APA format with working hyperlinks**

**Purpose:** Academic integrity (proper attribution), demonstrates research capability

---

## 7. SPECIFIC MULTIMEDIA CONTENT

### Image Assets

**Format:** JPEG or PNG (web-optimized)
**Resolution:** Minimum 800x600 pixels; maximum 1920x1080 pixels
**File Size:** Under 500KB per image (for optimal loading)
**Metadata:** Each image includes student ID watermark (Arial, size 8)

**Required Images:**
1. **Collage Images (4):** Diverse portfolio samples
2. **Experience Photos (2+):** Group members at computer
3. **Experience Role Images (2+):** Role-related visuals
4. **Education Photo:** Different group photo
5. **Additional:** Supporting images for content enhancement

**Total Estimated:** 8-12 images, approximately 3-5 MB combined

### Audio Content

**Format:** MP3 (lossy compression for web)
**Duration:** 30 seconds (±2 seconds acceptable)
**Bitrate:** 128 kbps or higher (quality/file-size balance)
**Sample Rate:** 44.1 kHz standard
**File Size:** Approximately 300-500 KB
**Content:** Introduction to group and Bachelor of Informatics programme

**Technical Requirements:**
- Clear audio (no background noise)
- Professional narration/speech
- Properly encoded for web playback

### Flash Animation

**Format:** SWF (Shockwave Flash)
**Duration:** 20-60 seconds (continuous loop recommended)
**Resolution:** 800x600 pixels or 1024x768 pixels
**File Size:** Under 2 MB (web-optimized)

**Content Specifications:**
- Animated sequence of all project images
- Images resized to match smallest image dimensions
- Smooth transitions (fade, slide, or zoom effects)
- Professional timing and pacing
- Does NOT include sound file
- Does NOT include banner images

**Estimated File Sizes Summary:**
- Images: 3-5 MB (total)
- Audio: 0.3-0.5 MB
- Flash Animation: 0.5-2 MB
- **Total Multimedia:** 4-8 MB

---

## 8. TESTING PLAN

### Testing Approach

**Technical vs. Design Testing**

**Technical Testing** focuses on functionality and compatibility:
- Are all links working and directing to correct pages?
- Do all multimedia files load properly?
- Does navigation function across all pages?
- Is the website compatible with different browsers?
- Are there any console errors or broken references?
- Does the responsive design work on mobile devices?

**Design Testing** focuses on user experience and visual consistency:
- Is the visual design consistent across all pages?
- Is the navigation intuitive and easy to use?
- Is the color scheme appealing and professional?
- Is the typography readable and well-hierarchized?
- Is the layout balanced and organized?
- Is the design accessible to users with disabilities?

*Nielsen, J. (2012). "Usability Testing Essentials." Nielsen Norman Group. Accessed from: https://www.nngroup.com/reports/usability-testing-essentials/*

### Why Testing is Necessary

**Quality Assurance:** Testing ensures the website functions as intended and meets all assignment requirements

**User Experience:** Identifies issues that could frustrate users or make content inaccessible

**Professional Standards:** Industry practice requires testing before deployment or submission

**Compliance Verification:** Confirms adherence to assignment brief specifications

**Error Detection:** Catches technical issues (broken links, missing files) before submission

### Testing Methodology

**Phase 1: Technical Testing**
1. **Link Verification:** Click all navigation links to verify they go to correct pages
2. **File Path Testing:** Ensure all CSS, images, audio, and Flash files load correctly
3. **Browser Compatibility:** Test in Chrome, Firefox, Safari, and Edge
4. **Responsive Testing:** Use browser developer tools to test mobile (320px), tablet (768px), desktop (1024px+)
5. **Error Checking:** Open browser console (F12) to check for JavaScript/resource errors

**Phase 2: Design Testing**
1. **Visual Consistency:** Verify colors, fonts, spacing are consistent across pages
2. **Readability Testing:** Check text contrast and font sizes for legibility
3. **Navigation UX:** Verify active states are clear, navigation is intuitive
4. **Image Quality:** Ensure all images display crisply without distortion
5. **Audio Playback:** Test audio player across different browsers
6. **Animation Performance:** Verify Flash animation plays smoothly without stuttering

**Phase 3: Accessibility Testing**
1. **Keyboard Navigation:** Ensure all elements accessible via keyboard
2. **Color Contrast:** Verify sufficient contrast for color-blind users
3. **Text Alternatives:** Ensure images have proper alt text
4. **Responsive Scaling:** Test zoom functionality at 150%, 200%

**Testing Environment:**
- Local file system (before zipping)
- After extraction from zip file (final verification)
- Multiple browsers and devices

---

## 9. REFERENCES

### Academic & Design Resources

Nielsen, J. (2012). *10 usability heuristics for user interface design.* Retrieved from Nielsen Norman Group: https://www.nngroup.com/articles/ten-usability-heuristics/

Nielsen, J. (2012). *Usability testing essentials: Ready to recruit and reward test participants.* Nielsen Norman Group.

W3C (World Wide Web Consortium). (2023). *Web Content Accessibility Guidelines (WCAG) 2.1.* Retrieved from https://www.w3.org/WAI/WCAG21/quickref/

Garrett, J. J. (2010). *The elements of user experience: User-centered design for the web and beyond.* New Riders Press.

### Web Technologies & Standards

Mozilla Developer Network (2024). *HTML: HyperText Markup Language.* Retrieved from https://developer.mozilla.org/en-US/docs/Web/HTML

Mozilla Developer Network (2024). *CSS: Cascading Style Sheets.* Retrieved from https://developer.mozilla.org/en-US/docs/Web/CSS

W3C (2023). *HTML Living Standard.* Retrieved from https://html.spec.whatwg.org/

### Design & Color Theory

Adobe. (2023). *Understanding color on the web.* Retrieved from https://www.adobe.com/products/color/fundamentals

Smashing Magazine (2023). *Web design principles.* Retrieved from https://www.smashingmagazine.com/

### Tools & Software

Adobe Dreamweaver. (2024). *Official homepage.* Retrieved from https://www.adobe.com/products/dreamweaver

Adobe Flash Professional. (2024). *Official homepage.* Retrieved from https://www.adobe.com/products/flash

Audacity (2024). *Free audio editor and recorder.* Retrieved from https://www.audacityteam.org/

Visual Studio Code. (2024). *Code editor.* Retrieved from https://code.visualstudio.com/

---

## SUBMISSION NOTES

**Document Status:** ✅ Ready for Submission

**To Convert to PDF/Word:**
1. Open this file in your markdown editor
2. Export/Save as PDF (recommended) or
3. Copy content to Word document and format

**Before Submission:**
- Fill in all [To be filled in] placeholders with actual project details
- Ensure all references include working URLs
- Verify all sections are complete and coherent
- Review for spelling and grammar errors
- Have teammates review for accuracy

**Assignment Compliance:**
✅ Covers all required sections of Part A  
✅ Includes flowchart/site layout  
✅ Explains navigation scheme with references  
✅ Details visual design choices with rationale  
✅ Specifies multimedia content types and sizes  
✅ Includes testing plan with references  
✅ References in APA format  

---

*Document prepared: May 7, 2026*  
*MMA Web Project - Part A Design Specifications*  
*Bachelor of Informatics Programme*
