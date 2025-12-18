---
layout: page
permalink: /
background: "/banner.jpg"
---

<a id="about"></a>
<div class="section-card">
  {{ "
# About

I am a Ph.D candidate in the [HeKa](https://heka.gitlabpages.inria.fr/) Inria team hosted at [PariSanté Campus](https://parisantecampus.fr/), under the supervision of [Sandrine Katsahian](https://www.researchgate.net/profile/Sandrine-Katsahian) and [Agathe Guilloux](https://sites.google.com/view/agatheguilloux-personalwebsite). Here is [a short CV](/CV_Emilien_Jemelen.pdf).

My primary research interests lie in statistics and machine learning, with a particular focus on medical imaging applications. In light of the limited interpretability of neural networks, I am especially interested in developing models augmented with application-wise abstention mechanisms (Selective Prediction) that provide performance guarantees and enhance the transparency and reliability of model outputs for end users.

### Contact:

* E-mail: name.surname@inria.fr
* Address: Équipe Inria HeKA, PariSanté Campus,
  2 - 10 Rue d'Oradour-sur-Glane, 75015 Paris. Métro Balard or Porte de Versailles.

### Some non-academic interests:
* Amateur road cycling with the [Equipe Cycliste Vélizy 78](https://www.ecvelizy78.com/) competition team since 2021.
* Long-standing practice of classical guitar, with a repertoire spanning mainly flamenco and Baroque pieces; check out this fantastic [podcast on the legendary duo Ida Presti and Alexandre Lagoya](https://www.radiofrance.fr/francemusique/podcasts/guitare-guitares/ida-presti-et-alexandre-lagoya-7807189) for an overview of one of the greatest duos in the history of the instrument.
" | markdownify }}
</div>

<a id="research"></a>
<div class="section-card">
  {{ "
# Research

### Journal papers:
* *Evaluating breast cancer screening performance without registries using medico-administrative data*. Emilien Jemelen, Francisco Orchard, William Madie, Bernard Valentin, Josine Belin, Enora Laas, Guillaume Jeannerod, Pierre Mares, Sandrine Katsahian, Agathe Guilloux. Nature Scientific Reports 15, 25096 (2025). Link: [paper](https://doi.org/10.1038/s41598-025-10115-w)

### Conference papers: 
* *Beyond Accuracy: Controlling Broad Error Types in Selective Classification*. Emilien Jemelen, Francisco Orchard, Sandrine Katsahian, Agathe Guilloux. Currently under review.

### Communications (by topic):
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
# Projects

### Deep.piste (2023–ongoing)  
The **Deep.piste** project (*deep learning* and *dépistage*—French for *screening*) aims to assess the **maximum potential impact of artificial intelligence** on the French breast cancer screening program. The project is the result of a collaboration between the [Regional Center for Cancer Screening (CRCDC) in Occitanie](https://occitanie-depistagecancer.fr/), [Epiconcept](https://www.epiconcept.fr/en/), the company responsible for the digitization of mammograms in Occitanie, and the [HeKa team](https://heka.gitlabpages.inria.fr/), which brings expertise in deep learning for medical applications.

**Main stages of the Deep.piste project:**
1. §2023-2024§ **Construction of reliable cancer labels** through systematic follow-up of all screened women using data from the [National Health Data System (SNDS)](https://documentation-snds.health-data-hub.fr/snds/introduction/01-snds.html). These labels include interval cancers, defined as cancers diagnosed within 24 months following a negative mammography.
2. §2024-2025§ **Training of convolutional neural network architectures** to achieve state-of-the-art performance on three tasks: cancer detection, cancer risk prediction, and normality classification.
3. §2025§ **Enhancing model trustworthiness for radiologists**, in particular through the integration of Selective Prediction mechanisms.
4. §2025-2026§ **Evaluation of the maximal performance gains** achievable by the screening program through the integration of trustworthy AI models at different stages of the screening workflow, leading to practical recommendations aimed at improving sensitivity and positive predictive value.

 " | markdownify }}
</div>

<a id="teaching"></a>
<div class="section-card">
  {{ "
# Teaching

- Course A
- Course B
" | markdownify }}
</div>
