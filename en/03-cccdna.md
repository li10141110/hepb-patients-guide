# Ch 3 · cccDNA: The Virus's "Hard Drive"

> If you only read one chapter in this whole book, read this one.

---

## Why it deserves its own chapter

You've probably heard this line:

> **"The reason hepatitis B still isn't cured is because of cccDNA."**

That's not an exaggeration. This tiny 3.2 kb DNA molecule is the wall that every effort in the last 60 years of antiviral warfare has crashed into.

Once you understand it, you can understand:

- Why nucleoside drugs **can suppress the virus but you can't stop taking them**
- Why HBsAg **won't come down**
- Why "functional cure" is a compromise target
- Why new drugs must be **combination therapy**
- Why CRISPR is the direction the field is both most excited about and most cautious about

---

## What is it exactly

**cccDNA** = **c**ovalently **c**losed **c**ircular **D**NA.

Break the name apart:

- **Circular** — head-to-tail, like a rubber band
- **Covalently closed** — both strands complete, no nicks
- **Double-stranded** — standard double helix
- **Supercoiled** — twisted even tighter

An infected cell usually has **1 to 50** cccDNAs. Don't let the number fool you — **just one is enough to keep making virus**.

It **doesn't integrate into the human genome**. It sits in the nucleus like a tiny independent chromosome. Host histones wrap around it and add epigenetic modifications. So some people describe it like this:

> **cccDNA is like a "parasitic chromosome" inside the hepatocyte nucleus.**

---

## How it forms

Quick refresher: what HBV delivers into the nucleus is the incomplete **rcDNA**.

- Positive strand is incomplete
- Negative strand has an RNA primer and the viral polymerase hanging off the end
- The ends aren't connected

Turning rcDNA into cccDNA takes 5 repair steps inside the nucleus:

1. Remove the polymerase protein
2. Remove the RNA primer
3. Remove extra bases
4. Complete the positive strand
5. Ligate the gap

**Almost all of this work is done by the host's own DNA repair enzymes** (TDP2, FEN1, LIG1/3, etc.).

> 🧠 An interesting drug-target idea — if you can inhibit these repair enzymes, cccDNA can't form.
> The problem is the host uses these enzymes too, so you can't just switch them off.

Once formed, cccDNA is **an extremely stable molecule**.

---

## Why it's so hard to deal with

Three reasons:

**① It doesn't need to replicate itself**

Unlike HIV, which has to integrate, or RNA viruses that have to replicate frantically, cccDNA just sits quietly in the nucleus as a template. **As long as the hepatocyte is alive, cccDNA is alive.**

**② It replenishes itself**

Some of the new capsids **recycle back into the nucleus** and turn back into cccDNA. **That's the "refill mechanism" for the cccDNA pool.** Even if you knock some out, as long as replication hasn't fully stopped, the pool gets topped back up.

**③ Hepatocytes live a long time**

Hepatocyte turnover is roughly 200 days to a few years. And even when a cell divides, cccDNA can get split between the daughter cells.

**Result: cccDNA's half-life is measured in years.**

---

## Why nucleoside drugs can't touch it

This is where the most patients get confused — **I'm taking my pills every day, my DNA is undetectable, why am I not cured?**

Back to the life cycle:

```
cccDNA ──transcribe──> pgRNA ──reverse transcribe──> new DNA ──> new virus
                                                                   │
                                    recycle refill ←────────────────┘
```

Nucleoside drugs work at the **reverse transcription** step. They stop pgRNA from turning back into DNA, so new virions can't be built.

**But — cccDNA is already in the nucleus and doesn't need reverse transcription to exist.**
**And — cccDNA is still cranking out mRNA and HBsAg.**

So on nucleoside drugs you see:

- ✅ HBV DNA: undetectable
- ✅ ALT: normal
- ❌ HBsAg: **barely dropping**
- ❌ cccDNA: **still there**

**Stop the drug and cccDNA immediately restarts, the virus comes roaring back.**

That's the molecular answer to "why can't I stop the drug."

---

## Why HBsAg won't come down either

HBsAg has two sources:

1. **cccDNA transcription** (the classic source)
2. **Integrated DNA transcription** (see next chapter)

Even if you completely silence cccDNA, the integrated portion keeps making HBsAg.

**To get "HBsAg loss" (functional cure), you have to knock out both sources at the same time.**

---

## Five ways to try to get rid of it

**A. Silence it** — don't destroy it, just stop it from being transcribed. Epigenetic modifications, blocking transcription factors. Safe, but the moment the silencing lifts, the virus comes back.

**B. Cut it directly (CRISPR/Cas9)** — use gene editing to slice cccDNA. In theory, one-and-done, but delivery is hard and there's a risk of off-target damage to the host genome. Currently preclinical, a few phase I.

**C. Base editing** — no cutting, just precisely rewrite key bases to knock the viral genes out. Finer-grained, but further from the clinic.

**D. Block formation** — inhibit host repair enzymes so rcDNA can't become cccDNA. Side effects are the biggest worry.

**E. Let the infected cell die** — wake up the immune system to clear hepatocytes carrying cccDNA. That's the logic behind therapeutic vaccines and immunotherapy — don't hit the virus, **wake up the immune system**.

Problem: how many to kill? Could it trigger fulminant hepatitis? Needs careful control.

---

## Can I get my cccDNA measured?

Honest answer: **not clinically, no.**

- The only reliable way is **liver biopsy + specialized PCR** — invasive, small sample
- You can't measure cccDNA itself in blood
- But you can infer indirectly via **HBV RNA** or **HBcrAg** (hepatitis B core-related antigen) in the blood

In new drug trials, HBV RNA and HBcrAg are already used as surrogates for cccDNA activity. You'll see them all the time when reading phase 3 data.

---

## One-line summary

> **cccDNA is HBV's hard drive. Nucleoside drugs can only pull the power cord — they can't yank the drive. To really cure this, you have to wipe the drive.**

---

## 📍 Key Points

- cccDNA is the **covalently closed circular DNA** in the hepatocyte nucleus
- It's the transcription template for all HBV mRNAs, and the root of chronic infection
- Stable, self-replenishing, half-life in years
- Existing nucleoside drugs **cannot clear it**
- Five future paths to a cure: silence, cut, edit, block formation, immune clearance
- Currently, **HBV RNA / HBcrAg** are used as indirect readouts

---

**Further Reading**
- Nassal M. *HBV cccDNA: key obstacle for a cure*. Gut. 2015
- Allweiss L, Dandri M. *The Role of cccDNA in HBV Maintenance*. Viruses. 2017
- Lucifora J. et al. *Specific and nonhepatotoxic degradation of nuclear HBV cccDNA*. Science. 2014

> Next chapter → [Ch 4 · HBV DNA Integration: The Overlooked Other Half](./04-integration.md)
