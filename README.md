# 🌴 KeraHealth Athithi (കേരഹെൽത്ത് അതിഥി)
> **Digital Health Record Management & Disease Surveillance System for Migrant Workers in Kerala**  
> *Aligned with UN Sustainable Development Goals (SDG 3.3, 3.8, & 10.2)*

[![Live Demo](https://img.shields.io/badge/Live-Demo_Online-059669?style=for-the-badge&logo=github)](https://ankitgh27.github.io/kerahealth-athithi/)
[![Hackathon](https://img.shields.io/badge/SIH_2025%2F2026-Problem_25083-blue?style=for-the-badge)](https://www.sih.gov.in/)
[![Department](https://img.shields.io/badge/Govt_of_Kerala-Health_Service_Dept-amber?style=for-the-badge)](https://dhs.kerala.gov.in/)

---

## 📌 Problem Statement Overview
* **Problem Statement ID:** 25083
* **Organization:** Government of Kerala
* **Department:** Health Service Department & National Health Mission (NHM)
* **Category:** Software (MedTech / HealthTech / Public Health)

### Context & Challenge
Kerala hosts an interstate migrant workforce ("Athithi Thozhilalis") numbering in the millions, primarily hailing from West Bengal, Bihar, Assam, Odisha, and Uttar Pradesh. Due to continuous interstate mobility, high population density in labor camps, and language barriers, these workers often lack portable health records. Consequently, delays in diagnosis can turn individual infections into community outbreaks of diseases like Malaria, Tuberculosis (TB), Dengue, and Leprosy.

**KeraHealth Athithi** solves this with a lightweight, multilingual, offline-capable digital health surveillance platform and portable digital health pass.

---

## 🚀 Key Modules & System Capabilities

### 1. 🌐 Multilingual Accessibility Engine
* Provides instant UI switching across **5 native languages**: English, Malayalam (മലയാളം), Hindi (हिन्दी), Bengali (বাংলা), and Assamese (অসমীয়া).
* Accommodates varying literacy levels with standardized medical iconography, color cues, and visual dosage tags.

### 2. 🪪 Athithi Universal Digital Health Pass (QR Identity)
* Generates a unique, ABHA-compliant digital health identity (`KL-ATH-YYYY-XXXX`).
* Embeds verifiable medical parameters: blood group, critical allergies, employer/contractor contacts, and vaccination history (Tetanus, Hep-B, COVID).
* Includes specialized `@media print` styling for instant on-site printing and physical laminated badge creation at PHCs.

### 3. 🚨 DEWS: Disease Early Warning System
* Real-time epidemiological monitoring integrated with **Chart.js** to track monthly disease incidence trends (Malaria, Dengue, TB).
* District risk-grading engine flagging high-density industrial clusters:
  * **Ernakulam:** Perumbavoor Plywood Cluster
  * **Palakkad:** Kanjikode Industrial Belt
  * **Kozhikode:** Feroke / Beypore Tile & Timber Hub
  * **Thiruvananthapuram:** Vizhinjam Port Project
* Automated one-click sentinel alerts dispatched to District Medical Officers (DMO) and Integrated Disease Surveillance Program (IDSP) teams.

### 4. 🩺 Doctor OPD Consultation & Diagnosis Registry
* Fast patient record lookup using Athithi ID, Mobile Number, or Aadhaar.
* Infectious disease surveillance checklist:
  * Malaria (RDT / Peripheral Blood Smear)
  * Tuberculosis (CBNAAT / GeneXpert status)
  * Dengue (NS1 / IgM ELISA)
  * Leprosy & Occupational Silicosis checks
* Prescription management linking directly to Kerala state welfare provisions under the **AROGYAKIRANAM** and **AWAZ** schemes.

### 5. 🏕️ Field Camp & Barracks Screening Portal
* Mobile-responsive intake module built for Health Inspectors (HI) and ASHA workers visiting temporary labor camps and factories.
* On-the-spot logging for rapid tests, symptom checks (cough > 2 weeks, fevers, rashes), and instant digital pass enrollment.

---

## 🎯 Sustainable Development Goals (SDGs) Alignment

| SDG Target | Objective | Platform Implementation |
| :--- | :--- | :--- |
| **SDG 3.3** | End epidemics of communicable diseases | Sentinel surveillance, GeneXpert TB tracking, and rapid Malaria containment in labor colonies. |
| **SDG 3.8** | Universal health coverage & access to care | Portable digital pass ensuring unhindered, free care at all Kerala Taluk & Primary Health Centers. |
| **SDG 10.2** | Promote universal social & economic inclusion | Multilingual, non-discriminatory healthcare bridging language and state registry barriers. |

---

## 🛠️ Tech Stack & Architecture

* **Frontend:** Semantic HTML5, Tailwind CSS
* **Data Visualization:** Chart.js
* **Iconography:** FontAwesome 6.4
* **Application Logic:** Vanilla JavaScript (ES6+)
* **Hosting & Delivery:** GitHub Pages (Static Edge CDN)

---

## 💻 Local Setup & Execution

Since the project is built as a zero-dependency, self-contained single-page application (SPA), running it requires no complex package installations:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ankitgh27/kerahealth-athithi.git](https://github.com/ankitgh27/kerahealth-athithi.git)
   cd kerahealth-athithi
