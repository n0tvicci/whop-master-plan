# Daily Routine — Whop Clipping System
**Open this every morning. Follow it in order.**  
**Time required:** 2–4 hours/day

---

## MORNING BLOCK — Campaign Browsing
**8:00–9:00am PH | 30 minutes**

### Step 1 — Open Whop Creator Dashboard
Go to `whop.com/clips` and browse available campaigns.

Look for campaigns with:
- Active budget remaining (check the budget bar — no budget = no payout even with views)
- Visual product or content you can clip within 20 seconds
- Free trial, free tier, or public demo you can access without paying
- No geo-restriction, OR geo-restriction to Tier 1 countries (US/UK/CA/AU/NZ) — those pay more

### Step 2 — Evaluate Every Promising Campaign with the Program Evaluator

**When you see something that looks interesting — stop. Do not record anything yet.**

Open `prompts/program-evaluator-prompt.md`.

**What this prompt does:**  
It scores the campaign across 6 criteria — visual potential, clip-ability, execution difficulty, Tier 1 appeal, hook potential, and payout value — and gives you a final verdict: CLIP IT / SKIP IT / CLIP IT IF. It also flags whether the campaign is geo-restricted and what that means if you're posting from the Philippines. This prevents you from spending 90 minutes editing a clip for a campaign that was never going to pay out.

**How to use it:**
1. Copy the program name, description, key features, price, and whether a free trial exists
2. Open the prompt file → copy the full prompt
3. Paste it into Claude or ChatGPT
4. Replace the `[PASTE PROGRAM...]` section with the program details
5. Read the verdict:
   - **CLIP IT** → add to today's clip list
   - **CLIP IT IF** → check if you can meet the condition; if yes, add it; if no, skip it
   - **SKIP IT** → move on immediately, do not record
   - **Score below 18/30** → skip regardless of verdict label

### Step 3 — Lock In Today's Targets
Pick 1–2 programs to clip today. Write them down. That is your recording list for the midday block.

---

## MIDDAY BLOCK — Content Creation
**1:00–3:00pm PH | 90 minutes (allow 2.5–3 hours in your first month)**

### Step 4 — Generate Clip Ideas with the Content Idea Prompt

Open `prompts/content-idea-prompt.md`.

This prompt is built for entertainment programs: creator communities, exclusive content clubs, podcast memberships, fan communities, and entertainment tools.

**What this prompt does:**
Generates 3 fully built clip ideas — each with a different hook format (FOMO / Reaction-POV / Exclusive reveal), exact hook text, what appears in frame 1, a timestamped showcase flow, exact text overlay copy, retention hook for seconds 3–8, pattern interrupt at seconds 10–12, re-watch factor, viral angle, audio direction, caption copy, and execution difficulty. Pick the idea with the strongest hook AND a "Yes" execution difficulty.

**How to use:**
1. Copy the campaign name, what the program does or offers, and its key features
2. Open `prompts/content-idea-prompt.md` → copy the full prompt
3. Paste into Claude or ChatGPT
4. Replace the campaign placeholder at the bottom with your program details
5. Read all 3 ideas
6. Pick the one with: strongest hook text + "Yes" execution difficulty
7. Use the timestamped flow as your recording and editing script

### Step 5 — Capture Your Footage

Follow the flow from the idea you picked.

**Where to get your footage:**
- Free trial — join the trial, screen record the best moments inside, cancel before billing
- Public social posts — many creators share highlights from inside their community publicly on TikTok, Instagram, or YouTube
- Program landing page — the Whop sales page often has a trailer, demo reel, or highlight clip you can use
- Creator's public content — shows the style and vibe of what's inside the program
- Member testimonials — search for public reviews or reaction videos on TikTok or YouTube

Identify the single most surprising, funny, or curiosity-triggering 20–28 second moment in the source material. Capture more than you need — you will cut it down in editing.

### Step 6 — Edit in CapCut

Follow the 3-beat structure:

```
[0–3s]   HOOK      — Bold text from your chosen idea. Audio drop on frame 1.
[3–18s]  DEMO      — Your footage. Cut every 1–2 seconds. Text overlays every few seconds.
          (Entertainment: this beat is your SHOWCASE — community highlights, exclusive content preview)
[18–28s] RESULT    — The outcome. Reaction text overlay on the final frame.
          (Entertainment: this beat is your PAYOFF — the most compelling or FOMO-triggering moment)
```

**Editing rules:**
- Text: 1–5 words per frame, informal and reactive ("wait what" / "no way" / "bro what")
- Add a zoom punch at the pattern interrupt point (seconds 10–12)
- Use a trending audio from TikTok's built-in sound library
- Total length: 20–28 seconds — cut mercilessly
- No dead air — every second has something happening

**Export:**
1. Remove the CapCut watermark before exporting (free button in the export screen)
2. Save the clean file to your device
3. Do NOT download from TikTok to repost on other platforms — the TikTok watermark will get suppressed on Instagram and YouTube

### Step 7 — Run the Pre-Upload Checklist

Before exporting, open `docs/pre-upload-checklist.md` and go through every item.

**What this checklist does:**  
It catches every technical and content mistake before the clip goes live — weak hook, dead air, wrong audio source, missing watermark removal, wrong clip length, missing Whop tracking tags in the caption. One missed item can suppress the clip on all 3 platforms. This takes 2 minutes and prevents hours of wasted effort.

**Rule: If even one box is unchecked — fix it first. Do not upload until every box is checked.**

---

## EVENING BLOCK — Prepare & Schedule Upload
**7:00–8:00pm PH | 30–45 minutes**
*(US prime time is 7–9am PH = 7–9pm EDT. Prepare your uploads now and use each platform's scheduled post feature to deliver at 7–9am PH. Posting live at 7–8pm PH = 6–7am EST — not prime time. Do not post live in the evening.)*

### Step 8 — Write Captions with the Caption Writer Prompt

For each clip you're uploading, open `prompts/caption-writer-prompt.md`.

**What this prompt does:**  
It generates a ready-to-copy-paste caption for all 3 platforms — TikTok, Instagram Reels, and YouTube Shorts — each formatted correctly for that platform's character limits, hashtag strategy, and Whop tracking requirements. It also writes the first comment you post on TikTok immediately after upload, which is designed to invite replies and signal the algorithm that your content is active. You do not edit the output — you copy-paste directly.

**How to use it:**
1. Note your hook text and what the clip demonstrates (1–2 sentences)
2. Open the prompt file → copy the full prompt
3. Paste into Claude or ChatGPT
4. Fill in: hook used, what the clip shows, program niche
5. Copy each platform's caption — do not edit

### Step 9 — Upload to All 3 Platforms

**Upload order: TikTok first → Instagram Reels → YouTube Shorts**

**TikTok:**
- Upload the clean file (not downloaded from TikTok)
- Paste TikTok caption — must include `#whop` for Content Rewards tracking
- Use TikTok's built-in scheduled post feature — set delivery for 7–9am PH (not post live now)
- When the scheduled post goes live, immediately post the first comment from the caption prompt within 60 seconds — set a phone alarm for the delivery time

**Instagram Reels:**
- Upload the same clean file
- Paste Reels caption — must tag `@whop`
- Schedule delivery for 7–9am PH using Instagram's built-in scheduler (tap the clock icon before posting)
- Maximum 2 Reels per day on Instagram — if you made 3 clips today, post 2 on Reels and save the 3rd for TikTok/Shorts only

**YouTube Shorts:**
- Upload the same clean file
- Paste YouTube description — must include the word "whop" somewhere
- Schedule delivery for 7–9am PH using YouTube Studio's scheduling option

### Step 10 — Submit Every Clip to Whop

**Posting is not enough. You must submit the link or you do not get paid.**

For each clip you just posted, on each platform:
1. Copy the video link
2. Open the campaign page on Whop
3. Submit the link — enter the title and paste the URL
4. Repeat for each platform the campaign tracks

Do this immediately after posting while the links are fresh. Do not batch submissions to "later" — it's easy to forget and lose earnings.

**If a clip gets rejected:**
- Read the rejection reason before doing anything else
- If rejected for analytics: go to the campaign's support chat on Whop → send a full screen recording of your analytics for that video → Whop will manually review
- If rejected for content/format issues: fix the specific problem listed and resubmit

### Step 11 — Log Today's Clips

Write down for each clip:
- Hook text used
- Program/niche
- Which platform you posted on
- Whether it was submitted to Whop
- Date and time posted (scheduled delivery time, not prep time)
- Saves and shares (update this the next morning after the clip has been live for 24 hours)

You will need all of this — including saves and shares — for the Sunday weekly review prompt.

---

## SATURDAY — BATCH DAY
**Replaces the normal daily workflow**

Instead of making 3 clips to post today, make 5–7 clips and save them as drafts.

**Why:** Your draft buffer is insurance. When you're sick, burnt out, or have a bad week, you pull from drafts instead of skipping a day. Never let your draft folder drop below 3 clips. Consistency is the single most important variable in whether this system works — a skipped day is a signal to the algorithm that your account is inactive.

**Batch day workflow:**
1. Morning: Evaluate 3–4 campaigns with `program-evaluator-prompt.md`
2. Afternoon: Generate ideas for all of them with `content-idea-prompt.md`, capture footage for all, edit all in CapCut
3. Evening: Run `pre-upload-checklist.md` on each clip, write captions with `caption-writer-prompt.md`, save as drafts

---

## SUNDAY — WEEKLY REVIEW
**Once per week | 20–30 minutes**

### Open `prompts/weekly-review-prompt.md`

**What this prompt does:**  
It takes your week's raw stats — views per clip, saves, shares, watch time, and Whop earnings — and returns a specific action plan for the next 7 days. It tells you which hook format to keep, which to retire, which audio energy to target, which platform to prioritize, what day and time to post, and one specific experiment to run next week. Following this prompt weekly is what separates accounts that plateau at 200 views per clip from accounts that reach 10k+ per clip by Month 3.

**How to use it:**
1. Check TikTok, Instagram, and YouTube analytics for the week
2. Copy views, saves, shares, and completion rates for each clip
3. Open the prompt file → copy the full prompt
4. Paste into Claude or ChatGPT
5. Fill in all stats — write "unknown" for anything you can't find
6. Read the action plan and follow it exactly for the next 7 days

**Also do this every Sunday:**
1. Check your TikTok Analytics → Followers → Top territories
2. Add up US + UK + CA + AU + NZ percentages
3. If combined is under 40% → do not increase posting volume yet. Adjust post time and audio first.
4. Check Whop creator dashboard for your current month's earnings

---

## When a Clip Underperforms — Use the Hook Optimizer

If any clip gets significantly fewer views than your average, open `prompts/hook-optimizer-prompt.md`.

**What this prompt does:**  
It diagnoses exactly why your original hook failed — too generic, too vague, too long, no curiosity gap, sounds like an ad, or weak opening word. Then it rewrites the hook into 5 stronger variations, each using a different format (curiosity gap / POV / controversy / number-stat / pain point). For each variation it gives you the exact text, recommended formatting, why it's stronger, when in the audio it should appear, and how hard it is to execute. You remake the clip with the new hook — same demo, same result, new hook only.

**How to use it:**
1. Identify the underperforming clip
2. Copy the original hook text and clip context
3. Open the prompt file → copy the full prompt
4. Paste into Claude or ChatGPT
5. Fill in: original hook, what the clip was about, total views, completion rate (if available), which platform it flopped on
6. Pick the strongest variation
7. Remake the clip — change the hook only, keep everything else

---

## Quick Reference — Prompt Decision Guide

**You see a campaign on Whop that looks interesting**
→ `prompts/program-evaluator-prompt.md`

**Campaign passed the evaluator — need video ideas**
→ `prompts/content-idea-prompt.md`

**Finished editing — need captions for all 3 platforms**
→ `prompts/caption-writer-prompt.md`

**About to upload — run the final check**
→ `docs/pre-upload-checklist.md`

**A clip got way fewer views than normal**
→ `prompts/hook-optimizer-prompt.md`

**It's Sunday — time to review the week**
→ `prompts/weekly-review-prompt.md`

---

## Daily Checklist Summary

**Morning (8–9am)**
- [ ] Browse Whop creator dashboard
- [ ] Run `program-evaluator-prompt.md` on each interesting campaign
- [ ] Lock in 1–2 programs to clip today

**Midday (1–3pm)**
- [ ] Generate ideas with `content-idea-prompt.md`
- [ ] Capture your footage
- [ ] Edit 3 clips in CapCut (Hook → Demo → Result)
- [ ] Run `pre-upload-checklist.md` before exporting
- [ ] Export without watermark

**Evening (7–8pm PH) — prepare & schedule for 7–9am PH delivery**
- [ ] Generate captions with `caption-writer-prompt.md`
- [ ] Schedule TikTok upload for 7–9am PH — set alarm to post first comment when it goes live
- [ ] Schedule Instagram Reels for 7–9am PH (max 2 per day)
- [ ] Schedule YouTube Shorts for 7–9am PH
- [ ] Submit every clip link to Whop after each goes live (one submission per clip per platform)
- [ ] Log today's clips (hook text, niche, platform, submitted, date)

**Saturday**
- [ ] Make 5–7 clips and save as drafts
- [ ] Draft folder must never drop below 3 clips

**Sunday**
- [ ] Pull weekly stats from all 3 platforms
- [ ] Run `weekly-review-prompt.md`
- [ ] Check Tier 1 view ratio (TikTok Analytics)
- [ ] Check Whop earnings dashboard
- [ ] Follow the action plan for next week exactly
