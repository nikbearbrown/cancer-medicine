# Invasion: How Cancer Leaves Its Tissue

## Learning Objectives

After working through this chapter, you should be able to:

1. **Explain** why local invasion through the basement membrane is the molecular event that separates a curable *in situ* carcinoma from a potentially lethal invasive one.
2. **Describe** the epithelial-mesenchymal transition (EMT), identify its core molecular hallmark, and **trace** how the EMT transcription factors repress E-cadherin.
3. **Analyze** the miR-200/ZEB feedback loop and **explain** why double-negative feedback produces a bistable switch and an EMT spectrum.
4. **Relate** the matrix metalloproteinase (MMP)–TIMP balance to basement-membrane breach, and **evaluate** why broad-spectrum MMP inhibitors failed in clinical trials.
5. **Distinguish** the modes of cancer-cell migration (single-cell mesenchymal, amoeboid, collective) and **predict** which might evade a given anti-invasion strategy.

## Opening Case

A 49-year-old woman has a screening mammogram showing microcalcifications. Biopsy returns **ductal carcinoma *in situ* (DCIS)** — malignant epithelial cells filling a breast duct but contained entirely behind an intact basement membrane. Her five-year survival approaches 100%. She is, by any reasonable definition, curable.

Down the hall, a second woman with the same cell type — the same malignant epithelium — has a tumor in which a small fraction of cells have crossed the basement membrane and infiltrated the surrounding stroma. Her diagnosis is **invasive ductal carcinoma**, and a subset of those invasive cells may already be traveling. Her prognosis depends entirely on whether they have spread.

The genetics of these two tumors can be nearly identical. The cells look almost the same under the microscope. What separates a near-certain cure from a potentially fatal disease is a single discrete cellular *capacity*: the ability to invade — to detach, degrade the barrier in front, and crawl through tissue. Most cancer cells in any tumor cannot do this. They proliferate and pile up but stay put. A small minority — sometimes a handful in a tumor of ten million — acquire the machinery to leave. That minority is what kills patients. This chapter asks the question that organizes invasion biology: *what makes a cancer cell mobile?*

## Core Concepts

### The barrier that defines invasion

Most solid cancers arise from **epithelial** tissue — the cells that line surfaces (skin, gut, lung) and form glands (breast, prostate, pancreas). Epithelial cells are organized, polarized, and stationary. They have a defined **apical** surface (facing the lumen) and **basolateral** surface (facing neighbors and the basement membrane). They are glued to each other by **tight junctions**, **adherens junctions**, and **desmosomes**, and anchored to the **basement membrane** (a specialized extracellular-matrix sheet of type IV collagen, laminin, and nidogen) through **integrins** and hemidesmosomes. They form sheets that maintain organ architecture.

The basement membrane is the barrier. Epithelial cells normally never cross it. *Crossing it is the molecular event that defines the transition from in situ carcinoma to invasive carcinoma* — exactly the difference between the two patients in the opening case (Liotta, 1986). To cross, a cancer cell needs three capabilities, which the rest of this chapter develops in turn: it must loosen its attachments to its neighbors (EMT), degrade the matrix in its path (MMPs), and physically crawl (cytoskeletal reorganization).

### Epithelial-mesenchymal transition

**Mesenchymal cells** are the opposite of epithelial: loose, individually motile, lacking strict apical-basal polarity. Fibroblasts are the canonical example — they migrate through tissue and remodel matrix. The **epithelial-mesenchymal transition (EMT)** is a developmental program by which an epithelial cell sheds its epithelial character and acquires mesenchymal character (Thiery, 2002). EMT is essential and normal in embryogenesis — gastrulation, neural crest migration, and heart-valve formation all require it. *Cancers reactivate this developmental program inappropriately.* A cancer cell that undergoes EMT weakens its junctions, loses polarity, reorganizes its cytoskeleton, and gains migratory capacity. It can then detach from the mass and invade.

The molecular markers track the transition:

| Lost in EMT (epithelial) | Gained in EMT (mesenchymal) |
|---|---|
| E-cadherin (adherens-junction glue) | N-cadherin (weaker, dynamic adhesion) |
| Cytokeratins (epithelial filaments) | Vimentin (mesenchymal filament) |
| Claudins, occludins (tight junctions) | Fibronectin (matrix protein) |
| EpCAM (epithelial adhesion molecule) | Smooth-muscle actin (context-dependent) |

The single most consequential change is **loss of E-cadherin** — the molecular glue holding epithelial cells in organized sheets. Its cytoplasmic tail binds **β-catenin**, which links to the actin cytoskeleton. When E-cadherin is lost, two things happen at once: the cells lose tight cell-cell adhesion *and* the β-catenin that was tethered at junctions is freed to enter the nucleus and drive Wnt-pathway transcription of pro-proliferative, pro-invasive genes. So E-cadherin loss does not merely unstick cells — it actively signals (Thiery, 2002).

In some cancers, E-cadherin (*CDH1*) is mutated directly: about half of lobular breast carcinomas carry biallelic *CDH1* inactivation, and germline *CDH1* mutation causes hereditary diffuse gastric cancer. But in most EMT, E-cadherin is silenced by *transcriptional repression*, not mutation — the work of the EMT transcription factors.

<!-- → [DIAGRAM: epithelial cell → EMT → mesenchymal cell, showing junction disassembly, E-cadherin→N-cadherin cadherin switch, β-catenin release to the nucleus, and acquisition of migratory front-back polarity] -->

### The EMT transcription factors

A small family of transcription factors switches EMT on by repressing E-cadherin and activating mesenchymal genes:

- **SNAI1 (Snail) and SNAI2 (Slug)** — zinc-finger factors that bind E-boxes in the *CDH1* promoter and recruit chromatin-modifying complexes to silence E-cadherin.
- **ZEB1 and ZEB2** — zinc-finger E-box-binding factors that repress E-cadherin and activate vimentin. They are central to cancer EMT and form the feedback loop described below.
- **TWIST1 and TWIST2** — basic helix-loop-helix factors driving E-cadherin repression in many cancers.

These factors are induced by a convergence of upstream signals: **TGF-β** (the dominant inducer in many contexts, acting through SMAD transcription factors), **Wnt** (through β-catenin), **Notch**, **receptor tyrosine kinases** (EGFR, HGF/MET, FGF, PDGF acting through Ras-MAPK and PI3K-AKT), and **hypoxia** (through HIF-1α — linking back to the angiogenesis chapters: the same hypoxia that drives VEGF also drives EMT). *EMT is not a single signal but a convergence.* In a tumor with stromal TGF-β, outpaced blood supply causing hypoxia, and oncogenic kinase signaling, EMT is multiply driven, and individual cells transition asynchronously — producing a heterogeneous pool, some of which acquire metastatic capacity.

### Partial EMT and the EMT spectrum

The textbook binary — fully epithelial flips to fully mesenchymal — has been refined. Most cancer cells undergoing EMT *in vivo* achieve only **partial EMT**: they keep some epithelial features (residual E-cadherin, cytokeratin) while gaining mesenchymal ones (vimentin, motility, invasiveness). And the partial-EMT cells appear to be *the most metastatic* (Nieto et al., 2016). Why? They retain enough adhesion to migrate as small protected clusters rather than lone cells, and they retain the **plasticity** to reverse course — to undergo **mesenchymal-epithelial transition (MET)** and re-epithelialize at a distant site, which is required to seed and grow a metastasis.

The mechanism enforcing intermediate states is the **miR-200/ZEB double-negative feedback loop**. The microRNA family **miR-200** represses **ZEB1/2**; ZEB1/2 in turn represses miR-200 transcription. Two mutual repressors create a **bistable switch**: the system settles into either high-miR-200/low-ZEB (epithelial) or low-miR-200/high-ZEB (mesenchymal), resisting intermediate noise — but tunable, by the strength of incoming EMT signals, into stable *partial* states. This is why EMT behaves as a *spectrum* rather than a toggle, confirmed by single-cell RNA sequencing showing many coexisting EMT states within one tumor.

### Matrix metalloproteinases and ECM degradation

To pass through tissue, a cell must chew through the **extracellular matrix (ECM)** — the dense protein-and-polysaccharide network filling tissue (collagen, laminin, fibronectin, proteoglycans). The enzymes that degrade it are the **matrix metalloproteinases (MMPs)** — a family of 23 zinc-dependent proteases. Key players in invasion: the **gelatinases MMP-2 and MMP-9** (which cleave the type IV collagen of the basement membrane) and the **membrane-type MT1-MMP (MMP-14)** (anchored in the cell surface to degrade matrix right where the cell touches it).

MMPs are secreted as inactive **zymogens** and activated by cleavage (MT1-MMP activates MMP-2; plasmin activates others). Their activity is opposed by **tissue inhibitors of metalloproteinases (TIMPs)**. *The MMP–TIMP balance determines net matrix proteolysis at any location.* In tumors, the balance shifts hard toward proteolysis: cancer cells overexpress MMP-2, MMP-9, and MT1-MMP, and tumor-associated fibroblasts and macrophages add more. MMP-9 is upregulated in essentially every invasive cancer; beyond cutting type IV collagen, it *releases ECM-bound growth factors* (TGF-β, VEGF, FGF), feeding further EMT, angiogenesis, and immunosuppression — so the protease that opens the path also amplifies the signals that drive invasion.

<!-- → [FIGURE: invasion through the basement membrane — an invadopodium concentrating MT1-MMP and MMP-2/9 at the cell surface, cleaving type IV collagen, with TIMPs shown opposing and the MMP–TIMP balance tipped toward proteolysis] -->

**The cautionary tale.** Broad-spectrum MMP inhibitors (marimastat, batimastat, prinomastat) were taken to phase 3 trials in the 1990s–2000s. *All failed* (Coussens et al., 2002). The reasons: musculoskeletal toxicity (from blocking MMPs needed for normal tissue homeostasis), poor pharmacokinetics, and — critically — *timing*: by the time cancer is clinically detected, MMP-driven invasion has usually already happened. The field largely abandoned broad-spectrum inhibitors. This is a recurring lesson in cancer medicine: a mechanism can be genuinely necessary for the disease and still be a poor drug target, because of where it also operates and when in the disease course it acts.

### Cytoskeletal reorganization and modes of migration

A cell that has loosened its junctions and degraded its matrix still has to *move*. Migration is a coordinated cycle: **polarization** (front-back asymmetry), **protrusion** (actin polymerization pushing the leading edge forward — broad **lamellipodia** via the Arp2/3 complex, finger-like **filopodia** via formins), **adhesion** (new integrin-mediated **focal adhesions** to the matrix), **contraction** (myosin II pulling the cell body forward), and **rear retraction**. The **Rho-family GTPases** coordinate it: Cdc42 (filopodia), Rac1 (lamellipodia), RhoA (rear contraction). In cancer cells this machinery is hyperactivated, and cells form specialized **invadopodia** — actin-rich protrusions that concentrate MT1-MMP and drill through the matrix. Invadopodia are the cellular drilling apparatus for breaching barriers, regulated by Src kinase and the Tks5 scaffold.

Cancer cells invade in distinct modes, and the distinction matters therapeutically:

- **Single-cell mesenchymal invasion** — lone cells using integrin traction, invadopodia, and MMPs. Classical EMT-driven invasion.
- **Amoeboid invasion** — cells squeeze through tissue by actomyosin contractility *without* needing matrix proteases. Faster than mesenchymal migration. *This mode can evade MMP-inhibitor therapy entirely* — a partial explanation for why blocking proteolysis is not enough.
- **Collective invasion** — cohorts move together keeping cell-cell contacts; leader cells acquire EMT features and drive, follower cells stay epithelial. Common in breast, colon, and head-and-neck cancer.

These modes are not fixed; a single tumor can use several, and cells can switch between them — which is precisely why a therapy aimed at one mode often fails to stop invasion.

## Worked Example

**Situation.** A drug developer reasons as follows: invasion requires cancer cells to degrade the basement membrane; MMPs do that degradation; MMP-9 is upregulated in essentially every invasive cancer. Therefore a potent MMP-9 inhibitor should block invasion and improve survival in patients with established invasive cancer. They design a phase 3 trial in advanced disease. Predict the outcome and explain it mechanistically.

**Reasoning.** The first two premises are correct — MMPs are genuinely required for matrix breach, and MMP-9 is genuinely overexpressed. So the temptation is to predict success. *The dead end:* "necessary mechanism therefore good target" skips two questions the chapter has flagged. First, *where else does the target work?* MMPs are needed for normal tissue homeostasis (wound healing, bone remodeling, immune function), so systemic inhibition will produce off-tumor toxicity — historically, musculoskeletal pain severe enough to limit dosing. Second, *when in the disease does the mechanism act?* Invasion through the basement membrane happens early — typically long before the cancer is clinically detectable. In a patient with *advanced* disease, the invasive cells have already crossed barriers and disseminated; inhibiting the protease now is closing the gate after the herd has left.

There is a third problem the developer ignored: even at the right time, cancer cells can switch to **amoeboid migration**, squeezing through tissue without proteases at all, bypassing the drug's entire mechanism.

**Resolution.** The trial fails — which is exactly what happened to marimastat, batimastat, and prinomastat (Coussens et al., 2002). The drug engages its target, but the target's normal roles cause toxicity, its critical window has passed, and an alternative migration mode routes around it.

**The lesson.** A mechanism can be necessary for a disease and still be a bad drug target — because of where else it works, when it acts, and whether the cell has a bypass.

**The limit.** The failure of *broad-spectrum* MMP inhibition does not prove MMPs are untargetable. Selective inhibitors of specific MMPs, or anti-MT1-MMP strategies deployed earlier in the disease, remain under investigation; the conclusion is about a class and a clinical setting, not about the mechanism's validity `[verify — selective-inhibitor outcomes still emerging]`.

## Common Misconceptions

**"An *in situ* carcinoma is just an early invasive cancer that hasn't grown yet."** The DCIS patient in the opening case shows why this is wrong. The difference is not size or time — it is a discrete *capacity*: whether cells have crossed the basement membrane. An *in situ* lesion can be large; an invasive lesion can be tiny. What changes prognosis is the breach of the barrier, not the bulk of the tumor.

**"EMT is a one-way switch from epithelial to mesenchymal."** The miR-200/ZEB bistable loop and the partial-EMT data refute this. Cells occupy a *spectrum*, and the most metastatic cells are the *partial* ones — precisely because they keep the plasticity to reverse (MET) and re-epithelialize at the distant site. A cell locked fully mesenchymal cannot seed a metastasis. Reversibility is the point.

**"Cancer cells invade as lone wolves."** Often they move as cohesive groups — collective invasion with leader and follower cells — and circulating clusters are far more efficient at metastasis than single cells (a thread the next chapter picks up). The lone-mesenchymal-cell image is one mode among several, and not the most dangerous one.

**"If MMPs are necessary for invasion, blocking them must help patients."** The worked example and the failed phase 3 trials are the direct counter. Necessity of a mechanism does not imply a good drug — the target's normal roles, its timing in the disease, and the cell's bypass routes (amoeboid migration) all defeated the obvious inference. This is the same proxy-versus-truth discipline from the therapy chapters: target engagement is not clinical benefit.

## Exercises

1. **(Understand)** State, in one sentence, the single molecular event that distinguishes invasive carcinoma from carcinoma in situ, and name the barrier involved.

2. **(Apply)** A breast tumor shows loss of E-cadherin with no mutation in *CDH1*. Propose the most likely mechanism of E-cadherin loss, name two transcription factors that could mediate it, and explain what happens to the β-catenin released from the disassembled junctions.

3. **(Apply/Analyze)** A patient's tumor is treated with a selective MT1-MMP inhibitor, yet invasion continues in tissue-culture invasion assays. Propose a migration mode that could explain continued invasion despite protease blockade, and explain why that mode does not require MMP activity.

4. **(Produce — mechanism map)** Draw the miR-200/ZEB double-negative feedback loop. Show the two mutual-repression arrows, label the epithelial and mesenchymal stable states, and annotate where a strong, sustained TGF-β signal would push the system. In one sentence, explain why this loop produces a *spectrum* of states rather than a binary toggle.

5. **(Produce — invasion checklist)** Build a three-row "capabilities" chart for invasion (loss of adhesion; matrix degradation; motility). For each row, name the key molecules involved and one candidate therapeutic strategy, and mark with a note which strategy a switch to amoeboid migration would defeat.

## What Would Change My Mind

The chapter's central claim is that invasion is an acquired, discrete cellular capacity — crossing the basement membrane via loss of adhesion, matrix degradation, and motility — and that this capacity, not tumor bulk, separates curable from lethal disease. The finding that would force revision: convincing, repeated demonstration that clinically lethal metastatic spread routinely occurs *without* any loss of epithelial adhesion, without matrix-degrading proteolysis, and without acquired motility — for instance, if cells were shown to disseminate passively in large numbers and seed distant organs while remaining fully epithelial and immotile, with no enrichment for invasion-associated programs in the cells that succeed. The discovery that EMT is *dispensable* for metastasis in some models already pushes on the "EMT is required" sub-claim and is why this chapter frames EMT as one route to motility rather than the only one. But the broader claim — that some acquired migratory/invasive capacity distinguishes the cells that kill — would need genuinely passive, capacity-free metastasis to fall.

## Still Puzzling

- **Is EMT strictly required for metastasis?** Some mouse models report metastasis proceeding with EMT genetically blocked, while EMT-positive cells still dominate the disseminating population in others. The evidence does not yet cleanly distinguish "EMT is required" from "EMT is one common route among several." This unsettles how aggressively to target EMT therapeutically.

- **Why did selective MMP inhibition not obviously rescue the failed class?** If broad-spectrum failure was mostly about toxicity and timing, well-timed selective inhibitors should help — yet clear wins have been slow to appear. Whether the limit is timing, redundancy among proteases, or migration-mode switching is unresolved.

- **What governs the switch between migration modes?** Cells move between mesenchymal, amoeboid, and collective modes, but we cannot yet predict or reliably control the switch. A therapy that blocks one mode may simply select for another — the central reason invasion has resisted targeting, and a thread that runs straight into the metastasis chapter.

## References

- Liotta, L. A. (1986). Tumor invasion and metastases — role of the extracellular matrix: Rhoads Memorial Award lecture. *Cancer Research*, 46(1), 1–7.
- Thiery, J. P. (2002). Epithelial-mesenchymal transitions in tumour progression. *Nature Reviews Cancer*, 2(6), 442–454.
- Nieto, M. A., Huang, R. Y.-J., Jackson, R. A., & Thiery, J. P. (2016). EMT: 2016. *Cell*, 166(1), 21–45.
- Coussens, L. M., Fingleton, B., & Matrisian, L. M. (2002). Matrix metalloproteinase inhibitors and cancer: trials and tribulations. *Science*, 295(5564), 2387–2392.
- National Cancer Institute. Types of Cancer Treatment. https://www.cancer.gov/about-cancer/treatment/types

## Prompts

<!-- This section is populated automatically by the Cowork enrichment
     pass. Each D3 figure generated in this chapter gets an entry here:
     the figure number, a short title, and a ready-to-paste prompt
     that produces a close approximation of that figure. -->

*No figures have been generated for this chapter yet.*
