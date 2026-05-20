# Prompts Guide

All prompts live in this folder. Copy the prompt, paste into Claude or ChatGPT, fill in the fields, and execute.

---

## When to Use Each Prompt

---

### 1. program-evaluator-prompt.md
**When:** Before you decide to clip a program  
**What it does:** Scores a Whop program across 5 criteria — visual potential, clip-ability, execution difficulty, Tier 1 appeal, and hook potential. Gives you a CLIP IT / SKIP IT / CLIP IT IF verdict so you never waste time on a program that can't be executed.  
**Input needed:** Program name, description, features, price, free trial availability  
**Output:** Score out of 25, final verdict, and strongest hook angle if worth clipping

---

### 2. content-idea-prompt.md
**When:** After deciding a program is worth clipping  
**What it does:** Generates 3 ready-to-execute video ideas for a campaign. Each idea uses a different hook format (curiosity, POV, shock) and comes with a timestamped demo flow, exact text overlays, viral angle, audio vibe, caption, and execution difficulty rating.  
**Input needed:** Program name, what it does, key features, price, free trial info  
**Output:** 3 complete video ideas — pick the one with the best hook and "Yes" execution difficulty

---

### 3. caption-writer-prompt.md
**When:** After finishing your clip in CapCut, right before uploading  
**What it does:** You export ONE video and upload that same file to all 3 platforms. But each platform has a different text box to fill in at upload time — TikTok has its caption field, Instagram has its description, YouTube has its description box. This prompt generates the exact text to paste into each of those fields, formatted correctly for that platform with the right hashtags, tone, and length. One video, three different captions.  
**Input needed:** Your hook text, what the clip shows, program niche  
**Output:** 3 copy-paste texts — one per platform upload screen, ready to go

---

### 4. hook-optimizer-prompt.md
**When:** When a clip underperforms (low views compared to your average)  
**What it does:** Takes your original hook and rewrites it into 5 stronger variations — each using a different hook format (curiosity gap, POV, controversy, number/stat, pain point). Tells you why each is stronger and how hard it is to execute.  
**Input needed:** Original hook text, what the clip was about, view count, which platform it flopped on  
**Output:** 5 new hook variations — re-make the clip with the best one, keep everything else the same

---

### 5. weekly-review-prompt.md
**When:** Every Sunday, before planning next week  
**What it does:** Analyzes your week's clip performance, identifies patterns in what worked and what failed, and gives you a specific action plan for the next 7 days — including which hook format to use, which to stop, audio energy to target, and one new experiment to try.  
**Input needed:** Total clips posted, total views, per-clip breakdown (hook, topic, views, best platform), current month earnings  
**Output:** Full next-week action plan with realistic view target

---

## Recommended Order Per Clip

```
Step 1 → program-evaluator-prompt   (should I clip this?)
Step 2 → content-idea-prompt        (what should the clip look like?)
Step 3 → Record + Edit in CapCut
Step 4 → caption-writer-prompt      (what do I write when uploading?)
Step 5 → Upload using pre-upload-checklist
Step 6 → hook-optimizer-prompt      (only if clip underperforms)
Step 7 → weekly-review-prompt       (every Sunday)
```
