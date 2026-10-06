# BuildWise — Phase 1

This is the Phase 1 frontend prototype based on the BuildWise planning flow.

## Included

- Home
- Plot Details
- Building Requirements
- Rooms & Facilities
- Budget
- Preferences
- Generate/processing placeholder
- Responsive mobile + desktop UI
- Local React state for the complete wizard

## Not included yet

- Real AI/OpenAI API
- Database/Auth
- Real 2D floor-plan engine
- Cost calculation backend
- My Projects
- Version history
- PDF/download generation

Those are planned for later phases.

## Run locally

Install Node.js (LTS), then:

```bash
npm install
npm run dev
```

Open:

http://localhost:3000

## GitHub

Create a new GitHub repository named `buildwise-phase1`, then:

```bash
git init
git add .
git commit -m "BuildWise Phase 1"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

## Next phase

Phase 2 will connect:
1. AI processing
2. Structured floor-plan generation
3. 2D editable floor plan
4. Cost estimate
5. Plan summary
