# Benjamin Taylor - Personal Portfolio & Resume Website

**Course**: ISDS 4125: Analysis and Design of Information Systems  
**Instructor**: Dr. Gabriele Piccoli | LSU E.J. Ourso College of Business  
**Live Website**: [https://taylor-benjamin.github.io/resume_website/](https://taylor-benjamin.github.io/resume_website/)  
**GitHub Repository**: [https://github.com/taylor-benjamin/resume_website](https://github.com/taylor-benjamin/resume_website)  

---

## Project Overview

This project is a personal professional portfolio website built with Google Antigravity IDE, HTML5, and vanilla CSS, featuring a precision, PlayStation/Sony-inspired aesthetic tailored for technical recruiters.

The project structure consists of:
- **`index.html`** – Single-page hub carrying the four required sections: Profile (academic credentials & cyber risk focus), Skills (querying, platforms, certifications), Experience (IT operations & systems roles), and Contact (email, phone, LinkedIn, GitHub, PDF resume).
- **`resume.html`** – Dedicated curriculum vitae page expanding on full professional history, technical competencies, and an integrated downloadable PDF copy.
- **`project.html`** – In-depth case study analyzing U.S. health sector data breaches from HHS OCR records using the NIST SP 800-30 Risk Assessment framework.
- **`styles.css`** – Centralized stylesheet containing the shared PlayStation-inspired design tokens, sharp geometry, and responsive layouts.
- **`favicon.svg`** – Custom vector brand mark matching the header identity chip.

---

## Learning Reflection

Early in the project, I didn't understand why the agent introduced flexible container heights and flexbox wrapping instead of setting fixed pixel heights, which initially caused my top navigation bar to clip and overflow on smaller viewports. When I asked the agent why the navigation text was breaking its bounds and how to fix the overly bubbly appearance, it explained that fixed pixel heights (such as `height: 72px`) prevent containers from recalculating when screen dimensions change. Through this interaction, I learned that pairing `min-height` with fluid padding allows the layout to naturally accommodate varying screen sizes, and that switching from large border-radii to tighter 2–4px corners produces a sharper, more deliberate enterprise feel rather than a generic, AI-generated look.
