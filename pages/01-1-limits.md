## ③ Disclose technical limits

**Definition** — A number or a performance claim means nothing without **task, comparison set, conditions and data range**. Remove any one of them and the number is advertising, not information.

**Measured frequency** — cited in **29 of 107 cards (27%)**, the most common failure.

### Why

Benchmark scores are products of a *measurement design*. The same model re-ranked by a different evaluation harness produces a different order. Coverage keeps "first", "record", "surpasses humans" and drops the conditions. Readers memorise the number and quote it again.

| Missing element | What the reader loses |
|---|---|
| Task | what was actually measured (writing? coding? proof?) |
| Comparison set | what it beat (7th on the full leaderboard, 1st inside a vendor's table) |
| Conditions | whether it can be reproduced (prompt, attempts, model version) |
| Data range | where it applies (was the test set in training data?) |

### Three check questions

1. Which **task** produced this number, and what is it compared **against**?
2. Does the same benchmark's **independent leaderboard** show the same rank?
3. What does the source say the model **still cannot do**?

### Real case

> 「Z.ai unveils legal model 'GLM-Legal'」 (AI Times, 2026-10-12) — [original](https://www.aitimes.com/news/articleView.html?idxno=216260)

Domestic coverage reported a **19.17% pass rate** on the Harvey LAB benchmark, ahead of Claude Fable 5 (11.25%) and Kimi K3 (12.92%).

**What is wrong** — 19.17% is a figure inside the vendor's own table. On the same benchmark's independent leaderboard ([Vals AI, 79 systems](https://codepress.dev/benchmarks/harvey-lab)) the model sits **7th**. The same model was reported as 23.58%, 11.7% and 6.67% under three different harnesses. "First" is a narrowed comparison set, and the article omits the counter-evidence.

**Corrected**

> Z.ai released its legal-specialised model 'GLM-Legal' on 2026-10-12. Its vendor-reported Harvey LAB task pass rate is 19.17%, above Claude Fable 5 (11.25%) and Kimi K3 (12.92%) in the same table. **On the Vals AI leaderboard (79 systems) it ranks 7th, and ranking changes with the evaluation harness.**

### Correction formula

> `On [date], [organisation] released [model]. Its [benchmark] [metric] is [number], above [comparison]. However, on [independent board / other conditions] the result is [different], and [what it still cannot do] is not disclosed.`

Do not delete the number. **Attach the condition to it.**