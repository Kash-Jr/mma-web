# MMA Web Project - Part A Design Specifications Template

**Note:** Complete this document AFTER reviewing the template structure created in Part B. 
This ensures your specifications accurately reflect what you intend to build.

---

## 1. INTRODUCTION/GOAL

**What is this project?**
[Describe the purpose of your MMA Web portfolio project. It's an educational multimedia project showcasing...]

**Why are you making it?**
[Beyond it being an assignment, explain the value of creating a professional portfolio website as multimedia developers.]

**Target Audience:**
[Who will view this website? (e.g., potential employers, academic advisors, peers in the informatics programme)]

---

## 2. TARGET AUDIENCE

[Be specific about who this website is for. Consider:]
- Academic advisors and lecturers
- Potential employers in the multimedia/IT sector
- Other informatics students
- General public/portfolio viewers

[What are their expectations and technical capabilities?]

---

## 3. SITE LAYOUT (FLOWCHART)

[Create a visual representation showing:]
- How all 5 pages connect to each other
- Navigation flow
- Hierarchy of information
- Use simple text-based diagram or ASCII art if drawing tools unavailable

```
Example structure:
HOME (index.html)
├── EXPERIENCE (experience.html)
├── EDUCATION (education.html)
├── COURSES (courses.html)
└── REFERENCES (references.html)
```

---

## 4. NAVIGATION SCHEME

**How will users move between pages?**
[Describe your navigation structure. In our template:
- Horizontal navigation bar at top of each page
- Links to all other pages visible
- Current page highlighted/inactive
- Consistent placement across all pages]

**Why is a "consistent" navigation scheme very important?**

[Research and answer in your own words:]
- [Point 1 - To be filled in]
- [Point 2 - To be filled in]
- [Point 3 - To be filled in]

**Reference:** [At least one non-Wikipedia source required]
[Example: Nielsen, J. (2012). Usability 101: Introduction to Usability. Nielsen Norman Group.]

---

## 5. VISUAL ELEMENTS/STYLE - "LOOK" OF PAGES

**Color Scheme:**
- **Primary Background:** #e8f0f7 (Soft Blue-Grey)
  - *Why:* Professional yet inviting, reduces eye strain, commonly used in corporate web design
  
- **Primary Color:** #1a5f7a (Dark Blue)
  - *Why:* Conveys trust, professionalism, and technical competence
  
- **Accent Color:** #2a7a9e (Medium Blue)
  - *Why:* Creates hierarchy, guides user attention to important elements
  
- **Highlight Color:** #ff6b6b (Coral Red)
  - *Why:* Creates visual contrast for active states, draws attention to current page

**Typography:**
- **Font Family:** Arial, Helvetica, sans-serif
  - *Why:* Highly legible on web, professional appearance, universal compatibility
  
- **Font Sizes:**
  - Page Title: 2.5rem (large, prominent)
  - Page Heading: 1.8rem (section hierarchy)
  - Body Text: 1rem (comfortable reading)
  - *Why:* Clear visual hierarchy aids navigation and readability

**Layout Approach:**
- Grid-based design using CSS (no frames)
- Layers/positioning for content placement
- Responsive design for mobile/tablet compatibility
- White space for visual breathing room

---

## 6. CONTENT DETAILS FOR EACH PAGE

### **Page 1: HOME/COVER (index.html)**
**Content Overview:**
- Large impressive collage of key images from the project
- Embedded student names and programme details
- Personal profile information for both group members
- Professional header and footer

**Structure:**
- Title: "Welcome"
- Collage section (4-6 images)
- Two profile info blocks (one per student)
- Each profile includes: Name, Student ID, DOB, Contact, Email, Languages
- Programme/Course information
- Footer with copyright

### **Page 2: EXPERIENCE (experience.html)**
**Content Overview:**
- Practical experience as multimedia developers
- Roles performed in this specific project
- Professional photograph with computer
- Career aspirations and role preferences
- Community involvement

**Structure:**
- For each group member:
  - Ideal role in multimedia project
  - Short explanation of why this role appeals to them
  - Role-related image
  - List of activities and community involvement
  - Professional photo with both members at computer

### **Page 3: EDUCATION (education.html)**
**Content Overview:**
- Educational background and journey
- 30-second audio introduction by both members
- Different photograph from Page 2
- Motivation for pursuing Bachelor of Informatics

**Structure:**
- Audio player with introduction file
- Different group photo
- For each member:
  - Primary education details
  - Secondary education details
  - Current programme information
  - Personal motivation for programme choice

### **Page 4: COURSES (courses.html)**
**Content Overview:**
- All third-year Bachelor of Informatics courses
- Lecturer names for each course
- Flash animation of all project images

**Structure:**
- Table format with 3 columns: Code, Course Name, Lecturer
- At least 8 third-year courses listed
- Flash animation container
- Animation includes all images (except banners) resized proportionally

### **Page 5: REFERENCES (references.html)**
**Content Overview:**
- All sources used throughout project
- Career research links
- Image attribution
- Software homepage links
- All in APA format with working hyperlinks

**Structure:**
- Organized by category:
  1. Career & Professional Development
  2. Image & Media Resources
  3. Software & Development Tools
  4. Web Development & Design Resources
- Each reference includes full citation + working link

---

## 7. SPECIFIC MULTIMEDIA CONTENT

### **Images:**
- **Format:** JPG or PNG
- **Number:** Minimum 8 images (for collage + pages)
- **Size per image:** ~300-600KB each (web-optimized)
- **Total image size:** Approximately 3-5 MB combined
- **Special requirement:** Each image must have student ID embedded (Arial, size 8)
- **Images with computer photo:** 2 high-quality professional photographs
- **Collage images:** 4-6 diverse portfolio samples

### **Audio:**
- **Format:** MP3
- **Duration:** 30 seconds
- **Content:** Joint introduction by both students explaining educational choices
- **File size:** ~500KB
- **Recording quality:** Clear audio, minimal background noise
- **Bit rate:** 128-192 kbps

### **Flash Animation:**
- **Format:** SWF (Adobe Flash)
- **Content:** All images from project (excluding banners)
- **Duration:** 8-15 seconds (loop)
- **Dimensions:** Proportional, resized to match smallest image dimensions
- **Animation type:** Slideshow/carousel format with transitions
- **File size:** ~2-3 MB

### **Total Multimedia Size Estimate:**
- Images: 3-5 MB
- Audio: 0.5 MB
- Flash: 2-3 MB
- **Total Project:** ~6-8.5 MB

---

## 8. TESTING

### **What is the difference between Technical Testing and Design Testing?**

**Technical Testing:** [To be filled in]
- Verifying functionality and code integrity
- [Add 2-3 more points]

**Design Testing:** [To be filled in]
- Evaluating user experience and visual appeal
- [Add 2-3 more points]

### **How will you test that your site works properly?**

**Technical Testing Approach:**
1. [Method 1 - To be filled in]
2. [Method 2 - To be filled in]
3. Cross-browser testing (Chrome, Firefox, Safari, Edge)
4. Mobile/responsive device testing
5. Link validation (all navigation links functional)
6. Media file loading (images, audio, animation)

**Design Testing Approach:**
1. [Method 1 - To be filled in]
2. [Method 2 - To be filled in]
3. User feedback from test group
4. Visual hierarchy assessment
5. Color contrast and readability check
6. Navigation intuitiveness

**Reference:** [Non-Wikipedia source required]
[Example: WCAG 2.1 Guidelines - https://www.w3.org/WAI/WCAG21/quickref/]

### **Why is there a need for testing?**

[Answer in your own words - To be filled in. Consider:]
- Ensuring quality and functionality
- Identifying and fixing bugs before submission
- Verifying assignment requirements are met
- Ensuring accessibility for all users
- Validating user experience goals

---

## 9. REFERENCES

[Format all references in APA style. Examples:]

Example 1 (Website):
Nielsen, J. (2012). Usability 101: Introduction to usability. Retrieved from https://www.nngroup.com/articles/usability-101-introduction-to-usability/

Example 2 (Color Theory):
Halcomb, E. (2020). Web design color theory. Retrieved from [URL]

Example 3 (Web Standards):
W3C. (2021). Web Content Accessibility Guidelines (WCAG). Retrieved from https://www.w3.org/WAI/WCAG21/quickref/

[Add your actual references here - To be filled in]

---

## NOTES FOR COMPLETION

- [ ] Research and answer all "Why?" questions with own words
- [ ] Include at least one non-Wikipedia reference for navigation importance
- [ ] Include at least one non-Wikipedia reference for testing
- [ ] Format all references in APA style
- [ ] Proofread for spelling and grammar
- [ ] Ensure strict adherence to assignment brief
- [ ] Total document should show attention to detail and understanding of project

---

**Document Created:** May 7, 2026  
**To Be Completed By:** [Date - To be filled in]  
**Student Names:** [To be filled in]
