# Stella Nwae — Portfolio Website

A single-page portfolio showing my work history and projects, built with AI assistance as a Rewriting the Code (RTC) project.

**Live site:** [portfolio-nwae.netlify.app](https://portfolio-nwae.netlify.app/)

## What's on the page
- **Intro** – who I am and what I'm working towards
- **About** – my path into tech
- **Timeline** – my jobs and projects, newest first, with filter buttons (All / Jobs / Projects)
- **Contact** – email, LinkedIn and GitHub

## Tech stack
- HTML, CSS and a little JavaScript, all in one `index.html` file
- Google Fonts (Poppins and Inter)
- Deployed free on Netlify

## How I built it (AI-assisted workflow)
1. **Scoped first** – asked an AI assistant what a one-page portfolio should include and what to leave out, before writing any code.
2. **Wrote a spec** – created an Architecture Decision Record in `docs/adr/portfolio.md` describing what I'm building, why, and what's out of scope.
3. **Built from the spec** – used Cursor to turn the ADR into the first version of the site.
4. **Iterated on the design** – refined the colours and layout with AI help until it matched the rich, bold look I wanted.
5. **Tested before shipping** – checked the layout on phone and tablet sizes, accessibility (headings, links, contrast) and the filter buttons.

## Adding a new project
Copy one `<li class="card">` block in `index.html`, paste it at the top of the timeline list, set `data-type` to `"job"` or `"project"`, and update the text.

## Contact
- LinkedIn: [linkedin.com/in/stella-nwae](https://www.linkedin.com/in/stella-nwae/)
- GitHub: [github.com/Stellanwae](https://github.com/Stellanwae)
