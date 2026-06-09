# Cancer Immunotherapy: Releasing the Immune System on Cancer

## Learning Objectives

By the end of this chapter, you should be able to:

- **Explain** the two-signal model of T-cell activation and **describe** how CTLA-4 and PD-1/PD-L1 act as inhibitory checkpoints at distinct steps (Leach et al., 1996; Ishida et al., 1992).
- **Contrast** the mechanism of checkpoint blockade — which acts on the immune system — with that of drugs that act directly on cancer cells, and **justify** why this logic produces durable responses in some patients (Hodi et al., 2010).
- **Analyze** why CAR-T therapy succeeds in B-cell malignancies but struggles in solid tumors, **identifying** the specific biological features responsible (Maude et al., 2014).
- **Evaluate** the relationship between immune-related adverse events and anti-tumor response, and **assess** what that relationship reveals about the mechanism.
- **Distinguish** "hot" from "cold" tumors and **predict**, from a tumor's immune phenotype, whether checkpoint blockade alone is likely to help.

## Opening Case

A 52-year-old man is diagnosed with metastatic melanoma that has spread to his liver and lungs. Two decades earlier, this diagnosis would have meant a median survival measured in months; chemotherapy did almost nothing. He is started on a combination of two antibodies — one blocking CTLA-4, one blocking PD-1. Neither antibody touches his cancer cells. Within weeks he develops severe diarrhea and a rash; bloodwork shows his thyroid is inflamed and his liver enzymes are climbing. His oncology team pauses the drugs and gives high-dose corticosteroids. On the next set of scans, the liver and lung metastases have shrunk dramatically. Three years later he remains disease-free, off all therapy.

Two facts about this case sit uncomfortably together. The drugs that saved him never attacked his tumor — they attacked the brakes on his own T cells. And the toxicity that nearly derailed treatment, the autoimmune-like inflammation of his gut and thyroid, was not an unrelated side effect but a signature of the very mechanism that worked. This chapter is about that strange therapeutic logic: treating the immune system to treat the cancer, and paying for it in autoimmunity.

## Core Concepts

### The two-signal model and the idea of a checkpoint

Recall from the previous chapter that a T cell needs two signals to activate. **Signal 1** is the antigen–MHC complex binding the T-cell receptor; it provides specificity. **Signal 2** is co-stimulation — the receptor CD28 on the T cell binding CD80/CD86 on an antigen-presenting cell; it provides the "go." A T cell that receives signal 1 without signal 2 does not activate; it goes anergic. This design protects against autoimmunity by requiring a second confirmation before a T cell commits to killing.

An **immune checkpoint** is an inhibitory receptor on a T cell that, when engaged, dampens or terminates activation. Its normal job is **peripheral tolerance** — preventing activated T cells from attacking healthy tissue once they have left the lymph node. Checkpoints are brakes, and they are essential; remove them entirely and you get autoimmune disease. The therapeutic insight, which won the 2018 Nobel Prize for James Allison and Tasuku Honjo, is that *tumors press these same brakes to escape T-cell attack.* Release the brake, and the existing anti-tumor T cells can do their work.

### CTLA-4 and PD-1 act at different steps

Two checkpoints anchor current therapy, and they are not redundant — they act at different points in the cancer–immunity cycle.

**CTLA-4** (cytotoxic T-lymphocyte-associated protein 4) appears on activated T cells and on regulatory T cells. It competes with CD28 for CD80/CD86, binding with higher affinity, and so it steals signal 2. Its dominant effect is to limit *priming* in the lymph node — it sets the threshold for which T cells get activated in the first place. James Allison's group showed in 1996 that blocking CTLA-4 with an antibody caused established tumors to regress in mice (Leach et al., 1996), the founding experiment of the field.

**PD-1** (programmed death-1) appears on activated and **exhausted** T cells. Its ligand **PD-L1** is expressed broadly — including on tumor cells and tumor-associated macrophages, often induced by the very interferon that infiltrating T cells produce. PD-1 engagement inhibits T-cell effector function in *peripheral tissue*, including inside the tumor. So its dominant effect is to suppress the *killing* step, late in the cycle, rather than priming. Tasuku Honjo's group identified PD-1 in 1992 (Ishida et al., 1992); the receptor–ligand axis was later shown to be a major tumor escape route.

The practical consequence: CTLA-4 blockade widens the pool of T cells that get activated; PD-1/PD-L1 blockade lets already-primed T cells keep killing once they reach the tumor. Blocking both attacks the cycle at two separate points — which is why the combination is more potent, and more toxic, than either alone.

<!-- → [DIAGRAM: checkpoint blockade mechanism — CTLA-4 stealing CD80/86 from CD28 during priming in the lymph node, versus PD-1 engaging PD-L1 to shut down killing in the tumor; antibodies blocking each] -->

### Checkpoint blockade: the clinical reality

The therapeutic strategy is **checkpoint blockade** — monoclonal antibodies that bind an inhibitory receptor or its ligand and prevent the off signal.

- **Ipilimumab** (anti-CTLA-4) was approved in 2011 for metastatic melanoma, the first checkpoint inhibitor and the first drug ever to extend overall survival in that disease (Hodi et al., 2010). Response rates were modest (roughly 15–20%), but a subset of responders achieved durable remissions — the famous flat "tail" on the survival curve, suggesting some patients were functionally cured.
- **Nivolumab** and **pembrolizumab** (both anti-PD-1) followed in 2014, with **atezolizumab**, **durvalumab**, and others (anti-PD-L1) after. **Relatlimab** (anti-LAG-3) was approved in 2022 with nivolumab for melanoma — the first checkpoint combination beyond CTLA-4.

Across these drugs, FDA approvals now span more than 20 cancer types, including a *tumor-agnostic* approval for microsatellite-instability-high tumors regardless of where they arise. But response is far from uniform. Hodgkin lymphoma responds in roughly 65–75% of patients; melanoma in 30–45% with single-agent anti-PD-1; "cold" tumors such as pancreatic cancer and microsatellite-stable colorectal cancer respond in under 5%. The pattern is informative: tumors that are **"hot"** — high mutational burden, high PD-L1, pre-existing T-cell infiltration — tend to respond; **"cold"** tumors — low mutation burden, low PD-L1, few infiltrating T cells — tend not to. Checkpoint blockade releases brakes on T cells that are already present and primed. If those T cells were never there, releasing the brake does nothing.

### Combinations and the logic behind them

Single agents are limited, so combinations dominate practice. **Ipilimumab + nivolumab** in melanoma raises response rates to roughly 60% and five-year survival above 50% — but at a steep cost: about 55% of patients suffer grade 3–4 immune-related toxicity, versus about 20% with nivolumab alone. **Anti-PD-1 + chemotherapy** is now first-line in lung, triple-negative breast, and head-and-neck cancer; chemotherapy kills cancer cells immunogenically, releasing antigen. **Anti-PD-1/L1 + anti-angiogenic agents** normalize tumor vasculature and relieve VEGF-driven immunosuppression. Each combination is chosen by mechanism — what compensatory escape route the first drug leaves open, and what the second closes.

### CAR-T: rebuilding the T cell instead of releasing it

Checkpoint blockade works only if competent anti-tumor T cells already exist. **Adoptive cellular therapy** takes a different route — remove a patient's T cells, modify them, and return them. The leading form is **CAR-T**: chimeric antigen receptor T cells. A patient's own T cells are engineered to express an artificial receptor — the **chimeric antigen receptor** — built from an antibody-derived antigen-binding domain fused to intracellular T-cell signaling domains. When the CAR binds its target on a cancer cell, it triggers killing *directly, without MHC presentation.*

That last point is the crux. CAR-T bypasses several evasion mechanisms from the previous chapter: it needs no MHC class I (so MHC-downregulated tumors are still vulnerable), no professional antigen presentation, no normal priming.

**Tisagenlecleucel** (anti-CD19), approved in 2017 for B-cell acute lymphoblastic leukemia, produced complete-response rates around 80% in heavily pretreated children who had exhausted every other option (Maude et al., 2014). Anti-CD19 products for lymphoma and anti-BCMA products for multiple myeloma followed.

<!-- → [DIAGRAM: CAR-T workflow — leukapheresis, genetic engineering of the chimeric receptor, ex vivo expansion, reinfusion, and direct MHC-independent killing of a CD19+ cell] -->

### Why CAR-T works in blood cancers and stalls in solid tumors

The success in B-cell malignancies is not luck — it reflects features that happen to be ideal for CAR-T:

- The target (CD19) is on essentially *all* the malignant cells, so there is no antigen-negative subclone to escape.
- CD19 is also on normal B cells — but losing your normal B cells is survivable (immunoglobulins can be replaced). The on-target/off-tumor toxicity is acceptable.
- The cancer cells are in blood and lymphoid organs, physically accessible to the infused cells.

Solid tumors violate all three. Their antigen expression is **heterogeneous**, so a single-target CAR misses antigen-negative subclones. Few solid-tumor antigens are truly cancer-specific, so candidate targets are also on critical normal tissue, making on-target/off-tumor toxicity severe. And the solid-tumor microenvironment — dense matrix, immunosuppressive signals, hypoxia, nutrient depletion — physically blocks infiltration and exhausts the cells that do get in. No CAR-T product for solid tumors is yet approved.

CAR-T also carries distinctive toxicities. **Cytokine release syndrome (CRS)** — a flood of cytokines from massively activated cells — causes fever, hypotension, and hypoxia, treated with the anti-IL-6-receptor antibody tocilizumab. **Immune effector cell-associated neurotoxicity syndrome (ICANS)** ranges from confusion to seizures. Both are predictable and manageable in specialized centers, and acceptable given the benefit in approved settings.

### Other cellular therapies and vaccines, briefly

**TIL therapy** expands a patient's own tumor-infiltrating lymphocytes — cells that have already recognized tumor antigens — and reinfuses them; lifileucel was the first approved (2024, melanoma). **TCR-T** engineers T cells with an MHC-restricted receptor, allowing it to target *intracellular* antigens that get processed and presented. **Personalized neoantigen vaccines** sequence a patient's tumor, predict its neoantigens, and manufacture a peptide or mRNA vaccine to prime T cells against them; a randomized trial of an mRNA neoantigen vaccine (mRNA-4157) plus pembrolizumab improved recurrence-free survival over pembrolizumab alone in melanoma (Weber et al., 2024). The pairing is mechanistically natural: the vaccine creates new T-cell responses, and the checkpoint inhibitor keeps the tumor from shutting them off.

## Worked Example

**Situation.** Two patients have the same metastatic cancer. Patient 1's tumor has high mutational burden, strong PD-L1 staining, and dense CD8+ T-cell infiltration on biopsy. Patient 2's tumor has low mutational burden, no PD-L1, and almost no T cells inside. Both are offered single-agent anti-PD-1. The team must predict who benefits and decide what to do for the other.

**Reasoning — first attempt (a dead end).** The team's instinct is that anti-PD-1 is a powerful drug with approvals across 20+ cancers, so both patients should get it and the more advanced patient (Patient 2, more symptomatic) should be prioritized. But this treats the drug as if it acted on the cancer cell. It does not. Anti-PD-1 releases the PD-1 brake on T cells that are *already inside the tumor*. The question is not "how aggressive is the cancer?" but "are there primed T cells present for the drug to unleash?" Prioritizing by tumor aggressiveness is the wrong axis.

**Reasoning — second attempt.** The team reads each tumor against the hot/cold framework. Patient 1 is textbook **hot**: high mutational burden means abundant neoantigens, PD-L1 expression means the tumor is actively pressing the PD-1 brake (so there is a brake to release), and the dense CD8+ infiltrate means the T cells are already there. Releasing PD-1 should let them kill. Patient 2 is **cold**: few neoantigens, no PD-L1, and — decisively — no T cells inside. Releasing a brake on T cells that were never recruited accomplishes nothing.

**Resolution.** Patient 1 is the strong candidate for single-agent anti-PD-1. Patient 2 is unlikely to benefit from anti-PD-1 alone; the limiting problem is not an engaged brake but an *absent* T-cell response. A rational path for Patient 2 is a strategy aimed at *generating* a response — chemotherapy or radiation to release antigen, a combination to recruit T cells, or a different modality entirely — not monotherapy that presumes T cells are waiting.

**The lesson.** Checkpoint blockade releases a brake; it does not build a car. Predicting benefit means asking whether primed T cells already exist in the tumor, not how dangerous the tumor is.

**The limit.** The hot/cold framework predicts *populations* well but misfires on individuals: some PD-L1-negative tumors respond and some PD-L1-high tumors do not, because PD-L1 staining, mutational burden, and infiltration are imperfect, partly redundant proxies for a complex state. Which biomarker, or combination, best selects responders remains unsettled [contested — see pantry flag].

## Common Misconceptions

**"Immunotherapy is a kind of chemotherapy that's gentler on the patient because it's natural."** This misunderstands the mechanism on two counts. Checkpoint inhibitors are not gentler chemotherapy — they do not poison dividing cells at all; they release inhibitory brakes on T cells. And they are not necessarily gentle: the opening case shows life-threatening colitis, hepatitis, and thyroiditis. The toxicity profile is *autoimmune*, not cytotoxic, precisely because the mechanism is to override peripheral tolerance.

**"If a tumor has lots of mutations, checkpoint blockade will work."** High mutational burden raises the *odds* of response because it generates neoantigens — but the worked example shows why it is not sufficient. Checkpoint blockade also requires that primed T cells be present in the tumor and that the relevant brake (e.g., PD-L1) actually be engaged. A high-mutation tumor that excludes T cells, or relies on a checkpoint your antibody doesn't block, can still resist. Mutational burden is one input to a multi-step prediction, not the answer.

**"The autoimmune side effects mean the drug is harming the patient and the dose is wrong."** Tempting, and clinically you do manage severe toxicity aggressively. But mechanistically the immune-related adverse events arise from the same overriding of tolerance that produces the anti-tumor effect — and patients who develop some immune-related toxicity tend, on balance, to have *better* tumor responses. The autoimmunity is the cost of the mechanism, not a sign the mechanism has gone astray. In the opening case, the inflamed gut and thyroid traveled alongside the shrinking metastases, not against them.

## Exercises

1. **(Understand.)** Explain why blocking CTLA-4 and blocking PD-1 are not redundant. In your answer, locate each checkpoint's dominant effect on the cancer–immunity cycle (priming vs. killing) and predict why the combination is both more effective and more toxic than either alone.

2. **(Apply.)** A patient's tumor biopsy shows MHC class I downregulation across nearly all cancer cells. You are choosing between (a) anti-PD-1 checkpoint blockade and (b) CD19-directed CAR-T (assume the tumor expresses CD19). Which is mechanistically more likely to work, and why does MHC loss favor one over the other?

3. **(Apply+.)** A solid tumor expresses a candidate antigen at high levels. Before designing a CAR-T against it, list the three solid-tumor obstacles from this chapter (heterogeneity, on-target/off-tumor toxicity, the microenvironment) and, for each, describe one specific piece of evidence you would gather to estimate whether this particular antigen and tumor can overcome it.

4. **(Produce.)** Write the explanation a clinician would give a patient starting ipilimumab + nivolumab, covering in plain language: how the drugs work (no jargon-free pass on "they don't attack the cancer directly"), why new diarrhea or a thyroid problem must be reported immediately, and why such side effects are not necessarily a reason to despair about whether the drug is working. Keep it under 250 words.

5. **(Apply.)** Personalized neoantigen vaccines are being tested *in combination* with checkpoint inhibitors rather than alone. Using the cancer–immunity cycle, explain the mechanistic rationale for pairing them, naming the step each component addresses.

## What Would Change My Mind

The central claim of this chapter is that checkpoint blockade works by *releasing brakes on pre-existing, primed anti-tumor T cells* — which is why "hot," infiltrated tumors respond and "cold," T-cell-poor tumors do not. The finding that would force a revision: a well-powered trial showing durable checkpoint-blockade responses in genuinely cold tumors — tumors verified before treatment to have no neoantigen-specific T cells anywhere in the patient, no tumor infiltrate, and no PD-L1 — at rates comparable to hot tumors. If responses did not require a pre-existing T-cell response, the "release the brake on T cells already there" model would be wrong, and we would need a mechanism by which the antibodies generate anti-tumor immunity de novo. The mutational-burden and infiltration correlations make this unlikely, but a clean negative result would overturn the framework.

## Still Puzzling

- Why do some patients sustain remission for a decade after stopping therapy while others with apparently identical tumors relapse? The determinants of the durable "tail" on the survival curve are not understood.
- Can a cold tumor be reliably converted to a hot one? Many strategies are tested — radiation, chemotherapy, oncolytic viruses, intratumoral agents — but no general, predictable method exists yet. This is genuinely unsettled.
- The immune-related-adverse-event-versus-response correlation is real but imperfect. Is anti-tumor immunity mechanistically separable from autoimmune toxicity, or are they two faces of one process that cannot be uncoupled?
- Why has CAR-T's MHC-independent killing not translated to solid tumors despite the apparent advantage? Is the microenvironment the dominant barrier, or is antigen heterogeneity the deeper problem?

## References

- Hodi, F. S., O'Day, S. J., McDermott, D. F., et al. (2010). Improved survival with ipilimumab in patients with metastatic melanoma. *New England Journal of Medicine*, 363(8), 711–723.
- Ishida, Y., Agata, Y., Shibahara, K., & Honjo, T. (1992). Induced expression of PD-1, a novel member of the immunoglobulin gene superfamily, upon programmed cell death. *EMBO Journal*, 11(11), 3887–3895.
- Leach, D. R., Krummel, M. F., & Allison, J. P. (1996). Enhancement of antitumor immunity by CTLA-4 blockade. *Science*, 271(5256), 1734–1736.
- Maude, S. L., Frey, N., Shaw, P. A., et al. (2014). Chimeric antigen receptor T cells for sustained remissions in leukemia. *New England Journal of Medicine*, 371(16), 1507–1517.
- Weber, J. S., Carlino, M. S., Khattak, A., et al. (2024). Individualised neoantigen therapy mRNA-4157 (V940) plus pembrolizumab versus pembrolizumab monotherapy in resected melanoma (KEYNOTE-942). *The Lancet*, 403(10427), 632–644.

## Prompts

<!-- This section is populated automatically by the Cowork enrichment
     pass. Each D3 figure generated in this chapter gets an entry here:
     the figure number, a short title, and a ready-to-paste prompt
     that produces a close approximation of that figure.

     Prerequisites: paste CLAUDE.md and DESIGN.md from the brutalist/
     folder before each prompt, or load them into your Claude project
     context once and reference them by name.
-->

*No figures have been generated for this chapter yet.*
