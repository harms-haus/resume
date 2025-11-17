<!-- 200cf3f5-5700-4537-9fe4-e6f6c881daaa d399e5fc-49c2-45d7-84e8-5b1366651112 -->
# Create Modern Resume HTML (resume2.html)

## Overview

Build a single-file HTML resume with modern design, smooth animations, navy-gold gradient highlights, and system-aware dark/light mode toggle.

## Design Specifications

### Color Scheme

- **Dark Mode:**
- Background: Dark navy (#0a1929 or similar)
- Foreground: White (#ffffff)
- Highlights: Navy-gold gradient (navy #001f3f → gold #ffd700)

- **Light Mode:**
- Background: Lightly yellowed bright gray (#f5f5f0 or similar)
- Foreground: Dark navy (#001f3f)
- Highlights: Navy-gold gradient (same as dark mode)

### Typography

- Sans-serif font (e.g., Inter, Poppins, or system stack)
- Modern, clean hierarchy

### Features

- System theme detection (defaults to prefers-color-scheme)
- Smooth theme toggle button
- Fade-in and scroll animations
- Navy-gold gradient accent lines on panels (alternating left/right sides)
- Sharp corners (no border-radius) on all panels
- Sharp shadows (no blur) on panels
- Fully responsive design
- All content from resume.md included

## Implementation Steps

1. **HTML Structure**

- Single-file HTML5 document
- Semantic sections: header, main, sections for each resume part
- Include all content from resume.md (summary, experience, skills, education, additional info)

2. **CSS Styling**

- CSS variables for theme colors
- Dark mode: dark navy bg, white text
- Light mode: yellowed gray bg, dark navy text
- Navy-gold gradients for highlights, section dividers, hover states
- Smooth transitions (0.3s ease)
- Modern card-based layout for experience items
- Grid layout for skills section
- Responsive breakpoints

3. **Animations**

- Fade-in on scroll for sections
- Smooth hover transitions
- Gradient animations on interactive elements
- Smooth theme transition

4. **JavaScript**

- Theme detection: check system preference first, then localStorage
- Theme toggle button functionality
- Listen for system theme changes
- Scroll animations using Intersection Observer or scroll events

5. **Content Integration**

- Parse and structure all content from resume.md:
- Header with name, location, contact info
- Professional Summary
- Professional Experience (Emerson, Wood)
- Skills (all categories)
- Education
- Additional Information

## File to Create

- `/home/blake/Documents/resume/resume2.html` - Complete single-file resume with embedded CSS and JavaScript