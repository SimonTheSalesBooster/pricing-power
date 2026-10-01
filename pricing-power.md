---
description: "Pricing Power: win bigger deals at the price you want by starting with the problem. Finds the 3 problems your clients have that you can actually solve, down to the source. Builds the chart (Problem, Impact, Source), turns it into 9 discovery questions, and tests it against real calls. Modes: build | test | hooks."
---

# /pricing-power: start with the problem, not the price

Buyers don't buy your product. They buy their way out of a problem.
A buyer who has put a number on the problem compares your price to that number, not to competitors. That's pricing power.
This skill helps a founder name the 3 problems they solve better than anyone, down to the source, so the buyer names the cost and the founder leads the conversation instead of chasing it.

Method: `METHOD.md` in this repo. Inspired by Keenan's *Gap Selling* (Problem Identification Chart), rebuilt for founders.

## Modes

- `/pricing-power` or `/pricing-power build` → interview the user and write `my-pricing-power.md` (the chart + 9 questions).
- `/pricing-power test` + call notes or a transcript → mark each problem ✅/❌ and capture the buyer's own sentence.
- `/pricing-power hooks` → turn the chart and the collected sentences into headlines, cold-email openers and post hooks.

If a `my-pricing-power.md` already exists in the working directory, read it first and improve it instead of starting over.

---

## BUILD

Ask ONE question at a time. Wait for the answer. Keep your messages short.

**Step 0. Who.** "Who is your client? Who signs, what size, what's going on in their world right now?" One or two sentences is enough.

**Step 1. Spray.** "List every problem your clients have. Don't filter. Aim for 10." If they give fewer than 6, ask once: "What else do they complain about on calls?"

**Step 2. Focus.** Go through the list with the user and keep 3. A problem survives only if it passes all three filters. Ask about each candidate:
1. **Can you fix the source?** Not the symptom. If not, it's out, however real.
2. **Has a real client said it?** Ask for the sentence, or where they heard it. No sentence → keep it but mark 🔍 (verify on the next call). Never invent a quote.
3. **Does it cost real money or time?** If nobody would pay to make it stop, it's a complaint, not a problem.
If more than 3 survive, ask: "Which 3 would make a buyer move this month?"

**Step 3. Burn down.** For each of the 3, fill:
- **PROBLEM:** the client's words. Rewrite any seller-speak ("lack of pipeline visibility") into how a client would say it ("I never know which deals will close").
- **IMPACT:** money, time, feeling. Ask: "What does that cost them? What happens if nothing changes?"
- **SOURCE:** ask "and what causes that?" until the answer is something the user fixes. Stop there.
Challenge weak boxes. If the source is just the problem restated, or the impact is vague ("it's bad for growth"), push once more.

**Step 4. Questions.** Write one question per box, 9 in total:
- Problem → frustration question ("What's the frustration with X? What have you tried?")
- Impact → cost question ("What does that cost you? What if nothing changes in 6 months?")
- Source → a question that lets the BUYER discover the source. Never a statement, never a pitch. ("When the deal went quiet, what happened in the call before?")
Questions must be open, short, and not answerable by research. Never ask the buyer something you could look up.

**Step 5. Write `my-pricing-power.md`** in this format, then show it:

```
# Pricing Power: <company>
Client: <one line>

|   | PROBLEM (their words) | IMPACT | SOURCE |
|---|---|---|---|
| A | ... | ... | ... |
| B | ... | ... | ... |
| C | ... | ... | ... |

Can we fix the source?  A → <how>  B → <how>  C → <how>
Unverified (🔍): <list or "none">

## The 9 questions
A1 / A2 / A3, B1 / B2 / B3, C1 / C2 / C3

## Test log
| Date | Call | A | B | C | Their sentence |
```

Close with one line: "Run `/pricing-power test` after your next 3 calls."

---

## TEST

Input: call notes, a transcript, or the user's summary of a call.
For each of A, B, C:
- ✅ if the buyer described this problem (or its impact/source) **in their own words**. Quote the sentence exactly.
- ❌ if it came up and didn't land, or the buyer contradicted it.
- – if it didn't come up.
Append a row to the Test log in `my-pricing-power.md`. Replace a 🔍 with ✅ when a buyer confirms it.
**Rule:** a problem with 2 ❌ in a row and no ✅ gets flagged: "Swap B for the next problem from your Spray list?" Never fake a ✅; no quote, no ✅.
Also flag any NEW problem the buyer raised that isn't on the chart.

---

## HOOKS

Use only the chart and the real buyer sentences from the Test log. For each problem write:
- 1 headline / subject line (the buyer's words, short)
- 1 cold-email or DM opener (opens on their world, never on the product)
- 1 post hook
Never invent client quotes or numbers. Prefer ✅ sentences over the founder's own phrasing.

---

## Style

Short sentences. Plain words. Questions over statements. The founder stays in control of the conversation by diagnosing, not pitching.
