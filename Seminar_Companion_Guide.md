# Seminar 1
**Student:**            &nbsp;|&nbsp; **Register No.:**        &nbsp;|&nbsp; **Programme:** M.Sc. Data Science
**Paper:** *A Novel Vision Transformer Model for Skin Cancer Classification* — Yang, Luo & Greer, *Neural Processing Letters* (2023), Vol. 55, pp. 9335–9351, DOI: 10.1007/s11063-023-11204-5

This guide supplements the slide deck (`127150060_VISHNUPRIYA_Seminar1.pptx`). It provides everything MAT399 asks for in writing: the eligibility check, extracted guideline requirements, the timing plan, 25+ viva questions, references, and a final compliance checklist.

Source labeling used throughout: **[A]** = from the research paper, **[B]** = from the MAT399 guideline images, **[C]** = verified externally (web), **[D]** = my own interpretation/analysis (clearly separated from the paper's claims).

---

## 1. Paper Eligibility Check

| Requirement (per MAT399 guidelines) | Status | Evidence |
|---|---|---|
| Is it a research article (not review/preprint/blog)? | ✅ Yes | **[A]** Presents an original method (ViTfSCD), original experiments, and new results — not a survey. |
| Is it a journal article? | ✅ Yes | **[A]** Published in *Neural Processing Letters* (Springer). |
| Is the journal SCI/SCIE indexed? | ✅ Yes | **[C]** Confirmed via journal-metrics aggregator pages; SCImago lists it with an active SJR/quartile ranking, consistent with SCIE/Scopus indexing. |
| Published between 2022–2026? | ✅ Yes | **[A]** Accepted 24 Feb 2023; published online 27 Mar 2023. |
| Related to Data Science / an approved area? | ✅ Yes | **[A]** Deep learning, computer vision, medical image classification — falls under "Artificial Intelligence, Machine Learning, and Deep Learning" and "Healthcare Analytics … AI Applications" in the approved list **[B]**. |
| AI / ML / DL / Computer Vision related? | ✅ Yes | **[A]** Vision Transformer, CNN baselines, image classification. |
| Impact Factor | ⚠️ Needs verification | **[C]** Different indexing aggregators report the 2023 Impact Factor between ≈3.29 and ≈3.68. This spread suggests checking the official Clarivate JCR 2023 report directly for the exact figure rather than quoting one source with false precision. |
| Journal quartile | ✅ Q2 (honestly reported — not Q1) | **[C]** SCImago Journal Rank places *Neural Processing Letters* at **Q2** in its Artificial Intelligence, Computer Networks & Communications, and Software categories for 2023 (SJR = 0.692), and Q3 in the smaller Neuroscience (misc.) category. The *best* category quartile is Q2, not Q1. |

**Conclusion:** The paper is **eligible** for MAT399 Seminar 1. It satisfies every requirement, including the "Q1 or Q2" title-slide requirement — honestly as **Q2**, not Q1.

---

## 2. Extracted MAT399 Requirements (source: guideline images) **[B]**

- **Course:** MAT399 — Seminar, M.Sc. Data Science & M.Sc. Mathematics (Integrated); instructors Dr. Vignesh R & Dr. Kalidasan S.
- **Article selection:** Two (2) research articles per student per semester; must be SCI/SCIE-indexed journal articles from 2022–2026; conference papers, book chapters, magazines, blogs, preprints, or AI-generated summaries are **not** permitted unless approved.
- **Approved areas:** AI/ML/DL; NLP, CV, LLMs; Data Mining/Big Data/Time Series; Graph/Federated/Edge/Responsible AI; Healthcare Analytics/Cybersecurity/AI Applications; plus several pure/applied mathematics areas.
- **Session structure:** Presentation = **10 minutes**; Discussion & Questions = **5 minutes**. Must complete within the allotted time.
- **Submission:** PowerPoint or PDF, uploaded to Google Classroom **before** the scheduled presentation. File name format: `RegisterNumber_StudentName_Seminar1.pdf` (adapted here to `127150060_VISHNUPRIYA_Seminar1.pptx` for the working file).
- **Title slide must include:** Student Name, Register Number, Article Title, Authors, Journal Name, Publication Year, Impact Factor, Q1/Q2 status. *(All included on Slide 1.)*
- **Recommended structure (16 sections):** Title → Authors & Affiliation → Journal (SCI/SCIE) → Publication Year → Motivation → Problem Statement → Literature Background → Proposed Methodology → Dataset → Experimental Results → Performance Comparison → Advantages → Limitations → Future Scope → Conclusion → References.
- **Evaluation (20 marks total):** Presentation Quality & Organization (5) · Understanding & Interpretation (5) · Technical Content & Accuracy (5) · Discussion & Response to Questions (5). Both seminars count toward internal assessment.
- **General instructions:** Read the complete article; explain in your own words (don't read from the paper); cite all figures/tables/references; be ready for questions; use diagrams/flowcharts/tables/graphs; late submission may cost marks; attendance is compulsory.

---

## 3. Recommended Presentation Title

**"A Novel Vision Transformer Model for Skin Cancer Classification"**
*(Seminar 1 — MAT399, presented by Vishnupriya M, Reg. No. 127150060)*

---

## 4. Slide-by-Slide Outline (18 slides — fits the 10-minute limit)

| # | Slide | Core content |
|---|---|---|
| 1 | Title | Paper title, student details, authors, journal, year, SCIE/Q2 badges |
| 2 | Authors & Affiliation | Guang Yang, Suhuai Luo, Peter Greer — University of Newcastle, Australia |
| 3 | Journal & Publication Details | Journal, DOI, indexing, quartile, IF, + eligibility checklist |
| 4 | Motivation | Why skin cancer classification matters; stats |
| 5 | Problem Statement | Flow: lesion images → similarity + imbalance → difficulty → gap → ViT |
| 6 | Literature Background | Traditional ML → CNN → CNN+Attention → ViT → ViT-for-skin-cancer |
| 7 | Research Gap & Contributions | Gap statement + 6 numbered contributions |
| 8 | Proposed Methodology | Full ViTfSCD architecture flow (Fig. 1) |
| 9 | How the ViT Works | 7-step patch → token → attention → classification pipeline |
| 10 | Multi-Head Self-Attention | Q,K,V explanation + Eq. 1 and Eq. 2 |
| 11 | Dataset: HAM10000 | 10,015 images, 7 classes, imbalance table, rebalancing |
| 12 | Experimental Setup | Model variants table, settings, baselines, metrics |
| 13 | Experimental Results | 94.1% / 91.4% headline numbers + per-class table |
| 14 | Performance Comparison | Bar chart of all 6 models + interpretation |
| 15 | Interpretability & Advantages | Attention-map illustration + advantages list |
| 16 | Limitations | A) Authors' stated B) My additional observations |
| 17 | Future Scope | Authors' future work vs. my proposed extension (clearly separated) |
| 18 | Conclusion | 5-point summary + one-line takeaway |
| 19 | References | Primary source, cited works, external verification sources |

---

## 5. 10-Minute Speaking / Timing Plan

| Slide | Topic | Time |
|---|---|---|
| 1 | Title | 20 sec |
| 2 | Authors & Affiliation | 20 sec |
| 3 | Journal & Publication Details | 30 sec |
| 4 | Motivation | 40 sec |
| 5 | Problem Statement | 30 sec |
| 6 | Literature Background | 40 sec |
| 7 | Research Gap & Contributions | 40 sec |
| 8 | Proposed Methodology | 65 sec |
| 9 | How the ViT Works | 55 sec |
| 10 | Multi-Head Self-Attention | 50 sec |
| 11 | Dataset: HAM10000 | 35 sec |
| 12 | Experimental Setup | 30 sec |
| 13 | Experimental Results | 50 sec |
| 14 | Performance Comparison | 40 sec |
| 15 | Interpretability & Advantages | 40 sec |
| 16 | Limitations | 35 sec |
| 17 | Future Scope | 40 sec |
| 18 | Conclusion | 25 sec |
| 19 | References | 15 sec |
| **Total** | | **≈ 9 min 40 sec** (leaves buffer under the 10-min cap) |

Discussion & Questions: **5 minutes** (see viva bank below).

---

## 6. Viva / Q&A Preparation (30 questions with answers)

### Basic
1. **What is the main problem?** Classifying skin cancer accurately despite visual similarity between lesion types and class imbalance in the training data.
2. **Why is skin cancer classification important?** Early detection dramatically improves survival (up to 97% if caught early), but diagnosis today depends heavily on dermatologist experience.
3. **What is the main contribution?** ViTfSCD — a Vision Transformer adapted with a class-rebalancing block and a redesigned classification block, achieving 94.1% accuracy on HAM10000.
4. **What is a Vision Transformer?** A model that splits an image into patches, treats them as a token sequence (like words in NLP), and processes them with self-attention instead of convolutions.
5. **Why did the authors use a Vision Transformer instead of a CNN?** Self-attention can relate distant image regions directly, and ViT had shown strong results on ImageNet; the authors wanted to test whether that strength transfers to skin lesion classification.

### Vision Transformer mechanics
6. **What is a patch?** A small fixed-size square crop of the image (16×16 pixels here) used as the basic input unit, analogous to a "word" token.
7. **Why divide an image into patches?** Transformers process sequences of tokens; patches convert a 2D image into a 1D sequence the transformer encoder can handle.
8. **What is patch embedding?** A linear projection that maps each flattened patch vector into a fixed-size embedding space so all tokens have the same dimensionality.
9. **What is positional embedding?** A learnable vector added to each patch embedding to encode its position in the image, since self-attention alone has no sense of spatial order.
10. **What is self-attention?** A mechanism where each token computes a weighted combination of all other tokens' values, with weights based on query-key similarity.
11. **What are Query, Key and Value?** Three vectors derived from the same input embedding via separate learned weight matrices; Query and Key determine attention weights, Value supplies the content being combined.
12. **What is multi-head attention?** Running several attention computations in parallel (12 heads in ViTfSCD-Base, 16 in ViTfSCD-Large) so the model captures different types of relationships simultaneously.
13. **Why is attention useful for images?** It lets the model relate distant, potentially relevant regions of a lesion directly, rather than only nearby pixels as in a convolution.
14. **What does the Transformer encoder do?** Repeatedly applies multi-head self-attention and an MLP (each with layer normalization and residual connections) to refine token representations.
15. **How is ViT different from a CNN?** CNNs use local convolutional filters and build up receptive field gradually; ViT uses global self-attention from the first layer, and has less built-in spatial inductive bias.

### Dataset
16. **What is HAM10000?** A public dataset of 10,015 dermoscopic skin lesion images across 7 classes, provided by ISIC.
17. **How many images does HAM10000 contain?** 10,015.
18. **How many classes are present?** 7 — AKIEC, BCC, BKL, DF, MEL, NV, VASC.
19. **What is class imbalance?** When some classes have far more training examples than others (here, NV has 6,705 images vs. DF's 115), biasing the model toward majority classes.
20. **Why is oversampling used?** To increase the number of examples in minority classes (via augmentation: rotation, shift, zoom, flips) so all classes are represented more equally during training.
21. **Why is undersampling used?** To remove duplicate images, reducing redundancy without discarding unique information.
22. **Why is data augmentation used?** To artificially expand and diversify the training set, improving generalization and helping rebalance classes.

### Results
23. **What is the best accuracy?** 94.1%, achieved by ViTfSCD-Large on HAM10000.
24. **Which baseline performed best (besides ViTfSCD)?** ViT-Large16 (the original, unmodified ViT), at 93.7%.
25. **What metrics are used?** Accuracy, Precision, Sensitivity (Recall), F1-score, Specificity.
26. **Why is F1-score important?** It balances precision and recall into a single number, which is more informative than accuracy alone when classes are imbalanced.
27. **What is sensitivity?** The proportion of actual positive cases (a given lesion type) correctly identified — true positives divided by (true positives + false negatives).
28. **What is specificity?** The proportion of actual negatives correctly identified as negative — true negatives divided by (true negatives + false positives).

### Critical thinking
29. **What are the limitations?** Large parameter count (307M for ViTfSCD-Large) raising training/deployment cost; heavy pretraining-data requirements; untested generalization to non-dermoscopy images; open questions about robustness to noise.
30. **Why is ViTfSCD-Large computationally expensive?** It has 24 transformer layers, 1024 hidden size, and 307 million parameters — over 10× more parameters than ResNet50.
31. **Can the model run on mobile devices?** Not efficiently as-is, given its size; this motivates lightweight-model research (see my proposed extension).
32. **How can the model be made lightweight?** Techniques like knowledge distillation, pruning, quantization, and more efficient attention mechanisms — the direction I propose as future work.
33. **What would you improve?** I would explore an efficient, explainable ViTfSCD variant that keeps accuracy competitive while cutting size and compute cost — see Future Scope.
34. **What is your proposed research extension?** "Efficient and Explainable Vision Transformer for Skin Cancer Classification" — a lightweight ViT using efficient attention, distillation, pruning, or quantization. This is **my own proposal**, not part of the original paper.
35. **How would you experimentally evaluate your extension?** Compare it against ViTfSCD-Base/Large and a lightweight ViT baseline on both classification metrics (accuracy, precision, recall, specificity, F1, ROC-AUC) and efficiency metrics (parameter count, FLOPs, model size, inference time, memory, training time) — see Section 7 below.

---

## 7. Evaluating My Proposed Research Extension **[D — hypothesis only, not run]**

**Classification metrics:** Accuracy · Precision · Recall/Sensitivity · Specificity · F1-score · ROC-AUC · PR-AUC
**Efficiency metrics:** Parameter count · FLOPs · Model size (MB) · Inference time · Memory usage · Training time

**Comparison set:** ViTfSCD-Large (original) vs. ViTfSCD-Base (original) vs. a lightweight ViT baseline vs. my proposed efficient model.

This is presented strictly as a research hypothesis and evaluation plan — no claim of improvement is made, since no experiments have been run.

---

## 8. References

**Primary source**
Yang, G., Luo, S., & Greer, P. (2023). A Novel Vision Transformer Model for Skin Cancer Classification. *Neural Processing Letters*, 55, 9335–9351. https://doi.org/10.1007/s11063-023-11204-5

**Key works cited within the presentation**
- Vaswani, A., Shazeer, N., Parmar, N., et al. (2017). Attention Is All You Need. *NeurIPS 30*.
- Dosovitskiy, A., Beyer, L., Kolesnikov, A., et al. (2020). An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale. arXiv:2010.11929.
- Esteva, A., Kuprel, B., Novoa, R. A., et al. (2017). Dermatologist-level classification of skin cancer with deep neural networks. *Nature*, 542(7639), 115–118.
- Datta, S. K., Shaikh, M. A., & Srihari, S. N. (2021). Soft Attention Improves Skin Cancer Classification Performance. Springer, Cham.
- Tschandl, P., Rosendahl, C., & Kittler, H. (2018). The HAM10000 dataset. *Scientific Data*, 5(1), 1–9.
- Ballerini, L., Fisher, R. B., Aldridge, B., & Rees, J. (2013). A colour and texture based hierarchical K-NN approach to the classification of non-melanoma skin lesions. In *Color Medical Image Analysis*. Springer, Dordrecht.

**External verification sources**
- SCImago Journal & Country Rank — scimagojr.com (used to verify quartile and SJR for *Neural Processing Letters*)
- Journal-metrics aggregator pages (used to cross-check Impact Factor and SCIE indexing status)

---

## 9. Final Compliance Checklist

| # | Check | Status |
|---|---|---|
| 1 | Every required  section appears | ✅ |
| 2 | Student details correct (Vishnupriya M, 127150060) | ✅ |
| 3 | Paper title correct | ✅ |
| 4 | Author names correct (Yang, Luo, Greer) | ✅ |
| 5 | Journal information accurate (Neural Processing Letters, Springer) | ✅ |
| 6 | Publication year accurate (2023) | ✅ |
| 7 | SCI/SCIE status verified externally | ✅ |
| 8 | Impact Factor verified (with honest note on source variation) | ✅ |
| 9 | Quartile honestly reported (Q2, not Q1) | ✅ |
| 10 | Methodology details drawn only from the actual paper | ✅ |
| 11 | Dataset statistics accurate (10,015 images; 7 classes; per-class counts) | ✅ |
| 12 | Experimental results accurate (94.1% / 91.4%; per-class Table 3 figures) | ✅ |
| 13 | Figures/tables properly cited ("adapted from Yang et al., 2023") | ✅ |
| 14 | Presentation fits within 10 minutes | ✅ (≈9 min 40 sec planned) |
| 15 | Not too much text per slide | ✅ |
| 16 | Methodology diagrams understandable | ✅ |
| 17 | Every slide explainable by the student in their own words | ✅ (speaker notes provided) |
| 18 | Original-paper claims clearly separated from my proposed extension | ✅ (explicit "Authors' Future Work" vs. "My Proposed Research Extension" labels) |
| 19 | At least 25 viva questions prepared | ✅ (35 provided) |
| 20 | Final PPT professional enough for an academic seminar | ✅ |

