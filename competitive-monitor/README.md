# Competitive Positioning Monitor

A prompt-driven tool that turns raw competitor messaging — taglines, value props, website copy — into a structured competitive positioning report with actionable differentiation opportunities.

## What This Tool Does

Given a collection of competitor messaging (taglines, value propositions, key messages, tone, pricing language, etc.), this tool produces a full competitive positioning report: per-competitor breakdowns, a cross-competitor messaging comparison, identified positioning gaps, concrete differentiation angles, and recommended messaging changes — all in one pass.

## Why Competitive Positioning Analysis Matters for PMMs

Positioning doesn't happen in a vacuum — it's relative to what every other player in the category is claiming. Without a structured view of competitor messaging, it's easy to:

- Duplicate a message a competitor already owns, diluting differentiation
- Miss audience segments or pain points that nobody is addressing
- React to competitor moves anecdotally instead of systematically

This tool turns ad hoc "what is X saying these days?" research into a repeatable analysis that surfaces real gaps, ranks them by opportunity, and translates them directly into messaging recommendations — the output a PMM can act on immediately, not just read.

## How to Use It (Step by Step)

1. Open `competitor-input.txt` and paste in competitor information — taglines, value propositions, key messages, tone of voice, target audience, pricing language, and any other relevant copy for each competitor.

2. Run the following prompt:
   > "Read competitor-input.txt and analyse it using the instructions in competitor-analysis.md. Save the output to competitive-report.txt"

3. Review `competitive-report.txt` — it will contain all 6 sections, structured and ready to share or act on.

## The 6 Output Sections

1. **Competitor Snapshots** — Per-competitor breakdown: value proposition, target audience, top messages, tone, emphasis, omissions, and biggest positioning weakness.
2. **Messaging Comparison Matrix** — Cross-competitor view of pricing, ease of use, enterprise readiness, integrations, and compliance/security — who owns each theme, who ignores it, and who is weakest.
3. **Positioning Gaps Analysis** — Messages nobody owns, underserved audience segments, and pain points the category isn't addressing.
4. **Differentiation Angles** — Three concrete positioning angles to own, each with a message, proof point, target persona, and the competitors it counters.
5. **Recommended Messaging Moves** — Specific, prioritised (high/medium/low) changes to current messaging, mapped to the competitor weakness each one exploits.
6. **Weekly Digest Summary** — A short executive summary of the week's competitive landscape, the biggest opportunity, and the recommended next action.

## Automatic Insight Flagging

The report doesn't just describe the landscape — it tells you what matters most. The top three most important findings are automatically flagged with **[KEY INSIGHT]**, so the highest-value takeaways are immediately visible without reading the full report.

## Built for Sharing

Section 6 produces a concise, ~150-word executive digest written for a CMO or marketing leadership audience — covering competitive movements, the biggest opportunity identified, and a recommended immediate action. It's designed to be copied directly into a status update, Slack digest, or leadership briefing with no further editing.

## Built With

This tool was built using **Claude Code**, demonstrating how AI-assisted workflows can support product marketing teams in turning raw competitive intelligence into structured, decision-ready analysis at speed.
