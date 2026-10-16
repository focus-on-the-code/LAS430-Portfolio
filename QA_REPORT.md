# LAS 430 GitHub Pages — QA and change log

## Scope and verification

- Audited **43 original HTML pages** from the previous replacement ZIP (the same package used as the redevelopment baseline).
- Attempted to retrieve the published GitHub Pages URL, but the web viewer reported a cache miss. **Live behavior, remote media availability, and deployed-version parity were not verified.**
- Checked static HTML navigation paths and original Canvas placeholders; the generated release has zero nonexistent internal HTML links.
- Existing external links and iframes have been retained; external destinations were not assumed functional.
- Student-specific feedback files and copyrighted attachments were not copied into the public package.

## Findings and high-impact changes

- Identified **62 Canvas-specific references across 43 course pages. They are flagged and their original destinations shown next to each link, not silently discarded.
- Expanded the Teaching Overview into a detailed, scan-first account of course design, humanities readings, staged portfolio work, and asynchronous student support.
- Added keyboard navigation, active sidebars, accessible embed titles, responsive styling, and external-link safety attributes.
- Added `link-audit.html`, listing original Canvas links that may need replacement.

## Page-by-page changes

### course.html — Full course | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### index.html — Teaching overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Added Resource audit navigation for transparent access to course link status.
- Expanded Teaching Overview with the course design challenge, humanities learning strands, Nussbaum-related inquiries, four stage-by-stage portfolio milestones, and asynchronous learner supports.
- Made learning/research versus portfolio deliverable explicit for each capstone checkpoint.
- Clarified outcome attribution as instructor-reported, not independently verified by Canvas export.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### link-audit.html — Resource audit | LAS 430

- Created a new resource audit listing every preserved Canvas-specific reference by source page and original URL.

### m0-i0.html — Start Here: Welcome To The Class! | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i1.html — Priority 1: Prof. T's Writing Expectations | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 3 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i10.html — Tech Resources: OFFICE 365 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added descriptive title and lazy loading to 1 original embed(s).
- Flagged image using a Canvas attachment placeholder; retained the original file reference.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i11.html — Cyber Cafe: Chit-Chat Channel | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i2.html — Priority 2: Prof. T's Generative AI Use Policy | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 4 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i3.html — Priority 3: Weekly Assignment Requirements - Discussions, Replies, Reflections, Portfolio Deliverables | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i4.html — Priority 4: Final Assignment Requirements – E-Portfolio | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 2 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 5 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 2 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i5.html — Priority 5: Productivity | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i6.html — Priority 6: Student-to-Student Guide – How to Succeed in Prof. T’s Class | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i7.html — Free Pass on One Assignment | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i8.html — Learning Resources: Reading | Analysis | Writing | Recording | Presenting | Canvas | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 6 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 6 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 6 Canvas-specific link(s) documented in `link-audit.html`.

### m0-i9.html — Learning Resources: Library and Online Writing Lab (OWL) | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m1-i0.html — Unit 1 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m1-i1.html — Unit 1 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 6 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 6 Canvas-specific link(s) documented in `link-audit.html`.

### m1-i2.html — Unit 1 Portfolio Deliverable | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 6 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 3 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 6 Canvas-specific link(s) documented in `link-audit.html`.

### m2-i0.html — Unit 2 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 3 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m2-i1.html — Unit 2 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 4 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 4 Canvas-specific link(s) documented in `link-audit.html`.

### m2-i2.html — Unit 2 Reflection | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m3-i0.html — Unit 3 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m3-i1.html — Unit 3 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m3-i2.html — Unit 3 Portfolio Deliverable | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 4 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 4 Canvas-specific link(s) documented in `link-audit.html`.

### m4-i0.html — Unit 4 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 4 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 3 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 4 Canvas-specific link(s) documented in `link-audit.html`.

### m4-i1.html — Unit 4 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 9 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 9 Canvas-specific link(s) documented in `link-audit.html`.

### m4-i2.html — Unit 4 Reflection | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m5-i0.html — Unit 5 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added descriptive title and lazy loading to 3 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m5-i1.html — Unit 5 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 2 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 2 Canvas-specific link(s) documented in `link-audit.html`.

### m5-i2.html — Unit 5 Portfolio Deliverable | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 3 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 3 Canvas-specific link(s) documented in `link-audit.html`.

### m6-i0.html — Unit 6 Overview | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 2 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 5 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 2 Canvas-specific link(s) documented in `link-audit.html`.

### m6-i1.html — Unit 6 Discussion | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m6-i2.html — Unit 6 Reflection (NEW) | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Secured external links opening in a new tab.
- Marked 6 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 2 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 6 Canvas-specific link(s) documented in `link-audit.html`.

### m7-i0.html — Unit 7 Overview | Finals | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 1 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added descriptive title and lazy loading to 1 original embed(s).
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 1 Canvas-specific link(s) documented in `link-audit.html`.

### m7-i1.html — Unit 7 Final Reflection | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### m7-i2.html — Final Assignment - E-Portfolio - Due Feb 26 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Marked 2 Canvas-only/file-placeholder hyperlink(s), preserving original URLs visibly while preventing dead relative-path navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 2 Canvas-specific link(s) documented in `link-audit.html`.

### module-0.html — Course Overview & Critical Info: Review in Priority Order | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-1.html — Unit 1 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-2.html — Unit 2 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-3.html — Unit 3 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-4.html — Unit 4 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-5.html — Unit 5 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-6.html — Unit 6 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

### module-7.html — Unit 7 | LAS 430

- Added keyboard-accessible skip navigation and semantic main landmark.
- Improved active section indication for keyboard and screen-reader navigation.
- Added Resource audit navigation for transparent access to course link status.
- Review priority: 0 Canvas-specific link(s) documented in `link-audit.html`.

## Publishing and validation

1. Replace the existing GitHub Pages repository contents with all files in the ZIP, including `link-audit.html`.
2. Wait for GitHub Pages deployment and clear browser cache before testing.
3. Follow every flagged placeholder in the resource audit; substitute an accessible authorized URL only when available.
4. Check third-party embeds/links in a browser, especially Canvas-authenticated resources and any external media requiring cookies.
5. Confirm the public display is appropriate for rights, privacy, and departmental expectations.