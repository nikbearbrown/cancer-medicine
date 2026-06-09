# Angiogenesis: The Tumor's New Blood Supply

## Learning Objectives

After working through this chapter, you should be able to:

1. **Explain** why solid tumors cannot grow beyond roughly one to two millimeters in diameter without recruiting new blood vessels, and **relate** this physical constraint to the concept of tumor dormancy.
2. **Trace** the HIF-1α–VEGF feedback loop step by step, identifying which molecular event a given genetic lesion (e.g., *VHL* loss) disrupts.
3. **Distinguish** vasculogenesis from sprouting angiogenesis, and **describe** the tip-cell/stalk-cell decision and its regulation by Notch signaling.
4. **Predict** how the structural abnormalities of tumor vasculature (leakiness, poor pericyte coverage, high interstitial pressure) affect drug delivery, oxygenation, and radiation response.
5. **Evaluate** why blocking a single pro-angiogenic factor (VEGF) does not reliably starve a tumor, and **anticipate** the resistance mechanisms developed in the next chapter.

## Opening Case

A 58-year-old man undergoes nephrectomy for clear cell renal cell carcinoma. The pathologist's report contains a detail the surgeon already half-expected from the operative bleeding: the tumor is extraordinarily vascular, threaded with chaotic, dilated vessels that bled at the slightest manipulation. Genetic testing of the tumor shows biallelic inactivation of the *VHL* gene — both copies lost, one by deletion, one by mutation.

This is not a coincidental pairing of two findings. The *VHL* loss and the tumor's vascularity are the same fact seen from two angles. Something about losing this one gene has told the tumor to build blood vessels relentlessly, far more than it needs, in a disorganized tangle. The same patient, had the tumor been caught as a one-millimeter nodule, might have carried it silently for years — a cluster of cancer cells unable to grow because it could not feed itself. Why does a tumor stall at a millimeter? Why does losing *VHL* unleash a flood of vessels? And if the tumor's life depends so completely on its blood supply, why has the obvious therapy — cut off the supply — proven so much harder than it sounds? This chapter answers the first two questions; the next answers the third.

## Core Concepts

### The diffusion limit: why size forces the question

Start with a physical constraint that has nothing to do with genetics. Oxygen and nutrients move into tissue by **diffusion** — passive movement down a concentration gradient. Diffusion is fast over short distances and hopelessly slow over long ones. In practice, a cell can survive on diffusion only if it sits within roughly 100–200 micrometers of a blood vessel.

A single cancer cell, or a cluster of a few hundred, lives comfortably on diffusion: oxygen reaches it through the surrounding tissue fluid, and waste diffuses out. But once a cluster reaches about one millimeter in diameter — on the order of a hundred thousand cells — the cells at the center are too far from any vessel. They starve and asphyxiate. The core becomes **necrotic** (dead tissue), and the mass cannot grow further (Folkman, 1971).

This is the central constraint of solid-tumor biology. *Without a blood supply, a tumor is dormant. With one, it can grow indefinitely.* Judah Folkman articulated this in a 1971 *New England Journal of Medicine* paper, proposing three things: that tumors must induce their own blood supply to become clinically dangerous; that drugs targeting that blood supply might starve tumors without the toxicity of chemotherapy; and that the molecular signals driving tumor blood-vessel growth would be discoverable (Folkman, 1971). The field rejected the idea for years, then vindicated all three claims.

<!-- → [DIAGRAM: the diffusion limit — a tumor sphere with a vascularized rim and a necrotic hypoxic core, annotated with the ~100–200 µm diffusion distance] -->

### How blood vessels form

Two distinct processes build vasculature. **Vasculogenesis** is the formation of blood vessels *de novo* from precursor cells — endothelial progenitor cells differentiating from mesoderm and coalescing into the first primitive networks. It dominates in the embryo and is rare in adults, though it contributes in some contexts (and, controversially, in some tumors).

**Angiogenesis** is the formation of new vessels *from existing ones*. This is the dominant mechanism in adult life — it operates during the menstrual cycle, pregnancy, wound healing, and exercise-induced muscle adaptation, and pathologically in cancer, diabetic retinopathy, and chronic inflammation.

**Sprouting angiogenesis** follows a stereotyped sequence. A pro-angiogenic signal — typically VEGF — reaches an existing capillary. One endothelial cell, selected by lateral inhibition through **Notch signaling** (a cell-cell signaling pathway in which one cell instructs its neighbors not to adopt the same fate), becomes the **tip cell**: it extends finger-like **filopodia** up the VEGF gradient and migrates toward the source. The cells behind it, the **stalk cells**, proliferate to extend the sprout. The cells hollow out to form a **lumen** (the central channel), the new vessel connects to another vessel (**anastomosis**), **pericytes** (support cells that wrap capillaries) are recruited, and a basement membrane is laid down. The vessel matures.

In healthy tissue this is tightly regulated, producing orderly vasculature with regular branching and selective permeability. *In tumors, the regulation is broken before it fails — the signals are amplified, the Notch-mediated tip/stalk decision is impaired, and the result is a chaotic tangle.* Hold that phrase: regulation that has come loose, not machinery that has stopped working.

### VEGF and the angiogenic signal

The dominant pro-angiogenic signal is **vascular endothelial growth factor (VEGF)** — a family of secreted glycoproteins. It was first described as *vascular permeability factor* by Senger and Dvorak in 1983, then rediscovered and cloned as VEGF by Napoleone Ferrara at Genentech in 1989 (the foundation of the entire therapeutic field) (Ferrara et al., 1989). **VEGF-A** (usually just "VEGF") is the main angiogenic ligand; VEGF-C and VEGF-D drive lymphatic vessel growth. The key receptor is **VEGFR-2** (a receptor tyrosine kinase — an enzyme that, when its ligand binds, phosphorylates tyrosine residues to launch intracellular signaling).

When VEGF-A binds VEGFR-2 on an endothelial cell, the receptor dimerizes, phosphorylates itself, and activates downstream cascades (PLC-γ, the Ras–Raf–MEK–ERK pathway, and PI3K–AKT). The combined effect: endothelial proliferation, migration, survival, and increased **vascular permeability** (leakiness — one of VEGF's originally named functions) (NCI, Angiogenesis Inhibitors).

Now the critical regulatory loop. VEGF expression is driven primarily by **hypoxia** (low oxygen), through the transcription factor **HIF-1α** (hypoxia-inducible factor 1-alpha). The *VEGF-A* gene carries hypoxia response elements in its promoter; HIF-1α binds them and drives transcription. So:

> A tumor outgrows its blood supply → its core becomes hypoxic → hypoxia stabilizes HIF-1α → HIF-1α drives VEGF expression → VEGF diffuses to nearby vessels → new vessels grow *toward* the hypoxic region → oxygen is restored → HIF-1α is degraded → VEGF falls.

This is the most elegant feedback loop in tumor biology: the tumor builds its own oxygen supply using a hypoxia sensor. And it is exactly why anti-angiogenic therapy is *logically* appealing — interrupt the loop, and the tumor cannot resupply oxygen. In theory.

<!-- → [DIAGRAM: the HIF-1α–VEGF feedback loop as a cycle — hypoxia → HIF-1α stabilization → VEGF transcription → endothelial VEGFR-2 → new vessels → reoxygenation → HIF-1α degradation, with VHL marked at the degradation step] -->

### Other angiogenic factors

VEGF is dominant but not alone. **Fibroblast growth factors (FGFs)** stimulate endothelial proliferation and cooperate with VEGF. **Platelet-derived growth factor (PDGF)**, through PDGFR-β on pericytes, recruits those support cells to stabilize new vessels — without proper pericyte coverage, vessels stay leaky and immature. **Angiopoietins** (Ang-1 stabilizing, Ang-2 destabilizing) act through the Tie-2 receptor. **TGF-β**, **HGF**, pro-angiogenic chemokines (CXCL8/IL-8, CXCL12/SDF-1), and **matrix metalloproteinases** (proteases that both clear matrix for migrating endothelium and release matrix-bound growth factors) all contribute. *The multiplicity of factors is the first hint of why blocking VEGF alone is rarely enough — the tumor can compensate.*

### The angiogenic switch

A small tumor can sit dormant indefinitely if it cannot trigger angiogenesis. Autopsies of people who died of unrelated causes routinely reveal microscopic *in situ* cancers in the prostate, thyroid, and breast — small dormant tumors that never progressed. Dormancy is a real and common state.

The **angiogenic switch** is the transition from dormant to actively growing. Mechanistically it is a shift in the *balance* between pro-angiogenic factors (VEGF, FGFs, others) and anti-angiogenic factors the cell also makes (**thrombospondin-1**, **endostatin** from collagen XVIII cleavage, **angiostatin** from plasminogen cleavage). The net signal decides whether the tumor grows.

Several events can flip the switch:
- **Genetic changes that raise VEGF.** Loss of *VHL* stabilizes HIF-1α and drives VEGF (this is the renal-cell case in the opening). Activating oncogenes (Ras, EGFR, PI3K) upregulate VEGF. Loss of wild-type p53 lowers thrombospondin-1 (which p53 normally induces), tilting the balance toward angiogenesis.
- **Hypoxia** as the tumor outgrows diffusion.
- **Recruitment of pro-angiogenic stromal cells** — tumor-associated macrophages, neutrophils, and platelets that release VEGF and FGFs.

Once flipped, the tumor enters a growth phase in which regions of high supply and regions of hypoxia alternate, the feedback loop maintaining an average oxygen level. Clinically, this matters: cancers that recur years or decades after apparent cure (some breast cancers, melanoma, prostate cancer) are thought to have been dormant micrometastases until something flipped their angiogenic switch — which is one reason adjuvant therapy and surveillance extend over many years.

### What tumor vasculature looks like

The vasculature tumors build is recognizably abnormal, and every abnormality has a clinical consequence:

- **Disorganized branching** — chaotic, with abrupt diameter changes, blind ends, and shunts. A tangle, not a hierarchy.
- **Leaky walls** — gaps between endothelial cells let macromolecules escape into the interstitium (the **enhanced permeability and retention effect** exploited by some nanoparticle drugs).
- **Incomplete pericyte coverage** — fewer, abnormal pericytes mean unstable, leaky vessels.
- **Vessel co-option** — some tumors (liver metastases, some brain tumors) grow by hijacking *existing* host vessels rather than building new ones. These tumors never depended on angiogenesis and are therefore intrinsically resistant to anti-angiogenic drugs.
- **Vasculogenic mimicry** — tumor cells themselves forming channel-like structures (described in melanoma and ovarian cancer; frequency debated) `[contested — frequency and importance unresolved]`.
- **High interstitial fluid pressure** — leaky vessels plus poor lymphatic drainage raise pressure 5- to 10-fold above normal, pushing back against inflowing blood and impeding drug penetration.
- **Persistent hypoxia** despite all the vessels — which drives more VEGF, more chaotic vessels, and a loop that never stabilizes.

The functional result: tumor blood flow is heterogeneous, intermittent, and inefficient. Drugs do not reach all regions equally. Hypoxic regions are **radioresistant** (radiation kills largely through oxygen-dependent ionization). The acidic, hypoxic microenvironment selects for the most aggressive cancer cells. This is why "starve the tumor" is too simple a slogan: normalizing the vessels — making them function more like normal capillaries — may be more useful than destroying them. That **vascular normalization** hypothesis, from Rakesh Jain's group, reshapes the next chapter (Jain, 2005).

## Worked Example

**Situation.** Return to the opening patient: clear cell renal cell carcinoma, biallelic *VHL* inactivation, strikingly vascular tumor. You are asked to explain *mechanistically* why these tumors are so vascular, and to predict whether a VEGF-targeting drug should help.

**Reasoning.** Start with the normal job of the VHL protein. VHL is part of the complex that, *under normal oxygen*, tags HIF-1α for destruction (it recognizes a hydroxyl group added to HIF-1α only when oxygen is present). So in a normal cell, oxygen → VHL tags HIF-1α → HIF-1α is degraded → VEGF stays low. Hypoxia removes the hydroxyl tag, VHL can no longer grab HIF-1α, HIF-1α accumulates, and VEGF rises. This is the sensor.

*A dead end first.* You might guess the tumor is vascular because it is large and therefore hypoxic — the ordinary route to VEGF. But that does not fit: these tumors are vascular even when small, and the vascularity is intrinsic, not a response to outgrowing supply. The hypoxia explanation under-predicts.

*The resolution.* With *both* copies of *VHL* lost, the cell has no functional VHL protein. HIF-1α is never tagged for destruction — *even in normal oxygen*. The cell behaves as though it were permanently hypoxic. It floods the microenvironment with VEGF constitutively, regardless of actual oxygen levels. The angiogenic switch is not merely flipped; the off-switch has been removed. That is why the tumor is vascular from the start and why the vessels are so abundant and chaotic.

Now the prediction. Because these tumors are pathologically *VEGF-addicted*, VEGF-pathway drugs should work unusually well here — and they do. Renal cell carcinoma is one of the diseases where anti-angiogenic therapy produces its largest, most reliable benefits, which the next chapter quantifies.

**The lesson.** A genetic lesion is most dangerous not when it breaks a machine but when it removes a regulator, so the machine runs without its off-switch.

**The limit.** Even in this best case, the drugs do not cure — resistance still emerges, because the tumor retains the non-VEGF angiogenic factors and adaptive routes covered in the next chapter. "VEGF-addicted" predicts a *better* response, not a permanent one.

## Common Misconceptions

**"A tumor stops growing when it runs out of room."** Plausible — masses do feel physically constrained. But the limiting resource at the millimeter scale is not space; it is *diffusion distance for oxygen and nutrients*. The dormant micro-tumor in the opening case is not boxed in by surrounding tissue — it is starved at its core. This is precisely why flipping the angiogenic switch, not finding empty space, is what lets the tumor expand.

**"Anti-angiogenic therapy starves the tumor to death."** This is Folkman's original vision and it is too clean. Tumor vessels are *already* barely functional; the goal of removing them entirely can backfire by making the tumor severely hypoxic — which selects for the most aggressive, hypoxia-tolerant cells and worsens drug delivery. The opening patient's tumor will respond to VEGF blockade, but "respond" means slowed growth and normalized vessels, not melting away. The relevant model is normalization, not starvation.

**"VEGF is a cancer protein."** VEGF is a normal, essential factor — it maintains vasculature throughout the body and runs wound healing and the menstrual cycle. That is exactly why anti-VEGF drugs cause predictable side effects (hypertension, proteinuria, poor wound healing): they hit VEGF wherever it works, not only in the tumor. A target shared with normal tissue is a target that predicts toxicity — a principle worth carrying into every therapy chapter.

**"More angiogenesis means a healthier, better-supplied tumor."** The opposite is often true. Tumor vessels are abundant *and* dysfunctional. The chaos itself — leakiness, high interstitial pressure, intermittent flow — produces hypoxia despite the vessel count. Vessel quantity is not perfusion quality.

## Exercises

1. **(Recall/Understand)** In two or three sentences, explain why a 0.5-mm cluster of cancer cells can survive indefinitely while a 2-mm cluster cannot grow without angiogenesis. Name the physical process that sets the limit.

2. **(Apply)** A tumor has an activating mutation in *Ras* and a separate loss of wild-type *p53*. Using the angiogenic-balance model, predict the direction each lesion pushes the pro-/anti-angiogenic balance, and name the specific anti-angiogenic factor affected by p53 loss.

3. **(Apply)** A liver metastasis from colorectal cancer shows little response to bevacizumab even though the patient's primary tumor was VEGF-high. Propose one structural feature of how this metastasis may be obtaining its blood supply that would make it intrinsically resistant, and explain the mechanism.

4. **(Produce — mechanism map)** Draw the HIF-1α–VEGF feedback loop as a labeled cycle (at least six nodes: oxygen level, HIF-1α, VHL, VEGF, endothelial VEGFR-2, vessel growth). Then mark with an "X" the exact node disrupted by (a) biallelic *VHL* loss and (b) a VEGFR-2 tyrosine kinase inhibitor. Use the diagram to explain why these two interventions act at different points of the same loop.

5. **(Produce — proxy audit)** Imaging shows a tumor has become *more* vascular on contrast MRI after a period of growth. A clinician reads this as "the tumor is getting healthier blood flow." Write a short audit: what does "more vascular on imaging" actually measure, what does it fail to capture about perfusion quality and hypoxia, and when would this signal mislead?

## What Would Change My Mind

The chapter's central claim is that solid tumors are fundamentally constrained by their blood supply and must induce angiogenesis to grow beyond the diffusion limit. The strongest finding that would force revision: robust, repeated demonstration that a substantial fraction of clinically lethal solid tumors grow to large size *without* either building new vessels or co-opting existing ones — i.e., sustaining a vascular-poor interior far beyond 1–2 mm through some unrecognized supply mechanism. Vessel co-option already shows that *new* vessel formation is not universally required; but co-option still depends on a pre-existing vascular supply, so it refines rather than refutes the claim. A tumor genuinely thriving with neither angiogenesis nor co-option — large regions of viable, proliferating cells far beyond any diffusion distance from any vessel — would break the framework. To date, the diffusion limit has held.

## Still Puzzling

- **What flips the switch in dormancy?** Micrometastases can remain angiogenically dormant for years, then suddenly recruit vessels and grow. We can list candidate triggers (inflammation, hormonal shifts, immune changes) but cannot yet predict, in a given patient, when or whether the switch will flip. This gap directly limits how long adjuvant therapy and surveillance should continue.

- **How much does vasculogenic mimicry actually matter?** Tumor cells lining channel-like structures have been described repeatedly, but whether they conduct meaningful blood flow and contribute materially to tumor supply — or are a histological curiosity — remains unsettled. If real and common, it would be a route entirely outside the reach of endothelial-targeted drugs.

- **Why does the same VEGF blockade help renal cell carcinoma far more than, say, glioblastoma?** Differences in *VHL* status and vessel co-option explain part of it, but not all. What distinguishes the truly VEGF-addicted tumor from the merely VEGF-using one is a question the next chapter's resistance biology takes up, and one the field has not fully solved.

## References

- Folkman, J. (1971). Tumor angiogenesis: therapeutic implications. *New England Journal of Medicine*, 285(21), 1182–1186.
- Ferrara, N., & Henzel, W. J. (1989). Pituitary follicular cells secrete a novel heparin-binding growth factor specific for vascular endothelial cells. *Biochemical and Biophysical Research Communications*, 161(2), 851–858.
- Senger, D. R., et al. (1983). Tumor cells secrete a vascular permeability factor that promotes accumulation of ascites fluid. *Science*, 219(4587), 983–985.
- Jain, R. K. (2005). Normalization of tumor vasculature: an emerging concept in antiangiogenic therapy. *Science*, 307(5706), 58–62.
- National Cancer Institute. Angiogenesis Inhibitors. https://www.cancer.gov/about-cancer/treatment/types/immunotherapy/angiogenesis-inhibitors-fact-sheet
- National Cancer Institute. Targeted Therapy for Cancer. https://www.cancer.gov/about-cancer/treatment/types/targeted-therapies

## Prompts

<!-- This section is populated automatically by the Cowork enrichment
     pass. Each D3 figure generated in this chapter gets an entry here:
     the figure number, a short title, and a ready-to-paste prompt
     that produces a close approximation of that figure. -->

*No figures have been generated for this chapter yet.*
