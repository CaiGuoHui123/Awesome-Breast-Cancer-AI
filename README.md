# Awesome-Breast-Cancer-AI

A curated collection of artificial intelligence studies for breast cancer screening and diagnosis, accompanying our review on technological advances, clinical applications, and clinical evidence.

## About

This repository accompanies our review manuscript:

**From Algorithms to Clinical Evidence: Artificial Intelligence for Breast Cancer Screening and Diagnosis**

Authors: [Guohui Cai](https://github.com/CaiGuoHui123), Jingjing Ma, Jinyong Wang, Leihao Zhao, and Shanshan Cai.

Artificial intelligence for breast cancer screening and diagnosis has evolved from handcrafted features and radiomics to deep learning, attention-based architectures, multimodal and multitask learning, and emerging foundation and vision–language models. Our review connects these technological developments with distinct clinical tasks and the evidence required to assess their reliability and applicability.

This repository organizes the cited literature by primary research focus and provides publication links for further reading.

> **Paper link:** To be updated after publication.

---

## Repository Status

> [!NOTE]
> This repository lists all **187 publications cited in the current manuscript**, including 153 original studies, 18 reviews or background syntheses, and 16 dataset, benchmark, or evaluation resources.
>
> The working literature corpus contained 285 candidate records; these should not be confused with the 187 cited publications. The entries below are based on the manuscript bibliography, and bibliographic metadata and DOI links remain subject to further verification.
>
> **Last updated: November 2026.**

---

## Research Topics

The review connects technological evolution, clinical applications, and evidence reliability across six principal research areas:

- Screening and future cancer risk prediction
- Lesion detection and localization
- Lesion and tissue segmentation
- Lesion classification and BI-RADS risk stratification
- Integrated diagnosis and disease characterization
- Clinical validation and human–AI collaboration

Complementary topics include datasets and reference standards, task-specific metrics, external validation, weak and self-supervised learning, federated learning, foundation models, and vision–language approaches.

---

## Literature Coverage

The cited literature covers **2020 to November 2026**. The review adopts a structured, task-oriented narrative synthesis rather than a preregistered systematic review or quantitative meta-analysis.

| Category                                            | Cited publications |
| --------------------------------------------------- | -----------------: |
| Reviews & Meta-analyses                             |                 18 |
| Screening & Future Risk Prediction                  |                 18 |
| Detection & Localization                            |                 24 |
| Lesion & Tissue Segmentation                        |                 26 |
| Classification & Differential Diagnosis             |                 24 |
| BI-RADS Assessment & Malignancy Risk Stratification |                 12 |
| Multimodal & Multitask Integrated Diagnosis         |                 15 |
| Clinical Validation & Human–AI Collaboration        |                 22 |
| Molecular Phenotype & Lymph Node Assessment         |                 12 |
| Datasets, Benchmarks & Evaluation Resources         |                 16 |
| **Total**                                           |            **187** |

The table counts reflect the current bibliography grouped by principal research focus, not the number of independent patient cohorts or trials. Related publications may share source datasets or clinical trial populations (for example, successive MASAI reports). Studies covering multiple tasks are listed once. The six clinical research areas in the manuscript combine some of these literature categories.

> **2026 coverage:** The manuscript covers publications through November 2026; 2026 does not represent a complete calendar year.

---

# Reviewed Literature

Each category below is expandable. Publication years, titles, authors, journals, and DOI links follow the current manuscript bibliography. The lists include studies discussed in the text as well as the representative studies in the comparison tables.


## Reviews & Meta-analyses (n=18)

Reviews, meta-analyses, and background syntheses of breast imaging AI, risk prediction, diagnostic methods, and clinical implementation.

<details>
<summary><b>Show 18 publications</b></summary>



- **2020** — Bahl. **Artificial intelligence: a primer for breast imaging radiologists.** *Journal of Breast Imaging*. [Paper](https://doi.org/10.1093/jbi/wbaa033)
- **2021** — Freeman et al.. **Use of artificial intelligence for image analysis in breast cancer screening programmes: systematic review of test accuracy.** *bmj*. [Paper](https://doi.org/10.1136/bmj.n1872)
- **2021** — Hickman et al.. **Adoption of artificial intelligence in breast imaging: evaluation, ethical constraints and limitations.** *British journal of cancer*. [Paper](https://doi.org/10.1038/s41416-021-01333-w)
- **2022** — Gastounioti et al.. **Artificial intelligence in mammographic phenotyping of breast cancer risk: a narrative review.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-022-01509-z)
- **2023** — Yoon et al.. **Standalone AI for breast cancer detection at screening digital mammography and digital breast tomosynthesis: a systematic review and meta-analysis.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.222639)
- **2024** — Dan et al.. **Diagnostic performance of deep learning in ultrasound diagnosis of breast cancer: a systematic review.** *NPJ precision oncology*. [Paper](https://doi.org/10.1038/s41698-024-00514-z)
- **2024** — Lin et al.. **A meta-analysis of MRI radiomics-based diagnosis for BI-RADS 4 breast lesions.** *Journal of Cancer Research and Clinical Oncology*. [Paper](https://doi.org/10.1007/s00432-024-05697-3)
- **2024** — Luo et al.. **Deep learning in breast cancer imaging: A decade of progress and future directions.** *IEEE Reviews in Biomedical Engineering*. [Paper](https://doi.org/10.1109/RBME.2024.3357877)
- **2025** — Goh et al.. **Challenges in implementing artificial intelligence in breast cancer screening programs: systematic review and framework for safe adoption.** *Journal of medical Internet research*. [Paper](https://doi.org/10.2196/62941)
- **2025** — Jannatdoust et al.. **Computer-Aided Detection (CADe) and Segmentation Methods for Breast Cancer Using Magnetic Resonance Imaging (MRI).** *Journal of Magnetic Resonance Imaging*. [Paper](https://doi.org/10.1002/jmri.29687)
- **2025** — Lu et al.. **AI in breast imaging: A systematic review of reader studies evaluating design, performance, and clinical impact.** *Medical physics*. [Paper](https://doi.org/10.1002/mp.70018)
- **2026** — Chua et al.. **Artificial intelligence for breast cancer management.** *Communications Medicine*. [Paper](https://doi.org/10.1038/s43856-025-01342-3)
- **2026** — Ciurescu et al.. **Ten Years of Artificial Intelligence in Screening Mammography: A Systematic Review and Meta-Analysis of Diagnostic Accuracy and Clinical Implementation (Literature Published 2015–2025).** *Diagnostics*. [Paper](https://doi.org/10.3390/diagnostics16183045)
- **2026** — El Aboudi et al.. **Recent advances in multimodal deep learning for breast cancer diagnosis using data fusion vision language models and foundation models.** *Discover Artificial Intelligence*. [Paper](https://doi.org/10.1007/s44163-026-02625-x)
- **2026** — Gao et al.. **Application of deep learning technology in breast cancer: a systematic review of segmentation, detection, and classification approaches.** *BioMedical Engineering OnLine*. [Paper](https://doi.org/10.1186/s12938-025-01502-5)
- **2026** — Lowry et al.. **Current state of mammography-based artificial intelligence for future breast cancer risk prediction: a systematic review.** *JNCI: Journal of the National Cancer Institute*. [Paper](https://doi.org/10.1093/jnci/djag002)
- **2026** — Musa et al.. **Generative Artificial Intelligence Models in Breast Cancer Diagnosis: A Systematic Review.** *Diagnostics*. [Paper](https://doi.org/10.3390/diagnostics16203428)
- **2026** — Sossavi et al.. **Artificial intelligence in breast cancer screening: a systematic review and meta-analysis of integration strategies.** *European Journal of Radiology Open*. [Paper](https://doi.org/10.1016/j.ejro.2026.100727)

</details>

---


## Screening & Future Risk Prediction (n=18)

Current-examination triage and screening strategies, future cancer incidence prediction, and individualized screening intervals.

<details>
<summary><b>Show 18 publications</b></summary>



- **2020** — Dembrower et al.. **Effect of artificial intelligence-based triaging of breast cancer screening mammograms on cancer detection and radiologist workload: a retrospective simulation study.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/S2589-7500(20)30185-0)
- **2021** — Raya-Povedano et al.. **AI-based strategies to reduce workload in breast cancer screening with mammography and tomosynthesis: a retrospective evaluation.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.2021203555)
- **2021** — Yala et al.. **Toward robust mammography-based models for breast cancer risk.** *Science translational medicine*. [Paper](https://doi.org/10.1126/scitranslmed.aba4373)
- **2022** — Arasu et al.. **Comparison of mammography artificial intelligence algorithms for 5-year breast cancer risk prediction.** *medRxiv*. [Paper](https://doi.org/10.1148/radiol.222733)
- **2022** — Lehman et al.. **Deep learning vs traditional breast cancer risk models to support risk-based mammography screening.** *Journal of the National Cancer Institute*. [Paper](https://doi.org/10.1093/jnci/djac142)
- **2022** — Yala et al.. **Optimizing risk-based breast cancer screening policies with reinforcement learning.** *Nature medicine*. [Paper](https://doi.org/10.1038/s41591-021-01599-w)
- **2022** — Yala et al.. **Multi-institutional validation of a mammography-based breast cancer risk model.** *Journal of Clinical Oncology*. [Paper](https://doi.org/10.1200/JCO.21.01337)
- **2023** — Eriksson et al.. **Long-term performance of an image-based short-term risk model for breast cancer.** *Journal of Clinical Oncology*. [Paper](https://doi.org/10.1200/JCO.22.01564)
- **2024** — Donnelly et al.. **AsymMirai: interpretable mammography-based deep learning model for 1–5-year breast cancer risk prediction.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.232780)
- **2024** — Eriksson et al.. **European validation of an image-derived AI-based short-term risk model for individualized breast cancer screening—a nested case-control study.** *The Lancet Regional Health–Europe*. [Paper](https://doi.org/10.1016/j.lanepe.2023.100798)
- **2025** — Jiang et al.. **Validation of a dynamic risk prediction model incorporating prior mammograms in a diverse population.** *JAMA network open*. [Paper](https://doi.org/10.1001/jamanetworkopen.2025.12681)
- **2025** — Rothwell et al.. **Evaluation of a mammography-based deep learning model for breast cancer risk prediction in a triennial screening program.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.250391)
- **2025** — Wang et al.. **Predicting short-to long-term breast cancer risk from longitudinal mammographic screening history.** *NPJ Breast Cancer*. [Paper](https://doi.org/10.1038/s41523-025-00831-x)
- **2026** — Arasu et al.. **Comparative 10-year performance of mammography artificial intelligence, polygenic, and clinical breast cancer risk models in the Kaiser Permanente Research Bank.** *JNCI: Journal of the National Cancer Institute*. [Paper](https://doi.org/10.1093/jnci/djag154)
- **2026** — Frazer et al.. **AI-based BRAIx risk score for the intermediate-term prediction of breast cancer: a population cohort study.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/j.landig.2026.100987)
- **2026** — Kaul et al.. **Performance of clinical breast cancer risk prediction models vs a mammography-based artificial intelligence risk model.** *JNCI: Journal of the National Cancer Institute*. [Paper](https://doi.org/10.1093/jnci/djag083)
- **2026** — Lamb et al.. **A Deep Learning Breast Cancer Risk Model for Precise Supplemental Screening.** *JAMA Network Open*. [Paper](https://doi.org/10.1001/jamanetworkopen.2026.10559)
- **2026** — Rothwell et al.. **Performance of breast cancer risk prediction algorithms across mammography systems in the UK screening programme.** *npj Digital Medicine*. [Paper](https://doi.org/10.1038/s41746-026-02507-7)

</details>

---


## Detection & Localization (n=24)

Lesion detection, spatial localization, multiview and volumetric detection, and domain generalization across mammography, DBT, ultrasound, and MRI.

<details>
<summary><b>Show 24 publications</b></summary>



- **2020** — Agarwal et al.. **Deep learning for mass detection in full field digital mammograms.** *Computers in biology and medicine*. [Paper](https://doi.org/10.1016/j.compbiomed.2020.103774)
- **2020** — Fan et al.. **Mass detection and segmentation in digital breast tomosynthesis using 3D-mask region-based convolutional neural network: a comparative analysis.** *Frontiers in molecular biosciences*. [Paper](https://doi.org/10.3389/fmolb.2020.599333)
- **2020** — Li et al.. **3D tumor detection in automated breast ultrasound using deep convolutional neural network.** *Medical Physics*. [Paper](https://doi.org/10.1002/mp.14477)
- **2020** — Yap et al.. **Breast ultrasound region of interest detection and lesion localisation.** *Artificial intelligence in medicine*. [Paper](https://doi.org/10.1016/j.artmed.2020.101880)
- **2021** — Ayatollahi et al.. **Automatic breast lesion detection in ultrafast DCE-MRI using deep learning.** *Medical Physics*. [Paper](https://doi.org/10.1002/mp.15156)
- **2021** — Li et al.. **Deep learning of mammary gland distribution for architectural distortion detection in digital breast tomosynthesis.** *Physics in Medicine & Biology*. [Paper](https://doi.org/10.1088/1361-6560/ab98d0)
- **2021** — Lotter et al.. **Robust breast cancer detection in mammography and digital breast tomosynthesis using an annotation-efficient deep learning approach.** *Nature medicine*. [Paper](https://doi.org/10.1038/s41591-020-01174-9)
- **2021** — Yan et al.. **Towards improved breast mass detection using dual-view mammogram matching.** *Medical image analysis*. [Paper](https://doi.org/10.1016/j.media.2021.102083)
- **2022** — Garrucho et al.. **Domain generalization in deep learning based mass detection in mammography: A large-scale multi-center study.** *Artificial Intelligence in Medicine*. [Paper](https://doi.org/10.1016/j.artmed.2022.102386)
- **2023** — Jailin et al.. **AI-based cancer detection model for contrast-enhanced mammography.** *Bioengineering*. [Paper](https://doi.org/10.3390/bioengineering10080974)
- **2023** — Meng et al.. **DGANet: a dual global attention neural network for breast lesion detection in ultrasound images.** *Ultrasound in medicine & biology*. [Paper](https://doi.org/10.1016/j.ultrasmedbio.2022.07.006)
- **2023** — Zhang et al.. **Deep learning-based automatic diagnosis of breast cancer on MRI using mask R-CNN for detection followed by ResNet50 for classification.** *Academic radiology*. [Paper](https://doi.org/10.1016/j.acra.2022.12.038)
- **2024** — Jing et al.. **Localization of contrast-enhanced breast lesions in ultrafast screening MRI using deep convolutional neural networks.** *European Radiology*. [Paper](https://doi.org/10.1007/s00330-023-10184-3)
- **2024** — Wang et al.. **Weakly supervised lesion detection and diagnosis for breast cancers with partially annotated ultrasound images.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2024.3366940)
- **2025** — Camurdan et al.. **Annotation-efficient, patch-based, explainable deep learning using curriculum method for breast cancer detection in screening mammography.** *Insights into Imaging*. [Paper](https://doi.org/10.1186/s13244-025-01922-w)
- **2025** — Chen et al.. **Combination of deep learning grad-CAM and radiomics for automatic localization and diagnosis of architectural distortion on DBT.** *Academic radiology*. [Paper](https://doi.org/10.1016/j.acra.2024.10.031)
- **2025** — Hirsch et al.. **High-performance open-source Ai for breast cancer detection and localization in MRI.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.240550)
- **2025** — Ma et al.. **YOLO AI model based on an automated breast volume scanner for the detection of benign and malignant breast lesions.** *Quantitative Imaging in Medicine and Surgery*. [Paper](https://doi.org/10.21037/qims-24-2079)
- **2025** — Martiniussen et al.. **Performance of two deep learning–based ai models for breast cancer detection and localization on screening mammograms from breastscreen norway.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.240039)
- **2025** — Oviedo et al.. **Cancer detection in breast MRI screening via explainable AI anomaly detection.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.241629)
- **2026** — He et al.. **Multi-scale and context-aware enhanced YOLOv8 for breast tumor detection in ultrasound images.** *Scientific Reports*. [Paper](https://doi.org/10.1038/s41598-026-59928-3)
- **2026** — Kim et al.. **Factors Associated with False-Positive Marks and False-Negative Cancers on Automated Breast Ultrasound Using an Artificial Intelligence–Based Computer-Aided Detection System.** *Journal of Imaging Informatics in Medicine*. [Paper](https://doi.org/10.1007/s10278-026-02306-2)
- **2026** — Panigrahi et al.. **Artificial Intelligence Detection of Interval Breast Cancers on False-negative Screening Mammograms: A Retrospective Lesion-level Analysis.** *Academic Radiology*. [Paper](https://doi.org/10.1016/j.acra.2026.08.034)
- **2026** — Tang et al.. **International Application of Artificial Intelligence for Lesion Detection on Digital Breast Tomosynthesis: Comparing Western and Eastern Databases.** *Academic Radiology*. [Paper](https://doi.org/10.1016/j.acra.2026.08.039)

</details>

---


## Lesion & Tissue Segmentation (n=26)

Pixel- and voxel-level delineation of breast lesions and tissues, including U-Net variants, Transformers, weak supervision, and adapted foundation models.

<details>
<summary><b>Show 26 publications</b></summary>



- **2020** — Byra et al.. **Breast mass segmentation in ultrasound with selective kernel U-Net convolutional neural network.** *Biomedical signal processing and control*. [Paper](https://doi.org/10.1016/j.bspc.2020.102027)
- **2020** — Gómez-Flores et al.. **A comparative study of pre-trained convolutional neural networks for semantic segmentation of breast tumors in ultrasound.** *Computers in Biology and Medicine*. [Paper](https://doi.org/10.1016/j.compbiomed.2020.104036)
- **2021** — Baccouche et al.. **Connected-UNets: a deep learning architecture for breast mass segmentation.** *NPJ breast cancer*. [Paper](https://doi.org/10.1038/s41523-021-00358-x)
- **2021** — Huo et al.. **Segmentation of whole breast and fibroglandular tissue using nnU-Net in dynamic contrast enhanced MR images.** *Magnetic Resonance Imaging*. [Paper](https://doi.org/10.1016/j.mri.2021.06.017)
- **2021** — Lei et al.. **Breast tumor segmentation in 3D automatic breast ultrasound using Mask scoring R-CNN.** *Medical physics*. [Paper](https://doi.org/10.1002/mp.14569)
- **2021** — Webb et al.. **Comparing deep learning-based automatic segmentation of breast masses to expert interobserver variability in ultrasound imaging.** *Computers in biology and medicine*. [Paper](https://doi.org/10.1016/j.compbiomed.2021.104966)
- **2021** — Xue et al.. **Global guidance network for breast lesion segmentation in ultrasound images.** *Medical image analysis*. [Paper](https://doi.org/10.1016/j.media.2021.101989)
- **2022** — Hirsch et al.. **Radiologist-Level Performance by Using Deep Learning for Segmentation of Breast Cancers on MRI Scans.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.200231)
- **2022** — Li et al.. **Deep weakly-supervised breast tumor segmentation in ultrasound images with explicit anatomical constraints.** *Medical image analysis*. [Paper](https://doi.org/10.1016/j.media.2021.102315)
- **2022** — Ning et al.. **SMU-Net: Saliency-Guided Morphology-Aware U-Net for Breast Lesion Segmentation in Ultrasound Image.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2021.3116087)
- **2022** — Shareef et al.. **ESTAN: Enhanced Small Tumor-Aware Network for Breast Ultrasound Image Segmentation.** *Healthcare*. [Paper](https://doi.org/10.3390/healthcare10112262)
- **2022** — Shen et al.. **Dilated transformer: residual axial attention for breast ultrasound image segmentation.** *Quantitative Imaging in Medicine and Surgery*. [Paper](https://doi.org/10.21037/qims-22-33)
- **2022** — Su et al.. **YOLO-LOGO: A transformer-based YOLO segmentation model for breast mass detection and segmentation in digital mammograms.** *Computer Methods and Programs in Biomedicine*. [Paper](https://doi.org/10.1016/j.cmpb.2022.106903)
- **2022** — Yue et al.. **Deep learning-based automatic segmentation for size and volumetric measurement of breast cancer on magnetic resonance imaging.** *Frontiers in oncology*. [Paper](https://doi.org/10.3389/fonc.2022.984626)
- **2023** — Wu et al.. **Cross-image dependency modeling for breast ultrasound segmentation.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2022.3233648)
- **2023** — Zhang et al.. **A robust and efficient AI assistant for breast tumor segmentation from DCE-MRI via a spatial-temporal framework.** *Patterns*. [Paper](https://doi.org/10.1016/j.patter.2023.100826)
- **2024** — Bartolotta et al.. **Artificial intelligence-based, semi-automated segmentation for the extraction of ultrasound-derived radiomics features in breast cancer: a prospective multicenter study.** *La radiologia medica*. [Paper](https://doi.org/10.1007/s11547-024-01826-7)
- **2024** — Chen et al.. **Modality-specific information disentanglement from multi-parametric MRI for breast tumor segmentation and computer-aided diagnosis.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2024.3352648)
- **2024** — Park et al.. **3D breast cancer segmentation in DCE-MRI using deep learning with weak annotation.** *Journal of Magnetic Resonance Imaging*. [Paper](https://doi.org/10.1002/jmri.28960)
- **2025** — Guo et al.. **ESAM2-BLS: Enhanced segment anything model 2 for efficient breast lesion segmentation in ultrasound imaging.** *Computerized Medical Imaging and Graphics*. [Paper](https://doi.org/10.1016/j.compmedimag.2025.102654)
- **2025** — Liu et al.. **ABVS breast tumour segmentation via integrating CNN with dilated sampling self-attention and feature interaction transformer.** *Neural Networks*. [Paper](https://doi.org/10.1016/j.neunet.2025.107312)
- **2025** — Manolakis et al.. **A two-stage lightweight deep learning framework for mass detection and segmentation in mammograms using YOLOv5 and depthwise SegNet.** *Journal of Imaging Informatics in Medicine*. [Paper](https://doi.org/10.1007/s10278-025-01471-0)
- **2026** — Haqkiem et al.. **BreAST-U²Net: A Twin-Stream U2Net with Attention-based Tumor Fusion for 2-D Tumor Segmentation in Automated Breast Ultrasound.** *Ultrasound in Medicine & Biology*. [Paper](https://doi.org/10.1016/j.ultrasmedbio.2025.09.011)
- **2026** — Kosugi et al.. **Dual-encoder 3D transformer-based U-Net with temporal attention for non-mass enhancement segmentation in breast dynamic contrast-enhanced MRI.** *Radiological Physics and Technology*. [Paper](https://doi.org/10.1007/s12194-025-01004-y)
- **2026** — Vicentini et al.. **Automated Segmentation of Mass Lesions in Mammography: Mask R-CNN Versus Classical Methods, Fuzzy Clustering and MedSAM.** *Diagnostics*. [Paper](https://doi.org/10.3390/diagnostics16203289)
- **2026** — Xu et al.. **DRSeg: a weakly supervised framework for breast ultrasound image segmentation.** *Scientific Reports*. [Paper](https://doi.org/10.1038/s41598-026-49728-0)

</details>

---


## Classification & Differential Diagnosis (n=24)

Benign–malignant classification and differential diagnosis, including radiomics, deep learning, cross-dataset testing, and specialized diagnostic tasks.

<details>
<summary><b>Show 24 publications</b></summary>



- **2020** — Fanizzi et al.. **A machine learning approach on multiscale texture analysis for breast microcalcification diagnosis.** *BMC bioinformatics*. [Paper](https://doi.org/10.1186/s12859-020-3358-4)
- **2020** — Lin et al.. **Contrast-enhanced spectral mammography-based radiomics nomogram for identifying benign and malignant breast lesions of sub-1 cm.** *Frontiers in Oncology*. [Paper](https://doi.org/10.3389/fonc.2020.573630)
- **2020** — Shu et al.. **Deep neural networks with region-based pooling structures for mammographic image classification.** *IEEE transactions on medical imaging*. [Paper](https://doi.org/10.1109/TMI.2020.2968397)
- **2020** — Wang et al.. **Inconsistent performance of deep learning models on mammogram classification.** *Journal of the American College of Radiology*. [Paper](https://doi.org/10.1016/j.jacr.2020.01.006)
- **2020** — Wang et al.. **Breast cancer classification in automated breast ultrasound using multiview convolutional neural network with transfer learning.** *Ultrasound in medicine & biology*. [Paper](https://doi.org/10.1016/j.ultrasmedbio.2020.01.001)
- **2021** — Chen et al.. **Domain knowledge powered deep learning for breast cancer diagnosis based on contrast-enhanced ultrasound videos.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2021.3078370)
- **2021** — Hu et al.. **Improved classification of benign and malignant breast lesions using deep feature maximum intensity projection MRI in breast cancer diagnosis using dynamic contrast-enhanced MRI.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.2021200159)
- **2021** — Romeo et al.. **Clinical value of radiomics and machine learning in breast ultrasound: a multicenter study for differential diagnosis of benign and malignant lesions.** *European radiology*. [Paper](https://doi.org/10.1007/s00330-021-08009-2)
- **2021** — Wan et al.. **Evaluation of the performance of traditional machine learning algorithms, convolutional neural network and AutoML Vision in ultrasound breast lesions classification: a comparative study.** *Quantitative imaging in medicine and surgery*. [Paper](https://doi.org/10.21037/qims-20-922)
- **2022** — Gu et al.. **Deep learning based on ultrasound images assists breast lesion diagnosis in China: a multicenter diagnostic study.** *Insights into imaging*. [Paper](https://doi.org/10.1186/s13244-022-01259-8)
- **2022** — Qu et al.. **A VGG attention vision transformer network for benign and malignant classification of breast ultrasound images.** *Medical Physics*. [Paper](https://doi.org/10.1002/mp.15852)
- **2022** — Wang et al.. **An artificial intelligence system using maximum intensity projection MR images facilitates classification of non-mass enhancement breast lesions.** *European Radiology*. [Paper](https://doi.org/10.1007/s00330-022-08553-5)
- **2022** — Wang et al.. **Diagnostic performance of perilesional radiomics analysis of contrast-enhanced mammography for the differentiation of benign and malignant breast lesions.** *European radiology*. [Paper](https://doi.org/10.1007/s00330-021-08134-y)
- **2023** — Jiménez-Sánchez et al.. **Memory-aware curriculum federated learning for breast cancer classification.** *Computer Methods and Programs in Biomedicine*. [Paper](https://doi.org/10.1016/j.cmpb.2022.107318)
- **2023** — Mo et al.. **Hover-trans: Anatomy-aware hover-transformer for roi-free breast cancer diagnosis in ultrasound images.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2023.3236011)
- **2023** — Zhao et al.. **Deep learning-based classification of breast lesions using dynamic ultrasound video.** *European Journal of Radiology*. [Paper](https://doi.org/10.1016/j.ejrad.2023.110885)
- **2024** — Kassis et al.. **Detection of breast cancer in digital breast tomosynthesis with vision transformers.** *Scientific Reports*. [Paper](https://doi.org/10.1038/s41598-024-72707-2)
- **2024** — Yan et al.. **A domain knowledge-based interpretable deep learning system for improving clinical breast ultrasound diagnosis.** *Communications Medicine*. [Paper](https://doi.org/10.1038/s43856-024-00518-7)
- **2024** — Zhang et al.. **Artificial intelligence-based classification of breast lesion from contrast enhanced mammography: a multicenter study.** *International journal of surgery (London, England)*. [Paper](https://doi.org/10.1097/JS9.0000000000001076)
- **2025** — Saldanha et al.. **Swarm learning with weak supervision enables automatic breast cancer detection in magnetic resonance imaging.** *Communications medicine*. [Paper](https://doi.org/10.1038/s43856-024-00722-5)
- **2025** — Woo et al.. **Subgroup evaluation to understand performance gaps in deep learning-based classification of regions of interest on mammography.** *PLOS Digital Health*. [Paper](https://doi.org/10.1371/journal.pdig.0000811)
- **2026** — Yan et al.. **Channel attention of the image for distinguishing ductal carcinoma in situ from benign mimics based on ultrasound images.** *Gland Surgery*. [Paper](https://doi.org/10.21037/gs-2026-0391)
- **2026** — Zhang et al.. **Development and validation of an interpretable ultrasound radiomics model for benign and malignant classification of breast lesions: a multicenter large-sample study.** *Insights into Imaging*. [Paper](https://doi.org/10.1186/s13244-026-02344-y)
- **2026** — Zhou et al.. **An explainable machine learning framework utilizing ultrasound radiomics for the preoperative differentiation between granulomatous lobular mastitis and breast cancer.** *Frontiers in Oncology*. [Paper](https://doi.org/10.3389/fonc.2026.1641681)

</details>

---


## BI-RADS Assessment & Malignancy Risk Stratification (n=12)

BI-RADS category or descriptor prediction and pathology-referenced risk estimation, including studies of suspicious lesions and biopsy decision support.

<details>
<summary><b>Show 12 publications</b></summary>



- **2020** — Hao et al.. **Application of MRI radiomics-based machine learning model to improve contralateral BI-RADS 4 lesion assessment.** *Frontiers in oncology*. [Paper](https://doi.org/10.3389/fonc.2020.531476)
- **2021** — Liu et al.. **A deep learning model integrating mammography and clinical factors facilitates the malignancy prediction of BI-RADS 4 microcalcifications in breast cancer screening.** *European Radiology*. [Paper](https://doi.org/10.1007/s00330-020-07659-y)
- **2022** — Tsai et al.. **A high-performance deep neural network model for BI-RADS classification of screening mammography.** *Sensors*. [Paper](https://doi.org/10.3390/s22031160)
- **2023** — Ezeana et al.. **A deep learning decision support tool to improve risk stratification and reduce unnecessary biopsies in BI-RADS 4 mammograms.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.220259)
- **2023** — Gu et al.. **Ultrasound-based deep learning in the establishment of a breast lesion risk stratification system: a multicenter study.** *European Radiology*. [Paper](https://doi.org/10.1007/s00330-022-09263-8)
- **2023** — Zhang et al.. **BI-RADS-NET-V2: a composite multi-task neural network for computer-aided diagnosis of breast cancer in ultrasound images with semantic and quantitative explanations.** *IEEE access*. [Paper](https://doi.org/10.1109/ACCESS.2023.3298569)
- **2024** — Guldogan et al.. **Artificial intelligence in BI-RADS categorization of breast lesions on ultrasound: can we omit excessive follow-ups and biopsies?.** *Academic Radiology*. [Paper](https://doi.org/10.1016/j.acra.2023.11.031)
- **2024** — Liu et al.. **Deep learning of mammogram images to reduce unnecessary breast biopsies: a preliminary study.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-024-01830-9)
- **2025** — Hu et al.. **Intra-and peri-tumoral radiomics based on dynamic contrast-enhanced MRI for prediction of benign disease in BI-RADS 4 breast lesions: a multicentre study.** *Radiation Oncology*. [Paper](https://doi.org/10.1186/s13014-025-02605-y)
- **2025** — Lu et al.. **Ultrasound-based deep learning radiomics for multi-stage assisted diagnosis in reducing unnecessary biopsies of BI-RADS 4A lesions.** *Quantitative Imaging in Medicine and Surgery*. [Paper](https://doi.org/10.21037/qims-24-580)
- **2025** — Tan et al.. **Mammography-based artificial intelligence for breast cancer detection, diagnosis, and BI-RADS categorization using multi-view and multi-level convolutional neural networks.** *Insights into Imaging*. [Paper](https://doi.org/10.1186/s13244-025-01983-x)
- **2026** — Liang et al.. **An interpretable AI system reduces false-positive MRI diagnoses by stratifying high-risk breast lesions.** *Nature Communications*. [Paper](https://doi.org/10.1038/s41467-026-69212-7)

</details>

---


## Multimodal & Multitask Integrated Diagnosis (n=15)

Multiview and multimodal fusion, joint diagnostic tasks, missing-modality handling, generative foundation models, vision-language models, and report analysis.

<details>
<summary><b>Show 15 publications</b></summary>



- **2021** — Huang et al.. **AW3M: An auto-weighting and recovery framework for breast cancer diagnosis using multi-modal ultrasound.** *Medical image analysis*. [Paper](https://doi.org/10.1016/j.media.2021.102137)
- **2021** — Qian et al.. **Prospective assessment of breast cancer risk from multimodal multiview ultrasound images via clinically applicable deep learning.** *Nature biomedical engineering*. [Paper](https://doi.org/10.1038/s41551-021-00711-2)
- **2021** — Zhou et al.. **Multi-task learning for segmentation and classification of tumors in 3D automated breast ultrasound images.** *Medical image analysis*. [Paper](https://doi.org/10.1016/j.media.2020.101918)
- **2022** — Pfob et al.. **The importance of multi-modal imaging and clinical information for humans and AI-based algorithms to classify breast masses (INSPiRED 003): an international, multicenter analysis.** *European radiology*. [Paper](https://doi.org/10.1007/s00330-021-08519-z)
- **2022** — Xu et al.. **Multi-region radiomics for artificially intelligent diagnosis of breast cancer using multimodal ultrasound.** *Computers in Biology and Medicine*. [Paper](https://doi.org/10.1016/j.compbiomed.2022.105920)
- **2023** — Tan et al.. **Multi-modal artificial intelligence for the combination of automated 3D breast ultrasound and mammograms in a population of women with predominantly dense breasts.** *Insights into Imaging*. [Paper](https://doi.org/10.1186/s13244-022-01352-y)
- **2024** — Sushil et al.. **A comparative study of large language model-based zero-shot inference and task-specific supervised classification of breast cancer pathology reports.** *Journal of the American Medical Informatics Association*. [Paper](https://doi.org/10.1093/jamia/ocae146)
- **2024** — Zhou et al.. **Multitask deep learning-based whole-process system for automatic diagnosis of breast lesions and axillary lymph node metastasis discrimination from dynamic contrast-enhanced-MRI: A multicenter study.** *Journal of Magnetic Resonance Imaging*. [Paper](https://doi.org/10.1002/jmri.28913)
- **2025** — Li et al.. **Vision transformer-based multimodal fusion network for classification of tumor malignancy on breast ultrasound: A retrospective multicenter study.** *International Journal of Medical Informatics*. [Paper](https://doi.org/10.1016/j.ijmedinf.2025.105793)
- **2025** — Xu et al.. **Optimizing breast lesions diagnosis and decision-making with a deep learning fusion model integrating ultrasound and mammography: a dual-center retrospective study.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-025-02033-6)
- **2026** — Azhar et al.. **Semiautomated breast ultrasound report generation using multimodal large language models and deep learning.** *Frontiers in Medicine*. [Paper](https://doi.org/10.3389/fmed.2026.1679203)
- **2026** — Chen et al.. **An Alignment and Imputation Network (AINet) for Breast Cancer Diagnosis With Multimodal Multi-View Ultrasound Images.** *IEEE Transactions on Medical Imaging*. [Paper](https://doi.org/10.1109/TMI.2025.3625254)
- **2026** — Khan et al.. **On the transfer learning behavior of domain-specific vision–language models in screening mammography.** *Journal of biomedical informatics*. [Paper](https://doi.org/10.1016/j.jbi.2026.104986)
- **2026** — Li et al.. **A deep learning system for non-invasive breast cancer diagnosis with multimodal data.** *Nature Biomedical Engineering*. [Paper](https://doi.org/10.1038/s41551-026-01654-2)
- **2026** — Yu et al.. **A foundation generative model for breast ultrasound image analysis.** *Nature Biomedical Engineering*. [Paper](https://doi.org/10.1038/s41551-026-01639-1)

</details>

---


## Clinical Validation & Human–AI Collaboration (n=22)

Standalone and reader comparisons, workflow simulations, controlled reader studies, prospective evaluation, randomized trials, and clinical deployment.

<details>
<summary><b>Show 22 publications</b></summary>



- **2020** — Kim et al.. **Changes in cancer detection and false-positive recall in mammography using artificial intelligence: a retrospective, multireader study.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/S2589-7500(20)30003-0)
- **2020** — Mango et al.. **Should we ignore, follow, or biopsy? Impact of artificial intelligence decision support on breast ultrasound lesion assessment.** *American Journal of Roentgenology*. [Paper](https://doi.org/10.2214/AJR.19.21872)
- **2020** — McKinney et al.. **International evaluation of an AI system for breast cancer screening.** *Nature*. [Paper](https://doi.org/10.1038/s41586-019-1799-6)
- **2020** — Schaffter et al.. **Evaluation of combined artificial intelligence and radiologist assessment to interpret screening mammograms.** *JAMA network open*. [Paper](https://doi.org/10.1001/jamanetworkopen.2020.0265)
- **2021** — Jiang et al.. **Artificial intelligence applied to breast MRI for improved diagnosis.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.2020200292)
- **2021** — van Winkel et al.. **Impact of artificial intelligence support on accuracy and reading time in breast tomosynthesis image interpretation: a multi-reader multi-case study.** *European radiology*. [Paper](https://doi.org/10.1007/s00330-021-07992-w)
- **2022** — Leibig et al.. **Combining the strengths of radiologists and AI for breast cancer screening: a retrospective analysis.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/S2589-7500(22)00070-X)
- **2023** — Dembrower et al.. **Artificial intelligence for breast cancer detection in screening mammography in Sweden: a prospective, population-based, paired-reader, non-inferiority study.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/S2589-7500(23)00153-X)
- **2023** — Dratsch et al.. **Automation bias in mammography: the impact of artificial intelligence BI-RADS suggestions on reader performance.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.222176)
- **2023** — Lång et al.. **Artificial intelligence-supported screen reading versus standard double reading in the Mammography Screening with Artificial Intelligence trial (MASAI): a clinical safety analysis of a randomised, controlled, non-inferiority, single-blinded, screening accuracy study.** *The Lancet Oncology*. [Paper](https://doi.org/10.1016/S1470-2045(23)00298-X)
- **2023** — Ng et al.. **Prospective implementation of AI-assisted screen reading to improve early detection of breast cancer.** *Nature Medicine*. [Paper](https://doi.org/10.1038/s41591-023-02625-9)
- **2024** — Salim et al.. **AI-based selection of individuals for supplemental MRI in population-based breast cancer screening: the randomized ScreenTrustMRI trial.** *Nature medicine*. [Paper](https://doi.org/10.1038/s41591-024-03093-5)
- **2024** — van Dooijeweert et al.. **Clinical implementation of artificial-intelligence-assisted detection of breast cancer metastases in sentinel lymph nodes: the CONFIDENT-B single-center, non-randomized clinical trial.** *Nature cancer*. [Paper](https://doi.org/10.1038/s43018-024-00788-z)
- **2025** — Chang et al.. **Artificial intelligence for breast cancer screening in mammography (AI-STREAM): preliminary analysis of a prospective multicenter cohort study.** *Nature Communications*. [Paper](https://doi.org/10.1038/s41467-025-57469-3)
- **2025** — Eisemann et al.. **Nationwide real-world implementation of AI for cancer detection in population-based mammography screening.** *Nature medicine*. [Paper](https://doi.org/10.1038/s41591-024-03408-6)
- **2025** — Hernström et al.. **Screening performance and characteristics of breast cancer detected in the Mammography Screening with Artificial Intelligence trial (MASAI): a randomised, controlled, parallel-group, non-inferiority, single-blinded, screening accuracy study.** *The Lancet Digital Health*. [Paper](https://doi.org/10.1016/S2589-7500(24)00267-X)
- **2026** — De Vries et al.. **Prospective evaluation of artificial intelligence integration into breast cancer screening in multiple workflow settings: the GEMINI study.** *Nature Cancer*. [Paper](https://doi.org/10.1038/s43018-026-01126-1)
- **2026** — Elías-Cabot et al.. **AI-based triage and decision support in mammography and digital tomosynthesis for breast cancer screening: a paired, noninferiority trial.** *Nature Medicine*. [Paper](https://doi.org/10.1038/s41591-026-04277-x)
- **2026** — Gommers et al.. **Interval cancer, sensitivity, and specificity comparing AI-supported mammography screening with standard double reading without AI in the MASAI study: a randomised, controlled, non-inferiority, single-blinded, population-based, screening-accuracy trial.** *The Lancet*. [Paper](https://doi.org/10.1016/S0140-6736(25)02464-X)
- **2026** — Kelly et al.. **Diagnostic accuracy, fairness and clinical implementation of AI for breast cancer screening: results of multicenter retrospective and prospective technical feasibility studies.** *Nature cancer*. [Paper](https://doi.org/10.1038/s43018-026-01127-0)
- **2026** — Lehnen et al.. **AI software as a third reader in breast cancer screening—a prospective diagnostic observational study.** *European radiology*. [Paper](https://doi.org/10.1007/s00330-026-12359-0)
- **2026** — Zhou et al.. **A non-invasive end-to-end intelligent assistance system for breast ultrasound.** *Nature Communications*. [Paper](https://doi.org/10.1038/s41467-026-73170-5)

</details>

---


## Molecular Phenotype & Lymph Node Assessment (n=12)

AI-assisted molecular subtype, biomarker, and lymph node assessment using imaging, histopathology, and complementary clinical information.

<details>
<summary><b>Show 12 publications</b></summary>



- **2020** — Jaber et al.. **A deep learning image-based intrinsic molecular subtype classifier of breast tumors reveals tumor heterogeneity that may affect survival.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-020-1248-3)
- **2020** — Zheng et al.. **Deep learning radiomics can predict axillary lymph node status in early-stage breast cancer.** *Nature communications*. [Paper](https://doi.org/10.1038/s41467-020-15027-z)
- **2021** — Yu et al.. **Magnetic resonance imaging radiomics predicts preoperative axillary lymph node metastasis to support surgical decisions and is associated with tumor microenvironment in invasive breast cancer: a machine learning, multicenter study.** *EBioMedicine*. [Paper](https://doi.org/10.1016/j.ebiom.2021.103460)
- **2021** — Zhou et al.. **Decoding the molecular subtypes of breast cancer seen on multimodal ultrasound images using an assembled convolutional neural network model: A prospective and multicentre study.** *EBioMedicine*. [Paper](https://doi.org/10.1016/j.ebiom.2021.103684)
- **2023** — Chen et al.. **Development and validation of convolutional neural network-based model to predict the risk of sentinel or non-sentinel lymph node metastasis in patients with breast cancer: a machine learning study.** *EClinicalMedicine*. [Paper](https://doi.org/10.1016/j.eclinm.2023.102176)
- **2023** — Ramtohul et al.. **Multiparametric MRI and radiomics for the prediction of HER2-zero,-low, and-positive breast cancers.** *Radiology*. [Paper](https://doi.org/10.1148/radiol.222646)
- **2024** — Chen et al.. **Quantification of intratumoral heterogeneity using habitat-based MRI radiomics to identify HER2-positive,-low and-zero breast cancers: a multicenter study.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-024-01921-7)
- **2024** — Liu et al.. **Deep learning radiomics based prediction of axillary lymph node metastasis in breast cancer.** *NPJ Breast Cancer*. [Paper](https://doi.org/10.1038/s41523-024-00628-4)
- **2025** — Tang et al.. **Preoperative prediction of axillary lymph node metastasis in patients with breast cancer through multimodal deep learning based on ultrasound and magnetic resonance imaging images.** *Academic radiology*. [Paper](https://doi.org/10.1016/j.acra.2024.07.029)
- **2025** — Wong et al.. **AI-driven MRI biomarker for triple-class HER2 expression classification in breast cancer: a large-scale multicenter study.** *Breast Cancer Research*. [Paper](https://doi.org/10.1186/s13058-025-02118-2)
- **2026** — Lu et al.. **A multimodal ultrasound-based model combining tumor radiomics and axillary lymph node morphologic classification for predicting axillary nodal burden in breast cancer.** *Frontiers in Endocrinology*. [Paper](https://doi.org/10.3389/fendo.2026.1847368)
- **2026** — Yu et al.. **Deep learning model for noninvasive prediction of Ki-67 expression and prognostic stratification in breast cancer: a multicenter retrospective study.** *European Radiology*. [Paper](https://doi.org/10.1007/s00330-025-12203-x)

</details>

---


## Datasets, Benchmarks & Evaluation Resources (n=16)

Breast imaging datasets, task benchmarks, evaluation studies, and reporting guidelines (CLAIM, TRIPOD+AI, and STARD-AI).

<details>
<summary><b>Show 16 publications</b></summary>



- **2021** — Buda et al.. **A data set and deep learning algorithm for the detection of masses and architectural distortions in digital breast tomosynthesis images.** *JAMA network open*. [Paper](https://doi.org/10.1001/jamanetworkopen.2021.19100)
- **2023** — Jeong et al.. **The EMory BrEast imaging Dataset (EMBED): A Racially Diverse, Granular Dataset of 3.4 Million Screening and Diagnostic Mammographic Images.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.220047)
- **2023** — Nguyen et al.. **VinDr-Mammo: A large-scale benchmark dataset for computer-aided diagnosis in full-field digital mammography.** *Scientific Data*. [Paper](https://doi.org/10.1038/s41597-023-02100-7)
- **2024** — Collins et al.. **TRIPOD+ AI statement: updated guidance for reporting clinical prediction models that use regression or machine learning methods.** *bmj*. [Paper](https://doi.org/10.1136/bmj-2023-078378)
- **2024** — Gómez-Flores et al.. **BUS-BRA: a breast ultrasound dataset for assessing computer-aided diagnosis systems.** *Medical physics*. [Paper](https://doi.org/10.1002/mp.16812)
- **2024** — Pawłowska et al.. **Curated benchmark dataset for ultrasound based breast lesion analysis.** *Scientific Data*. [Paper](https://doi.org/10.1038/s41597-024-02984-z)
- **2024** — Tejani et al.. **Checklist for artificial intelligence in medical imaging (CLAIM): 2024 update.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.240300)
- **2025** — Garrucho et al.. **A large-scale multicenter breast cancer DCE-MRI benchmark dataset with expert segmentations.** *Scientific data*. [Paper](https://doi.org/10.1038/s41597-025-04707-4)
- **2025** — Sounderajah et al.. **The STARD-AI reporting guideline for diagnostic accuracy studies using artificial intelligence.** *Nature medicine*. [Paper](https://doi.org/10.1038/s41591-025-03953-8)
- **2025** — Zhu et al.. **A benchmark for breast cancer screening and diagnosis in mammogram visual question answering.** *Nature Communications*. [Paper](https://doi.org/10.1038/s41467-025-66507-z)
- **2026** — Fridman et al.. **BreastDCEDL: A standardized deep learning-ready breast DCE-MRI dataset of 2,070 patients.** *Scientific Data*. [Paper](https://doi.org/10.1038/s41597-026-06589-6)
- **2026** — Mabrok. **Side-level versus patient-level evaluation in four-view mammography classification: a comprehensive benchmark on the CMMD dataset.** *Future Science OA*. [Paper](https://doi.org/10.1080/20565623.2026.2681575)
- **2026** — Pan et al.. **LUMINA: A Multi-Vendor Mammography Benchmark with Energy Harmonization Protocol.** *arXiv preprint arXiv:2603.14644*. [Paper](https://doi.org/10.48550/arXiv.2603.14644)
- **2026** — Trivedi et al.. **Open-Source Dataset for the RSNA Screening Mammography Cancer Detection Challenge.** *Radiology: Artificial Intelligence*. [Paper](https://doi.org/10.1148/ryai.250375)
- **2026** — Wang. **Breast Ultrasound AI Under Dataset Shift: A Patient-Leakage-Aware Benchmark.** *Diagnostics*. [Paper](https://doi.org/10.3390/diagnostics16101537)
- **2026** — Yu et al.. **A chain-of-thought reasoning breast ultrasound dataset covering all histopathology categories.** *Scientific Data*. [Paper](https://doi.org/10.1038/s41597-026-06702-9)

</details>

---

# Technology Evolution

**Handcrafted Features & Radiomics → Deep Representation Learning → Detection & Segmentation Networks → Attention & Transformers → Integrated Learning & Foundation Models**

Representative approaches include traditional machine learning, CNNs, volumetric and temporal learning, multiview fusion, weakly supervised and self-supervised learning, transfer learning, federated learning, multimodal and multitask learning, generative models, and vision–language models. These approaches coexist and are not mutually exclusive stages of development.

---

# Major Clinical Tasks

### Screening & Risk Prediction

Support current-examination interpretation, screening triage, and estimation of future cancer risk over defined prediction horizons.

### Detection & Localization

Identify suspicious breast abnormalities and their spatial locations in full images, multiple views, or three-dimensional examinations.

### Lesion & Tissue Segmentation

Delineate lesion and tissue boundaries to support quantitative imaging and downstream assessment.

### Classification & Risk Stratification

Distinguish benign from malignant lesions, predict clinically relevant lesion characteristics, and support BI-RADS assessment or pathology-referenced malignancy risk estimation.

### Integrated Diagnosis & Disease Characterization

Combine complementary imaging and clinical information or related prediction tasks, including molecular phenotype and lymph node assessment.

### Clinical Validation & Human–AI Collaboration

Evaluate AI in external cohorts, controlled reader studies, prospective clinical investigations, and real-world screening and diagnostic workflows.

---

# Evaluation Metrics

Different clinical tasks require different outcomes, reference standards, and units of analysis. Numerical values from different studies are not directly comparable without considering their evaluation settings.

| Task                                              | Representative metrics and outcomes                          |
| ------------------------------------------------- | ------------------------------------------------------------ |
| Screening and future risk prediction              | Cancer detection rate, recall rate, interval cancer rate, time-dependent AUC, C-index, calibration |
| Detection and localization                        | Sensitivity at specified false-positive operating points, FROC, AP, mAP, IoU |
| Segmentation                                      | Dice similarity coefficient, mask IoU, Hausdorff distance, surface-distance metrics |
| Classification and risk stratification            | ROC-AUC, PR-AUC, sensitivity, specificity, accuracy, precision, F1-score, calibration |
| Integrated diagnosis and disease characterization | Task-specific discrimination, segmentation overlap, subtype or nodal prediction performance |
| Clinical validation                               | Reader performance, reading workload, recall, interval cancer, safety, and clinically meaningful management outcomes |

Important evidence considerations include patient-level data separation, source-cohort overlap, independent external testing, cross-device generalization, reference standards, subgroup assessment, prospective evaluation, and human–AI interaction.

---

# Current Challenges

- Data heterogeneity and limited representative datasets
- Annotation burden and inconsistent reference standards
- Complex breast imaging characteristics and missing modalities
- Limited cross-center and cross-vendor generalizability
- Data leakage, calibration, uncertainty, and trustworthy evaluation
- Clinical integration, workflow trade-offs, and insufficient prospective evidence

---

# Emerging Directions

- Standardized multicenter datasets and data harmonization
- Data-efficient and annotation-efficient learning
- Advanced multimodal and integrated AI frameworks
- Robust and generalizable AI models
- Trustworthy AI and standardized evaluation
- Clinically oriented validation and human–AI collaboration

---

# Citation

This repository accompanies the following review manuscript:

**Cai, Guohui; Ma, Jingjing; Wang, Jinyong; Zhao, Leihao; and Cai, Shanshan.** *From Algorithms to Clinical Evidence: Artificial Intelligence for Breast Cancer Screening and Diagnosis*.

**Manuscript status:** Prepared for journal submission. The formal article citation and DOI will be added after publication.

If you use this repository before the review is formally published, you may cite the repository itself:

```bibtex
@misc{cai2026awesome_breast_cancer_ai,
  title        = {Awesome-Breast-Cancer-AI: A Curated Collection of Studies for Breast Cancer Screening and Diagnosis},
  author       = {Cai, Guohui and Ma, Jingjing and Wang, Jinyong and Zhao, Leihao and Cai, Shanshan},
  year         = {2026},
  howpublished = {GitHub repository},
  url          = {https://github.com/CaiGuoHui123/Awesome-Breast-Cancer-AI},
  note         = {Accessed: YYYY-MM-DD}
}
```

The formal citation for the review article will be provided after publication.

