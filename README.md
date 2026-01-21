# Computational Modeling of Multi-organ Microphysiological Systems for Human Pharmacokinetic Prediction

# 인체 약동학 예측을 위한 다중장기 미세생리학적 시스템의 계산 모델링

[![Conference](https://img.shields.io/badge/Conference-MPS%20World%20Summit%202026-blue)]()
[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs13206--025--00178--w-green)](https://doi.org/10.1007/s13206-025-00178-w)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

---

## 초록 (Korean Abstract)

기존의 2차원 체외 세포 배양 및 동물 모델은 종간 변이성과 제한된 생리학적 관련성으로 인해 인체 약동학(PK) 예측에 실패하는 경우가 많다. 기존 2차원 세포 배양 방법은 인체 생리학적 조건을 적절히 모방하지 못하며, 세포는 정적 조건에서 배양될 때 급격한 형태학적 및 기능적 변화를 겪는다. 미세생리학적 시스템(MPS)은 미세유체 기술과 인간 세포 공배양을 통합하여 인체 장기 기능과 세포 간 상호작용을 더 잘 재현하는 진보된 플랫폼으로 부상하였다. 본 연구는 다중장기 MPS를 위한 체계적인 계산 모델링 프레임워크를 개발하여 인체 PK 파라미터의 신뢰성 있는 예측을 가능하게 하는 것을 목표로 하였다. 우리는 중력 기반 양방향 흐름으로 연결된 장, 간, 신장 삽입체를 포함하는 다중장기 MPS를 개발하여 약물의 흡수, 분포, 대사, 배설 과정을 시뮬레이션하였다. 장, 간, 신장 구획에는 각각 인간 장 상피세포, HepaRG 간세포 스페로이드, 신장 근위세뇨관 상피세포를 사용하였다. 5단계 계산 모델링 전략이 수립되었다: (1) 기저 폴리카보네이트 패키지, 기저 배지, 다공성 막, 상피세포층, 정단 배지로 구성된 5층 장벽을 통한 약물 이동을 기술하는 상미분방정식을 사용한 기본 모델 구조 개발, (2) 민감도 분석을 통한 약물 대사 및 약동학 파라미터 수집, (3) 비결합 분율 및 막 투과성을 포함한 물질 관련 파라미터 결정을 위한 블랭크 칩 분석, (4) 내인성 청소율 및 겉보기 투과성을 포함한 세포 관련 파라미터 추정을 위한 세포 칩 분석, (5) 알로메트리 스케일링 및 생리학적 기반 약동학 모델링을 사용한 인체 스케일로의 외삽. 인체 반감기 예측은 다양한 물리화학적 특성을 가진 6가지 약물(antipyrine, benzylpenicillin, crizotinib, diclofenac, gefitinib, testosterone)을 사용하여 검증되었다. 단순 알로메트리 스케일링은 대부분의 화합물에서 관찰된 임상 값의 2배 이내 예측을 달성하였다. Diclofenac의 경우, 생리학적 기반 약동학 모델링 외삽이 Cmax 및 AUC의 임상 값 예측을 잘 보여주었다. 또한, gefitinib은 덱스트란 황산나트륨 유도 장 손상 모델에서 테스트되어 정상 조건 대비 장 투과성이 6배 감소함을 보여주었으며, 이는 질환 상태에서의 손상된 장 장벽 기능을 반영한다. 이 통합 MPS-계산 모델링 접근법은 여러 약물 클래스에 걸쳐 인체 PK 파라미터를 예측하기 위한 체계적인 프레임워크를 제공하고 질환 상태 변화의 정량화를 가능하게 하여, 초기 신약 개발에서 동물 실험에 대한 의존도를 잠재적으로 줄일 수 있다.

---

## Abstract (English)

Traditional in vitro cell cultures and animal models often fail to predict human pharmacokinetics (PK) due to interspecies variability and limited physiological relevance. Conventional two-dimensional cell culture methods inadequately mimic human physiological conditions, and cells undergo rapid morphological and functional changes when grown under static conditions. Microphysiological systems (MPS) have emerged as advanced platforms integrating microfluidic technologies with human cell cocultures to better replicate human organ functions and intercellular interactions. This study aimed to develop a systematic computational modeling framework for multi-organ MPS to enable reliable prediction of human PK parameters. We developed a multi-organ MPS incorporating gut, liver, and kidney inserts connected via gravity-driven bidirectional flow to simulate drug absorption, distribution, metabolism, and excretion processes. Human intestinal epithelial cells, HepaRG hepatocyte spheroids, and renal proximal tubule epithelial cells were used for gut, liver, and kidney compartments, respectively. A five-step computational modeling strategy was established: (1) base model structure development using ordinary differential equations describing drug movement across five-layer barriers comprising basal polycarbonate package, basal medium, porous membrane, epithelial cell layer, and apical medium, (2) drug metabolism and pharmacokinetic parameter collection with sensitivity analysis, (3) blank chip analysis to determine material-related parameters including unbound fraction and membrane permeability, (4) cell chip analysis to estimate cell-related parameters including intrinsic clearance and apparent permeability, and (5) extrapolation to human scale using allometry scaling and physiologically based pharmacokinetic modeling. Human half-life prediction was validated using six drugs with diverse physicochemical properties: antipyrine, benzylpenicillin, crizotinib, diclofenac, gefitinib, and testosterone. Simple allometry scaling achieved predictions within two-fold of observed clinical values for most compounds. For diclofenac, physiologically based pharmacokinetic modeling extrapolation well demonstrated prediction of clinical values of Cmax and AUC. Additionally, gefitinib was tested in a dextran sulfate sodium-induced intestinal damage model, revealing a six-fold reduction in gut permeability compared to normal conditions, reflecting compromised intestinal barrier function in disease states. This integrated MPS-computational modeling approach provides a systematic framework for predicting human PK parameters across multiple drug classes and enables quantification of disease-state alterations, potentially reducing reliance on animal testing in early drug development.

---

## Authors and Affiliations

**Suein Choi**<sup>1,2</sup> · **JungHyun Lee**<sup>1,2</sup> · **Okju Kim**<sup>3</sup> · **Yushin Jung**<sup>3</sup> · **Taehoon Ryu**<sup>3</sup> · **Su Jung Kim**<sup>4</sup> · **Eun Joo Kim**<sup>4</sup> · **Jong Hwan Sung**<sup>5</sup> · **Hwa Jun Cha**<sup>1,2</sup> · **Sungpil Han**<sup>1,2,*</sup>

<sup>1</sup> Department of Pharmacology, College of Medicine, The Catholic University of Korea, Banpodaero 222, Seocho-gu, Seoul, Republic of Korea

<sup>2</sup> Pharmacometrics Institute for Practical Education and Training (PIPET), College of Medicine, The Catholic University of Korea, Seoul, Republic of Korea

<sup>3</sup> ATG Lifetech Inc., Seoul, Republic of Korea

<sup>4</sup> Dyne Bio Inc., Seongnam-si, Gyeonggi-do 13209, Republic of Korea

<sup>5</sup> Department of Chemical Engineering, Hongik University, Seoul 04066, Republic of Korea

<sup>*</sup> **Corresponding author:** Sungpil Han (sungpil@catholic.ac.kr)

---

## Related Publication

This work is based on the following peer-reviewed publication:

> Choi, S., Lee, J., Kim, O., Jung, Y., Ryu, T., Kim, S.J., Kim, E.J., Sung, J.H., Cha, H.J., Han, S. (2025). **Integrating a Microphysiological System and Physiologically Based Pharmacokinetic Modeling to Predict Human Responses to Diclofenac.** *BioChip Journal*, 1-17. https://doi.org/10.1007/s13206-025-00178-w

---

## Research Background

### Limitations of Conventional Approaches

Traditional approaches for predicting human pharmacokinetics have significant limitations that hinder accurate translation from preclinical studies to clinical outcomes. Two-dimensional in vitro cell cultures fail to maintain the complex three-dimensional architecture and cell-cell interactions that characterize human tissues in vivo. Animal models, while providing systemic context, often produce misleading results due to fundamental differences in drug metabolism, transporter expression, and physiological parameters between species.

### Emergence of Microphysiological Systems

Microphysiological systems represent a paradigm shift in preclinical drug development by providing physiologically relevant human tissue models. These systems integrate microfluidic technologies with human cell cocultures to recreate the dynamic microenvironment of human organs, including mechanical forces, fluid flow, and cellular interactions that are absent in conventional static cultures.

---

## Methodology

### Multi-organ Microphysiological System Design

The multi-organ MPS platform was designed to recapitulate the key organs involved in drug absorption, distribution, metabolism, and excretion (ADME). The system incorporates three organ compartments connected through a shared circulation that mimics systemic blood flow.

| Organ Compartment | Cell Type | Physiological Function |
|-------------------|-----------|----------------------|
| Gut | Human intestinal epithelial cells (hiEC) | Drug absorption and intestinal metabolism |
| Liver | HepaRG hepatocyte spheroids | Hepatic metabolism and first-pass effect |
| Kidney | Renal proximal tubule epithelial cells (RPTEC) | Renal clearance and drug excretion |

The platform utilizes gravity-driven bidirectional flow to generate physiologically relevant shear stress and facilitate nutrient exchange between compartments without requiring external pumps, thereby minimizing the risk of contamination and bubble formation.

### Five-Step Computational Modeling Strategy

A systematic five-step approach was developed to extract pharmacokinetically relevant parameters from the MPS and translate them to human predictions.

**Step 1: Base Model Structure Development**

The base model was constructed using ordinary differential equations that describe drug movement across the five-layer barrier structure of each organ insert. The five layers comprise the basal polycarbonate package, basal medium, porous membrane, epithelial cell layer, and apical medium. Mass balance equations ensure conservation of drug mass across all compartments.

**Step 2: Drug Metabolism and Pharmacokinetic Parameter Collection**

Initial model parameters were derived from published drug metabolism and pharmacokinetic (DMPK) data, including apparent permeability from Caco-2 assays, intrinsic clearance from hepatocyte studies, and physicochemical properties. Sensitivity analysis was performed to identify critical parameters influencing model outputs and to determine optimal sampling time points.

**Step 3: Blank Chip Analysis**

Experiments were conducted using chips without cells to characterize material-related parameters, including drug binding to the polycarbonate and PDMS components, membrane permeability, and partition coefficients. These parameters were fixed in subsequent modeling steps.

**Step 4: Cell Chip Analysis**

With material parameters established, cell-containing chips were used to estimate biological parameters including intrinsic clearance and apparent permeability for each organ compartment. Both parent drug and metabolite concentrations were simultaneously modeled to capture the complete pharmacokinetic profile.

**Step 5: Extrapolation to Human Scale**

Two extrapolation approaches were employed to translate MPS-derived parameters to human predictions. Simple allometry scaling used body weight-based equations to scale clearance and volume parameters. Physiologically based pharmacokinetic (PBPK) modeling incorporated the MPS-derived parameters into a whole-body model that accounts for human anatomy and physiology.

---

## Results

### Validation with Six Drugs of Diverse Properties

The modeling framework was validated using six drugs representing diverse physicochemical and pharmacokinetic properties to demonstrate broad applicability across drug classes.

| Drug | Therapeutic Class | Key Characteristics |
|------|------------------|---------------------|
| Antipyrine | Analgesic | Low clearance, hepatic metabolism |
| Benzylpenicillin | Antibiotic | Renal elimination, hydrophilic |
| Crizotinib | Anticancer (TKI) | High hepatic metabolism, CYP3A substrate |
| Diclofenac | NSAID | Hepatic metabolism, enterohepatic circulation |
| Gefitinib | Anticancer (EGFR-TKI) | P-gp substrate, hepatic metabolism |
| Testosterone | Hormone | Extensive hepatic metabolism |

### Half-life Prediction Performance

Simple allometry scaling achieved predictions within two-fold of observed clinical values for most compounds tested, demonstrating the utility of MPS-derived parameters for human pharmacokinetic prediction without requiring complex physiological modeling for initial assessments.

### PBPK-based Extrapolation for Diclofenac

For diclofenac, physiologically based pharmacokinetic modeling extrapolation demonstrated accurate prediction of clinical pharmacokinetic parameters. The model successfully captured the concentration-time profile observed in human studies, validating the approach for compounds requiring more detailed mechanistic modeling.

### Disease Model Application with Gefitinib

The utility of the platform for studying disease-state pharmacokinetics was demonstrated using gefitinib in a dextran sulfate sodium (DSS)-induced intestinal damage model. The disease model revealed a six-fold reduction in gut permeability compared to normal conditions, reflecting the compromised intestinal barrier function characteristic of inflammatory bowel conditions. This finding demonstrates the capability of the integrated MPS-modeling approach to quantify disease-state alterations in drug absorption.

---

## Conclusions

This study presents an integrated microphysiological system and computational modeling framework that provides a systematic approach for predicting human pharmacokinetic parameters. The five-step modeling strategy enables extraction of physiologically meaningful parameters from MPS experiments and their translation to human predictions through allometry scaling or PBPK modeling. Validation with six drugs of diverse properties demonstrates broad applicability, while the disease model application illustrates the potential for studying pathophysiological alterations in drug disposition. This approach offers a promising alternative to animal testing in early drug development, potentially improving the efficiency and human relevance of preclinical pharmacokinetic assessments.

---

## Repository Contents

This repository contains the materials prepared for abstract submission to the 2026 MPS World Summit conference.

| File | Description |
|------|-------------|
| `README.md` | Comprehensive project documentation with bilingual abstracts |
| `abstract.md` | Final abstract for conference submission (350 words) |
| `submission.md` | Conference submission guidelines and requirements |
| `paper.md` | Full text of the related BioChip Journal publication |
| `choi.md` | Detailed presentation notes from MYSTER symposium |

---

## Acknowledgements

This work was supported by the Korea Health Technology R&D Project through the Korea Health Industry Development Institute (KHIDI), funded by the Ministry of Health & Welfare, Republic of Korea.

---

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

---

## Contact

For inquiries regarding this research, please contact:

**Sungpil Han, Ph.D.**
Department of Pharmacology, College of Medicine
The Catholic University of Korea
Banpodaero 222, Seocho-gu, Seoul, Republic of Korea
Email: sungpil@catholic.ac.kr
