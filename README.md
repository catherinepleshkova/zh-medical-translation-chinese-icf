# Medical Translation Portfolio: Informed Consent Form (ZH → RU)
### Clinical Trial Documentation Localization | Endocrinology (Type 2 Diabetes)

![Language Pair](https://img.shields.io/badge/Language-ZH%20%E2%86%92%20RU-2b7489)
![Domain](https://img.shields.io/badge/Domain-Clinical%20Trials%20%2F%20GCP-008080)
![Document Type](https://img.shields.io/badge/Document-Informed%20Consent%20Form%20(ICF)-d97706)
![Standard](https://img.shields.io/badge/Standard-ICH%20GCP%20%7C%20Plain%20Language-4f46e5)

**[🇷🇺 Русская версия (Russian Version)](https://github.com/catherinepleshkova/zh-medical-translation-chinese-icf/blob/main/README%20(RU).md)** | **[🇬🇧 English Version](README_EN.md)**

---

## 📌 Project Overview

This repository showcases a specialized medical translation and localization pet project: an excerpt of an **Informed Consent Form (ICF)** for a Phase III, multicenter clinical trial evaluating a novel GLP-1 receptor agonist for the treatment of Type 2 Diabetes Mellitus (T2D).

* **Source Language:** Simplified Chinese (Standard biomedical and regulatory register)
* **Target Language:** Russian (EAEU / Russian Federation clinical regulatory standards)
* **Segment Volume:** ~360 Chinese characters
* **Core Challenge:** Achieving an optimal balance between strict regulatory compliance under Good Clinical Practice (**ICH GCP**) and accessible, patient-friendly phrasing (**Plain Language**) suitable for trial subjects without a medical background.

---

## 📂 Repository Structure

```text
├── README.md                 # Case study presentation and commentary (Russian)
├── README_EN.md              # Case study presentation and commentary (English)
├── source_and_target.md      # Clean bilingual corpus for side-by-side review
├── glossary.csv              # Structured termbase in CSV format (CAT-tool ready)
└── LICENSE                   # Creative Commons Attribution 4.0 International (CC BY 4.0)
```

---

## 🔬 Parallel Corpus & Translation Commentary

### 1. Study Purpose and Design

| Component | Content |
| :--- | :--- |
| **Source Text (ZH)** | **研究目的与背景**<br>本试验是一项在经二甲双胍单药治疗后血糖控制不佳的成人2型糖尿病患者中开展的多中心、随机、双盲、阳性药平行对照III期临床研究。本研究旨在评价新型GLP-1受体激动剂（代号：DX-108）注射液对比西格列汀的疗效及长期安全性。 |
| **Target Translation (RU)** | **Цель и обоснование исследования**<br>Настоящее исследование представляет собой многоцентровое рандомизированное двойное слепое клиническое исследование III фазы с активным параллельным контролем с участием взрослых пациентов с сахарным диабетом 2 типа, у которых не был достигнут адекватный гликемический контроль на фоне монотерапии метформином. Цель исследования — оценить эффективность и долгосрочный профиль безопасности раствора для инъекций нового агониста рецепторов ГПП-1 (код: DX-108) в сравнении с ситаглиптином. |
| **Translator's Notes** | • **Syntactic Restructuring:** The dense Chinese pre-nominal modifier chain (`在经二甲双胍单药治疗后血糖控制不佳的成人2型糖尿病患者中开展的...`) was restructured into a natural Russian relative clause to eliminate translationese.<br>• **GCP Terminology:** `阳性药平行对照` was rendered using the standard regulatory equivalent *"активный параллельный контроль"* (active parallel-group control), avoiding literal calques.<br>• **Nomenclature Localization:** The abbreviation `GLP-1` was localized to the standard Russian clinical acronym **ГПП-1** (*глюкагоноподобный пептид-1*). |

---

### 2. Study Procedures and Glycemic Monitoring

| Component | Content |
| :--- | :--- |
| **Source Text (ZH)** | **研究流程与血糖监测**<br>若您同意参与本研究，您需要完成为期2周的筛选期和24周的治疗期。在此期间，您需要按要求定期前往研究中心进行静脉采血、糖化血红蛋白（HbA1c）检测及空腹血糖监测，并使用研究中心提供的血糖仪如实记录每日自我血糖监测（SMBG）日志。 |
| **Target Translation (RU)** | **Процедуры исследования и контроль уровня сахара в крови**<br>В случае вашего согласия на участие в исследовании вам предстоит пройти 2-недельный период скрининга (предварительного обследования) и 24-недельный период лечения. В течение этого времени вам потребуется регулярно посещать исследовательский центр для сдачи образцов венозной крови, анализа на гликированный гемоглобин (HbA1c) и определения уровня глюкозы натощак, а также вести дневник самоконтроля уровня глюкозы в крови с помощью выданного глюкометра. |
| **Translator's Notes** | • **Plain Language Principle:** The technical term `筛选期` (screening period) is accompanied by an explanatory parenthetical (*«предварительного обследования»*) to reduce patient cognitive load and anxiety.<br>• **Clinical Lexicon:** `空腹血糖` was translated using the established laboratory term *"уровень глюкозы натощак"* (fasting blood glucose level).<br>• **Acronym Adaptation:** The English-derived acronym `SMBG` was unpacked into clear, patient-oriented phrasing (*«дневник самоконтроля уровня глюкозы в крови»*). |

---

### 3. Safety Profile and Hypoglycemia Management

| Component | Content |
| :--- | :--- |
| **Source Text (ZH)** | **潜在风险与低血糖识别**<br>除常见的胃肠道反应（如轻至中度恶心、腹泻）外，您在使用试验药物期间可能存在发生低血糖的风险。若您出现心悸、出冷汗、手抖、头晕或饥饿感等低血糖早期症状，请立即按照指导摄入含糖食物，并第一时间联系您的研究医生。 |
| **Target Translation (RU)** | **Возможные риски и распознавание гипогликемии**<br>Помимо распространенных реакций со стороны желудочно-кишечного тракта (таких как тошнота или диарея легкой и умеренной степени), во время применения исследуемого препарата существует риск развития гипогликемии (патологического снижения уровня сахара в крови). Если вы почувствуете учащенное сердцебиение, холодный пот, дрожь в руках, головокружение или резкое чувство голода, вам следует незамедлительно принять легкоусвояемые углеводы (например, сладкий напиток или сахар) и как можно скорее связаться с врачом-исследователем. |
| **Translator's Notes** | • **Ethical ICF Standards:** Added an inline definition for `低血糖` (*«патологического снижения уровня сахара в крови»*), fulfilling ethics committee mandates for transparent risk disclosure.<br>• **Symptomatology:** Early warning signs (`心悸、出冷汗、手抖、头晕`) were localized in accordance with standardized Russian T2D patient questionnaires.<br>• **Pragmatic Adaptation:** The general instruction `摄入含糖食物` was specified in line with Russian clinical guidelines for hypoglycemia relief (*«принять легкоусвояемые углеводы (например, сладкий напиток или сахар)»*). |

---

## 📖 Terminology Glossary (Sample)

The complete termbase with translator annotations and ICH GCP equivalents is available in [`glossary.csv`](glossary.csv).

| Chinese Term (ZH) | Pinyin | Russian Target (RU) | ICH GCP Equivalent (EN) |
| :--- | :--- | :--- | :--- |
| **知情同意书** | zhīqíng tóngyì shū | Информированное добровольное согласие (ИДС) | Informed Consent Form (ICF) |
| **2型糖尿病** | èrxíng tángniàobìng | Сахарный диабет 2 типа (СД2) | Type 2 Diabetes (T2D) |
| **阳性药平行对照** | yángxìngyào píngxíng duìzhào | Активный параллельный контроль | Active parallel-group control |
| **GLP-1受体激动剂** | GLP-1 shòutǐ jīdòngjì | Агонист рецепторов ГПП-1 (аГПП-1) | GLP-1 receptor agonist |
| **二甲双胍** | èrjiǎshuāngguā | Метформин | Metformin |
| **西格列汀** | xīgéliètīng | Ситаглиптин | Sitagliptin |
| **糖化血红蛋白** | tánghuà xuèhóngdànbái | Гликированный гемоглобин (HbA1c) | Glycated hemoglobin (HbA1c) |
| **空腹血糖** | kōngfù xuètáng | Уровень глюкозы натощак / глюкоза плазмы натощак | Fasting Plasma Glucose (FPG) |
| **自我血糖监测** | zìwǒ xuètáng jiāncè | Самоконтроль уровня глюкозы в крови | Self-Monitoring of Blood Glucose (SMBG) |
| **低血糖** | dīxuètáng | Гипогликемия | Hypoglycemia |
| **研究医生** | yánjiū yīshēng | Врач-исследователь | Investigator / Study Doctor |

---

## 🛠 Quality Assurance (QA) Methodology

1. **Regulatory Compliance:**
   * Rules of Good Clinical Practice of the Eurasian Economic Union (ICH GCP E6(R2)).
   * Federal Law No. 61-FZ *"On Circulation of Medicines"*.
2. **Medical & Pharmaceutical Validation:**
   * Cross-checking adverse event terminology against **MedDRA**.
   * Aligning clinical phrasing with the Russian Association of Endocrinologists (RAE) Standards of Specialized Diabetes Care.
3. **Linguistic Proofreading:**
   * Eliminating source-language syntactic interference (Chinese topic-comment and modifier structures).
   * Ensuring strict terminological consistency, numerical accuracy, and proper measurement units across the text.

---

## 👤 About the Translator & Contact

* **Role:** Medical Translator (Chinese ↔ Russian) (Chinese ↔ English) (Russian ↔ English)
* **Credentials:** MA Degree in Linguistics (EN (C1), ZH (HSK5))
* **Contact:** [catherine.pleshkova@gmail.com] | [@katerina_pleshkova] | [https://www.linkedin.com/in/ekaterinapleshkova/]
