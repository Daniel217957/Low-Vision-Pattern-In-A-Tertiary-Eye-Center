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
From the Line chart in the Overview dashboard above, the majority of the patients presenting to the Eye Centre were elderly, that is, between 60 and 74 years(for both females and males). Following that were seniors (75 years and above: [WHO Age Classification](https://www.instagram.com/p/DKHg8O7ID2J/)). The least set of patients were youths(15-24 years) and young adults(25 to 44 years).

**Insight:** The age distribution of the paitents by WHO age classification shows that low vision positively correlates with ageing.

### 4. Causes of Low Vision
As shown in the stacked bar chart, the commonest cause of low vision in Guinness Eye Centre for that month was [cataract](https://www.hopkinsmedicine.org/health/conditions-and-diseases/cataracts): the clouding of the normally clear lens that sits in the eye behind the pupil. 75 patients(35% of the total) with low vision were diagnosed with cataract. This eye disease also demonstrated the general male to female ration of the total patients that presented to the hospital. 

Following closely was [glaucoma](https://www.cdc.gov/vision-health/about-eye-disorders/glaucoma.html): a heterogenous group of eye diseases that eventually damage the optic nerve, resulting in vision loss or blindness. 60 patients(about 28% of the total) with low vision were diagnosed with glaucoma. Cataract and glaucoma combined contributed about 63% (almost 2/3) of the cases of low vision in the Eye Centre in October 2024.

Other eye diseases diagnosed were refractive errors(myopia, hypermetropia, presbyopia, etc), pseudophakia, pterygium, corneal opacity, occular allergies, uveitis and many others. These contributed about 37%(roughly 1/3) of the cases of low vision for the centre in October 2024.

**Insight:** Something has to be done about preventing or slowing the progression of Cataract and glaucoma as these contribute significantly to the incidence of low vision.

![Breakdown](Ophthalmo%20Folder/ophthalmo%20power%20bi%20project%20for%20portfolio_2.png)
<p align="center"><b>Breakdown of Age and Visual Acuity</b></p>

### 5. Breakdown of Age and Visual Activity
In the dashboard, the 7th and 8th decades had the highest number of paitents (76 each), constituting over 71% of the patients with low vision for that month.

The treemap shows a breakdown of patients by visual acuity. Majority of the patients had a visual acuity of 6/18, 6/24 and 6/36, each corresponing to moderate visual impairment(WHO ICD 10 [classification](https://ugc.futurelearn.com/uploads/files/8d/0f/8d0ff8b4-5847-41f6-bb06-f5a3ba81ca82/1.6-Defining-visual-impairment.pdf)). The minority (about 12%) had acuities of 6/60 and 3/60 which fell under severe visual impairment.

**Insight:** Targeted interventions and prevention strategies have to implemented for these decades of life. In addition, measures have to be taken to prevent the progression from moderate to severe visual impairment for these patients, and if possible, downgrade to mild visual impairment and normal vision.

![Key Insights](Ophthalmo%20Folder/ophthalmo%20power%20bi%20project%20for%20portfolio_3.png)
<p align="center"><b>Key Influencer Analysis</b></p>

### 6. Further Insights
A key influencer analysis of the dataset showed that visual impairment is likely(1.11 times more) to be moderate in the elderly age group than in other age groups, as shown in the dashboard above.

**Insight:** This further strengthens the point that the elderly are more at risk for low vision.

