## ⑦ Cite verifiable sources

**Definition** — A source needs **organisation, date, document name and link**. An anonymous source is not a source but a **source grade**, and when anonymous becomes named, readers take the unverifiable for the confirmed.

**Measured frequency** — **19 cards (18%)**.

### Why

The quietest distortion in coverage is **source-grade promotion**.

```
"a source close to Tencent said, on background"
        ↓ in the article
"a Tencent official explained that ..."
```

The original also carried "Tencent has not responded officially". Drop that and the company appears to have admitted it. So this principle is not satisfied by adding a link: it requires **stating the nature of the source**.

### Source grades

| Grade | Example | How to treat it |
|---|---|---|
| Primary document | court filing, regulator decision, disclosure | quote directly |
| Official statement | company/institution release | quote as *the company's claim* |
| Peer-reviewed paper | journal publication | quote with sample and conditions |
| Self-published report | vendor/researcher posts own results | mark **not peer-reviewed** |
| Anonymous source | "according to people familiar" | treat as unconfirmed |
| No source | "a survey found" (no org/sample) | do not quote |

### Three check questions

1. Is there a link to the original — and does opening it say the same thing?
2. Is the source **official, anonymous, or self-reported**?
3. For numbers: is there a **polling organisation, sample and date**?

### Real case

> 「Chinese AI agents swept Alibaba's map service」 (AI Times, 2026-10-15) — [original](https://www.aitimes.com/news/articleView.html?idxno=216284)

The article states **"a Tencent official explained that the work was an evaluation of third-party models' web-browsing ability."**

**What is wrong**
- The original wording is a **"source close to Tencent"** speaking on background; the [independent report](https://swarmcha.se/posts/chinese-agent-fleet-full-report) records "Tencent has not responded officially". → **the source grade was promoted one step.**
- The researchers wrote they are **"deeply uncertain about what model was being evaluated"**, and some agents called themselves "claude" — a claim the researchers rejected. [The Decoder](https://the-decoder.com/researchers-tracked-down-a-rogue-fleet-of-chinese-ai-agents-in-the-wild-and-actually-talked-to-it/) notes the self-labelling was never verified. The Korean piece drops this caveat.
- The report is a **self-published report by an independent team, not peer-reviewed** — and the article never says so.

**Corrected**

> According to a report published on 2026-10-14 by the independent team SwarmChasers, AI agents running in a Tencent Cloud sandbox requested data from Alibaba's Amap more than 2,600 times between 2026-09-28 and 2026-10-08. **Most attempts failed**, and no breach of non-public systems was found. The researchers said they are **"deeply uncertain"** which model was evaluated. An anonymous source close to Tencent linked the run to a separate evaluation team; **Tencent issued no official response.** The report is **not peer-reviewed**.

### Correction formula

> `Source: [organisation] "「document」" ([date], [grade: primary/official/self-reported/anonymous]) — [link]`
> `Anonymous speech is labelled "a source close to X", together with "X has not responded officially".`