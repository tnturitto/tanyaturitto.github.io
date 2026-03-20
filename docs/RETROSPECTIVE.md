# Project Retrospective
**Project:** Wise Builder Resume Portfolio Site  
**Project #:** 1  
**Author:** Tanya Turitto  
**Status:** In Progress — updated as project evolves  
**Last Updated:** March 2026  

---

## What Went Well ✅

- **AI-assisted development worked effectively** — Using Claude to build 
  the initial site, audit accessibility, and generate documentation saved 
  significant time while producing professional quality output
- **WCAG compliance from the start** — Building accessibility in from day 
  one was far easier than retrofitting it later
- **GitHub Pages + Porkbun** — Free, reliable, and the setup process built 
  real technical knowledge
- **Documentation as you go** — Writing the PRD, Infra doc, and flowcharts 
  during the build (not after) kept everything accurate and fresh
- **GitHub Projects visibility** — Having a public project board makes the 
  PM process visible to anyone who looks, not just the finished product

---

## What Was Harder Than Expected ⚠️

- **DNS propagation** — The process of connecting Porkbun → Cloudflare → 
  GitHub Pages involved more steps than anticipated and required 
  troubleshooting nameserver conflicts
- **GitHub username mismatch** — Repo name not matching username caused 
  a nested URL issue that required renaming both
- **Cloudflare proxy settings** — Orange cloud vs grey cloud (proxied vs 
  DNS only) caused a temporary site outage — not immediately obvious why
- **HTTPS certificate delay** — SSL certificate issuance after DNS 
  propagation took longer than expected

---

## What I Would Do Differently 🔄

- **Buy the domain before starting the build** — Having the domain ready 
  from day one would have avoided the late-stage DNS troubleshooting
- **Set GitHub username before creating repo** — Avoids the mismatch issue 
  entirely
- **Document decisions in real time** — Some early decisions were made 
  before documentation was set up and had to be reconstructed from memory
- **Set up VS Code and Git before starting** — Local development from day 
  one is cleaner than editing files directly on GitHub

---

## Key Learnings 📚

| Learning | Application to Future Projects |
|----------|-------------------------------|
| DNS has multiple layers — registrar, nameservers, records | Set up domain infrastructure first on every future project |
| GitHub username = repo name for Pages to work correctly | Check username before creating any GitHub Pages repo |
| Cloudflare proxying breaks GitHub Pages | Always set DNS only for static sites on GitHub Pages |
| WCAG is easier to build in than bolt on | Start every project with accessibility as a requirement not an afterthought |
| AI tools accelerate but don't replace judgment | Review every AI output before committing — you own the decisions |
| Public documentation is itself a portfolio signal | Document every project as thoroughly as this one |

---

## Metrics at Launch

| Metric | Result |
|--------|--------|
| Time to build | ~1 week including documentation |
| Total cost | $10.00 (domain registration) |
| WCAG criteria passing | 7/7 AA criteria |
| Lighthouse Performance | 100/100 |
| Lighthouse Accessibility | 100/100 |
| Lighthouse Best Practices | 77/100 (GA + GitHub Pages headers) |
| Lighthouse SEO | 100/100 |
| Lines of code | ~650 (single index.html) |
| Documentation files | 4 (PRD, Infra, Flowchart, Retro) |
| GitHub issues created | 18 |


---

## Open Questions for v2

- Should the site be split into multiple pages as projects are added?
- When does it make sense to move from plain HTML to a static site 
  generator like Eleventy?
- How do I measure whether the portfolio is actually helping job search?
- Should each project have its own subdomain or stay as a subfolder?

---

## v2 Backlog Items Generated From This Retro

- [ ] Run Lighthouse audit and document scores
- [ ] Add Google Analytics to measure real visitor behavior  
- [ ] Add Open Graph meta tags for LinkedIn sharing
- [ ] Add contact form via Formspree
- [ ] Write case study narrative for this project
- [ ] Add projects page as Project #2 launches

---

*This retrospective is part of the Wise Builder AI PM Portfolio  
by Tanya Turitto · wisebuilder.me · Tanya@wisebuilder.me*
