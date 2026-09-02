# Week 8 Ops Review — Video Narration Script
**Target length:** ~15 minutes | **Slides:** 9 (see `Week8_Ops_Review_Slides.pdf`)
**Format:** Screen-record yourself presenting the slide deck (Loom, OBS, Zoom local recording, or PowerPoint "Record Slide Show")

**How to use this:** Open the slide PDF/PPTX and screen-share while you talk. Read this in your own voice — it's a scaffold, not something to recite word-for-word. Timings are approximate; adjust pace to fit 15 minutes total.

---

## Slide 1 — Title (0:00–0:30)

> "Good morning. Thank you for the time — I'm here to walk you through this quarter's Operations Review: where we stand on safety, equipment health, and supply chain performance across our Kenya depot network. I'll keep the headline up front, then go deeper into each area, and close with three concrete recommendations."

---

## Slide 2 — Executive Summary / BLUF (0:30–2:00)

> "Here's the bottom line up front. This quarter we found that one piece of equipment at Nairobi Depot — a single pump — has cost us an estimated $15.8 million in lost output this year. That's now fully root-caused and quantified, and we're recommending a funded pilot to fix it going forward, not just diagnose it.
>
> On the supply chain side, our demand forecasting is now accurate to within 4.4% — good enough to plan inventory against — and a properly sized safety-stock policy cuts simulated stockout days by roughly two-thirds.
>
> The ask today is straightforward: approve a sensor pilot on that one pump, and adopt the safety-stock policy across the network. I'll show you exactly why in the next few slides."

---

## Slide 3 — Equipment Health: The NBI-P03 Finding (2:00–4:00)

> "Starting with equipment health. Back in Week 5, we found that Nairobi Depot's throughput problem traces to one machine — NBI-P03 — not a site-wide issue. This isn't a hunch; it's statistically confirmed with a large, unambiguous effect size.
>
> We built an early-warning prototype that catches about 90% of bad shifts. But I want to be upfront about its limitation: it currently confirms a problem slightly before it's officially logged, rather than truly predicting it days in advance. The reason is simple — we don't have a real vibration or pressure sensor on this equipment yet, only indirect proxies like voltage and throughput.
>
> The number that matters here is on the right: 226,000-plus barrels lost annually, entirely attributable to this one pump. That's the size of the opportunity a real sensor retrofit unlocks."

---

## Slide 4 — Safety: Night-Shift Slip & Trip Risk (4:00–5:30)

> "Second safety finding, this one about people, not equipment. We identified 22 slip-and-trip incidents at Nairobi Depot this year, and 73% of them happened on the night shift, clustered at the transfer walkway.
>
> We didn't wait for this review to act — a safety alert went out to night-shift crews the same week we found this, with specific action steps, and a lighting and surface-condition inspection is underway now. We've also stood up a live HSE dashboard this quarter, so any site leader can filter incidents by site, date, and type in real time instead of waiting for a retrospective report like this one."

---

## Slide 5 — Supply Chain: Demand Forecasting (5:30–7:30)

> "Moving to supply chain. We built a demand forecasting model for Nairobi Depot that accounts for weekly patterns — weekends run lower — the mid-year seasonal peak, Kenyan public holidays, and known promotional periods.
>
> Tested against 45 days of real demand the model never saw during training, it comes in at 4.4% average error, with a day-to-day uncertainty of about 49 barrels. That 45-day horizon sits right in the middle of what we were asked to target. This isn't just a research exercise — that uncertainty number is exactly what feeds directly into the inventory policy on the next slide."

---

## Slide 6 — Supply Chain: Inventory Policy (7:30–9:30)

> "Here's where the forecast becomes an operational decision. We simulated two inventory policies over the same 180 days of actual demand — identical conditions, the only difference is whether we carry safety stock.
>
> Without it: 1.7% of days end in a stockout. With a safety stock of just 179 barrels — sized directly from our forecast uncertainty at a 95% service level — that drops to 0.6%. Same demand, same lead time, nearly a three-times reduction in stockout days, for a modest inventory increase. This is a small, quantified insurance policy, not padding."

---

## Slide 7 — Supply Chain: Distribution Optimization (9:30–11:00)

> "Last piece of the supply chain picture: how we allocate supply across all four depots — Nairobi, Mombasa, Kisumu, and Eldoret — at minimum shipping cost. Solving this as a linear program gives us a $24,978 weekly cost at the optimal allocation, meeting every depot's demand.
>
> One flag worth raising here: the terminal is running at almost full capacity today. There's very little slack. That's not a problem right now, but it means we have no buffer if demand spikes or if one depot needs more on short notice — something worth watching."

---

## Slide 8 — Strategic Recommendations (11:00–13:00)

> "That brings me to three recommendations, each with an estimated return.
>
> One: pilot vibration sensors on NBI-P03. This converts our reactive detector into a genuine early-warning system, days ahead instead of hours. The cost is modest — low five figures — against $15.8 million a year at risk.
>
> Two: adopt the 95% safety-stock policy depot-wide, not just at Nairobi. The carrying cost is small; the stockout reduction we demonstrated is large.
>
> Three: review terminal capacity headroom. We're at nearly 100% utilization with no buffer — I'd like a follow-up study on what it costs to build in some slack before that becomes a real constraint."

---

## Slide 9 — Q&A Simulation (13:00–15:00)

> "I'll leave time for questions, but I want to get ahead of one I expect: [pause, look at camera] 'Why do we need so much safety stock?'
>
> Here's my answer. That 179 barrels isn't a padded number — it's derived directly from our actual forecast error, 49 barrels a day, at a 95% service level, which is the standard industry balance between what it costs to hold extra inventory and what it costs to run out. In simulation, on our own real demand history, it cut stockout days roughly three-fold. The alternative isn't zero cost — it's paying for missed sales and rush orders instead of a small, quantified buffer we can size and defend with data.
>
> Happy to take other questions now."

---

## Delivery notes

- **Pacing:** ~15 minutes across 9 slides is roughly 100 seconds/slide on average — slides 3, 5, 6, and 8 carry the most content and deserve the most time; slides 1 and 9 can move faster.
- **If you're running long:** trim the "one flag worth raising" aside on Slide 7 — it's a good instinct but skippable under time pressure.
- **If you're running short:** add 20–30 seconds on Slide 6 walking through exactly how the 179-barrel number was calculated (Z-score × forecast std × √lead time) — CFOs respond well to seeing the math is simple, not a black box.
- **Camera:** look directly at camera for the Q&A slide's anticipated-question moment — it reads as confidence, not memorization, when you pause slightly before answering.
