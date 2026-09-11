# Benjamin Taylor - Personal Portfolio & Resume Website

**Course**: ISDS 4125: Analysis and Design of Information Systems  
**Instructor**: Dr. Gabriele Piccoli | LSU E.J. Ourso College of Business  
**Live Website**: 
**GitHub Repository**: [https://github.com/taylor-benjamin/resume_website](https://github.com/taylor-benjamin/resume_website)

---

## Project Overview

This project is a personal professional website, built with Google Antigravity IDE, HTML5, and vanilla CSS, with a precision, PlayStation/Sony-inspired look.

It's split into four files:
- **`index.html`** – Homepage with a quick overview of my profile (IS & Analytics degree, Cyber Risk concentration, LSU), skills, work experience, and contact info.
- **`resume.html`** – Full resume with career history and skills, formatted to print cleanly as a PDF.
- **`project.html`** – A case study on healthcare data breaches, analyzing attack patterns from HHS breach data using the NIST SP 800-30 risk framework.
- **`styles.css`** – Shared styles: sharp edges, flexible layouts, and reusable design variables.

---

## Learning Reflection

While building this project, I ran into two issues: my Git commit kept hanging, and the header's nav text was overflowing its box, with a design that looked too round and bubbly.

Debugging these taught me two things:

1. **Git commits**: if you skip `-m`, Git opens an interactive editor waiting for a commit message — and you also need to `git add` your changes before you can commit them.
2. **CSS layout**: fixed heights (like `height: 72px`) can cause content to overflow when the viewport changes. Also, swapping large border-radius values for smaller ones (2–4px) makes a design look sharp and professional instead of round and "AI-generated."
