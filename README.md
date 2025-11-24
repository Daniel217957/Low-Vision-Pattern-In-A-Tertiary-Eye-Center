# Investigating the Pattern of Low Vision in a Tertiary Eye Centre
![Schematic Diagram of the Cross-section of the Eye](Ophthalmo%20Folder/Gemini_Generated_Image_zajk9zajk9zajk9z.jpg "Schematic diagram of te cross-section of the eye")
<p align="center"><b>Schematic diagram of the cross-section of the eye</b></p>

## Skills
Power BI, DAX, data modeling, data analysis, data transformation and data visualization. 
## Project Context
According to the World Health Organization (WHO), low vision is defined as a visual acuity of less than 6/18 to 3/60 in the better eye with the best possible correction. This definition is based on the WHO's [International Classification of Diseases (ICD)](https://ecoo.info/2011/03/position-paper-low-vision/) and is widely accepted globally. Visual acuity(the clarity or sharpness of vision) is obtained on clinical examination using a [Snellen chart](https://my.clevelandclinic.org/health/diagnostics/24421-visual-acuity-test).
Many eye diseases predispose individuals to low vision, and some even progress to permanent blindness.

In this project, all the patient records in [Guinness Eye Centre, Onitsha](https://africaresearchconnects.com/institution/9000693622/) for October 2024 were taken, and patients who had low vision were selected, filtered and analyzed to uncover patterns and eye diseases most commonly associated with low vision in the centre. This work was part of my ophthalmology posting project in my penultimate year of medical school at [Nnamdi Azikiwe University Teaching Hospital](https://www.nauthnnewi.org.ng/).

Using Power BI, I developed an interactive and visually intuitive dashboard that produced several valuable insights on low vision at Guinness Eye Centre and proffered some public health interventions to reduce the incidence of low vision.
### Ethical Considerations
Ethical considerations are paramount in research involving human subjects. Approval to use the hospital records was obtained from the Head of the records department and the patient records were anonymized to comply with ethical standards.

## What I Analyzed
The dataset, titled “Ophthalmo Power BI,” contains categorical and numerical data collected from a group of individuals, including age, gender, visual acuity(in the better eye) and diagnosis. I engineered new columns like WHO Age Classification, Diagnosis Category, and Visual Impairment using DAX. I also calculated measures like Average Patient Age and Number of Patients using DAX to compute meaningful KPIs that brought the data to life in Power BI.
![Overview](Ophthalmo%20Folder/for_portfolio_split_1.jpg)
 <p align="center"><b>Overview of the Pattern of Low Vision at Guinness Eye Centre, Onitsha</b></p>
 
## Overview
### 1. Number of Patients and Average Patient Age
Out of all the patient records that were drawn from October 2024, 214 patients had low vision. In addition, the mean age of patients who presented to the Eye Centre in October 2024 who had low vision was 66.73 years.

### 2. Gender Distribution
Of the 214 patients, 144(67%) of the patients were females and 70(33%) were males.

**Insight:** More than 2/3 of the patients with low vision for that month were females. This higher burden of low vision in the female gender, extrapolated from the analysis, generates further questions on why females are more predisposed to low vision. Is it due to lifestyle, genetics, or just a reflection of the gender distribution of the population in Onitsha? Or do females have a better health-seeking behaviour than males? This calls for more investigation at Guinness Eye Centre, Onitsha.

### 3. Age Distribution by WHO Age Classification
From the Line chart in the Overview dashboard above, the majority of the patients presenting to the Eye Centre were elderly, that is, between 60 and 74 years(for both females and males). Following that were seniors (75 years and above: [WHO Age Classification](https://www.instagram.com/p/DKHg8O7ID2J/)).
![Breakdown](Ophthalmo%20Folder/ophthalmo%20power%20bi%20project%20for%20portfolio_2.png)
![Key Insights](Ophthalmo%20Folder/ophthalmo%20power%20bi%20project%20for%20portfolio_3.png)
