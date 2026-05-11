# MMA Web Project - Visual Structure & Navigation Map

```
╔════════════════════════════════════════════════════════════════╗
║           MMA WEB PROJECT - COMPLETE STRUCTURE                ║
║                    Created: May 7, 2026                       ║
╚════════════════════════════════════════════════════════════════╝
```

## 📊 WEBSITE NAVIGATION DIAGRAM

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
    ┌────▼────────────────┐   ┌────▼────────────────┐   ┌────▼────────────────┐
    │  COURSES.html       │   │  REFERENCES.html    │   │  (back to top)      │
    │  Page 4: Courses    │   │  Page 5: Links      │   │                     │
    │  + Flash Animation  │   │  + APA References   │   │  All pages linked   │
    └─────────────────────┘   └─────────────────────┘   └─────────────────────┘

┌─ All pages include:
│  ✓ Consistent navigation bar
│  ✓ Professional footer with © and year
│  ✓ Non-white background color
│  ✓ CSS-based layers (no frames)
└─
```

---

## 📁 COMPLETE FILE STRUCTURE

```
MMA Web/
│
├─ 📌 DOCUMENTATION (Read First!)
│  ├─ START_HERE.md ......................... Quick start guide
│  ├─ COMPLETE_IMPLEMENTATION_GUIDE.md ...... Full roadmap
│  ├─ README.md ............................. Project overview
│  ├─ IMPLEMENTATION_CHECKLIST.md ........... Progress tracker
│  └─ BRIEF_REPORT.txt ..................... Report template
│
├─ 📋 PART A SUPPORT
│  └─ PART_A_DESIGN_TEMPLATE.md ........... Design specs template
│
├─ 🌐 HTML PAGES (The Website)
│  ├─ index.html ........................... Page 1 - HOME
│  ├─ experience.html ...................... Page 2 - EXPERIENCE  
│  ├─ education.html ....................... Page 3 - EDUCATION
│  ├─ courses.html ......................... Page 4 - COURSES
│  └─ references.html ...................... Page 5 - REFERENCES
│
├─ 🎨 STYLING
│  └─ MyLook-1.css ......................... Main stylesheet
│     (REQUIRED FILENAME - do not change)
│
└─ 📦 ASSET FOLDERS (Create your content here)
   ├─ images/
   │  ├─ placeholder-1.jpg ................. Collage images
   │  ├─ placeholder-2.jpg
   │  ├─ experience-photo-1.jpg ............ Computer photos
   │  ├─ experience-photo-2.jpg
   │  ├─ education-photo.jpg .............. Different photo
   │  ├─ role-image-1.jpg ................. Role-related images
   │  └─ role-image-2.jpg
   │
   ├─ audio/
   │  └─ introduction.mp3 ................. 30-second intro
   │
   └─ flash/
      └─ portfolio-animation.swf ......... Image animation
```

---

## 🎯 PAGE SPECIFICATIONS AT A GLANCE

### PAGE 1: index.html (HOME - Collage & Profile)
```
┌──────────────────────────────────────────┐
│            WELCOME (Title)               │ ← Page Title
├──────────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ...      │ ← Navigation
├──────────────────────────────────────────┤
│                                          │
│        ◻ ◻ ◻ ◻  IMAGE COLLAGE            │ ← 4-6 images with
│        ◻ ◻ ◻ ◻  (with Student IDs)       │   Student IDs embedded
│                                          │
│  GROUP MEMBER 1                          │
│  • Name: [filled in]                     │
│  • ID: [filled in]                       │
│  • DOB: [filled in]                      │
│  • Contact, Email, Languages             │
│                                          │
│  GROUP MEMBER 2                          │
│  • Name: [filled in]                     │
│  • ID: [filled in]                       │
│  • DOB: [filled in]                      │
│  • Contact, Email, Languages             │
│                                          │
├──────────────────────────────────────────┤
│ © 2026 Names | Bachelor of Informatics   │ ← Footer
└──────────────────────────────────────────┘
```

### PAGE 2: experience.html (EXPERIENCE - Roles & Activities)
```
┌──────────────────────────────────────────┐
│         EXPERIENCE (Title)               │ ← Page Title
├──────────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ...      │ ← Navigation
├──────────────────────────────────────────┤
│                                          │
│  FOR EACH GROUP MEMBER:                  │
│  • Photo (both at computer)              │
│  • Ideal Role in Multimedia              │
│  • Why this role (explanation)           │
│  • Role-related image                    │
│  • Activities & Community involvement    │
│                                          │
├──────────────────────────────────────────┤
│ © 2026 Names | Bachelor of Informatics   │ ← Footer
└──────────────────────────────────────────┘
```

### PAGE 3: education.html (EDUCATION - Audio Introduction)
```
┌──────────────────────────────────────────┐
│        EDUCATION (Title)                 │ ← Page Title
├──────────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ...      │ ← Navigation
├──────────────────────────────────────────┤
│                                          │
│  30-SECOND AUDIO INTRODUCTION            │
│  [Audio Player]  ▶  ⏸ 00:15             │ ← Audio controls
│                                          │
│  [Different photo of both group members] │ ← Page 3 photo
│                                          │
│  FOR EACH GROUP MEMBER:                  │
│  • Primary education                     │
│  • Secondary education                   │
│  • Current programme details             │
│  • Why Bachelor of Informatics?          │
│                                          │
├──────────────────────────────────────────┤
│ © 2026 Names | Bachelor of Informatics   │ ← Footer
└──────────────────────────────────────────┘
```

### PAGE 4: courses.html (COURSES - Table & Animation)
```
┌──────────────────────────────────────────┐
│           COURSES (Title)                │ ← Page Title
├──────────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ...      │ ← Navigation
├──────────────────────────────────────────┤
│                                          │
│  CODE  │ COURSE NAME      │ LECTURER     │ ← Course Table
│  ────────────────────────────────────    │   (8+ courses)
│  [Code] │ [Name]          │ [Lecturer]   │
│  ...                                     │
│                                          │
│  FLASH ANIMATION OF ALL IMAGES           │
│  [Animation Container]                   │ ← Animated images
│  [Plays in loop]                         │
│                                          │
├──────────────────────────────────────────┤
│ © 2026 Names | Bachelor of Informatics   │ ← Footer
└──────────────────────────────────────────┘
```

### PAGE 5: references.html (REFERENCES - APA Links)
```
┌──────────────────────────────────────────┐
│         REFERENCES (Title)               │ ← Page Title
├──────────────────────────────────────────┤
│ HOME | EXPERIENCE | EDUCATION | ...      │ ← Navigation
├──────────────────────────────────────────┤
│                                          │
│  CAREER & PROFESSIONAL DEVELOPMENT       │ ← Categories
│  • Link to resource [clickable]          │
│  • Link to resource [clickable]          │
│                                          │
│  IMAGE & MEDIA RESOURCES                 │
│  • Image source [clickable link]         │
│  • Image source [clickable link]         │
│                                          │
│  SOFTWARE & DEVELOPMENT TOOLS            │
│  • VS Code: https://code.visualstudio... │
│  • [Tool 2]: [URL]                       │
│                                          │
│  WEB DEVELOPMENT & DESIGN RESOURCES      │
│  • [Resource]: [Link]                    │
│  • [Resource]: [Link]                    │
│                                          │
│  All in APA format with working links    │
│                                          │
├──────────────────────────────────────────┤
│ © 2026 Names | Bachelor of Informatics   │ ← Footer
└──────────────────────────────────────────┘
```

---

## 🎨 COLOR SCHEME

```
┌─────────────────────────────────────────┐
│  Primary Background  │  #e8f0f7         │ ← Soft Blue-Grey
│  Primary Color       │  #1a5f7a         │ ← Dark Blue (nav)
│  Accent Color        │  #2a7a9e         │ ← Medium Blue
│  Highlight/Active    │  #ff6b6b         │ ← Coral Red
│  Text Color          │  #333            │ ← Dark Grey
│  Links               │  #0066cc         │ ← Web Blue
└─────────────────────────────────────────┘
```

---

## 📊 CONTENT REQUIREMENTS MATRIX

| Element | Page 1 | Page 2 | Page 3 | Page 4 | Page 5 |
|---------|--------|--------|--------|--------|--------|
| Navigation | ✓ | ✓ | ✓ | ✓ | ✓ |
| Footer | ✓ | ✓ | ✓ | ✓ | ✓ |
| Images | Collage | Photos + Role | Photo | Animation | Links |
| Audio | - | - | ✓ | - | - |
| Animation | - | - | - | ✓ | - |
| Table | - | - | - | ✓ | - |
| Links | - | - | - | - | ✓ |

---

## 📋 SUBMISSION STRUCTURE

```
Your-Student-ID.zip
│
├─ 📄 index.html
├─ 📄 experience.html
├─ 📄 education.html
├─ 📄 courses.html
├─ 📄 references.html
├─ 📄 MyLook-1.css
│
├─ 📁 images/
│  ├─ placeholder-1.jpg
│  ├─ placeholder-2.jpg
│  ├─ [all image files with embedded IDs]
│
├─ 📁 audio/
│  └─ introduction.mp3
│
├─ 📁 flash/
│  └─ portfolio-animation.swf
│
├─ 📄 BRIEF_REPORT.txt
│
├─ 📄 Design_Specifications_Document.docx
│
└─ 📁 Storyboards/
   ├─ Page1_Storyboard.jpg
   ├─ Page2_Storyboard.jpg
   └─ [other storyboards]
```

---

## ✅ CRITICAL CHECKLIST

```
BEFORE SUBMISSION:

☐ Exactly 5 HTML pages (5, not 4 or 6)
☐ MyLook-1.css stylesheet exists and linked
☐ Non-white background color (#e8f0f7 or custom)
☐ CSS layers used, NO frames
☐ ONE Flash animation only (on Page 4)
☐ All images have student ID embedded
☐ NO University logo anywhere
☐ Consistent navigation on all pages
☐ Footer with © and year on all pages
☐ All links working (tested)
☐ Audio plays correctly
☐ All images load without errors
☐ No spelling or grammar errors
☐ Part A design specs completed
☐ Brief report completed (<30 words)
☐ All [To be filled in] placeholders removed
☐ Responsive design tested on mobile
☐ Cross-browser tested (Chrome, Firefox, Safari)
☐ Home page is index.html
☐ Zipped with Student ID as filename
```

---

## 🚀 NEXT STEPS

1. **Review** this structure
2. **Read** COMPLETE_IMPLEMENTATION_GUIDE.md
3. **Gather** information from group member
4. **Create** multimedia assets
5. **Fill** all content into HTML files
6. **Test** everything thoroughly
7. **Create** Part A design document
8. **Submit** before deadline

---

**Template Version:** 1.0  
**Created:** May 7, 2026  
**Status:** Ready for implementation ✅
