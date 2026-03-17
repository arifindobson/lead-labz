# Project Vercel01: Pilot Website Workflow

## Goal
Build a workflow with **Antigravity**, **GitHub**, and **Vercel** to allow a speedy **PRD -> Build -> Deploy** workflow.

## The Workflow
1. **Define PRD**: Create or update product requirements in the `PRD/` folder and reference them in `context.md`.
2. **AI Action**: Antigravity reads the requirement docs, implements changes, and verifies builds.
3. **Push to GitHub**: Changes are pushed to the `main` branch.
4. **Auto-Deploy**: Vercel triggers a deployment immediately upon push.

## Current status
- [x] Initial GitHub connection
- [x] Pilot landing page (`index.html`)
- [x] PRD directory created (`PRD/`)
- [x] Vercel integration (Push successful)
