
# Explainable AI for Class II Medical Devices (CT)

> **Regulatory Risk Analysis & Governance Framework**
> *May 2020 – June 2020*

## 📖 Overview
Long before the **EU AI Act** finalised its definition of "High-Risk AI" in Annexe III, this project analysed the regulatory and ethical vacuums in **Class II Medical Devices**, specifically **AI-driven Computed Tomography (CT)**.

While the industry focused on accuracy, this analysis focused on **Liability**, **Control**, and **Agency**. It evaluates the conflict between **Strict Product Liability** and **Medical Malpractice** when an autonomous algorithm makes a diagnostic error.

## Key Analysis

### 1. The Liability Gap: 
Navigating the legal conflict between:
* **Strict Product Liability:** Manufacturer responsibility for defective "products."
* **Vicarious Liability:** Hospital responsibility for "tools" used by clinicians.
* **The Problem:** When AI acts as a "Black Box," it becomes difficult to assign negligence to a human radiologist, creating a liability vacuum.


### 2. Agency Analysis (The "Steinert" Shift)
This project leverages **Steinert’s (2014) Robot Taxonomy** to map the ethical and legal trajectory of Medical AI. The analysis identifies a critical regulatory gap as AI shifts between these five categories:

1.  **Acting "Through" Robots (Instruments):** Robots are tools used to alter situations according to the human user's will.
   *Legal Status:* The human radiologist is the sole ethical agent; the AI is a "medical aid".
2.  **"Don't Hurt My Robot" (Recipients):** Robots as recipients of ethical behaviour due to emotional bonds formed with humans.
    * *Relevance:* Trust dynamics between clinicians/patients and "intelligent" assistants.
3.  **Acting Robots (Moral Agents):** Systems that make independent decisions where risk versus benefit must be evaluated.
    *The Conflict:* While hospitals legally treat AI as a **Type 1** instrument, deep learning diagnostic tools functionally act as **Type 3** agents, creating a liability vacuum.
4.  **Robots and People (Influence):** Robots that contribute to the restructuring of societal norms and standards.
    *Impact:* AI altering the "standard of care" in radiology.
5.  **Robots and Ethics (Meta-Perspective):** Using technology as a model to understand human features and ethical disciplines.

**Key Finding:** Current liability frameworks assume AI is a **Type 1 (Instrument)**, but autonomous diagnostic capability pushes it toward **Type 3 (Moral Agent)**. Without legal personhood, this leaves patients with no recourse for "black box" errors.

### 3. Governance Controls & Mitigations
Proposed controls to satisfy safety requirements for **Software as a Medical Device (SaMD)**:
* **Explainability by Design (XAI):** Mandatory for liability attribution.
* **Human-in-the-Loop:** Protocols to ensure the human remains the moral agent of record.
* **Automation Bias Mitigation:** Training to prevent radiologists from over-relying on automated outputs.

## 📂 Contents
* `slides/`: The complete presentation deck analysing AI Rights and Liability in Healthcare.
* `references/`: Citations including the EU AI Act (Drafts), FDA SaMD guidelines, and Steinert's Taxonomy.

## 🔗 Context 
This foundational work serves as the basis for my current **Regulatory Compliance & Risk Management Framework**, bridging technical engineering with global compliance standards (ISO 42001).
 
## 🚀 Evolution: The Unified Framework

This foundational analysis on High-Risk Medical AI serves as the architectural basis for my current **Multi-Jurisdictional Governance Ecosystem**.

I am currently expanding this logic into a unified **Regulatory Compliance & Risk Management Framework** that harmonises:

* **🇪🇺 EU AI Act & GDPR:** Mapping "High-Risk" classification and Data Protection Impact Assessments (DPIAs).
* **🇺🇸 NIST AI RMF:** Integrating "Map, Measure, Manage, Govern" functions into engineering workflows.
* **🌐 ISO Standards Suite:**
    * **ISO/IEC 42001:** AI Management Systems (The "Container").
    * **ISO/IEC 23894:** AI Risk Management (The "Methodology").
    * **ISO/IEC 42005:** AI System Impact Assessment.
    * **ISO/IEC 5259:** Data Quality for ML.

By synthesising these standards, the new framework uses a **Total Risk Score (TRS)** to trigger the appropriate compliance with major AI fairness regulatory frameworks.


