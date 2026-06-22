Title:  14 Cold Email Deliverability Lessons From 20 Million Emails (Stop Landing In Spam) 
Channel: Atishay Jain
Link: https://www.youtube.com/watch?v=dHCj-innFJs

## Key Takeaways

1. **Copy fatigue is a fingerprinting problem, not a writing problem.** ESPs don't penalize bad copy. They fingerprint structural patterns. The same template sent 100,000 times gets flagged automatically — even if no one complained about it recently.
2. **Subject lines are the most fingerprintable part of your email.** One subject line repeated 10,000 times is the easiest pattern to detect. Vary aggressively. 10+ variations minimum.
3. **Warm-up is prevention, not cure.** A burned domain stays burned. Replace it, don't try to recover it.
4. **Monitor at the domain level, not the inbox level.** One bad inbox on a domain will drag the rest down within days.
5. **25% drop week-over-week = act immediately.** Don't wait to see if it recovers. Pause, rotate copy, or replace domain.
6. **Stop tracking open rates. Full stop.** Introduces an HTML pixel, triggers spam filters, and the data is wrong anyway (Apple pre-opens emails since iOS 14).
7. **Diagnose copy vs infrastructure before fixing anything.** Two different problems with two different solutions. Treating an infrastructure problem like a copy problem wastes money, and vice versa.

---

## Lesson 1: Copy Fatigue = Email Fingerprinting

ESPs don't read your copy for quality. They fingerprint the structural signature of an email:

- Sentence patterns and phrasing
- Opening line structure
- CTA format
- Sender name
- Signature format
- Company identification info

When the same template is sent 100,000+ times, the fingerprint is recognized. If any previous version was marked as spam, new sends with the same fingerprint get auto-filtered — even to people who've never seen it before.

**Real example:** Scaled a campaign from 102,000 to 255,000 sends/month with the exact same copy and ICP. Reply rates dropped from 3%+ to 1.7% for no other reason than fingerprinting.

**Fix:** Generate structural variations using AI. Same offer, different structure — vary sentence length, paragraph order, phrasing, CTA format. Can't do this manually at scale. Use a prompt (she has one in her free guide).

---

## Lesson 2: Subject Line Variation

Subject lines are the most fingerprintable element because:
1. One subject line is repeated identically across thousands of emails
2. It's only 2–3 words — extremely easy to pattern-match

**Rules for cold email subject lines:**
- Max 3 words
- Vague — should look like an internal email between colleagues
- No spam trigger words (free, guarantee, urgent, etc.)
- Create a pool of 10+ variations per email variant
- Even just the company name as the subject line works (unique per prospect by definition)

---

## Lesson 3: Randomize Sender Names at Scale

Applies when sending 100,000+ emails/month.

One person named "John Doe" sending 100,000 emails with similar content is a red flag pattern. At this volume, use AI-generated generic names across your sender accounts. Each name should look like a real person but not tie back to your actual company identity.

---

## Lesson 4: Signature Hygiene

**The problem:** Even with randomized sender names, a static company website URL in the signature re-identifies your company across all sends.

**Common workarounds that don't work:**
- Typing `company.com` without hyperlinking it — Gmail and Outlook auto-detect and link URLs anyway
- Removing the hyperlink but keeping the domain — same result

**What to do instead:**
- Strip the `.com` entirely
- Use a variant of your brand name as a word (no domain extension)
- Spin-tax job titles across senders
- Keep signatures minimal: name + title + brand name variant only
- No links, no phone numbers, no addresses

---

## Lesson 5: Domain Naming and TLDs

**Avoid:**
- Numbers in domain names
- Hyphens
- Prefixes like "get" or "try"
- Obscure or expensive TLDs

**Use:**
- Generic, brandable, single-word names (doesn't have to be a real word — just easy to say)
- `.com`, `.info`, `.co`, `.net` only

**Volume-based rule:**
- Under 10,000 emails/day: branded domains (your company name variations) are fine
- Over 10,000 emails/day: use generic domains — your company name in the domain becomes a fingerprint pattern at that scale

---

## Lesson 6: Spread Domains Across Multiple Registrar Accounts

Not a deliverability issue — a risk management issue. People have lost 6,000 domains overnight when a registrar banned their account.

- Use multiple registrar accounts, distribute domains across them
- For Google mailboxes: use one domain per admin panel, 2–5 inboxes per admin panel, and run multiple admin panels

---

## Lesson 7: Warm-Up Is Prevention, Not Cure

Warm-up builds positive reputation for domains that start at zero. It does not rebuild reputation for domains already in negative territory.

If a domain is burned: delete the inboxes, abandon the domain, move to fresh domains.

**Warm-up ratios:**
| Inbox type | Cold email : Warm-up ratio |
|---|---|
| Google (Gmail/Workspace) | 1:1 to 1:1.5 (20 cold = 20–30 warm-up) |
| Azure/Intra | Follow vendor's specific guidelines |
| SMTP | 1:3 to 1:5 (20 cold = 60–100 warm-up) |

SMTP requires significantly more warm-up to maintain reputation.

---

## Lesson 8: Enterprise Targeting — Use Microsoft/SMTP, Not Google

Google inboxes are the most reliable and versatile for most use cases. But enterprise companies often use secure email gateways (Barracuda, Mimecast, Proofpoint) with their own internal blacklists.

If targeting enterprise accounts, shift proportions toward Microsoft Outlook and SMTP while keeping Google in the mix. Don't abandon Google, just rebalance.

---

## Lesson 9: Personal Email Domains Burn Domains Faster

Scraping personal emails (Gmail, Hotmail, Yahoo, iCloud, etc.) from Google Maps, Facebook, Instagram, etc. can work — these inboxes get less email and positive response rates can be good.

**But:** The sending domains you use for personal email outreach burn faster than those used for business email outreach. Personal email ESPs use stricter algorithms.

Keep these campaigns on separate domain pools if running both.

---

## Lesson 10: Redirects Hurt You at Scale

Standard practice is to redirect secondary sending domains back to your main website. This works fine at low-to-medium volume.

**Problem at 50,000+ emails/day:** Thousands of domains all redirecting to the same destination URL becomes a detectable pattern. AI pattern detection blacklists you based on the shared redirect even if everything else varies.

**Fix at this scale:** Don't add any redirects. Let the email itself explain what you do. Remove all domain redirects if sending at this volume.

---

## Lesson 11: Stop Tracking Open Rates

**Two reasons this is always wrong:**

1. **Deliverability:** Open tracking requires an HTML pixel in the email. HTML content triggers spam filters. Hurts deliverability every time.

2. **Data accuracy:** Since iOS 14, Apple Mail auto-opens all emails to preload images. This fires your tracking pixel even if the human never opened the email. Every major email client is moving in this direction. Your open rate numbers are inflated and unreliable.

**Use reply rate as your only metric.** It's the only signal that actually tells you something real.

---

## Lesson 12: Replace Burned Domains, Don't Recover Them

Deliverability is always a function of domain health.

If one inbox on a domain has poor reply rates, the other inboxes on that domain follow within days. Measure on the domain level, not the inbox level.

**When a domain underperforms:** Delete the inboxes, move to a fresh domain. Don't try warm-up recovery. Don't wait it out.

---

## Lesson 13: Monitor Reply Rates by Domain Week-Over-Week

**Two triggers to act immediately:**
1. Reply rate drops 25%+ below weekly baseline
2. Any sudden unexplained drop regardless of the percentage

**When triggered:** Pause the campaign. Rotate the copy first (cheap). If that doesn't fix it, replace the domain (more expensive but sometimes necessary).

**Don't wait.** The downside of acting fast is minimal. The downside of waiting is losing the domain and losing time.

---

## Lesson 14: Diagnose Copy vs Infrastructure

Two causes for dropping reply rates. Two different fixes. Identify which before doing anything.

**Heuristic 1 — Inbox age:**
- Fresh inboxes (under 1 week old) with bad reply rates → copy problem (the infrastructure is clean, the only variable is the email itself)
- 2–3 month old inboxes with declining reply rates → infrastructure problem (domain reputation has eroded from accumulated spam reports)

**Heuristic 2 — Cohort comparison:**
- Reply rates down uniformly across all domains → copy problem (same fingerprint affecting everything)
- Reply rates down only on some domains, others healthy → infrastructure problem (those specific domains are burned)

**When heuristics disagree:** Fix copy first. It's cheaper and faster than buying new domains.

---

## The 14 Lessons at a Glance

| # | Lesson |
|---|---|
| 1 | Copy fatigue = fingerprinting. Vary structure, not just wording |
| 2 | Vary subject lines aggressively. 10+ variations, max 3 words, vague |
| 3 | Randomize sender names at 100k+ emails/month |
| 4 | Strip domain from signature. No links. Name + title + brand variant only |
| 5 | Generic brandable domains, .com/.info/.co/.net only, no numbers/hyphens |
| 6 | Spread domains across multiple registrar accounts |
| 7 | Warm-up is prevention. Burned domain = replace, not recover |
| 8 | Enterprise targets need Microsoft/SMTP, not Google |
| 9 | Personal email domains burn your sending domains faster — use separate pools |
| 10 | No redirects at 50k+ emails/day — they become a fingerprint |
| 11 | Never track open rates — hurts deliverability and data is inaccurate |
| 12 | Replace burned domains. Don't try to recover them |
| 13 | Monitor reply rate by domain weekly. Act at 25% drop |
| 14 | Diagnose copy vs infrastructure before fixing anything |

---

## Common Mistakes

- Assuming bad copy caused the deliverability drop (it's usually fingerprinting of good copy sent too many times)
- Trying to warm-up recover burned domains (doesn't work, wastes time)
- Tracking open rates (hurts deliverability and the data is wrong)
- One registrar account for all domains (one ban wipes everything)
- Using the same sender name across 100k+ sends
- Putting website URLs in signatures (auto-linked even without hyperlinks)
- Waiting to act when reply rates drop ("let's give it another week")
- Using Google for enterprise outreach without adjusting for secure email gateways
