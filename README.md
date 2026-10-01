# Pricing Power

**Win bigger deals at the price you want. Start with the problem, not the price.**
A free Claude Code skill (and a one-page method) for B2B founders who want to lead the sales conversation instead of chasing it.

Three problems. Three columns. Nine questions. About 20 minutes. 🐬

You know the call. The buyer is friendly, nods along, asks for a proposal.
Then nothing.

It usually isn't the price. The buyer never said out loud what the problem costs them, or where it really comes from. So there was nothing pulling them to a yes.

Buyers don't buy your product. They buy their way out of a problem.
A buyer who has put a number on the problem compares your price to that number. Not to your competitors. That's pricing power. 🐯

Know the 3 problems you solve better than anyone, down to the source, and every call gets calmer. You ask. They talk. They name the cost themselves. Your price stops looking big, and you're in control from the first minute.

---

## The chart

|   | 1. PROBLEM (in their words) | 2. IMPACT (what it costs them) | 3. SOURCE (what really causes it) |
|---|---|---|---|
| **A** | | | |
| **B** | | | |
| **C** | | | |

- **Problem:** what the client says. Their sentence, not your diagnosis.
- **Impact:** money, time and how it feels. If nobody would pay to make it stop, it's a complaint.
- **Source:** the real cause underneath. The one thing that, fixed, makes the problem go away.

A problem only makes the chart if it passes the filter:
✅ you can fix the source · ✅ a real client said it · ✅ it costs real money or time.

Full method, the 5 steps and the 8 Steps mapping: [METHOD.md](./METHOD.md)

---

## Install

```bash
git clone https://github.com/SimonTheSalesBooster/pricing-power
cp pricing-power/pricing-power.md ~/.claude/commands/
```

**Build your chart (once per offer):**
```
/pricing-power
```
Claude interviews you, one question at a time, and writes `my-pricing-power.md`: your 3 problems, down to the source, plus 9 discovery questions.

**Test it after calls:**
```
/pricing-power test
[paste call notes or a transcript]
```
Each problem gets ✅ (the buyer said it in their own words, quoted) or ❌. Two ❌ in a row, swap it out.

**Turn it into copy:**
```
/pricing-power hooks
```
Headlines, cold-email openers and post hooks, built from the sentences your buyers actually said. 🌴

---

## What's in the repo

| File | What it is |
|---|---|
| `pricing-power.md` | The skill (build, test, hooks) |
| `METHOD.md` | The method on one page |
| `pricing-power-template.md` | Blank chart to fill in by hand |
| `examples/strategy-sprints.md` | Our own chart, with our 9 questions |

---

## Standing on Keenan's shoulders

Pricing Power is inspired by Keenan's *Gap Selling* and his Problem Identification Chart. Great book, read it.
We kept the core (problem, impact, root cause) and rebuilt it for founders, around what readers and practitioners struggle with:

- **Max 3 problems.** Discovery stays a conversation, not an interrogation.
- **Every problem needs a real client quote.** No "I know your problem better than you."
- **Solvability filter.** If you can't fix the source, it's off the chart.
- **The output is questions, not a pitch.** The buyer names the source.
- **✅/❌ after every call.** Your own evidence, problem by problem.
- **Built once per offer.** Not a form to fill for every deal.

---

## Who made this

**[Strategy Sprints](https://www.strategysprints.com)**, Simon Severino. We help B2B founders take control of sales. 2,400+ founders have gone through our programs. Before that, Simon coached 2,000+ teams, including Google, BMW and Airbus.

Pricing Power is the homework. The conversation is the 8 Steps of the Repeatable Sale: Problem feeds Step 2 (Frustration), Impact feeds Steps 3 and 4 (Importance, Cost of Inaction). Homework done, you walk in calm and stay in control. That's what we train. 🐬

Want more skills like this one, plus our sales tools and a community of founders using them?
Join the **Sprint Club**: https://www.strategysprints.com

Ready to accelerate now? Book a Discovery Call: https://calendly.com/strategysprint/discovery-call

Happy hunting.
Simon & The Sprinters 🐬⚡️🐆

---

## License

[Apache-2.0](./LICENSE)
