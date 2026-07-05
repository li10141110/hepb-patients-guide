# Ch 7 · Why cccDNA Persists

> This is the ceiling for nucleoside drugs.

---

Chapter 3 covered what cccDNA is. This chapter tackles another question: **if it's so critical, why after 60 years is there still no drug that can wipe it out?**

---

## Triple defense

cccDNA is hard to clear not for one reason, but because **three layers of defense stack up**.

### Defense 1: it hides in the nucleus

Most drugs work in the **cytoplasm**. To hit the nucleus, a drug has to:

- Cross the cell membrane
- Cross the nuclear membrane
- Get near cccDNA
- Bind precisely

This pathway alone already knocks out lots of candidate drugs.

### Defense 2: it wears a "host chromatin" disguise

cccDNA in the nucleus isn't naked DNA. It's **wrapped in host histones**, just like human chromosomes.

Which means:

- To cut it, an enzyme has to recognize it first
- But it looks too much like human DNA, so friendly fire is easy
- Its epigenetic state can be "locked silent," but **locked isn't cleared**

### Defense 3: it has a "backup pool"

Even if you clear some, as long as:

- Some hepatocytes still have surviving cccDNA
- Replication hasn't fully stopped (pgRNA → new rcDNA → new cccDNA)

**The pool gets refilled.**

That's why "partial clearance" is meaningless — **as long as one cccDNA molecule is alive, the whole pool can rebuild in a few months**.

---

## Nucleoside drugs can only "lock the power switch"

Back to a diagram from Chapter 3:

```
cccDNA ──transcription──> pgRNA ──reverse transcription──> new DNA ──> new virus
                                                                          │
                                    replenishment loop ←──────────────────┘
```

Nucleoside analogs (ETV/TDF/TAF) act on **reverse transcription** — they stop pgRNA from turning back into DNA. New virus can't be assembled, and the **replenishment supply to the cccDNA pool gets cut**.

**In theory**, if replenishment is fully cut and hepatocytes turn over naturally, cccDNA should slowly get depleted.

**In reality** — the math says even with perfect viral suppression, cccDNA half-life is estimated at **over 10 years**. Meaning you'd have to take drugs for decades to potentially "drain" it.

And this model assumes:
- Drugs are 100% effective — unrealistic
- No replication slips through — unrealistic
- Hepatocytes turn over normally — but chronic HBV livers often have inflammation and fibrosis, and turnover works differently

So the real situation is — **nucleoside drugs can lower cccDNA count, but rarely to zero**.

---

## Then why does HBsAg sometimes turn negative?

A small fraction of long-term nucleoside users do achieve HBsAg seroconversion (functional cure).

But the yearly rate is very low — **about 0.3-1% per year**.

These "lucky ones" are usually:
- People whose baseline HBsAg was already low
- People whose immune system was already "on the edge of waking up"
- People whose T cells got activated during treatment for some reason (other infection, immune modulation)

**Nucleoside drugs don't actively clear cccDNA. They just give the immune system a "breather."**

The real work is still done by immunity.

---

## Can new-generation drugs directly take out cccDNA?

Look at the candidate approaches:

**A. siRNA / ASO** — hits mRNA, not cccDNA itself. cccDNA is still there, just "muted."

**B. Capsid Modulator** — blocks new virus assembly. In theory it can also cut replenishment. Still doesn't clear existing cccDNA.

**C. Entry Inhibitor** — blocks virus from infecting new hepatocytes. Prevents spread, but does nothing to cccDNA in already infected cells.

**D. Therapeutic vaccine / immunotherapy** — sends T cells to clear cells carrying cccDNA. **This is the indirect clearance approach**.

**E. CRISPR / base editing** — directly cut or rewrite cccDNA. **This is the only "direct removal" approach**, but still very early stage.

**All currently approved and Phase III drugs are neither D nor E.** They all "hit the surroundings" — lower HBsAg, cut replenishment, lock transcription — **hoping the immune system will clear cccDNA on its own after pressure eases**.

That's why "functional cure" is the realistic goal right now, and "total cccDNA clearance" is the long-term vision.

---

## An analogy

Think of HBV as an occupied factory:

- **Nucleoside drugs** = cut the factory's **power supply** (reverse transcription). Production stops, but the factory is still there.
- **siRNA/ASO** = cut the factory's **communication lines** (mRNA). Nobody takes orders, but the equipment's still there.
- **Capsid inhibitors** = tear down the factory's **assembly line** (assembly). Raw material warehouse is still there.
- **Therapeutic vaccine** = send in troops to clear the factory, **but the troops were previously ordered to sleep**.
- **CRISPR** = directly **blow up** the factory — but might take out the neighbor's house too.

**None of them is perfect on its own. Combined, they might actually make the factory disappear.**

That's why Chapter 21 focuses on **combination therapy**.

---

## 📍 Key Points

- cccDNA's triple defense: **hidden in the nucleus, host chromatin disguise, backup pool**
- Nucleoside drugs can only lock "replenishment," not directly clear
- In theory, long-term nucleoside use could drain cccDNA, but half-life is >10 years
- In reality, HBsAg seroconversion is only 0.3-1% per year
- All current drugs "hit the surroundings," relying on immunity to finish
- Only **CRISPR is the sole "direct removal" path**, still very early

---

**Further Reading**
- Werle-Lapostolle B. et al. *Persistence of cccDNA during natural history and NUCs*. Gastroenterology. 2004
- Boyd A. et al. *cccDNA kinetics during NUC therapy*. J Hepatol. 2016

> Next chapter → [Ch 8 · Where HBsAg Comes From](./08-hbsag-sources.md)
