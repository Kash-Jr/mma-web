# MMA Web Project - Template Structure

## Project Overview
This is a starter template for the Multimedia Web Project (Part B) following the detailed assignment specifications.

## File Structure
```
MMA Web/
├── index.html              # Page 1 - Home/Cover with Collage
├── experience.html         # Page 2 - Experience & Roles
├── education.html          # Page 3 - Education & Audio Introduction
├── courses.html            # Page 4 - Courses & Flash Animation
├── references.html         # Page 5 - References & Links (APA Format)
├── MyLook-1.css           # Main stylesheet (required by assignment)
├── README.md              # This file
├── images/                # Image assets directory
├── audio/                 # Audio files directory
└── flash/                 # Flash animation directory
```

## Key Implementation Notes

### 1. **Stylesheet (MyLook-1.css)**
   - All styling is contained in `MyLook-1.css` as required
   - Uses layers (relative/absolute positioning) for content placement
   - Non-white background color implemented (#e8f0f7 - soft blue-grey)
   - Responsive design included for various screen sizes
   - Color scheme: Dark blue (#1a5f7a) with accents (#2a7a9e, #ff6b6b)

### 2. **Navigation**
   - Consistent navigation across all 5 pages
   - Active page is highlighted with different styling
   - Navigation links are in the header of each page
   - Currently active page link has no href (as per spec) but styled to indicate current page

### 3. **Content Layers**
   - `.content-layer` class provides main content container
   - `.layer-header`, `.layer-body`, `.layer-footer` provide z-index positioning
   - Uses CSS `position: relative` and `z-index` for layer management

### 4. **Page 1 - Home (index.html)**
   - Collage grid layout implemented with CSS Grid
   - Profile information sections for both group members
   - Personal details: Name, Student ID, DOB, Contact, Email, Languages
   - Course/Programme information section
   - Footer with names, copyright symbol, and year

### 5. **Page 2 - Experience (experience.html)**
   - Separate sections for each group member
   - Photo with computer (to be uploaded to images/experience-photo-1.jpg)
   - Role information with preference and explanation
   - Role-related image (to be uploaded to images/role-image-1.jpg)
   - Activities & community involvement list
   - Note: Same photo can be used for both members or different ones

### 6. **Page 3 - Education (education.html)**
   - 30-second audio introduction file: audio/introduction.mp3
   - HTML5 audio element with controls
   - Different photo from Page 2 (images/education-photo.jpg)
   - Educational background for each member
   - Sections: Primary, Secondary, Current Programme
   - Explanation of why pursuing Bachelor of Informatics

### 7. **Page 4 - Courses (courses.html)**
   - Table listing all third-year courses
   - Columns: Course Code, Course Name, Lecturer Name
   - Flash animation container (currently placeholder)
   - To add Flash: Uncomment the `<object>` tag and point to your .swf file
   - Animation should include all images except banners, resized to smallest image dimensions

### 8. **Page 5 - References (references.html)**
   - Organized by category:
     1. Career & Professional Development
     2. Image & Media Resources
     3. Software & Development Tools
     4. Web Development & Design Resources
   - All links are clickable and open in new tabs
   - APA format template provided
   - Professional attribution and licensing information

## To Fill In

### Group Member Information
Replace all `[To be filled in]` placeholders with actual information:
- Names (both group members)
- Student IDs
- Dates of birth
- Contact information
- Languages spoken
- Programme/Course details

### Multimedia Assets
Create and place the following in their respective directories:

**Images** (`images/` directory):
- `placeholder-1.jpg` through `placeholder-4.jpg` - For collage (Page 1)
- `experience-photo-1.jpg` and `experience-photo-2.jpg` - With computer (Page 2)
- `role-image-1.jpg` and `role-image-2.jpg` - Role-related images (Page 2)
- `education-photo.jpg` - Different photo from Page 2 (Page 3)

**Important**: All images must have student ID embedded (Arial, font size 8) as per assignment requirements.

**Audio** (`audio/` directory):
- `introduction.mp3` - 30-second introduction for Page 3

**Flash** (`flash/` directory):
- `portfolio-animation.swf` - Animation of all images (Page 4)

## Color Scheme
- Primary Background: #e8f0f7 (soft blue-grey)
- Primary Color: #1a5f7a (dark blue)
- Accent Color: #2a7a9e (medium blue)
- Highlight Color: #ff6b6b (coral red for active/current page)
- Text Color: #333 (dark grey)

## Font Family
- Primary: Arial, Helvetica, sans-serif
- Font sizes are scaled proportionally throughout

## Testing & Optimization
- All 5 HTML pages created and functional
- CSS is external (MyLook-1.css) as required
- Navigation works across all pages
- Responsive design tested for mobile and tablet views
- No frames used (as per spec) - uses semantic HTML and CSS layouts

## Important Reminders
✓ All images must have Student ID embedded (Arial, font size 8)
✓ Only ONE animation (Flash on Page 4)
✓ No University logo anywhere
✓ Non-white background implemented
✓ Footer with copyright symbol and year on all pages
✓ No frames - using CSS layers instead
✓ CSS file named exactly: MyLook-1.css

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile-friendly responsive design
- HTML5 compliant
- CSS3 support required for Grid and Flexbox layouts

## Next Steps

1. **Fill in all placeholder information** with actual group member details
2. **Add multimedia assets**:
   - Create/capture images with embedded student IDs
   - Record 30-second audio introduction
   - Create Flash animation of all images
3. **Complete references section** with actual URLs and attributions
4. **Customize colors and fonts** if needed in MyLook-1.css
5. **Create Part A design specification document** based on this template structure
6. **Test all navigation links** across browsers
7. **Verify all images load correctly** with proper dimensions
8. **Test audio playback** on different devices
9. **Create brief report** (max 30 words) with:
   - Optimal viewing platform and resolution
   - Home page filename (index.html)
   - Any difficulties or changes to original specs

## Questions or Issues?
Refer back to the assignment brief for specific requirements. The template provides all structural requirements; content customization is the remaining task.

---
**Created:** May 7, 2026  
**Template Version:** 1.0  
**Status:** Ready for content fill-in
