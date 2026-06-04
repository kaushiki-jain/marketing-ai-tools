# Content Repurposing Tool

A prompt-driven tool that transforms a single piece of long-form content into five platform-ready marketing formats — in one step.

---

## What It Does

Paste any blog post or article into `input.txt`, run one prompt in Claude Code, and get a complete set of repurposed content saved to `output.txt`. No manual reformatting. No copy-pasting across tools.

---

## Why It's Useful for Marketers

Most marketing teams write one piece of content and publish it once. This tool removes the friction of repurposing by automating the transformation into every format a modern content workflow needs.

- Saves 1-2 hours per content piece
- Maintains consistent tone and messaging across platforms
- Produces publish-ready copy, not rough drafts
- Works with any brand, topic, or industry

---

## How to Use It

1. **Add your content** — paste any blog post or article into `input.txt`
2. **Open Claude Code** in this directory
3. **Run this prompt:**

   ```
   Read input.txt and repurpose it using the instructions in repurpose.md. Save the output to output.txt.
   ```

4. **Find your outputs** in `output.txt` — formatted, labelled, and ready to use

---

## Output Formats

Each run produces five formats:

| Format | Specification |
|---|---|
| LinkedIn Post | 100–150 words, hook-led, ends with a question, 3 hashtags |
| Tweet Variations (x3) | Under 280 characters each — pain point, benefit, and conversational angles |
| Email Subject + Preview | Subject under 50 characters, preview under 90 characters |
| Ad Headlines (x3) | Under 8 words each, direct and benefit-focused |
| Instagram Caption | 80–100 words, conversational tone, ends with a question, 5 hashtags |

---

## File Structure

```
content-repurposer/
├── input.txt        ← paste your source content here
├── repurpose.md     ← repurposing instructions for Claude
├── output.txt       ← generated outputs saved here
└── README.md
```

---

## Built With

[Claude Code](https://claude.ai/code) — Anthropic's AI coding and content assistant, used to design the repurposing workflow, write the prompt instructions, and generate all outputs.

---

*Built as part of a marketing AI workflow project exploring how AI tools can accelerate content production without sacrificing quality.*
