# Ch 4 · HBV DNA Integration: The Overlooked Other Half

> cccDNA is the main culprit. Integrated DNA is the "mole."

---

## A fact many patients don't know

If you only read popular articles, you've probably heard of cccDNA, but **you haven't heard of integration**.

Even some clinicians skip integration as a detail.

But in the last five years the field has gotten more and more sure of this:

> **After long-term antiviral treatment, most of the HBsAg in your blood is no longer coming from cccDNA. It's coming from HBV DNA that has integrated into the host genome.**

Read that again. This one sentence determines: **why HBsAg is so hard to drop, and what the new drugs actually have to target.**

---

## HBV isn't HIV. How does it integrate?

Good question.

Strictly speaking, HBV **has no integrase**. It doesn't insert precisely into the genome like HIV does.

But integration still happens, just by a different mechanism:

- **HIV integration** — has its own integrase, inserts precisely
- **HBV integration** — **accidental event**, host DNA repair (NHEJ) "patches" a linear HBV DNA fragment into the genome

This "accident" actually **happens a lot** in hepatocytes.

Hepatitis, oxidative stress, cell division — they all create double-strand breaks in the host genome, and during repair HBV gets pulled in.

An infected person's liver can have **10⁷ to 10⁹ integration sites**.

---

## What actually gets integrated?

What gets integrated is **not the complete viral genome**. It's **fragments**.

The region that gets integrated most often is **the S gene** (which encodes HBsAg). So:

- Integrated DNA **can keep making HBsAg**
- But **can't make a complete virion** (missing pgRNA, C region, P region)

In other words:

> **Integrated DNA is a factory that "only makes HBsAg, not virus."**

That explains a strange pattern — many long-term treated patients have:

- HBV DNA: undetectable
- HBeAg: negative
- HBsAg: **still positive, and stubbornly refuses to drop**

**That stubborn HBsAg is very likely coming from integration.**

---

## cccDNA vs integrated DNA

![Comparing the two sources](../assets/cccdna-vs-integration-zh.svg)

| Dimension | cccDNA | Integrated DNA |
|------|--------|---------|
| Location | Independent minichromosome in nucleus | Embedded in host genome |
| Completeness | Complete | Fragmented (often missing C/P) |
| Can make virus? | Yes | **No** |
| Can make HBsAg? | Yes | **Yes** |
| Copies | 1-50 per cell | 10⁷-10⁹ per liver |
| Nucleoside drugs | ❌ ineffective | ❌ ineffective |
| **siRNA / ASO** | ✅ **effective** | ✅ **equally effective** |
| CRISPR | ✅ theoretically feasible | ⚠️ high risk of damaging host |

**Remember those bottom-right rows** — that's the key to understanding why new drugs can do what the old drugs can't.

---

## Why siRNA / ASO can "hit both sources"

siRNA and ASO target **not DNA, but mRNA**.

Whether the mRNA comes from cccDNA or integrated DNA, as long as the sequence matches (the HBV S region sequence is the same), siRNA/ASO can recognize and degrade it.

**That's their killer feature — they hit everything.**

It's also why in clinical trials, siRNA/ASO monotherapy can knock HBsAg down by 2-3 logs — something nucleoside drugs can't do.

See chapters 22 and 23 for more.

---

## Integration's other hidden danger: liver cancer

Integration also brings a more serious problem — **hepatocellular carcinoma (HCC)**.

Three mechanisms:

**① Disrupting tumor suppressors or activating oncogenes**

If HBV happens to integrate near key genes like TERT (telomerase promoter), MLL4, or CCNE1, it can disrupt them and push the cell toward cancer.

**② Continuous HBx protein expression**

Fragmented integration often **preserves the X region**. HBx protein can:
- Promote proliferation
- Suppress apoptosis
- Interfere with DNA repair
- Reprogram epigenetics

**It's one of the core drivers of HBV-related liver cancer.**

**③ Genome instability**

Massive numbers of integration sites mean massive insertional mutations — the hepatocyte genome becomes "fragile."

Result:
- Annual liver cancer rate in untreated chronic HBV: ~0.5-1%
- In cirrhotic patients: up to 3-8% per year
- **Even after the virus is fully suppressed, the cancer risk from integration remains**

That's why liver cancer surveillance **can't stop** even after "functional cure."

---

## When does integration start?

The old belief was that integration was a late-stage thing in chronic infection.

**Research in the last five years has changed that — integration starts in the acute phase of infection**, and can be detected within weeks of infection.

Meaning: even if a newly infected person starts treatment early, **some hepatocytes have already been "marked."**

So "the earlier you treat, the better" isn't just about protecting liver function — it's also about **shrinking the integration pool**.

---

## Can we get rid of integrated DNA?

Honest answer: **not right now.**

Directions being explored:

**A. Let infected cells die** — immunotherapy + therapeutic vaccine, wake up T cells. Problem: too many cells; clearing them all at once would cause liver failure.

**B. Silence transcription of integrated DNA** — epigenetic modifications targeting HBx and the S promoter. No clinical-grade drug yet.

**C. Long-term suppression** — use siRNA/ASO to keep integrated DNA "silent." Needs lifelong treatment, but closer to cure than nucleoside drugs.

**D. Precise CRISPR** — with 10⁷ integration sites, this is **way harder than editing cccDNA**.

---

## Why this chapter matters

Back to the opening line: **after long-term treatment, HBsAg comes mostly from integrated DNA.**

Once you get that, you can understand:

1. **Why the old drugs will never clear HBsAg** — they never targeted integration in the first place
2. **Why siRNA/ASO is revolutionary** — they target mRNA, so they hit both sources
3. **Why "functional cure" is a pragmatic goal** — clearing integration itself is too hard
4. **Why liver cancer surveillance can't stop after HBsAg loss** — the genome damage from integration is permanent

This chapter is **a mental turning point** — it changes the angle you look at future drugs from.

---

## 📍 Key Points

- HBV has no integrase; integration is a **host DNA repair "accident"**
- Integration happens early in infection, up to 10⁷-10⁹ sites
- Integrated DNA **doesn't make virus but keeps making HBsAg**
- After long-term treatment, HBsAg's main source **shifts from cccDNA to integrated DNA**
- **siRNA/ASO is the only mechanism that "hits both sources"**
- Integration is closely tied to liver cancer; even after HBsAg loss, cancer surveillance continues

---

**Further Reading**
- Tu T. et al. *HBV DNA Integration*. Viruses. 2021
- Podlaha O. et al. *Genomic Modeling of HBV Integration Frequency*. PLoS ONE. 2019
- Johns Hopkins. *Transcription of HBsAg shifts from cccDNA to integrated HBV DNA during treatment*. 2025

> Next chapter → [Ch 5 · Global and Chinese Epidemiology](./05-epidemiology.md)
