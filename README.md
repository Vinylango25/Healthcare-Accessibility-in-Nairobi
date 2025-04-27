# Enhancing Healthcare Accessibility in Nairobi, Kenya

> A data-driven case study analyzing healthcare accessibility in Nairobi with respect to SDG Goal 3: Health and Wellbeing.

---

## Introduction

The United Nations Sustainable Development Goals (SDGs) blueprint, adopted in 2015, highlights **Goal 3**: *Good Health and Wellbeing*, as critical to human capital development and economic growth.  
Healthier populations are pivotal for driving social, political, and economic prosperity (UNDP).

This project evaluates Nairobi's healthcare accessibility with a focus on:
- Assessing the current healthcare infrastructure.
- Understanding population demographics.
- Providing actionable recommendations aligned with **SDG Goal 3 targets** (e.g., Universal Health Coverage - UHC).

Kenya's **Vision 2030** and various legislative efforts (e.g., NHIF reforms) are foundational to these goals, but success depends on collaboration between national and county governments.

---

## Population Demographics

Understanding demographic dynamics is crucial for tailoring healthcare services to vulnerable groups.

- **Total Population:** 4.397 million (2019 Census).
- **Gender Distribution:** 49% Male, 51% Female.
- **Age Distribution:** Over 70% of the population is **below 35 years**; **~12% are children under 5**.

### 📊 Figure 1: Age distribution of Nairobi's population
![Figure 1](fig1.png)

### 📊 Figure 2: Population density by sub-county
![Figure 2](fig2.png)

**Key insights:**
- Healthcare services should prioritize young populations and children.
- Sub-counties like **Mathare**, **Kamukunji**, **Makadara**, and **Kibra** are densely populated, mainly with informal settlements (slums).
- Higher poverty indices in these areas exacerbate the spread of communicable and non-communicable diseases (e.g., tuberculosis, diabetes, hypertension).

---

## Healthcare Accessibility

We analyzed the number of healthcare facilities and their operational hours across Nairobi's sub-counties.

### 📊 Figure 3: Health facilities per sub-county and facility density
![Figure 3](fig3.png)

### 📊 Figure 4: Facility operation - 24 hours and weekend accessibility
![Figure 4](fig4.png)

**Key insights:**
- **Embakasi** and **Starehe** have the highest number of facilities, but **Embakasi**'s facility density remains low due to its large population.
- On average, **>50% of facilities are open on weekends**, but **<30% operate 24 hours**.
- For a city like Nairobi, which operates 24/7, especially in the CBD (Starehe), there is a clear gap in 24-hour healthcare services.

---

## Availability of Healthcare Services

Availability of specific health services across sub-counties was also analyzed.

### 📊 Figure 5: Healthcare services availability across sub-counties
![Figure 5](fig5.png)

**Key insights:**
- Only **five** healthcare services (ART, C-IMCI, FP, HBC, IPD) are widely available.
- Critical services missing include:
  - Antenatal Care (ANC)
  - Prevention of Mother to Child Transmission (PMTCT)
  - Basic and Comprehensive Essential Obstetric Care (BEOC, CEOC)
  - Immunizations (EPI)
  - Diagnostic services (TB labs, XRAY)

> 🛑 This limits Nairobi's progress toward **SDG Goal 3.1**, **3.2**, **3.3**, **3.4**, and **3.8**.

---

## Children's Accessibility to C-IMCI Services

**Integrated Management of Childhood Illnesses (C-IMCI)** services are critical for reducing child mortality, especially for children under 5 years (12% of Nairobi's population).

### 📊 Figure 6: Accessibility of C-IMCI services across sub-counties
![Figure 6](fig6.png)

**Key insights:**
- **Lang’ata** has relatively better access to C-IMCI services.
- **Kasarani** and **Mathare** have poor C-IMCI accessibility, posing risks to child health (SDG Goal 3.2).

---

## Conclusion and Recommendations

### Conclusion
- Significant progress is seen in healthcare accessibility in **Starehe**, **Langata**, and **Westlands**.
- **Low-income sub-counties** like **Mathare** lag significantly behind.
- Healthcare facilities in Nairobi offer a **narrow range of services**, hampering universal health coverage efforts.

### Recommendations
- **Youth-focused healthcare:** With 70% of the population under 35 years, Nairobi should design health systems geared towards young people.
- **Multifaceted interventions** in slum areas to improve both healthcare accessibility and affordability.
- **Expand healthcare infrastructure** in under-served sub-counties to reduce facility strain.
- **Diversify healthcare services** to cover critical maternal, child, and chronic disease management needs.
- **Enhance C-IMCI service availability** especially in Kasarani and Mathare.

---

## Project Structure

```bash
Healthcare-Accessibility-in-Nairobi/
│
├── data/                # Datasets (Health facilities, Population)
├── figures/             # Saved figures (fig1.png to fig6.png)
├── notebooks/           # Jupyter Notebooks for analysis
├── README.md            # Project overview
└── requirements.txt     # Python dependencies
