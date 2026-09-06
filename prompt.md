# ROLE

You are a Senior GitHub Profile README Designer, GitHub Actions Engineer, Developer Branding Specialist, and Markdown Engineer.

Your task is to completely redesign and upgrade the existing GitHub Profile repository for **Nguyễn Công Quân**.

This is NOT a request for recommendations only.

You must:

1. Inspect the current repository.
2. Understand the existing README.
3. Rebuild the GitHub Profile README.
4. Create and configure GitHub Actions for the contribution Snake animation.
5. Validate all URLs and username references.
6. Review the final diff.
7. Leave the repository locally ready to commit and push.

Do NOT push automatically.

---

# TARGET PROFILE

Use the following verified identity throughout the repository:

```text id="9k16fr"
FULL_NAME=Nguyễn Công Quân
DISPLAY_NAME=Nguyen Cong Quan

GITHUB_USERNAME=congquan92

GITHUB_PROFILE=https://github.com/congquan92

PROFILE_REPOSITORY=congquan92/congquan92

PROFILE_REPOSITORY_URL=https://github.com/congquan92/congquan92

WEBSITE=https://nguyencongquan.id.vn

LINKEDIN=https://www.linkedin.com/in/nguyencongquan255

FACEBOOK=https://www.facebook.com/cucngau.quan/

PRIMARY_ROLE=Software Engineer
SECONDARY_ROLE=Frontend Developer
```

Do NOT use placeholder usernames such as:

```text id="2dnhjl"
YOUR_USERNAME
USERNAME
github_username
```

For all GitHub-dependent components, the correct username is:

```text id="fbxct7"
congquan92
```

---

# USER BACKGROUND

The profile belongs to Nguyễn Công Quân.

Known technical background:

```text id="dij6ci"
Information Technology student

Software Engineer / Frontend Developer

Main interests:
- Software Engineering
- Frontend Development
- Full-stack Web Development
- Web architecture
- Backend APIs
- Databases
- DevOps fundamentals
- AI-assisted development
```

Primary known stack:

```text id="5qtz9n"
TypeScript
JavaScript
HTML
CSS

React
Next.js
Tailwind CSS
shadcn/ui

Node.js
NestJS
Express.js

PostgreSQL
Prisma
Supabase

Docker
Git
GitHub
GitHub Actions
Postman
VS Code

Python
```

Do not invent professional experience, companies, certifications, awards, years of experience, or skill levels.

Do not call the user:

```text id="or6iz9"
Senior Software Engineer
Lead Engineer
Staff Engineer
Architect
Expert
```

unless actual repository/user data proves it.

---

# CURRENT REPOSITORY

You are operating inside the special GitHub Profile repository:

```text id="jfpw00"
congquan92/congquan92
```

This is the repository GitHub uses to render:

```text id="16d0x7"
https://github.com/congquan92
```

Do NOT create another profile repository.

Do NOT rename the repository.

Do NOT change the Git remote.

Do NOT initialize another Git repository inside this repository.

Inspect the current state first using safe commands such as:

```bash id="s6wwi2"
git status
git remote -v
git branch --show-current
git log --oneline -10
```

Also inspect the file tree.

---

# REFERENCE DESIGN

The desired style is inspired by modern animated GitHub profiles that contain:

```text id="03rivq"
Animated header
Developer introduction
Contact/social badges
Tech Stack
GitHub statistics
Top Languages
Contribution streak
Contribution Snake
GitHub Actions automation
```

The target should have functionality equivalent to or better than profiles that use:

```text id="qy620e"
capsule-render
shields.io
github-readme-stats
streak-stats
Platane/snk
```

But do NOT blindly copy another developer's personal information.

Build a profile specifically for Nguyễn Công Quân.

---

# PRIMARY OBJECTIVE

Transform the profile into a polished developer landing page.

A visitor should understand within roughly 10–15 seconds:

```text id="e1hpux"
Who is Nguyễn Công Quân?
        ↓
What does he do?
        ↓
What stack does he use?
        ↓
What projects/areas does he work with?
        ↓
Where is his portfolio?
        ↓
How can he be contacted?
        ↓
What does his GitHub activity look like?
```

The profile should feel:

```text id="yyvnaa"
modern
clean
technical
minimal
professional
developer-oriented
slightly futuristic
```

Avoid making it childish or visually chaotic.

---

# REQUIRED FILES

The final repository should at minimum contain:

```text id="kcgq4h"
README.md

.github/
└── workflows/
    └── snake.yml
```

Create `.github/workflows/` if it does not already exist.

Do not create unnecessary application files.

This is NOT a Next.js application.

This is NOT a Node.js project.

Do not create:

```text id="hccvik"
package.json
node_modules/
src/
app/
vite.config.*
next.config.*
Dockerfile
```

unless they already exist for a legitimate unrelated reason.

---

# README ARCHITECTURE

Rebuild `README.md` using approximately the following architecture.

---

## SECTION 1 — ANIMATED HERO

Start with a full-width animated banner.

Prefer:

```text id="5kx152"
Capsule Render
https://capsule-render.vercel.app/
```

Display prominently:

```text id="668r5j"
Nguyen Cong Quan
```

Subtitle:

```text id="dof9pk"
Software Engineer | Frontend Developer
```

Potential implementation:

```html id="uuyw04"
<div align="center">
    <img width="100%" src="..." alt="Nguyen Cong Quan - Software Engineer and Frontend Developer" />
</div>
```

Use a tasteful gradient.

Good directions:

```text id="gmney4"
waving
gradient
tokyonight-like
blue-purple
dark developer aesthetic
```

Do not overdo animation.

Ensure URL query parameters are correctly encoded.

---

# SECTION 2 — INTRODUCTION

Create a short introduction.

Suggested tone:

```text id="vjou3e"
Hi, I'm Nguyen Cong Quan 👋
```

or a more polished equivalent.

Communicate accurately:

- Information Technology student.
- Software Engineer / Frontend Developer.
- Focused on modern web development.
- Mainly works with TypeScript.
- Interested in frontend, backend, databases, and software architecture.
- Builds practical applications and continuously improves engineering skills.

Keep this section concise.

Avoid generic AI-generated paragraphs such as:

```text id="pg08so"
I am a passionate developer who loves turning coffee into code...
```

Avoid excessive motivational text.

Make it sound like a real developer profile.

---

# SECTION 3 — CONTACT / SOCIAL

Add:

```md id="430xtr"
## 🌐 Connect with me
```

Use real links only.

Required links:

```text id="3g8y3x"
GitHub:
https://github.com/congquan92

Portfolio:
https://nguyencongquan.id.vn

LinkedIn:
https://www.linkedin.com/in/nguyencongquan255

Facebook:
https://www.facebook.com/cucngau.quan/
```

Use consistent Shields.io badges.

Example visual style:

```text id="5okmx4"
style=for-the-badge
```

Do not include fake:

```text id="jwjkku"
Instagram
Twitter
Discord
Email
```

unless the repository contains clearly verified links.

Do not create empty links.

---

# SECTION 4 — TECH STACK

Create:

```md id="g22d6h"
## 💻 Tech Stack
```

Do not put 30 badges in one massive row.

Organize technologies logically.

Recommended structure:

### Languages

```text id="2eskw7"
TypeScript
JavaScript
Python
HTML5
CSS3
```

### Frontend

```text id="aqw8e3"
React
Next.js
Tailwind CSS
shadcn/ui
```

### Backend

```text id="xdq6lv"
Node.js
NestJS
Express.js
REST APIs
```

### Database & ORM

```text id="wag26p"
PostgreSQL
Prisma
Supabase
```

### DevOps & Tools

```text id="za2eih"
Docker
Git
GitHub
GitHub Actions
Postman
VS Code
```

Use Shields.io where appropriate.

Example:

```text id="r8gcnc"
https://img.shields.io/badge/...
```

Use official/simple-icons logos when supported.

Keep badge style consistent.

---

# TECHNOLOGY ACCURACY

Do NOT inherit unrelated technologies from another README template.

Do not add technologies merely because they look impressive.

Examples that should NOT automatically be added:

```text id="e2462v"
AWS
Azure
GCP
Kubernetes
Terraform
Kafka
RabbitMQ
Redis
GraphQL
Java
Spring Boot
PHP
Laravel
.NET
Rust
Go
```

Only add extra technologies if the current GitHub repositories provide clear evidence that the user actually works with them and their inclusion materially improves the profile.

---

# SECTION 5 — GITHUB STATS

Create:

```md id="0nv0oz"
## 📊 GitHub Stats
```

Every GitHub statistics service must use:

```text id="poeh6o"
username=congquan92
```

Never another username.

Include three components.

---

## 5.1 GENERAL STATS

Use a reputable GitHub README Stats endpoint.

Conceptual:

```text id="6c1np0"
.../api?username=congquan92
```

Preferred options when supported:

```text id="3xszj7"
show_icons=true
theme=tokyonight
hide_border=true
include_all_commits=true
count_private=true
```

Do not manually hard-code GitHub statistics.

---

## 5.2 TOP LANGUAGES

Use:

```text id="3rnu4k"
username=congquan92
```

Recommended configuration:

```text id="374804"
layout=compact
theme=tokyonight
hide_border=true
langs_count=8
```

Remember:

Top Languages is based on repository code statistics.

Do NOT label it as:

```text id="8w02uq"
Languages I master
```

Use wording such as:

```text id="71ahvj"
Most Used Languages
```

or simply allow the card to speak for itself.

---

## 5.3 CONTRIBUTION STREAK

Use:

```text id="j1gyh3"
https://streak-stats.demolab.com/
```

with:

```text id="ifnxyt"
user=congquan92
```

Recommended:

```text id="k4fj45"
theme=tokyonight
hide_border=true
```

---

# STATS LAYOUT

Center statistics.

GitHub-compatible example:

```html id="92pxf0"
<div align="center">...</div>
```

Desktop should look balanced.

Mobile should naturally wrap.

Do NOT attempt custom CSS.

GitHub README does not allow arbitrary stylesheets.

---

# SECTION 6 — CONTRIBUTION SNAKE

Add:

```md id="k5ug5p"
## 🐍 Contribution Snake
```

The generated Snake must represent:

```text id="ie2d2i"
congquan92
```

Expected dark image URL:

```text id="v2b1fj"
https://raw.githubusercontent.com/congquan92/congquan92/output/github-snake-dark.svg
```

Expected light version:

```text id="3omp37"
https://raw.githubusercontent.com/congquan92/congquan92/output/github-snake.svg
```

Prefer using `<picture>` so GitHub automatically uses the correct asset for dark/light mode.

Example conceptual implementation:

```html id="zcqd8m"
<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/congquan92/congquan92/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/congquan92/congquan92/output/github-snake.svg" />
    <img alt="GitHub contribution snake for congquan92" src="https://raw.githubusercontent.com/congquan92/congquan92/output/github-snake.svg" />
</picture>
```

Ensure the syntax works in GitHub Markdown.

---

# GITHUB ACTIONS

Create:

```text id="o4cqzp"
.github/workflows/snake.yml
```

The workflow should generate the contribution Snake automatically.

---

# WORKFLOW NAME

Use a clear workflow name, for example:

```yaml id="8jdfrr"
name: Generate Contribution Snake
```

---

# WORKFLOW TRIGGERS

Support manual execution:

```yaml id="wsk7a8"
workflow_dispatch:
```

Also run automatically once per day.

For example:

```yaml id="lisn8t"
schedule:
    - cron: "0 0 * * *"
```

Remember GitHub Actions cron uses UTC.

There is no requirement to run this multiple times per day.

Optionally trigger after changes to the profile if appropriate, but avoid unnecessary Action executions.

---

# WORKFLOW PERMISSIONS

The workflow needs permission to publish to the `output` branch.

Add:

```yaml id="htawwk"
permissions:
    contents: write
```

Do NOT request excessive permissions.

Do NOT request:

```text id="adwjlm"
issues: write
pull-requests: write
packages: write
id-token: write
```

unless truly required.

---

# SNAKE GENERATION

Use the established:

```text id="55njlr"
Platane/snk
```

GitHub Action.

Do not implement the Snake generator manually.

Use the GitHub repository owner dynamically:

```yaml id="2tcjm2"
github_user_name: ${{ github.repository_owner }}
```

Prefer this over:

```yaml id="66w3t9"
github_user_name: congquan92
```

because it makes the workflow portable.

Generate at least:

```text id="rlrils"
dist/github-snake.svg
dist/github-snake-dark.svg
```

Configure dark mode appropriately.

---

# OUTPUT BRANCH

Publish generated assets to:

```text id="s68cuf"
output
```

The architecture should be:

```text id="4xxhax"
main
│
├── README.md
│
└── .github/
    └── workflows/
        └── snake.yml
              │
              │ GitHub Actions
              ▼
          Platane/snk
              │
              ▼
         generated SVG
              │
              ▼
          output branch
              │
              ├── github-snake.svg
              └── github-snake-dark.svg
```

Do NOT commit generated Snake SVG files into `main`.

---

# OUTPUT PUBLISHING

Use a reputable branch publishing mechanism compatible with the current Platane/snk workflow.

If the reference implementation uses a working publishing Action, preserve the proven architecture when reasonable.

Potential approaches include a maintained branch deployment Action.

Do not:

```text id="6vkx6u"
hard-code PAT tokens
create personal access tokens
print secrets
commit credentials
```

Use GitHub's built-in:

```text id="vgxn2k"
${{ secrets.GITHUB_TOKEN }}
```

when required.

---

# ACTION VERSION POLICY

Before choosing Action versions:

1. Inspect any existing workflow.
2. Prefer maintained versions.
3. Avoid deprecated Action versions.
4. Do not perform unrelated dependency upgrades.

Keep the workflow simple.

---

# OPTIONAL PROJECT SECTION

Inspect the user's public repositories.

Current profile may contain projects such as:

```text id="ww06e3"
TKB_SGU
tts-vna
RAG
SZ
ChatWeb
QLBH
```

Do NOT automatically create fake project descriptions.

If repository descriptions are available and useful, you may add:

```md id="cfxqtg"
## 🚀 Featured Projects
```

Limit this to approximately 3–4 strong projects.

Prefer projects that demonstrate:

```text id="0m29db"
TypeScript / Next.js
Full-stack development
Backend/API skills
Real applications
Interesting engineering work
```

If there is insufficient information to create a high-quality Featured Projects section, omit it.

Do NOT clutter the README merely to satisfy this optional section.

---

# OPTIONAL CURRENT FOCUS

A small section such as this is acceptable:

```md id="w6xsg3"
## 🎯 Current Focus
```

Possible factual themes:

```text id="9k9mxu"
Modern web development
Software engineering
Frontend architecture
Backend development
Databases
DevOps fundamentals
```

Keep it very short.

Do not create generic motivational content.

---

# FOOTER

Optionally finish with a subtle footer/header wave using Capsule Render.

Do not add noisy content like:

```text id="suocbo"
Thanks for visiting!!! ⭐⭐⭐⭐⭐
Follow me!!!
Buy me a coffee!!!
```

unless intentionally required.

A clean visual ending is preferred.

---

# DESIGN RULES

Maintain a coherent visual system.

Preferred aesthetic:

```text id="7ebuw5"
Tokyo Night
Dark blue
Purple
Cyan accent
Dark-mode friendly
```

But do NOT specify arbitrary custom CSS.

Keep:

- header style
- badges
- stats
- Snake

visually consistent.

---

# DARK MODE + LIGHT MODE

The GitHub profile must remain readable in both.

Avoid text embedded inside images where contrast becomes unreadable.

Where possible, use:

```html id="14fkhu"
<picture></picture>
```

for dark/light adaptive graphics such as Snake.

---

# MARKDOWN RULES

GitHub README supports a limited subset of HTML.

Allowed/common elements:

```text id="l2dd1a"
div
p
img
a
picture
source
table
details
summary
```

Do not use:

```text id="qur67g"
<script>
<style>
<iframe>
JavaScript
external CSS
```

GitHub will strip or block them.

---

# RESPONSIVENESS

The README should work on:

```text id="7zcbj9"
desktop
tablet
mobile
GitHub dark mode
GitHub light mode
```

Use natural Markdown wrapping.

Do not rely on exact pixel layouts.

Avoid huge hardcoded widths for stats cards.

Header can use:

```text id="kt3xkt"
width="100%"
```

---

# ACCESSIBILITY

Use meaningful alt attributes.

Examples:

```text id="g1kp5d"
Nguyen Cong Quan GitHub Profile Header
Nguyen Cong Quan GitHub Stats
Most Used Languages
GitHub Contribution Streak
GitHub Contribution Snake
```

Avoid:

```text id="1gn5b3"
image
img
picture1
```

---

# SECURITY RULES

Never inspect or display secrets unnecessarily.

Never output:

```text id="2sraja"
PAT
GitHub tokens
SSH private keys
.env secrets
credentials
cookies
```

Never commit credentials.

Do NOT modify:

```text id="0h82mu"
.git/config
.git/
SSH configuration
system Git credentials
```

Reading:

```bash id="ewi68c"
git remote -v
```

is allowed.

---

# PROTECTED REMOTE OPERATIONS

Do NOT execute:

```bash id="wcfp99"
git push
git push --force
git reset --hard
git clean -fd
gh repo delete
gh repo rename
git branch -D
```

Do NOT modify remote GitHub settings automatically.

Do NOT trigger GitHub Actions remotely.

Prepare everything locally only.

---

# IMPLEMENTATION PLAN

Execute the following phases.

---

## PHASE 1 — INSPECT

Inspect:

```text id="rsmauq"
repository tree
README.md
.github/
Git status
Git branch
Git remote
```

Run appropriate safe commands.

Determine what currently exists.

---

## PHASE 2 — AUDIT

Audit current `README.md`.

Identify:

```text id="1mnjpd"
weak introduction
outdated information
poor formatting
missing tech stack
missing stats
missing contribution Snake
missing GitHub Actions
broken URLs
duplicate links
placeholder data
unnecessary HTML
```

Do not report only.

Continue to implementation.

---

## PHASE 3 — IMPLEMENT README

Rebuild:

```text id="bfxmgs"
README.md
```

according to this specification.

Prefer a coherent final README over incremental patchwork.

Preserve existing valid personal URLs where useful.

---

## PHASE 4 — IMPLEMENT SNAKE

Create/update:

```text id="1en8qf"
.github/workflows/snake.yml
```

Ensure:

```text id="vvgfj0"
workflow_dispatch
daily cron
contents: write
Platane/snk
github.repository_owner
light SVG
dark SVG
output branch
```

---

## PHASE 5 — IDENTITY SEARCH

Search the entire repository for accidental leftover identities.

At minimum search:

```text id="dvy53r"
lhhuy02012005
Lê Hữu Huy
Huu Huy
Backend Engineer
Distributed Systems
YOUR_USERNAME
USERNAME
example.com
```

None of these should survive unintentionally.

---

# CORRECT IDENTITY CHECK

Confirm occurrences of:

```text id="eicaku"
congquan92
Nguyễn Công Quân
Nguyen Cong Quan
nguyencongquan.id.vn
nguyencongquan255
```

are intentional and syntactically correct.

---

# URL VALIDATION

Inspect every URL written into README.

Pay special attention to:

```text id="o91s0q"
Capsule Render
Shields.io
GitHub Stats
Streak Stats
raw.githubusercontent.com
Portfolio
LinkedIn
Facebook
```

Avoid malformed ampersands/query strings.

When writing URLs inside HTML attributes, ensure HTML remains valid.

---

# WORKFLOW VALIDATION

Review YAML manually.

If an already-installed YAML parser/linter exists, it may be used.

Do NOT install dependencies just for validation.

Check:

```text id="qutl2u"
valid indentation
valid YAML syntax
trigger structure
permissions
job structure
action inputs
output paths
output branch
```

---

# FINAL DIFF REVIEW

Run:

```bash id="qtr9s5"
git diff --check
git diff
git status --short
```

Review all changes.

Verify only intended profile files changed.

Do NOT commit.

---

# ACCEPTANCE CRITERIA

Do not consider the task complete until all applicable items are satisfied.

## Identity

- [ ] Profile represents Nguyễn Công Quân.
- [ ] GitHub username is `congquan92`.
- [ ] GitHub profile link is correct.
- [ ] Repository references use `congquan92/congquan92`.
- [ ] Portfolio points to `https://nguyencongquan.id.vn`.
- [ ] LinkedIn uses `nguyencongquan255`.
- [ ] No old template owner remains.

## Hero

- [ ] Animated modern header exists.
- [ ] Name reads `Nguyen Cong Quan`.
- [ ] Role communicates Software Engineer / Frontend Developer.
- [ ] Header works on GitHub.

## About

- [ ] Short useful introduction.
- [ ] No fake experience.
- [ ] No exaggerated seniority.
- [ ] Information Technology background represented appropriately.

## Technology

- [ ] TypeScript
- [ ] JavaScript
- [ ] React
- [ ] Next.js
- [ ] Tailwind CSS
- [ ] Node.js
- [ ] NestJS
- [ ] Express
- [ ] PostgreSQL
- [ ] Prisma
- [ ] Supabase
- [ ] Docker
- [ ] Git

are represented appropriately.

## GitHub Stats

- [ ] Stats use `congquan92`.
- [ ] Top Languages use `congquan92`.
- [ ] Streak uses `congquan92`.
- [ ] Consistent theme.
- [ ] No hard-coded fake metrics.

## Snake

- [ ] Snake section exists.
- [ ] Light Snake supported.
- [ ] Dark Snake supported.
- [ ] URLs point to `congquan92/congquan92`.
- [ ] Asset branch is `output`.

## Workflow

- [ ] `.github/workflows/snake.yml` exists.
- [ ] Manual run supported.
- [ ] Automatic schedule configured.
- [ ] `contents: write` configured.
- [ ] Uses `${{ github.repository_owner }}`.
- [ ] Snake assets generated correctly.
- [ ] Assets published to `output`.
- [ ] No secret is hard-coded.

## Repository Safety

- [ ] No application dependencies introduced.
- [ ] No unrelated files modified.
- [ ] No remote changes performed.
- [ ] No push performed.
- [ ] Final diff reviewed.

---

# QUALITY BAR

Do not produce something that looks like a generic README generator result.

Avoid:

```text id="5cycb6"
20+ badges with no grouping
10 animated GIFs
huge text walls
random emojis everywhere
fake quotes
useless widgets
multiple visitor counters
duplicate stats cards
```

Prefer:

```text id="1ujjm3"
strong hero
short intro
clear tech stack
real links
useful GitHub stats
clean contribution Snake
good spacing
consistent visual language
```

The final README should be suitable for putting on a CV or portfolio.

---

# FINAL RESPONSE

After implementation, return:

## Completed

Describe the work actually completed.

## Files Changed

Example:

```text id="dudp8n"
README.md
- Rebuilt profile README
- Added hero
- Added About section
- Added contact badges
- Added categorized Tech Stack
- Added GitHub Stats
- Added contribution Snake

.github/workflows/snake.yml
- Added automated Snake generation
- Added daily schedule
- Added manual workflow trigger
- Added output branch publishing
```

## Verification

Report real validation results.

Example:

```text id="1hxm28"
GitHub username: congquan92 ✓
Profile repository: congquan92/congquan92 ✓
Old template identity references: 0 ✓
git diff --check: PASS
README URLs: reviewed
Snake workflow: reviewed
Remote operations performed: none
```

Do not claim PASS for checks that were not performed.

## Remaining Manual Steps

Tell the user to run:

```bash id="e2ofvn"
git add README.md .github/workflows/snake.yml
git commit -m "feat: redesign GitHub profile"
git push origin main
```

Then:

```text id="mtvyxh"
GitHub
→ congquan92/congquan92
→ Actions
→ Generate Contribution Snake
→ Run workflow
```

After a successful first execution, confirm branch:

```text id="mcwic3"
output
```

exists and contains:

```text id="we030d"
github-snake.svg
github-snake-dark.svg
```

If GitHub rejects write access, tell the user to inspect:

```text id="r8cqgf"
Repository
→ Settings
→ Actions
→ General
→ Workflow permissions
```

and ensure the repository configuration allows the workflow to write repository contents.

Do not push or change these settings yourself.

---

# EXECUTION DIRECTIVE

Do not stop at analysis.

Do not return only recommendations.

Do not ask unnecessary questions.

Inspect the existing repository and perform all safe local modifications required to transform `congquan92/congquan92` into the finished GitHub Profile.

Use the exact verified identity:

```text id="ky7gou"
Nguyễn Công Quân
congquan92
https://github.com/congquan92
https://nguyencongquan.id.vn
https://www.linkedin.com/in/nguyencongquan255
```

Preserve factual accuracy.

Do not invent information.

Do not perform remote write operations.

Finish with a verified local diff ready for the user to commit and push.
