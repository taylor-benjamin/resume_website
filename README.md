# Benjamin Taylor - Personal Portfolio & Resume Website

**Course**: ISDS 4125: Analysis and Design of Information Systems  
**Instructor**: Dr. Gabriele Piccoli | LSU E.J. Ourso College of Business  
**Live Website**: [https://taylor-benjamin.github.io/resume_website/](https://taylor-benjamin.github.io/resume_website/)  
**GitHub Repository**: [https://github.com/taylor-benjamin/resume_website](https://github.com/taylor-benjamin/resume_website)

---

## Project Overview

This project is a personal professional website developed using Google Antigravity IDE, semantic HTML5, and vanilla CSS. Designed with an executive PlayStation/Sony-inspired precision tech aesthetic, the website adheres to a hybrid architecture:
- **`index.html`**: A single-page hub providing high-level overviews of my Profile (B.S. in Information Systems & Analytics with Cyber Risk Concentration at LSU), Core Competencies, Work Experience, and Contact information.
- **`resume.html`**: A dedicated, comprehensive resume with complete career timelines, technical skills, and optimized `@media print` styling for clean PDF export.
- **`project.html`**: An in-depth case study analyzing healthcare attack vectors and mitigation strategies from the HHS Data Breach repository using the NIST SP 800-30 framework.
- **`styles.css`**: A shared design system featuring rigid geometric edges, responsive flex layouts, and custom CSS design tokens.

---

## Learning Reflection

During the development of this project, I initially encountered an issue where my Git commit would not complete and was getting stuck, while the top navigation text was spilling outside the bounding box of the header bar. I asked the agent why I couldn't commit and why the design looked overly rounded and bubbly with misaligned text. Through this troubleshooting, I learned two important technical concepts: first, that Git opens an interactive `COMMIT_EDITMSG` buffer waiting for a non-empty message if `-m` is omitted, and that file modifications must be staged with `git add` before committing. Second, I learned how rigid fixed container heights (`height: 72px`) can force flex items to overflow their parent bounds when viewport dimensions change, and how replacing bubbly border-radius values with clean, low-pixel geometric constraints (`2px` to `4px`) transforms a site from an amateur or AI-generated appearance into a sharp, executive-level enterprise interface.
