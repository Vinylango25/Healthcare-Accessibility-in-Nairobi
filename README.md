# Enhancing Healthcare Accessibility in Nairobi, Kenya

> This project presents a comprehensive, data-driven narrative that delves into the current state of Nairobi’s healthcare infrastructure. By leveraging multiple datasets, including population demographics and health facility distributions, it evaluates how well the city is positioned to meet the healthcare needs of its diverse population. The analysis is anchored within the framework of the United Nations Sustainable Development Goal 3, which aims to ensure healthy lives and promote well-being for all at all ages. Through detailed examination of healthcare accessibility, service availability, and facility operational hours, this study identifies critical gaps and opportunities for improvement. Ultimately, the findings serve as a foundation for informed policy-making and strategic interventions designed to advance Nairobi’s journey towards achieving SDG 3.



## Introduction

# Enhancing Healthcare Accessibility in Nairobi, Kenya

## Introduction

In 2015, the United Nations set forth a bold and transformative vision with the launch of the Sustainable Development Goals (SDGs), a global agenda designed to address some of the world’s most pressing challenges. These 17 goals encompass a wide range of issues, from eradicating poverty and hunger to combating climate change and ensuring access to clean water. Among these, **SDG 3: Good Health and Wellbeing** is particularly significant as it serves as a foundational pillar that supports the achievement of many other goals. Good health is intrinsically linked to social and economic development, influencing factors such as workforce productivity, educational outcomes, and societal stability. The goal’s comprehensive scope—from reducing maternal and child mortality to combating epidemics and promoting mental health—reflects the critical role health plays in building sustainable and resilient communities worldwide.

In Kenya, the national response to this global agenda is embedded within its **Vision 2030** framework, a blueprint aimed at transforming the country into a middle-income economy with improved standards of living for all citizens. Central to Vision 2030 is the commitment to develop an inclusive and efficient healthcare system that provides equitable access to quality services. As the country’s capital and largest urban center, Nairobi holds a unique position in this vision. It acts as the economic heartbeat of Kenya and a melting pot of diverse populations, including some of the most vulnerable groups such as residents of informal settlements. Nairobi’s healthcare infrastructure and policies must therefore reflect the complexities of urban health challenges while pioneering innovations that can be scaled nationwide.

Over the past decade, Kenya has made commendable strides in enhancing its healthcare system through legislative reforms and institutional developments. The establishment of the **Social Health Authority (SHA)**, for instance, marks a critical step towards achieving Universal Health Coverage (UHC), aiming to reduce financial barriers and improve service quality. Despite these advancements, Nairobi continues to face significant disparities in healthcare accessibility and quality. Challenges such as uneven distribution of facilities, limited operational hours, and inadequate availability of specialized services disproportionately affect low-income and high-density areas. These gaps highlight the urgent need for data-driven approaches to better understand the dynamics at play and to inform targeted interventions.

This report harnesses a rich dataset that includes demographic statistics, health facility locations, and service availability across Nairobi’s sub-counties to provide an in-depth assessment of the city’s healthcare landscape. By integrating quantitative analysis with contextual understanding, the study not only uncovers critical insights into who is served and who remains underserved but also examines the operational challenges faced by healthcare providers. The results reveal a nuanced picture of progress and persistent barriers, drawing attention to areas requiring urgent attention such as maternal health, child healthcare, and 24-hour service availability in a city that never sleeps.

Building on these findings, the report offers actionable recommendations aligned with the specific targets of **SDG 3**. These include strategies to expand healthcare infrastructure, diversify services to meet a broad range of health needs, and enhance accessibility for vulnerable populations. The ultimate goal is to support policymakers, health practitioners, and stakeholders in Nairobi to make informed decisions that will accelerate progress toward good health and well-being for all residents. This data-driven approach is not only crucial for Nairobi’s local development but also serves as a model for other rapidly growing urban centers facing similar health challenges across the globe.

---

## 🛠️ Tools and Technologies Used

This project was powered by a suite of modern data analysis tools and open-source technologies, enabling detailed exploration, visualization, and storytelling with data:

- **Python**: Core programming language for data preprocessing, analysis, and visualization.
- **Pandas & NumPy**: Efficient data structures and operations for cleaning, transforming, and manipulating healthcare and demographic datasets.
- **Matplotlib & Seaborn**: Static plotting libraries used for bar charts, line plots, and categorical summaries.
- **Plotly & GeoPandas**: Interactive mapping and choropleth tools for spatial exploration of healthcare availability across Nairobi’s sub-counties.
- **Jupyter Notebook**: A dynamic environment for exploratory data analysis, code execution, and inline visualization.
- **Markdown & LaTeX**: Used to create structured documentation, section headers, annotated captions, and math/statistics notation.

These tools together enabled the creation of a reproducible, transparent, and visually compelling data story that can be shared, extended, or integrated into policy briefs and urban health dashboards.

## Nairobi's Demographic Landscape

The first step in enhancing healthcare is gaining a deep understanding of the population it aims to serve. Effective health planning and resource allocation require accurate and comprehensive demographic data to identify the needs and characteristics of the community. In Nairobi, where the population is diverse and rapidly growing, such insights are especially critical. By analyzing demographic profiles, health authorities can tailor interventions that address the unique health challenges faced by different groups, ensuring that no segment of the population is left behind.

According to the **2019 Kenya National Population Census**, Nairobi’s population stands at **4.397 million** people. This population is almost evenly divided by gender, with **49% male** and **51% female** residents. Understanding this near-equal gender distribution is essential, as it informs health service providers about potential differences in healthcare needs, utilization patterns, and risk factors between males and females. Such demographic knowledge lays the foundation for developing inclusive health strategies that promote equitable access and improved outcomes for all Nairobi residents.


![Figure 1: Age distribution](fig1.png)

Figure 1 reveals a striking demographic feature of Nairobi’s population: a pronounced youth bulge. More than **70%** of Nairobi’s residents are under the age of 35, highlighting a predominantly young population that shapes the city’s social and economic fabric. This youthful majority represents a vital segment of the population that has the potential to drive innovation, productivity, and development if their health and wellbeing are adequately supported. At the same time, this demographic trend brings unique challenges, as young people often face specific health risks and require targeted services to address their needs effectively.

Among this youthful population, children under the age of five constitute approximately **12%**, signaling the critical importance of early childhood healthcare. This group is particularly vulnerable to preventable diseases such as pneumonia, diarrhea, and malaria, which remain leading causes of child mortality in many low- and middle-income countries. The high proportion of young children necessitates robust maternal and pediatric healthcare systems that ensure timely access to essential services such as immunization, nutrition programs, and growth monitoring to reduce infant and child mortality rates and promote healthy development.

Young people, broadly defined as those aged 15 to 35, face a distinct set of health challenges that extend beyond childhood illnesses. Sexual and reproductive health services become crucial during adolescence and early adulthood, as young people navigate issues related to family planning, sexually transmitted infections, and adolescent pregnancy. Mental health also emerges as a pressing concern, with rising cases of depression, anxiety, and substance abuse among youth worldwide, including Nairobi. Preventive and counseling services, as well as community-based interventions, are essential to address these complex needs.

Given this demographic landscape, healthcare interventions in Nairobi must prioritize youth and child-centric services to be effective. This includes expanding immunization programs, enhancing antenatal and postnatal care, and integrating mental health counseling into primary healthcare. School-based health education programs offer a strategic platform to promote healthy behaviors, raise awareness, and reduce risk factors among children and adolescents. By focusing on these critical services, Nairobi can leverage its youthful population as a powerful driver of sustainable development aligned with SDG Goal 3.


![Figure 2: Population density by sub-county](fig2.png)

Beyond age, population density in Nairobi varies significantly across its sub-counties, revealing stark contrasts in living conditions and health challenges. High-density areas such as **Mathare**, **Kamukunji**, **Makadara**, and **Kibra** are characterized by densely populated informal settlements where thousands of residents live in cramped spaces. These neighborhoods often lack basic amenities like clean water, sanitation facilities, and waste management systems, creating an environment ripe for the spread of infectious diseases such as cholera, typhoid, and respiratory infections. The overcrowding not only exacerbates health risks but also complicates efforts to provide timely and effective healthcare.

The concentration of people in these informal settlements places immense pressure on the existing healthcare infrastructure, which is often under-resourced and ill-equipped to handle the volume and complexity of health needs. Public health systems in high-density areas face challenges such as long patient queues, inadequate medical supplies, and a shortage of trained healthcare professionals. These limitations hinder the delivery of essential services including maternal and child health, immunizations, and treatment for chronic diseases, disproportionately affecting the most vulnerable populations.

Addressing these challenges requires innovative and decentralized healthcare approaches that bring services closer to the community level. Community health workers, mobile clinics, and local health outreaches have emerged as vital strategies to overcome barriers related to accessibility and mobility within crowded urban environments. By empowering communities and enhancing local healthcare capacity, Nairobi can mitigate the adverse effects of population density on health outcomes and move closer to achieving the targets outlined in SDG 3 for Good Health and Wellbeing.

---

## Distribution of Healthcare Facilities

While Nairobi hosts a considerable number of health facilities, their distribution across the city does not adequately reflect the varying healthcare needs of its diverse population. Many health centers and hospitals are concentrated in relatively affluent or centrally located sub-counties, leaving densely populated and low-income areas underserved. This imbalance means that residents in high-need regions such as informal settlements often face longer travel distances, increased waiting times, and limited access to specialized medical services. The disparity in facility distribution highlights systemic inequalities that undermine efforts to provide equitable healthcare access to all Nairobi residents.

Moreover, the mismatch between healthcare infrastructure and population demand exacerbates the strain on existing facilities, leading to overcrowded clinics and stretched resources in areas where services are available. This overburdening compromises the quality of care, reduces patient satisfaction, and can lead to adverse health outcomes, particularly for vulnerable groups like children, the elderly, and people with chronic illnesses. Addressing this issue calls for strategic investment in healthcare infrastructure, focusing on building new facilities and upgrading existing ones in underserved sub-counties, as well as optimizing resource allocation to ensure efficient service delivery aligned with population needs.

![Figure 3: Health facilities per sub-county and healthcare density](fig3.png)

Sub-counties like **Embakasi** and **Starehe** stand out as having the highest number of health facilities within Nairobi, suggesting at first glance a robust healthcare infrastructure. However, these raw numbers can be deceptive when not considered alongside population size and distribution. **Embakasi**, for instance, despite boasting numerous clinics, hospitals, and dispensaries, is also one of the most populous sub-counties in Nairobi. This vast population base dilutes the impact of facility numbers, resulting in a **low healthcare facility density** — a critical measure indicating how many facilities serve each segment of the population. Consequently, residents may face overcrowded facilities and longer wait times, reducing the overall effectiveness of healthcare delivery despite facility availability.

Conversely, sub-counties such as **Mathare** and **Kasarani** suffer from a dual challenge: they not only have fewer health facilities overall but also experience low facility density relative to their population size. This compounded deficit significantly exacerbates the healthcare gap in these areas, especially considering that Mathare is home to some of Nairobi’s largest informal settlements. The scarcity of health facilities forces many residents to seek care far from home or forego treatment altogether, contributing to worsening health outcomes and perpetuating cycles of poverty and ill health. This shortage highlights the urgent need for targeted investment and strategic planning to expand healthcare infrastructure in underserved neighborhoods.

Beyond the mere presence of healthcare facilities, accessibility must also account for geographic and financial barriers faced by Nairobi’s residents. For many living in informal settlements, the closest health center might be several kilometers away, requiring hours of walking or costly transport that many cannot afford. This physical distance, combined with the financial strain of medical fees and transportation costs, often results in delayed or missed healthcare visits. Therefore, improving healthcare accessibility demands a comprehensive approach that goes beyond increasing the number of facilities to include enhancing transportation options, subsidizing care costs, and decentralizing services closer to communities in need. Only by addressing these multifaceted challenges can Nairobi move closer to achieving equitable healthcare for all its citizens.

---

## Facility Operational Hours and Service Availability

Availability of healthcare services is not solely determined by the number or location of health facilities; operational hours play a crucial role in defining when and how people can access care. For many Nairobi residents, especially those working irregular hours or multiple jobs, clinics and hospitals that operate only during standard business hours fail to meet their needs. This limited availability can result in delayed treatment, worsening of illnesses, and increased reliance on emergency services for conditions that could have been managed earlier with timely care. Furthermore, extended or after-hours services are often concentrated in private facilities, which may be prohibitively expensive for the majority of Nairobi’s population. This mismatch between health service availability and community needs creates significant barriers to effective healthcare delivery.

Moreover, in densely populated and underserved areas, the scarcity of 24/7 or weekend healthcare options compounds accessibility issues. When primary healthcare centers close after hours, patients are forced to travel longer distances to reach hospitals with emergency services, incurring additional time and costs that many cannot bear. This gap disproportionately affects vulnerable populations such as the elderly, children, and those with chronic conditions who require regular or urgent care outside typical hours. To address these challenges, Nairobi’s health system must prioritize extending operational hours and implementing flexible service models, including mobile clinics and telemedicine, that can reach people beyond the confines of traditional schedules. Doing so will be instrumental in closing service gaps and improving health outcomes in line with the goals of SDG 3.

![Figure 4: Healthcare facility operational status](fig4.png)

Though it is encouraging that more than half of Nairobi’s health facilities remain open during weekends, the stark reality is that fewer than 30% offer round-the-clock, 24-hour services. This limitation disproportionately affects critical sub-counties like Starehe, which encompasses the bustling Nairobi Central Business District (CBD). In this area, a significant portion of the population works outside typical 9-to-5 hours, including night shifts, part-time jobs, and informal sector employment. For these residents, access to healthcare during non-traditional hours is essential but often unattainable, creating a critical gap in the health system’s ability to serve its people effectively.

The lack of adequate 24/7 healthcare services has severe consequences. Patients with urgent medical needs, such as mothers in labor, trauma victims, or those experiencing acute illnesses, face delays that can worsen their conditions or even result in fatalities. Emergency rooms become overcrowded during off-hours as patients seek care in hospitals that are open, increasing wait times and straining limited resources. This situation not only endangers patients but also puts immense pressure on healthcare workers and infrastructure, reducing the overall quality and efficiency of care. In turn, this affects public trust in the healthcare system and undermines efforts to improve population health outcomes.

Extending operational hours of health facilities is therefore not simply a matter of convenience or customer service—it is a critical intervention that can save lives and improve the resilience of Nairobi’s health system. To truly align with SDG 3’s vision of ensuring healthy lives and promoting well-being for all, policymakers and healthcare providers must invest in expanding 24-hour service availability, particularly in high-need areas like Starehe. Innovative approaches such as staggered shifts for health workers, mobile emergency units, and partnerships with private sector clinics could help bridge this gap. Ultimately, enhancing access to timely care regardless of the hour is a foundational step toward equitable, effective, and compassionate healthcare for Nairobi’s diverse population.

---

## Comprehensive Service Coverage

Availability of essential health services forms the backbone of a resilient and effective healthcare system. Without reliable access to key interventions, even the most well-equipped facilities fall short in delivering comprehensive care to the communities they serve. To assess Nairobi’s readiness in this regard, we analyzed the extent to which health centers across the city provide a suite of vital services that address some of the most pressing health challenges.

Our focus was on critical programs such as **Antiretroviral Therapy (ART)**, which is essential for managing HIV/AIDS — a major public health concern in Kenya. Equally important is **Antenatal Care (ANC)**, ensuring pregnant women receive the monitoring and support necessary to promote safe pregnancies and deliveries. The **Prevention of Mother-to-Child Transmission (PMTCT)** of HIV is closely linked, aimed at reducing the risk of HIV transmission during pregnancy, childbirth, or breastfeeding, thereby safeguarding the next generation.

We also examined the availability of **Tuberculosis (TB) Diagnostics**, as TB remains a leading cause of morbidity and mortality in the region. Early and accurate diagnosis is fundamental to controlling this infectious disease. The **Expanded Program on Immunization (EPI)** was another focal point, highlighting Nairobi’s efforts to protect children from vaccine-preventable diseases through systematic immunization schedules. Lastly, we evaluated the provision of both **Basic and Comprehensive Emergency Obstetric Care**, which are indispensable for addressing complications during childbirth, reducing maternal and neonatal mortality rates.

Together, these services paint a holistic picture of Nairobi’s healthcare capacity to meet both routine and emergency needs. Their availability, distribution, and operational status directly influence the city’s progress toward achieving Sustainable Development Goal 3, emphasizing good health and well-being for all.
![Figure 5: Availability of healthcare services](fig5.png)

While ART and Family Planning services are moderately distributed, many critical services are almost absent. There are sub-counties with no **ANC**, **PMTCT**, or **obstetric emergency services**. The lack of **TB diagnostics**, **X-ray** facilities, and immunization infrastructure puts the city at risk of disease outbreaks and worsens chronic health disparities.

These service gaps directly compromise Kenya’s ability to meet:
- **SDG 3.1**: Reduce maternal mortality
- **SDG 3.2**: End preventable child deaths
- **SDG 3.3**: Combat HIV/AIDS, TB, and other diseases
- **SDG 3.4**: Reduce premature deaths from NCDs

---

## Pediatric Care: C-IMCI Accessibility

![Figure 6: Children's accessibility to C-IMCI services](fig6.png)

**C-IMCI (Community Integrated Management of Childhood Illnesses)** is a well-established and effective strategy designed to reduce child mortality by improving the diagnosis and treatment of the most common and life-threatening childhood illnesses. These include pneumonia, diarrhea, malaria, and malnutrition, which together account for a large proportion of deaths among children under five. By empowering community health workers with training and resources to manage these conditions promptly and effectively, C-IMCI extends critical healthcare services beyond formal facilities and into the communities where children live. This approach not only improves survival rates but also strengthens overall health system resilience at the grassroots level.

In Nairobi, access to C-IMCI services varies widely between sub-counties. Areas like **Lang’ata** demonstrate relatively better coverage, where community outreach and facility-based programs collaborate effectively to reach vulnerable children. In contrast, high-density informal settlements such as **Mathare** and **Kasarani** show significant gaps in service availability. This disparity poses a serious concern, as children living in underserved areas are at greater risk of preventable illnesses and death. The uneven distribution of C-IMCI highlights the urgent need to address healthcare inequities and ensure that lifesaving interventions reach all children regardless of their geographic or socio-economic status.

Given that children under the age of five make up approximately **12% of Nairobi’s population**, prioritizing child survival strategies like C-IMCI is critical for the city’s public health agenda. Expanding the coverage and quality of C-IMCI services will contribute directly to reducing child mortality rates and achieving **Sustainable Development Goal 3.2**, which aims to end preventable deaths of newborns and children under five by 2030. Strengthening these efforts not only saves lives but also supports broader goals of health equity, social justice, and sustainable development across Nairobi.

## Conclusion and Key Recommendations

This data-driven analysis reveals a sobering but actionable reality: while Nairobi boasts substantial healthcare infrastructure in select sub-counties like **Westlands**, **Starehe**, and **Lang’ata**, many areas remain critically underserved. **Mathare**, **Embakasi**, and **Kasarani**, characterized by high population densities and informal settlements, exhibit significant gaps in healthcare availability, operational hours, and essential service provision. If Nairobi is to lead Kenya in achieving **Sustainable Development Goal 3: Good Health and Wellbeing**, targeted interventions must bridge these divides with urgency and precision.

A responsive healthcare system must reflect the demographic and geographic needs of its population. The high proportion of youth and children, coupled with the reality of urban poverty and informal living conditions, demands a holistic, inclusive, and forward-thinking strategy. The following recommendations are grounded in the data and aligned with the SDG 3 targets to ensure Nairobi advances toward universal health coverage, reduced mortality, and equitable access to care.

### Key Recommendations

1. **Design Youth-Oriented Health Programs**  
   With over 70% of Nairobi’s population under 35, there is an urgent need for youth-centric health services. These should include accessible mental health counseling, comprehensive sexual and reproductive health education, and regular screenings for lifestyle diseases. Equipping youth with the tools and knowledge to manage their health promotes long-term societal wellbeing and productivity.

2. **Prioritize Informal Settlements**  
   Sub-counties like Mathare and Kibra, home to thousands in low-income communities, must receive focused attention. Expanding mobile clinics, deploying community health volunteers, and investing in localized health education campaigns can dramatically improve health outcomes in these vulnerable zones.

3. **Establish 24-Hour Health Centers**  
   Nairobi’s identity as a 24-hour economy requires a healthcare system that matches its rhythm. Emergency obstetric care, accident response, and night-time healthcare services must be available round-the-clock, especially in areas with high traffic, crime, or industrial activity like Starehe and Embakasi.

4. **Ensure Service Completeness**  
   Healthcare is not just about buildings, but about the services they offer. Facilities must be equipped with comprehensive services including antenatal care, immunizations, diagnostic testing (like TB and HIV), and emergency obstetrics. This ensures continuity of care and reduces the need for referrals, which often delays treatment.

5. **Enhance Pediatric Coverage**  
   With 12% of the population under five years of age, the city must invest heavily in child-specific health programs. Expanding the reach and quality of **C-IMCI** services, along with vaccination campaigns and nutritional support, is critical in lowering child mortality and ensuring a healthy next generation.

6. **Public-Private Partnerships (PPP)**  
   The private sector holds untapped potential in bridging healthcare gaps. Strategic collaborations with private hospitals, diagnostic labs, and telemedicine providers can rapidly expand reach and improve quality—especially in diagnostic imaging, specialist services, and emergency care infrastructure.

---

## 🧠 Insights and Implications

This project underscores the urgent need for data-driven policymaking in Nairobi’s healthcare planning. As the population continues to grow and urbanize, Nairobi faces mounting pressure to deliver equitable, timely, and effective healthcare to all its residents. The disparities uncovered in this analysis are not just statistical—they translate to real lives affected by preventable illnesses, delayed treatments, and missed opportunities for early intervention.

By highlighting spatial and service-related inequalities across sub-counties, this work emphasizes the importance of aligning health infrastructure with demographic realities. A significant portion of Nairobi’s population is young, densely concentrated, and economically vulnerable, necessitating tailored strategies that address their unique health needs. The insights derived from this data can directly inform policy, budget allocation, and public health interventions, ultimately helping to reduce mortality, decongest emergency services, and improve health system resilience.

In an age where data is increasingly pivotal to development, integrating such granular, evidence-based insights into local governance frameworks offers a path forward. The goal is not only to meet Sustainable Development Goal 3 (Good Health and Wellbeing) by 2030 but to build a system that can adapt, evolve, and respond equitably to its population’s needs far beyond that milestone.

---

## Project Structure

```bash
Healthcare-Accessibility-in-Nairobi/
├── data/                # Datasets (Health facilities, Population census)
├── figures/             # Figures used in analysis (fig1.png to fig6.png)
├── notebooks/           # Jupyter notebooks for full data analysis
├── README.md            # Detailed project overview and documentation
└── requirements.txt     # Required Python libraries
