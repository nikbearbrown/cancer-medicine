# Tumor Immunology: Surveillance, Antigens, and the Immune Response

## Learning Objectives

By the end of this chapter, you should be able to:

- **Explain** the cancer immunoediting framework (elimination, equilibrium, escape) and **evaluate** the experimental and clinical evidence that supports each phase (Dunn et al., 2002; Shankaran et al., 2001).
- **Distinguish** the major categories of tumor antigen — tumor-specific versus tumor-associated — and **predict**, for a given antigen, what normal tissue toxicity an immune response against it would cause.
- **Trace** the adaptive anti-tumor response from dendritic-cell antigen capture through cytotoxic T-cell killing, **identifying** at each step where tumors interrupt the chain (Chen & Mellman, 2013).
- **Analyze** why tumor mutational burden correlates with neoantigen load and immune visibility, and **assess** the limits of mutational burden as a predictor of immune control.
- **Compare** the killing mechanisms of CD8+ T cells, natural killer cells, and macrophages, and **justify** which effector matters most for an MHC-low tumor.

## Opening Case

A 34-year-old woman receives a kidney transplant and begins lifelong immunosuppression to keep her body from rejecting the graft. Eight years later she develops a melanoma on her forearm. When the pathologist examines the tumor and the surrounding tissue, something is strange: the cancer is unusually advanced for its short clinical history, and her oncologist notes that melanomas in transplant recipients tend to behave more aggressively than in patients with intact immune systems. More striking still, a review of her donor's records reveals that the organ donor had a history of melanoma treated fifteen years earlier and declared cured. The recipient's melanoma is donor-derived. Cells that her donor's immune system had apparently been holding silent for over a decade — never eliminated, never grown — began to expand once they were transplanted into a body whose immune defenses were deliberately switched off.

Nothing about the tumor cells changed. What changed was the surveillance around them. The case raises the question this chapter is built on: if an immune system can hold cancer cells in check for fifteen years, what is it recognizing, how is it recognizing it, and why does that recognition eventually fail?

## Core Concepts

### Immunosurveillance: the body patrols for transformed cells

The plain-language claim is old and intuitive: the immune system continuously inspects the body's cells and destroys the ones that have turned cancerous before they ever become tumors. Paul Ehrlich gestured at the idea in 1909; Lewis Thomas and Macfarlane Burnet gave it modern form in the 1950s and 1970s (Burnet, 1970). The formal term is **immunosurveillance** — the hypothesis that the immune system recognizes and eliminates transformed cells, so that clinically detectable cancer represents a *failure* of that surveillance.

The hypothesis was contested for decades because the evidence was indirect. It became hard to dismiss when mouse genetics let researchers remove specific immune components and watch what happened. Mice lacking functional T and B cells (RAG2-knockout), or lacking the interferon-γ response, or lacking perforin, developed spontaneous and carcinogen-induced tumors at dramatically elevated rates (Shankaran et al., 2001). Remove the watchers and the cancers appear. In humans the same pattern emerges from the clinic: transplant recipients and people with HIV/AIDS have substantially elevated rates of cancer — most dramatically the virally driven ones (Kaposi sarcoma, certain lymphomas, HPV-related cancers), where the immune system is containing both the cancer cell and the virus that drives it.

<!-- → [DIAGRAM: cancer immunoediting — the three Es, showing a population of transformed cells being eliminated, a subset held in equilibrium, and a resistant clone escaping into clinical tumor] -->

### Immunoediting: elimination, equilibrium, escape

The modern refinement of immunosurveillance is **cancer immunoediting** (Dunn et al., 2002), which describes a dynamic, three-phase relationship between the immune system and a developing cancer:

- **Elimination.** The immune system recognizes and destroys most transformed cells before they form a tumor. This is classical immunosurveillance.
- **Equilibrium.** Some cells survive elimination by acquiring partial resistance. They are not destroyed, but they are held in check by ongoing immune pressure — dormant or slow-growing, sometimes for years or decades. This is the phase the transplant case made visible: the donor's cells sat in equilibrium for fifteen years.
- **Escape.** Eventually, a variant acquires changes that let it evade immune pressure entirely. It expands into a clinically detectable cancer. Escape is what we are seeing whenever we diagnose a tumor.

The word "editing" carries the key idea. Immune pressure is a selection force. By killing the most visible cells, the immune system sculpts the surviving population toward invisibility — so the tumor that finally escapes is, almost by definition, one that has been shaped to evade the very system that was containing it. This reframes a diagnosis: the cancer you can see is the one that won an evolutionary contest you never knew was happening.

### What makes a cancer cell visible: tumor antigens

For the immune system to attack a cell, the cell must look different. A **tumor antigen** is any molecule on a cancer cell that the immune system can recognize as a target. Antigens fall into two broad classes that differ in a way that matters enormously for therapy.

**Tumor-specific antigens (TSAs)** exist only on cancer cells, never on normal cells. They are the cleanest targets because an immune response against them cannot damage healthy tissue. Two important sources:

- **Viral antigens.** Cancers transformed by oncogenic viruses often express viral proteins — the E6/E7 oncoproteins of HPV in cervical and oropharyngeal cancer, EBV antigens in certain lymphomas and nasopharyngeal carcinoma. These proteins are genuinely foreign.
- **Neoantigens** — antigens arising from cancer-specific mutations. A point mutation that changes one amino acid can produce a peptide the immune system has never encountered. Neoantigens are tumor-specific and personal to each patient's tumor (treated in detail below).

**Tumor-associated antigens (TAAs)** are expressed on cancer cells *and* on some normal cells, usually at lower levels or in restricted contexts. Targeting them can drive an anti-tumor response, but at the risk of collateral damage to normal tissue. Subtypes include **cancer-testis antigens** (e.g., NY-ESO-1, MAGE-A1) normally restricted to germ cells, which Lloyd Old's group helped define (Chen et al., 1997); **differentiation antigens** such as tyrosinase in melanocytes, CD19/CD20 in B cells, or PSA in prostate; and **overexpressed antigens** such as HER2, present at low levels normally but at high density in amplified cancers.

The practical lesson is a single question you can ask of any antigen: *what normal tissue shares this target?* The answer predicts the toxicity. Attack CD19 and you lose normal B cells (survivable). Attack a protein your heart also expresses and you may not survive it.

### Neoantigens and central tolerance

Neoantigens are central to modern immunotherapy because of a deep feature of how T cells are educated. During development in the thymus, T cells whose receptors strongly recognize the body's own peptides are deleted — this is **central tolerance**, and it is why a healthy immune system does not attack its own tissues. Self-peptides include every normal protein. A neoantigen, by contrast, was never present during thymic education, so T cells capable of recognizing it survive selection. Neoantigens can therefore be attacked without first overcoming tolerance — they are foreign in the only sense that matters to a T cell.

Neoantigen supply scales with **tumor mutational burden (TMB)**, the number of mutations in a tumor's genome. More mutations mean more chances to produce a novel peptide. Cancers with high TMB — melanomas with a UV mutational signature, smoking-related lung cancers, microsatellite-instability-high (mismatch-repair-deficient) tumors, POLE-mutant cancers — generate many neoantigens. Pediatric cancers and many hematological cancers generate few. This is the mechanistic root of why high TMB tends to predict response to immune-releasing therapy (the subject of the next chapter): more mutations, more neoantigens, more potential T-cell targets.

### The adaptive anti-tumor response, step by step

When the immune system mounts an effective response, the central killers are CD8+ **cytotoxic T lymphocytes (CTLs)**. The sequence — sometimes drawn as the *cancer–immunity cycle* (Chen & Mellman, 2013) — runs:

<!-- → [DIAGRAM: the cancer-immunity cycle — antigen release, dendritic cell capture, priming in the lymph node, T-cell trafficking, infiltration, and killing, drawn as a loop] -->

1. **Antigen capture.** Dendritic cells in the tumor take up antigen from dying cancer cells and process it — proteasome-degraded fragments onto MHC class I (for CD8+ cells), endosome-degraded fragments onto MHC class II (for CD4+ cells).
2. **Migration and maturation.** The antigen-loaded dendritic cell travels to a lymph node and matures, raising its MHC, its co-stimulatory molecules (CD80/CD86), and its cytokines.
3. **Priming.** The dendritic cell presents to T cells. Activation needs two signals: *signal 1*, the antigen–MHC complex binding the T-cell receptor; *signal 2*, co-stimulation through CD28 binding CD80/CD86. (Cytokines such as IL-12 provide a third.) Without signal 2, the T cell goes anergic rather than active — a fact the next chapter will show tumors exploit.
4. **Expansion and trafficking.** Activated T cells proliferate massively, then leave the node and follow chemokine gradients (CXCL9/10/11) back to the inflamed tumor.
5. **Killing.** The CTL recognizes its antigen on MHC class I on the cancer cell and kills it — through perforin/granzyme (punching pores and delivering apoptosis-inducing enzymes) and through death receptors (FAS ligand, TRAIL). One CTL can kill many targets.
6. **Memory.** Most effectors die; a few become long-lived memory cells.

The chain is robust when intact, but every link is a place a tumor can cut.

### Innate immunity and the MHC-loss trap

Not all anti-tumor killing is antigen-specific. **Natural killer (NK) cells** kill through the same perforin/granzyme machinery as CTLs but recognize targets differently. NK cells use **missing-self recognition**: they attack cells that have *downregulated* MHC class I. This matters because MHC downregulation is exactly the trick some tumors use to hide from CTLs — and in doing so they expose themselves to NK cells. NK cells also use **stress-ligand recognition**, attacking cells displaying stress-induced ligands (MICA, MICB, ULBPs) common on transformed cells. Macrophages, dendritic cells, the complement system, and inflammasomes round out the innate contribution. The interplay matters: innate immunity initiates and amplifies inflammation, and adaptive immunity depends on innate co-stimulation to function.

## Worked Example

**Situation.** A research team studies two patient tumors of the same histologic type. Tumor A responds vigorously to therapy that releases T-cell brakes; Tumor B does not respond at all. Both have abundant T cells in the blood. The team wants to know why B is resistant.

**Reasoning — first attempt (a dead end).** The obvious hypothesis: Tumor B must have fewer neoantigens — lower mutational burden, fewer targets. The team sequences both. To their surprise, Tumor B has a *higher* mutational burden than Tumor A and a longer predicted neoantigen list. By the TMB-predicts-response logic, B should respond better, not worse. The mutational-burden explanation fails. This is the trap of treating a correlation as the whole mechanism: TMB predicts response *on average across populations*, but it is upstream of many steps, any one of which can break the chain in an individual tumor.

**Reasoning — second attempt.** The team stops asking "are there targets?" and walks the cancer–immunity cycle link by link. Step 1–2 (antigen capture, dendritic-cell migration): intact. Step 3 (priming): intact — both patients have circulating tumor-reactive T cells, so priming happened. Step 4 (trafficking): here the difference appears. Tumor A is densely infiltrated with CD8+ T cells in contact with cancer cells. Tumor B has plenty of T cells stacked at its margin but almost none inside — an **excluded** phenotype. The T cells are present, primed, and competent; they simply cannot reach the cancer cells, blocked by dense matrix and an abnormal vasculature that fails to display the right chemokines.

**Resolution.** Tumor B is resistant not because it lacks targets but because it lacks *access*. The relevant lesion is in step 4 (trafficking and infiltration), not in antigen supply. A therapy that only releases T-cell brakes will do little for B, because the brakes were never the limiting problem — the limiting problem is a wall.

**The lesson.** Immune control is a chain of sequential steps; the limiting step, not the average potential, decides the outcome. Find the broken link before choosing the intervention.

**The limit.** Identifying the excluded phenotype tells you *where* the chain breaks, not *how* to fix it. Converting an excluded "cold" tumor into an infiltrated "hot" one remains only partly solved, and which combination accomplishes it for a given patient is unsettled [contested — see pantry flag].

## Common Misconceptions

**"A strong immune system simply prevents cancer, so people who get cancer must have weak immune systems."** Plausible, and partly true — immunocompromised people do get more cancer. But immunoediting shows the relationship is not a simple strong/weak axis. A perfectly competent immune system can hold a tumor in equilibrium for years and still lose, because immune *pressure* selects for immune *evasion*. The donor in the opening case was not immunodeficient; her immune system was containing the melanoma successfully for fifteen years. The cancer escaped not because surveillance was weak but because surveillance was strong enough to edit the tumor toward invisibility. Strength and eventual failure are not opposites here.

**"Cancer cells look like normal cells, so the immune system can't tell them apart — that's why cancer grows."** This conflates two different things. Many cancer cells *do* display recognizably abnormal antigens — especially neoantigens from mutations, which are genuinely foreign. The problem in an escaped tumor is usually not that there is nothing to see but that the tumor has actively suppressed the seeing: downregulated MHC, recruited regulatory cells, engaged checkpoint brakes. The transplant case is the cleanest disproof — the cells were the same; only the surveillance was removed, and the cancer grew.

**"More mutations always means a more immune-visible, more treatable tumor."** Tumor mutational burden correlates with neoantigen load and, on average, with immune visibility — but the worked example shows why "always" fails. TMB sits at the top of a long chain. A high-TMB tumor that excludes T cells, or downregulates MHC, or saturates checkpoints, can be more immune-resistant than a lower-TMB tumor with an open, infiltrated microenvironment. TMB is a useful population-level predictor, not a guarantee for the individual.

## Exercises

1. **(Recall/Understand.)** State the three phases of cancer immunoediting and give one line of evidence for each. For the equilibrium phase, explain why the opening case (donor-derived melanoma) is specifically evidence *for* equilibrium rather than for elimination or escape.

2. **(Apply.)** For each of the following antigens, name the normal tissue (if any) that shares the target and predict the on-target toxicity of an immune response against it: (a) HPV E7, (b) CD19, (c) tyrosinase, (d) HER2, (e) a private neoantigen from a missense mutation. Rank them from cleanest target to most dangerous and justify the ranking.

3. **(Apply+.)** A tumor has high mutational burden but does not respond to brake-releasing immunotherapy. Walk through the cancer–immunity cycle and propose three distinct mechanistic explanations, each located at a *different* step of the cycle. For each, state one observation (something you could measure on a biopsy or blood sample) that would confirm or rule it out.

4. **(Produce.)** Design a one-page decision aid for a tumor board that takes a tumor's immune phenotype as input ("hot/infiltrated," "excluded," "cold/desert") and outputs the most likely *limiting step* in the cancer–immunity cycle plus the category of intervention that addresses it. Include at least one place where your aid should say "uncertain — needs more data" rather than giving an answer.

5. **(Apply.)** A tumor evades CD8+ T cells by downregulating MHC class I. Explain why this strategy is double-edged, name the innate effector it exposes the tumor to, and describe the recognition mechanism that effector uses.

## What Would Change My Mind

The central claim of this chapter is that immunoediting — immune pressure selecting tumors toward evasion — is a real and general driver of the cancer the immune system fails to contain, not merely a description of immunodeficiency. The cleanest finding that would force a revision: a large, prospective study of immunocompetent patients showing that the tumors which eventually escape are *not* enriched for immune-evasion features (intact MHC, no checkpoint-ligand upregulation, no antigen loss relative to early lesions) compared with tumors held in equilibrium — in other words, evidence that escaped tumors are no more "edited" than contained ones. If escape turned out to be unrelated to acquired immune-evasion phenotypes, the editing model would lose its core mechanistic content and reduce to a restatement that immunodeficiency raises cancer risk.

## Still Puzzling

- How long can a human tumor genuinely persist in equilibrium, and what tips a stable equilibrium into escape? The transplant cases prove decades are possible, but the trigger remains obscure.
- Why do some tumors with abundant neoantigens still fail to prime any detectable T-cell response, even before evasion mechanisms engage? Is the failure in antigen processing, dendritic-cell function, or something we have not named?
- Tumor mutational burden predicts response on average, yet individual high-TMB tumors fail and some low-TMB tumors respond. What additional features (clonality of neoantigens? the specific MHC alleles a patient carries?) would convert a population-level correlation into an individual-level prediction? This is genuinely unsettled.

## References

- Burnet, F. M. (1970). The concept of immunological surveillance. *Progress in Experimental Tumor Research*, 13, 1–27.
- Chen, D. S., & Mellman, I. (2013). Oncology meets immunology: the cancer-immunity cycle. *Immunity*, 39(1), 1–10.
- Chen, Y.-T., et al. (1997). A testicular antigen aberrantly expressed in human cancers detected by autologous antibody screening (NY-ESO-1). *Proceedings of the National Academy of Sciences*, 94(5), 1914–1918.
- Dunn, G. P., Bruce, A. T., Ikeda, H., Old, L. J., & Schreiber, R. D. (2002). Cancer immunoediting: from immunosurveillance to tumor escape. *Nature Immunology*, 3(11), 991–998.
- Shankaran, V., Ikeda, H., Bruce, A. T., et al. (2001). IFNγ and lymphocytes prevent primary tumour development and shape tumour immunogenicity. *Nature*, 410(6832), 1107–1111.
- Ehrlich, P. (1909). Ueber den jetzigen Stand der Karzinomforschung. *Nederlandsch Tijdschrift voor Geneeskunde*, 5, 273–290.

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
