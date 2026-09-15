# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary audience is a broad personal network, not a single narrow segment: recruiters and hiring managers evaluating Araceli for data science/CS internships and full-time roles, alongside professors, classmates, and other personal contacts encountering the site as a general professional and personal presence.

## Product Purpose

A personal website for Araceli Siedschlag that serves as a general portfolio and personal record — an honest, complete showcase of her academic work, professional experience, projects, and personality. Success is not narrowly tied to landing one job; it is the site accurately and proudly representing who she is and what she has done.

## Positioning

A two-degree computer science / data science student (BS + combined BS/MS at Colorado School of Mines) whose experience spans applied ML/data projects, IT service and documentation leadership, and enterprise software/ESG tooling work — a combination of technical modeling depth and operational/people leadership that a single-track CS or DS student profile would not have.

## Operating Context

- Built and deployed as Project 1 for CSCI 498E/598E ("Coding with AI Agents") at Colorado School of Mines: a personal site driven by Claude Code, hosted on GitHub Pages at the repo's root (`AraceliSiedschlag.github.io`).
- The repo is public, including full commit history; no secrets, home address, phone number, unpublished work, or other people's photos may be committed.
- Deployed via GitHub Pages "Deploy from a branch" (`main`, root); relies on relative paths and the `.nojekyll` file at the repo root to avoid path/Jekyll-stripping breakage.
- Course deliverables tracked alongside the site: `DECISIONS.md` (decision log), a `verification/` folder proving the live URL works, and other course artifacts (video, peer comments) that live outside this repo's product scope.

## Capabilities and Constraints

- Plain HTML/CSS build (no framework, no build step); JetBrains Mono via Google Fonts.
- Single-page site with in-page navigation to four sections — Professional, Coursework/Education, Projects, Personal — plus a downloadable résumé PDF and an email/résumé closing call-to-action.
- Personal section currently has empty photo placeholder slots pending real photos.
- No required page count, framework, or section list was imposed by the assignment; content and structure are Araceli's choice.

## Evidence on Hand

- `Araceli_Siedschlag_Resume.pdf` — real résumé, linked from the nav and the closing CTA. Current on disk (verified Sep 15).
- Real professional history (Mines PMO, Mines IT Service Desk, Janus Henderson Investors x2, Convercent) and real coursework/degree facts, already written into the current `index.html`.
- Three real project write-ups (Predictive Housing Investment Model, City of Idaho Springs Economic Impacts Dashboard, Clue Digital Simulation).
- Contact: aasiedschlag@mines.edu; GitHub: github.com/AraceliSiedschlag; LinkedIn: linkedin.com/in/araceli-siedschlag.
- No personal photos yet on hand for the Personal section's photo grid (four placeholder slots, unfilled), and no headshot yet for the hero placeholder either.

## Product Principles

- Specificity over polish: real employers, real course names, real numbers (GPA, class rankings) outrank generic portfolio boilerplate.
- The site should read as unmistakably hers, not templated — content and voice take priority over conforming to a generic "student portfolio" pattern.
- Honesty about gaps (empty photo slots, in-progress coursework) is preferable to filling them with placeholder or invented content.
- Durability first: since GitHub Pages serves this at the repo root, path correctness and relative links are load-bearing product constraints, not just implementation detail.

## Accessibility & Inclusion

No product-specific accessibility requirement was established beyond general web accessibility good practice.
