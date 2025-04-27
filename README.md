# Enhancing Healthcare Accessibility in Nairobi, Kenya

> A data-driven case study focusing on Nairobi’s healthcare infrastructure in relation to the United Nations Sustainable Development Goals (SDG) — specifically Goal 3: Health and Wellbeing.

---

## Introduction

The United Nations Sustainable Development Goals (SDGs) blueprint, adopted in 2015, places human health and wellbeing as one of the key goals to be attained by 2030. Healthier populations are better positioned to contribute socially, politically, and economically to their nations (UNDP).

**Goal 3: Good Health and Wellbeing** is critical and intertwined with the achievement of other sustainable development goals. Achieving this goal requires championing and implementing policies geared towards having **Universal Health Coverage (UHC)**.

In Kenya, under the **Vision 2030** framework, the government has passed parliamentary laws to make healthcare affordable and accessible. However, the success of these implementations depends heavily on the collaboration between the national government, county governments, and the **National Health Insurance Fund (NHIF)**.

This case study focuses on deriving **data-driven insights** to assess Nairobi’s position in attaining **SDG Goal 3**.  
It aims not only to provide insights on healthcare accessibility across different sub-counties and demographics but also to provide **actionable recommendations**, benchmarked against specific SDG Goal 3 targets.

---

## Population Demographics

A key stage in enhancing healthcare accessibility is understanding demographic statistics.  
This helps governments and healthcare service providers tailor services to vulnerable groups effectively.

To assess healthcare accessibility in Nairobi, statistical analysis was conducted to understand the demographic and geographic distribution at the sub-county level.

- According to the **2019 Kenya National Census**, Nairobi has a total population of **4.397 million**.
- **Gender distribution:** 49% Male and 51% Female.

![Figure 1: Age distribution](fig1.png)

**Insights from Figure 1:**
- Over **70%** of the population is youthful (under 35 years).
- About **12%** are children under the age of 5.

➡️ **Healthcare provision must focus on young people and children**, who form the majority.

![Figure 2: Population density by sub-county](fig2.png)

**Insights from Figure 2:**
- Sub-counties like **Mathare**, **Kamukunji**, **Makadara**, and **Kibra** are densely populated.
- These areas contain a significant portion of slums and low-income settlements, requiring **multifaceted interventions** in healthcare accessibility and affordability to meet SDG Goal 3.8 (Universal Health Coverage).

Slum settlements are known to exacerbate the spread of diseases (e.g., hypertension, diabetes, tuberculosis, HIV).  
Thus, **access to healthcare services for both communicable and non-communicable diseases** must be prioritized to achieve SDG Goals 3.4 and 3.5.

---

## Healthcare Accessibility

To get insight into healthcare accessibility across Nairobi’s sub-counties, a statistical analysis was made on the:
- Number of health facilities
- Status of their operations during weekdays and weekends

![Figure 3: Health facilities per sub-county and healthcare density](fig3.png)

**Insights from Figure 3:**
- **Embakasi** and **Starehe** have the highest number of healthcare facilities.
- However, **Embakasi**, despite the high number of facilities, has **low facility density** due to its large population size.

- Sub-counties like **Mathare** and **Kasarani** have **relatively lower healthcare facility densities**, meaning a shortage of healthcare coverage compared to their population size.

**Intervention Needed:**
- To avoid overstretching existing facilities, more health centers need to be built.
- There is also a need to **diversify healthcare service provision**.

---

## Healthcare Facility Operational Status

![Figure 4: Healthcare facility operational status](fig4.png)

**Insights from Figure 4:**
- **Weekend accessibility** is relatively good — on average, over **50%** of facilities remain open.
- **24-hour accessibility** is poor — only **<30%** of facilities operate around the clock.

Considering Nairobi as a **24-hour economy city** (especially areas like Nairobi CBD — Starehe), this is a major gap.

**Recommendation:**
- To truly align with **UHC goals** (SDG Goal 3.8), healthcare facilities must increase 24-hour operational coverage.

---

## Availability of Healthcare Services

This section analyzed which healthcare services were available across different sub-counties.

![Figure 5: Availability of healthcare services](fig5.png)

**Key findings from Figure 5:**
- Only five healthcare services are relatively well distributed: **ART**, **C-IMCI**, **FP**, **HBC**, and **IPD**.
- Critical healthcare services are missing:
  - **Antenatal Care (ANC)** and **PMTCT** services are absent.
  - No **Basic Essential Obstetric Care (BEOC)** or **Comprehensive Essential Obstetric Care (CEOC)** available.
  - Poor availability of diagnostic services such as **TB diagnosis**, **X-Ray**, **EPI** (Expanded Program of Immunization).

➡️ **Impact on SDGs:**
- The absence of these services directly impedes progress toward **SDG Goals 3.1, 3.2, 3.3, 3.4, and 3.8**.
- It increases maternal and child mortality risks and hampers the fight against epidemics and chronic illnesses.

**Action Needed:**
- Governments and healthcare stakeholders should prioritize infrastructure that enables the provision of a **full range of healthcare services**.

---

## Children's Accessibility to C-IMCI Health Services

**C-IMCI** (Integrated Management of Childhood Illnesses) aims to improve access and quality of care for newborns and children under 5 years old — critical for achieving **SDG Goal 3.2**.

![Figure 6: Children's accessibility to C-IMCI services](fig6.png)

**Key insights from Figure 6:**
- Accessibility to C-IMCI services is **relatively good** in sub-counties like **Lang’ata**.
- Accessibility is **poor** in **Mathare** and **Kasarani**.

Given that children under 5 represent 12% of Nairobi’s population, improving access to child-specific services is critical.

**Recommendation:**
- Strengthen healthcare infrastructure to enhance **C-IMCI services** in poorly served areas to meet SDG Goal 3.2.

---

## Conclusion and Recommendations

### Conclusion
- Nairobi has made progress towards healthcare accessibility, especially in sub-counties like **Starehe**, **Langata**, and **Westlands**.
- However, low-income sub-counties like **Mathare** still lag behind significantly.
- The **narrow range of healthcare services** limits Nairobi’s ability to achieve **universal health coverage (UHC)**.

---

### Recommendations

- **Focus on Youth:**  
  Design healthcare systems that prioritize the needs of the under-35 population.

- **Targeted Interventions in Slums:**  
  Sub-counties with slums and high poverty levels require multifaceted intervention to enhance healthcare accessibility and affordability.

- **Expand Health Infrastructure:**  
  More facilities should be built, especially in low-density areas, to reduce strain on existing centers.

- **Service Diversification:**  
  A broader range of health services must be provided, especially in maternal, child, and infectious disease sectors.

- **Strengthen Child Healthcare:**  
  Infrastructure for **C-IMCI** services must be established, especially in **Mathare** and **Kasarani**, to ensure child survival rates improve.

---

## Project Structure

```bash
Healthcare-Accessibility-in-Nairobi/
│
├── data/                # Datasets (Health facilities, Population census)
├── figures/             # Figures used in analysis (fig1.png to fig6.png)
├── notebooks/           # Jupyter notebooks for full data analysis
├── README.md            # Detailed project overview and documentation
└── requirements.txt     # Required Python libraries
