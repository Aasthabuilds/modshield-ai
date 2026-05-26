# modshield-ai
A Devvit-based Reddit moderation tool that detects toxic thread spikes, speeds up mod actions, and helps reduce burnout.

# ModShield AI

AI-powered moderation control plane for faster, safer Reddit communities.

## Overview
ModShield AI is a Devvit-based moderation tool designed to help Reddit moderators detect toxic thread spikes early, take action faster, and reduce burnout.

## Problem
Moderators often face:
- fast-moving toxic threads,
- repetitive moderation actions,
- overloaded queues,
- and long work sessions that cause burnout.

## Solution
ModShield AI combines three focused layers:
- Cascade Breaker
- Native Mod HUD
- Burnout Router

## Features
### Cascade Breaker
Tracks thread velocity and flags risky conversations before they escalate.

### Native Mod HUD
Surfaces quick moderation actions directly inside the workflow.

### Burnout Router
Helps balance moderator workload and surface break prompts.

## Architecture
1. Thread activity is monitored.
2. Risk is evaluated using rule-based detection.
3. Moderator alerts are triggered when thresholds are crossed.
4. Quick actions are shown in the mod HUD.
5. Workload balancing logic reduces overload.

## Tech Stack
- Reddit Devvit
- TypeScript
- Rule-based risk detection
- Mobile-first product design

## Project Structure
- `src/` - source code
- `docs/` - PRD, TRD, architecture, and pitch deck
- `assets/` - screenshots and mockups

## Demo
- Demo Video: add link here
- https://youtube.com/shorts/y693R1RvRDY?si=zf5RZ30CPdYejv0H
- Devpost Submission: add link here
- GitHub Repository: add link here

## Setup
```bash
git clone https://github.com/<your-username>/modshield-ai.git
cd modshield-ai
npm install


Limitations
•Current version is hackathon MVP-focused.
•Risk detection is rule-based.
•Advanced automation is planned for future versions.

Future Work
•Sentiment-aware toxicity scoringC
•ustom alert thresholds
•Analytics dashboard
•Better automation

Credits
•Product direction:
•Development:
•Design:

License
MIT

## 2) `LICENSE`
```txt
MIT License

Copyright (c) 2026 <Aastha sukhadiya
>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.



3) .gitignore
node_modules/
dist/
build/
coverage/
.env
.DS_Store
*.log

4) devvit.yaml
name: modshield-ai
version: 1.0.0
description: AI-powered moderation control plane for Reddit communities


5) package.json
{
  "name": "modshield-ai",
  "version": "1.0.0",
  "description": "AI-powered moderation control plane for Reddit communities",
  "main": "index.js",
  "scripts": {
    "build": "tsc",
    "start": "devvit start"
  },
  "keywords": [
    "reddit",
    "devvit",
    "moderation",
    "hackathon",
    "modtool"
  ],
  "author": "Your Name",
  "license": "MIT"
}


6) tsconfig.json
{
  "compilerOptions": {
    "target": "ES2020",
    "module": "ESNext",
    "moduleResolution": "Node",
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src",
    "esModuleInterop": true,
    "skipLibCheck": true
  },
  "include": ["src"],
  "exclude": ["node_modules", "dist"]
}


7) src/index.ts
export {};


8) docs/architecture.md
# ModShield AI Architecture

## Flow
1. Thread activity is monitored.
2. Cascade Breaker checks velocity and risk.
3. If thresholds are crossed, a mod alert is triggered.
4. Native Mod HUD shows quick actions.
5. Burnout Router monitors workload balance.

## Core Components
- Cascade Breaker
- Native Mod HUD
- Burnout Router

## Design Goal
Create a fast, low-friction, moderator-first workflow for Reddit communities.

9) docs/workflow.md
# ModShield AI Workflow

## Moderator Flow
1. A thread becomes active.
2. Activity is measured.
3. Risk is detected.
4. Moderator sees action buttons.
5. Workload is balanced if overload happens.

## Key Actions
- Lock
- Freeze
- Remove
- Escalate

10) docs/demo-notes.md
# Demo Notes

- Show problem first.
- Show Cascade Breaker.
- Show Native Mod HUD.
- Show Burnout Router.
- End with impact statement.

11) docs/PRD.md if you want a text version
# Product Requirements Document

## Product Name
ModShield AI

## Goal
Help Reddit moderators detect toxic spikes early, act faster, and reduce burnout.

## Core Features
- Cascade Breaker
- Native Mod HUD
- Burnout Router

## Success Criteria
- Faster moderation decisions
- Better workflow clarity
- Reduced mod overload


12) assets/ file namesUse these exact names:
modshield-ai/
└── assets/
    ├── hero.png
    ├── problem.png
    ├── cascade-breaker.png
    ├── mod-hud.png
    ├── burnout-router.png
    ├── impact.png
    └── thumbnail.png


13) Optional .github/ files
CONTRIBUTING.md

# Contributing

This project is part of a hackathon build. Contributions should focus on improving moderation workflow clarity, UI polish, or documentation.

CODE_OF_CONDUCT.md

# Code of Conduct

Be respectful, constructive, and collaborative.




