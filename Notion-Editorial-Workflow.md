# Editorial workflow in Notion: quick-start guide  
_A lightweight, copy-and-paste starter for any content team_

---

## Why bother?  
A clean editorial workflow keeps ideas moving, cuts approval bottlenecks, and surfaces what’s really blocking your content calendar. If your team already lives in Notion, you get kanban, calendar, database, and doc creation in a single pane of glass—no costly add-ons needed.

---

## Prerequisites
- **Notion access** with _workspace-level_ permission to create pages & databases  
- A clear owner for each **role** below (one person can wear multiple hats):
  - **Writer / SME**
  - **Editor**
  - **Stakeholder / Approver**
  - **Publisher / Ops**

---

## 1. Create a master “Content Pipeline” database
| Property | Type | Purpose |
| -------- | ---- | ------- |
| **Title** | Title | Working headline |
| **Status** | Select | Workflow stage (see next step) |
| **Content Type** | Select | Blog, case study, video, etc. |
| **Owner** | Person | Primary writer / DRI |
| **Reviewer** | Person | Editor or SME reviewer |
| **Publish Date** | Date | Target or firm date |
| **Priority** | Select | P0 / P1 / P2 |
| **Channel** | Multi-select | Blog, LinkedIn, GitHub, etc. |
| **Link** | URL | Final destination or repo link |
| **Notes** | Text | Quick context, blockers, sprint tags |

> **Template tip:**  
> In the **New** menu, create pre-filled templates for “Blog Post,” “Case Study,” “Newsletter,” etc., including page outlines and checklists.

---

## 2. Build a kanban board view
1. Add a **Board** view to the same database.  
2. Drag **Status** into the Columns field.  
3. Use these baseline stages (rename freely):
   - **Backlog** → **In Draft** → **Internal Review** → **External Review** → **Approved** → **Scheduled** → **Published** → **Archived**

Keep it brutally honest: if pieces are piling up in **Internal Review**, you don’t have a writing problem—you have a feedback bottleneck.

---

## 3. Slice the data with smart views
| View name | Filter | Why it matters |
|-----------|--------|----------------|
| **My Queue** | Owner = Me & Status ≠ Published | Daily focus list |
| **Calendar** | Publish Date is not empty | See gaps / collisions |
| **Stalled >14 days** | Last edited is before 14 days ago & Status not Published | Smoke detector |
| **Upcoming Releases** | Publish Date within next 30 days | Stakeholder briefing |

---

## 4. Automate repetitive tasks
- **Notion buttons**: e.g., **“Send to Review”** → sets Status to _Internal Review_ & pings Reviewer.  
- **Relations**: Link the pipeline to a **“Design Assets”** database so creatives know what’s coming.  
- **Integrations** (optional): Use Zapier/Make to open GitHub issues when Status hits **Scheduled**, or post a Slack update when Status flips to **Published**.

---

## 5. Define working agreements (governance light)
| Role | Responsibilities |
|------|------------------|
| **Writer** | Draft in Notion, request review, own revisions |
| **Editor** | Line-edit, enforce style, track deadlines |
| **Stakeholder** | Approve factual accuracy within 48 h |
| **Publisher** | Move to CMS, schedule, update Status |

Write these on the database home page so nobody can claim ignorance.

---

## 6. Measure and iterate
- **Weekly 15-min retro**: What got stuck? Why?  
- **Metrics to track** (use Notion roll-ups or export to Sheets):
  - Draft-to-publish cycle time
  - # of edit rounds per asset
  - % on-time publishes vs. target dates

Relentlessly prune extra steps. Complexity kills momentum.

---

## Optional: add GitHub version control
If your dev-heavy org demands markdown + PR review:

1. Create a **/content/** folder in the repo.  
2. Use Notion’s **Export → Markdown & CSV** for the finished piece.  
3. Commit the file; open a pull request for SME sign-off.  
4. Merge → deploy via static site or CMS pipeline.

Now you’ve combined Notion’s speed with Git rigor.

---

## Next steps
1. **Clone** this page into your workspace.  
2. **Populate** the pipeline with one week of real assignments.  
3. **Run a pilot**: follow the workflow from Backlog to Published once.  
4. **Debrief**: fix friction points before rolling out to the full team.  

When you’re ready to layer in advanced features—content scoring, cross-team OKR roll-ups, analytics dashboards—ping me and we’ll level it up.

> **Pro move:** Lock this page and database schema after launch. Guardrails keep the “helpful” power users from adding 20 new status columns on day two.

---

### License  
MIT — Do anything you want, just don’t blame me if your VP insists on seven approval rounds.

