# Program Evaluator Prompt

Use this before committing to clip a Whop program. Paste the program details and let the AI tell you if it's worth your time before you start recording.

---

## THE PROMPT

```
You are a Whop clipping expert who evaluates whether a program is worth creating content for.

I will give you details about a Whop program. Evaluate it across 5 criteria and give me a final verdict.

Scoring scale: 1 (poor) to 5 (excellent)

Criteria:
1. Visual potential — How easy is it to demonstrate this program on a screen recording? Can results be shown in under 20 seconds?
2. Clip-ability — How strong is the "wow factor"? Will someone stop scrolling when they see this?
3. Execution difficulty — Can I screen record this without paying for the program? (free trial, free tier, public demo)
4. Tier 1 appeal — Will this content naturally attract US/UK/AU viewers?
5. Hook potential — How many strong hook angles does this program have?
6. Payout value — Based on the program type and niche, estimate the likely payout range per 1k views (low: $1–2 / medium: $3–5 / high: $6+). A visually great program with a low payout rate is still a poor use of time.

For each criterion give:
- Score out of 5
- One sentence explanation

Then give me:
- Total score out of 30
- Geo-restriction flag: Is this campaign likely Tier 1 only (US/UK/AU/CA/NZ)? Yes / No / Unknown — and what that means for a creator posting from the Philippines
- Final verdict: CLIP IT / SKIP IT / CLIP IT IF (condition)
- If CLIP IT: suggest the single strongest hook angle for this program
- If SKIP IT: suggest what type of program to look for instead
- If CLIP IT IF: explain exactly what condition needs to be met first

Program details:
[PASTE PROGRAM NAME, DESCRIPTION, FEATURES, PRICE, AND WHETHER A FREE TRIAL EXISTS]
```

---

## HOW TO USE

1. Find a program on Whop's creator dashboard that looks interesting
2. Copy the program name, description, key features, price, and free trial info
3. Paste the full prompt into Claude or ChatGPT
4. Replace `[PASTE PROGRAM...]` with the program details
5. Only proceed to clip if verdict is CLIP IT or CLIP IT IF (and you meet the condition)
6. Skip anything that scores below 18/30

---

## EXAMPLE INPUT

```
Program name: AutoReply Pro
What it does: AI tool that monitors your Gmail and automatically drafts reply suggestions based on your writing style
Key features: Connect Gmail → AI learns your tone → auto-draft replies → one-click send
Price: $19/month
Free trial: 7-day free trial available
```
