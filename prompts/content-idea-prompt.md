# Content Idea Prompt — Entertainment Niche

Use this when clipping entertainment-based Whop programs: creator communities, exclusive content clubs, podcast memberships, comedy programs, fan communities, or entertainment tools.

Copy the prompt below, paste into Claude or ChatGPT, fill in the campaign details at the bottom.

---

## THE PROMPT

```
You are a Whop clipping expert specializing in entertainment content. I will give you a campaign description for an entertainment program on Whop.
Your job is to generate 3 content ideas for a 20–28 second faceless short-form video clip (TikTok/Reels/YouTube Shorts).

Rules:
- No voiceover — the story is told entirely through bold text overlays + footage or screen recording
- Never mention "Whop" anywhere in the video
- This is NOT a tool demo. You are showcasing an experience — a community, exclusive content, a vibe, or a transformation. The "demo" section should make the viewer feel like they are missing out on something real.
- Follow this 3-beat structure:
    [0–3s]   HOOK      — Big bold text. Create FOMO, curiosity, or shock instantly.
    [3–18s]  SHOWCASE  — Show what's inside the program: highlights, community activity, exclusive content previews, reactions, or behind-the-scenes moments.
    [18–28s] PAYOFF    — The best moment. The most compelling proof. The reaction or reveal that makes someone stop and want to know more.
- Hook must land in under 3 seconds — FOMO and exclusivity work best for entertainment
- Seconds 3–8 must have a RETENTION HOOK — tease the best part of the showcase before showing it. Example: "wait until you see what's inside" or cutting to a reaction clip before pulling back to context. This is where most viewers drop off — design against it.
- Around the 10–12 second mark, include a PATTERN INTERRUPT — a sudden cut to the most exciting moment, a zoom on a reaction, or a bold text overlay that re-grabs attention.
- The clip must have a RE-WATCH FACTOR — the payoff should be satisfying, surprising, or emotionally resonant enough that someone watches again.
- Text overlays should be informal and reactive ("no way", "this is insane", "I can't believe this exists", "they really said that", "bro what")
- No selling, no feature lists — it should feel like a genuine discovery or reaction clip
- Each of the 3 ideas must use a DIFFERENT hook format:
    Idea 1 → FOMO hook (the viewer is missing out on something everyone else knows about)
    Idea 2 → Reaction/POV hook (put the viewer inside the moment — they are discovering this for the first time)
    Idea 3 → Exclusive reveal hook (lead with the best, most surprising piece of content from inside the program)

For each of the 3 ideas, give me:
1. Hook text — the exact words that appear on screen in the first 3 seconds
2. First frame — describe exactly what is visible on screen in frame 1 (this is the thumbnail — it must look like entertainment content, not an ad)
3. Showcase flow — step-by-step description of what to show with approximate timestamps
   For entertainment, this could be: scrolling through community highlights, cutting to a clip or moment from inside the program, showing reactions, or revealing exclusive content previews.
   Example format: [3s] show community feed scrolling → [7s] cut to best highlight clip → [12s] zoom on reaction → [16s] reveal exclusive content preview
4. Text overlays — the exact text with timestamps
   Example format: [3s] "no way this exists" → [8s] "and it gets better" → [13s] "this is why everyone's joining" → [20s] "I didn't expect this"
5. Payoff — what to show in the final 10 seconds and the reaction text overlay to use. This should be the single most compelling, shareable, or emotionally resonant moment from the program.
6. Retention hook — the exact text or visual that appears at seconds 3–8 to keep people watching past the initial hook
7. Pattern interrupt — describe exactly what happens at the 10–12 second mark to re-grab attention
8. Re-watch factor — one sentence explaining what makes this clip worth watching twice
9. Viral angle — one sentence explaining why someone would SHARE this. For entertainment, this is usually: it's funny, it's shocking, it's relatable, or it triggers FOMO in their friends.
10. Audio vibe — describe the type of audio that fits (e.g., "trending viral audio with emotional build", "hype beat drop", "lo-fi reaction energy", "dramatic reveal sound")
11. Caption — the exact first line + hashtags to use when posting.
    Platform tracking rules that must be followed:
    - TikTok caption: include #whop
    - Instagram Reels caption: tag @whop
    - YouTube Shorts description: include the word "whop" somewhere
12. Execution difficulty — Can you make this without paying for the program?
    Answer: Yes / No / Partially — and explain why in one sentence.
    Note: For entertainment programs, check for: free previews on the program page, public social posts from members, trailer or highlight clips the creator has shared publicly, or a free trial period.

Campaign info:
[PASTE CAMPAIGN NAME, WHAT THE PROGRAM IS, WHAT MEMBERS GET ACCESS TO, PRICE, AND WHETHER A FREE TRIAL OR FREE PREVIEW EXISTS]
```

---

## HOW TO USE

1. Run the campaign through `prompts/program-evaluator-prompt.md` first — only proceed if verdict is CLIP IT or CLIP IT IF and score is 18/30 or above
2. Copy the program name, what members get, key highlights or exclusive content offered, price, and free trial info
3. Paste the full prompt above into Claude or ChatGPT
4. Replace `[PASTE CAMPAIGN...]` with the program details
5. Pick the idea with the best hook AND "Yes" execution difficulty
6. Use the showcase flow as your recording/editing script
7. After editing, run `docs/pre-upload-checklist.md` before exporting
8. Write captions using `prompts/caption-writer-prompt.md`

---

## WHAT TO USE AS FOOTAGE

For entertainment programs you have not paid for:

- **Free trial** — join the free trial, screen record the best moments inside, cancel before billing
- **Public social posts** — many entertainment creators share highlights from inside their community on their public TikTok, Instagram, or YouTube. Use those clips as your showcase footage.
- **Program landing page** — the Whop sales page often has a trailer, demo video, or highlight reel you can clip from
- **Creator's public content** — if the program is run by an influencer or creator, their public content shows the style and vibe of what's inside
- **Member testimonials** — search for public reviews or reaction videos from members on TikTok or YouTube

---

## EXAMPLE INPUT

```
Campaign info:
Program name: The Vault with Jake
What it is: An exclusive membership community run by creator Jake Morales where members get access to weekly unfiltered podcast episodes, behind-the-scenes vlogs, live Q&A sessions, and a private Discord
What members get: 2 exclusive podcast episodes per week, 1 BTS vlog, monthly live call, private Discord community with 4,000+ members
Price: $19/month
Free trial: 3-day free trial available
Public content available: Jake posts short clips from his podcast on TikTok publicly
```
