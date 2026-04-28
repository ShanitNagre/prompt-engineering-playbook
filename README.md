# 📊 AI Feature Prioritization Model

> An interactive, browser-based tool for scoring and ranking product features using RICE, ICE, and Impact vs Effort frameworks. Built for AI PM workflows.

**Author:** Shanit Nagre — AI Product Manager  
**Live demo:** [shanitnagre.github.io/ai-feature-prioritization](https://shanitnagre.github.io/ai-feature-prioritization)

---

## What It Does

Product teams spend hours debating feature priority in spreadsheets. This tool:

- Scores features across **3 frameworks** (RICE, ICE, Impact vs Effort)
- Automatically **ranks and tiers** features into Ship Now / Consider / Deprioritize / Cut
- Visualizes scores with **progress bars** for each scoring dimension
- Provides a **2×2 matrix view** for stakeholder presentations
- Comes preloaded with **real sample features** from AI product work

---

## Frameworks Included

### RICE Score
`Score = (Reach × Impact × Confidence%) / Effort`

Best for: Features with measurable user reach data. Standard at most product orgs.

| Input | Range | Description |
|-------|-------|-------------|
| Reach | 100–50,000 | Users/week affected |
| Impact | 0.25–3 | Impact per user (0.25=minimal, 3=massive) |
| Confidence | 10–100% | How sure are you about estimates? |
| Effort | 0.5–26 | Person-weeks to build |

### ICE Score
`Score = Impact × Confidence × Ease`

Best for: Fast, gut-check prioritization in early-stage teams. Used at startups and during discovery sprints.

### Impact vs Effort Matrix
Plots features on a 2×2 grid for visual stakeholder communication.

---

## Sample Features (Preloaded)

The tool comes with 8 sample features from real AI product work:

| Feature | Category | Framework Context |
|---------|----------|------------------|
| Denial Auto-Resolution Engine | AI/ML | SPRY claims pipeline |
| Claims Pre-Submission Scrubbing | Automation | SPRY billing |
| Appeal Letter Generator | AI/ML | Denial management |
| Payer Rule Auto-Update | Integration | Payer intelligence |
| Multi-Payer Eligibility Check | Integration | Revenue cycle |
| ERA Batch Analytics Dashboard | Analytics | Billing ops |
| HIPAA Audit Trail Enhancement | Compliance | Regulatory |
| Provider Portal Redesign | UX | Client experience |

---

## How to Use

1. Open `index.html` in any browser (no server needed)
2. Select your scoring framework
3. Add features with the form, or click "Load Sample Features"
4. Switch between List view and Matrix view
5. Toggle sort order (by score or by category)

---

## Why I Built This

Every sprint planning session I've been in has had the same problem: 12 features, 5 opinions, no shared framework. RICE scores in a spreadsheet work, but they don't give you instant visual feedback on trade-offs.

This tool externalizes the scoring so the team debates inputs (is this really a 3 for impact?), not outputs (which rank should this be?). The conversation shifts from opinion to evidence.

The matrix view is specifically for stakeholder presentations — it's much easier to explain "top-left quadrant = ship now" than to defend a ranked list in a room full of non-PMs.

---

*Part of Shanit Nagre's AI PM portfolio — [shanitnagre.github.io](https://shanitnagre.github.io)*
