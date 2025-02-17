# ICMR Antimicrobial Resistance
Date : 05-02-2025


## Description

Antimicrobial resistance (AMR) occurs when microorganisms, such as bacteria, viruses, and fungi, evolve to resist the effects of antibiotics and other antimicrobial drugs. This growing issue makes infections harder to treat and increases the risk of severe illness, complications, and death. As pathogens continue to develop resistance, many common antibiotics become ineffective, posing significant challenges to public health and modern medicine. Addressing AMR requires global efforts, including responsible antibiotic use, infection prevention, and promoting research for new treatments.

Antimicrobial resistance (AMR) poses a significant public health challenge in India, exacerbated by the country's high burden of infectious diseases and substantial antibiotic consumption. In 2019, AMR was associated with approximately 4.95 million deaths globally, with 1.27 million directly attributed to drug-resistant infections. Notably, a significant portion of these deaths occurred in India, underscoring the severity of the issue within the country

This project mainly focuses on the Data analysis on AMR. Data was collected from the official Indian Council of Medical Research (ICMR) website.

## Tools used
- Python
  - Numpy
  - Pandas
  - Matplotlib
  - Seaborn
  - Plotly


## Contents

### 1. Data preperation

- Renaming of columns
  - All columns are renamed with reference to metadata provided with dataset.
- Replacing numerical values with original values in respective columns
  - In dataset all numerical data is replaced with catagorical data.

### 2. Data Analysis

- Data info
- Data Cleaning
- Haneling Null Values
- Remove unnecessary columns
- Classification of colum into catagorical and non catagorical
- Analysis and Visualization
  - Patients age
  - Patients Gender
  - Urban-Rural classification
  - Infection type
  - Patients with Devices
  - Patients by Region
  - Infection over Time
  - Antimicrobial Resistance (AMR)
  - State wise AMR
  - Location and gender wise Antimicribial resistance
  - Antimicrobial resistance for Patients with devices
  - Antimicrobial resistance for Infection type
  - Antimicrobial resistance for Organism
  - Antimicrobial Resistance aganist Antibiotics


## Data Preperation

(```Data Preparation.ipynb```)

The data was obtained in a ```.dta``` file and was all in numerical format, making it hard to analyse. So I choose to replace the numerical values with the category values specified in the metadata file ```1730700015_amr_metadata.pdf```. I began by renaming columns and then replaced all numerical data in categorical columns with string data. Finally, I saved the changed file as ```.csv```.


## Data Analysis

(```AMR Code.ipynb```)

This notebook is focused on preparing and analyzing data for a project related to antimicrobial resistance (AMR). The analysis likely aims to identify patterns or trends in resistance data, which is a critical issue in public health.

### 1. Patients age

Patients under the age of two and those between the ages of 22 and 70 have infections.
![image](https://github.com/user-attachments/assets/348b23c1-b269-43b4-b875-efef60b57c6d)


### 2. Patients Gender

Males make up the majority of patients, accounting for more than half of the total. Female patients account for less than half of total patient count.
![image](https://github.com/user-attachments/assets/f7180b68-31fe-43f8-86cc-facdea65d290)


### 3. Urban-Rural classification

The vast majority of infections are found in rural areas rather than urban ones.
![image](https://github.com/user-attachments/assets/c89a873f-5443-4f75-8422-288b527f43aa)


### 4. Infection type

The majority of diseases are contracted through community infection, while infections linked to healthcare are rare but not insignificant.
![image](https://github.com/user-attachments/assets/9794a93f-d620-4542-a0ad-1118707ff1c3)


### 5. Patients with Devices

Approximately one thousand patients have devices, while the majority are without them.
![image](https://github.com/user-attachments/assets/13b5c5e6-bd95-40c6-8e9a-f59b5241d6eb)


### 6. Patients by Region

Tamil Nadu alone accounts for nearly half of all infections, with Puducherry and Assam coming in second and third.
![image](https://github.com/user-attachments/assets/03f00f5b-ee9d-4df6-ae8d-229c4eeb2839)


### 7. Infection over Time

This graph shows the infections reported over time.
![image](https://github.com/user-attachments/assets/2c33db46-36b8-4d1b-bb22-bfedc84b3312)


### 8. Antimicrobial Resistance (AMR)

Around 40 % of total infections are resistant and 5.3% are intermediate stage.
![image](https://github.com/user-attachments/assets/b617337b-6284-45f8-a724-96bd536cfb4b)


### 9. State wise AMR

This graph shows the state wise Antimicrobial Resistance.
![image](https://github.com/user-attachments/assets/028a1a62-cf5b-4769-937c-c41ee3494f54)


### 10. Location and gender wise Antimicribial resistance

This plot displays the gender-based antimicrobial resistance of patients by location.
![image](https://github.com/user-attachments/assets/da822416-ed71-494b-9eeb-6c7baee74702)


### 11. Antimicrobial resistance for Patients with devices

This graph shows the AMR for patients with devices.
![image](https://github.com/user-attachments/assets/1177c240-4669-495c-afe1-ff591413ddcc)


### 12. Antimicrobial resistance for Infection type

Health care-associated infections have a notably elevated AMR.
![image](https://github.com/user-attachments/assets/94d73838-2d17-4208-93d9-eef110a11694)


### 13. Antimicrobial resistance for Organism

![image](https://github.com/user-attachments/assets/334e9ce3-29f9-4060-ae67-0ac2d7fcec93)

### 14. Antimicrobial Resistance aganist Antibiotics

![image](https://github.com/user-attachments/assets/dd308f56-10c7-471d-aad3-5bbdd76866b9)







