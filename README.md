# How did COVID-19 impact Opiod Overdose Cases ?

[![Contributors][contributors-shield]][contributors-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

## About The Project

The goal of this project is to investigate how COVID-19 impacted opiod overdose cases in Philadelphia, Pennsylvania. We aim 
to answer this question by analyzing the following questions/hypotheses:

1. How did masking policies change the progression of confirmed COVID-19 cases during the defined period ?
2. The number of drug overdoses cases during the COVID-19 pandemic is significantly higher than before the start of the pandemic
3. The age does not affect the dosage of Naloxone administered
4. The drug type does not affect the dosage of Naloxone administer

The following is the structure of the directory and files present:

```
.
├── README.md
├── data
│   ├── processed
│   │   ├── Pennsylvania-Drug-Overdose.csv
│   │   ├── Philadelphia-Ages.csv
│   │   └── Philadelphia-Pennsylvania-Covid-Data.csv
│   └── raw
│       ├── CONVENIENT_us_confirmed_cases.csv
│       ├── CONVENIENT_us_deaths.csv
│       ├── RAW_us_confirmed_cases.csv
│       ├── U.S._State_and_Territorial_Public_Mask_Mandates_From_April_10__2020_through_August_15__2021_by_County_by_Day.csv
│       └── mask-use-by-county.csv
├── documents
│   ├── HCDS Course Project_ A7 - Project Report.pdf
│   └── Sharma-Apoorv-Drug_Overdose-Pecha_Kucha.pptx
└── src
    ├── A4-Common-Analysis.ipynb
    └── A5-Extension.ipynb
```

## Dataset

We use 2 different datasets for our analysis:

1. [COVID-19 data from John Hopkins University](https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university?select=RAW_global_deaths.csv)
    * This dataset is licensed under the Attribution 4.0 International (CC BY 4.0) license
    * The dataset contains daily cases for all states and counties in the USA

2. [Overdose Information Network Data CY](https://data.pa.gov/Opioid-Related/Overdose-Information-Network-Data-CY-January-2018-/hbkk-dwy3)
    * This dataset is licensed under the Public Domain U.S. Government license
    * This dataset contains summary information on overdose responses and naloxone administrations by Pennsylvania criminal justice agencies and some third-party (i.e. EMS, Fire, Medical Staff, etc) first responders voluntarily entering incident data. Due to the voluntary nature of the application, the ODIN information provided may not represent the totality of all overdose and/or naloxone administration incidents involving criminal justice agencies occurring within the Commonwealth.

## Results

For each of the following questions/hypothesis, we obtained the following result:

1. How did masking policies change the progression of confirmed COVID-19 cases during the defined period ?
    * There was not significant change in cases during the masking mandate
2. The number of drug overdoses cases during the COVID-19 pandemic is significantly higher than before the start of the pandemic
    * The number of opiod overdose case increase was marginally significant during the pandemic
3. The age does not affect the dosage of Naloxone administered
    * We fail to reject this NULL hypothesis
4. The drug type does not affect the dosage of Naloxone administer
    * We fail to reject this NULL hypothesis

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/sharma-apoorv/data-512-a2.svg?style=for-the-badge
[contributors-url]: https://github.com/sharma-apoorv/data-512-a2/graphs/contributors
[license-shield]: https://img.shields.io/github/license/sharma-apoorv/data-512-a2.svg?style=for-the-badge
[license-url]: https://github.com/sharma-apoorv/data-512-a2/blob/main/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/sharmavapoorv/