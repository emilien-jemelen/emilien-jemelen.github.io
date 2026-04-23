---
layout: page
permalink: /
background: "/banner.jpg"
---

### Emilien Jemelen

PhD candidate in statistics and deep learning @ Inria & Epiconcept

<a id="Welcome"></a>
<div class="section-card">
  {{ "
## Welcome

I am a Ph.D candidate in the [HeKa](https://heka.gitlabpages.inria.fr/) Inria team hosted at [PariSanté Campus](https://parisantecampus.fr/), under the supervision of [Sandrine Katsahian](https://www.researchgate.net/profile/Sandrine-Katsahian) and [Agathe Guilloux](https://sites.google.com/view/agatheguilloux-personalwebsite). Here is [a short CV](/CV_Emilien_Jemelen.pdf).

My research interests lie in statistics and machine learning, with a particular focus on medical imaging applications in high-stakes domains such as cancer screening or treatment response prediction.

Given the current limited interpretability of neural networks, I am especially interested in human–machine interaction and in developing models equipped with abstention mechanisms (Selective Prediction), so that they can defer to the end user when they are more likely to be wrong.

I am also very interested in recent advances in domain generalization in machine learning. More generally, I would be very excited to see the emergence of sufficiently large, well-annotated datasets for cancer detection — including systematic patient follow-up after screening — that could support the development of a foundation model for pattern detection in X-ray mammography. This could help move beyond the endless fine-tuning on relatively small (given the dimensionality of the images), highly imbalanced datasets, which is still a major issue as acquisition devices keep evolving and current CNN architectures often suffer from substantial performance degradation.

I am currently looking for a postdoctoral position in statistical learning or deep learning applied to imaging. Please feel free to get in touch if you would like to discuss.

#### Contact:

* E-mail: name.surname@inria.fr or name.surname@gmail.com
* Address: Équipe Inria HeKA, PariSanté Campus,
  2 - 10 Rue d'Oradour-sur-Glane, 75015 Paris. Métro Balard or Porte de Versailles.

#### Some non-academic interests:
* Amateur road cycling with the [Equipe Cycliste Vélizy 78](https://www.ecvelizy78.com/) competition team since 2021.
* Classical guitar, with a repertoire spanning flamenco and Baroque pieces; for a much better illustration of the instrument: check out this fantastic [podcast on the legendary duo Ida Presti and Alexandre Lagoya](https://www.radiofrance.fr/francemusique/podcasts/guitare-guitares/ida-presti-et-alexandre-lagoya-7807189) starring one of the greatest duos in the history of classical music.
" | markdownify }}
</div>

<a id="research"></a>
<div class="section-card">
  {{ "
## Research

#### Journal papers:
* *Evaluating breast cancer screening performance without registries using medico-administrative data*. Emilien Jemelen, Francisco Orchard, William Madie, Bernard Valentin, Josine Belin, Enora Laas, Guillaume Jeannerod, Pierre Mares, Sandrine Katsahian, Agathe Guilloux. Nature Scientific Reports 15, 25096 (2025). Link: [paper](https://doi.org/10.1038/s41598-025-10115-w)

#### Conference papers: 
* *Beyond Accuracy: Controlling Broad Error Types in Selective Classification*. Emilien Jemelen, Francisco Orchard, Sandrine Katsahian, Agathe Guilloux. Currently under review.

#### Workshop papers:
* *Beyond Accuracy: Controlling Broad Error Types in Selective Classification*. Emilien Jemelen, Francisco Orchard, Sandrine Katsahian, Agathe Guilloux—accepted at the AISTATS 2026 workshop on Uncertainty Calibration—online release expected in Spring 2026.
* *Where to Drop: Tuning Monte Carlo Dropout for Uncertainty Calibration in Image Classification*. Lina Benyamina and Emilien Jemelen—accepted at the AISTATS 2026 workshop on Uncertainty Calibration—online release expected in Spring 2026.

![Different impact](/error_types.png)

#### Ongoing work (draft titles):
* [Journal paper] Performance of retrospective breast cancer screening pathways integrating CNN-based models trained for 2-year cancer detection and equipped with abstention mechanisms — _submission expected in summer 2026_
* [Journal paper] Linkage analysis of the deep.piste breast cancer screening database with the SNDS (the French national health insurance claims database) — _submission expected in summer 2026_
* [Conference or workshop paper] Knowledge transfer across mammography datasets: leveraging domain adaptation to limit performance degradation in breast cancer screening tasks — _submission expected in summer/fall 2026_

#### Communications (by topic):
* **Uncertainty calibration for neural nets in imaging tasks**
  * Posters presentation at the [AISTATS workshop _Towards Trustworthy Predictions: Theory and Applications of Calibration for Modern AI_](https://calibration-workshop.github.io/). Tanger. May 2026.
* **Breast cancer detection with convolutional networks on screening mammograms**
  * Poster presentation at [the Women's Health Conference](https://www.mcascientificevents.eu/womens-health-conference/). Paris. September 2025.
  * Oral presentation at the Journée Nationale de la FEHAP (a private hospitals network). Remote. June 2025.
  * Poster presentation at [the annual IABM conference](https://iabm2025.sciencesconf.org/). Nice. March 2025.
* **Breast cancer identification and screening performance estimates based on [the National Health Data System (SNDS) medico-administrative database](https://documentation-snds.health-data-hub.fr/snds/introduction/01-snds.html)**
  * Oral presentation at [the annual Congrès de l'information médicale (EMOIS)](https://www.emois.org/). Nancy. March 2025.
  * Poster presentation at the annual seminar of [the ED393 doctoral school](https://ed393.sorbonne-universite.fr/). Saint-Malo. February 2025.
  * Oral and poster presentations at [the annual conference of the Société française de Sénologie et de Pathologie Mammaire (SFSPM)](https://www.senologie.com/congres/Nantes-2024). Nantes. November 2024.
  * Oral presentation at the annual [Journées françaises de Radiologie (JFR)](https://www.jfr.plus/jfr-2024). Paris. October 2024.
  * Poster presentation at [the EPICLIN conference](https://www.ces-asso.org/conference-epiclin-2024). Dijon. May 2024.
* **[Deep.piste project](https://www.epiconcept.fr/custom-project/deep-piste/) general communications**
  * Oral presentation at [the PariSanté Campus *Démo Day*](https://parisantecampus.fr/agenda/demo-day-3-vivez-linnovation-sante-ia-au-coeur-de-parisante-campus/). Paris. November 2025.
  * Oral presentation at [the Open Science day](https://www.health-data-hub.fr/page/journee-de-lopen-science-en-sante) held by [the Health Data Hub](https://www.health-data-hub.fr/). Paris. April 2024.
" | markdownify }}
</div>

<a id="projects"></a>
<div class="section-card">
  {{ "  
## Projects

#### Deep.piste (2023–ongoing)  
The **Deep.piste** project (*deep learning* and *dépistage*—French for *screening*) aims to assess the **maximum potential impact of artificial intelligence** on the French mammography-based breast cancer screening program. The project is the result of a collaboration between the [Regional Center for Cancer Screening (CRCDC) in Occitanie](https://occitanie-depistagecancer.fr/), [Epiconcept](https://www.epiconcept.fr/en/), the company responsible for the digitization of mammograms in Occitanie, and the [HeKa team](https://heka.gitlabpages.inria.fr/), which brings expertise in deep learning for medical applications.

![Mammograms](/mammos.png)

**Main stages of the Deep.piste project:**
1. §2023-2024§ **Construction of reliable cancer labels** through systematic follow-up of all screened women using data from the [National Health Data System (SNDS)](https://documentation-snds.health-data-hub.fr/snds/introduction/01-snds.html). For this purpose, [sndskit](https://github.com/Epiconcept-Paris/sndskit), a Python package for retrieving SNDS codes and their corresponding dates, was developed.
2. §2024-2025§ **Training of convolutional neural network architectures** to achieve state-of-the-art performance on three tasks: cancer detection, cancer risk prediction, and normality classification.
3. §2025§ **Enhancing model trustworthiness for radiologists**, in particular through the integration of Selective Prediction mechanisms.
4. §2025-2026§ **Evaluation of the maximal performance gains** achievable by the screening program through the integration of trustworthy AI models at different stages of the screening workflow, leading to practical recommendations aimed at improving sensitivity and positive predictive value.

 " | markdownify }}
</div>
