<a name="readme-top"></a>
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents (click me)</summary>
  <ol>
    <li>
      <a href="#About-the-project">About The Project</a>
    </li>
    <li>
      <a href="#Data-Analysis">Data Analysis</a>
      <ul>
        <li><a href="#Dataset-Description">Dataset Description</a></li>
        <li><a href="#Workflow">Workflow</a></li>
        <li><a href="#Example-plots-in-EDA">Example plots in EDA</a></li>
        <li><a href="#Stepwise-Model-fitting-with-all-variables">Stepwise Model fitting with all variables</a></li>
        <li><a href="#Results-and-Conclusions">Results and Conclusions</a></li>
      </ul>
    </li>   
    <li><a href="#Reports-and-slides">Reports and slides</a></li>    
    
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Tracheostomy is a common procedure in the ICU when there is expectation of prolonged mechanical ventilation. Recent adult studies have shown that the rates of tracheostomy in the United States have increased from 64,000 tracheostomies per year in 1996 to currently greater than 100,000 per year. There is little data on tracheostomy practices and outcomes in the pediatric population, and optimal timing tracheostomy after mechanical ventilation is unknown.

The goal of this project is to describe post-hospital outcomes of tracheostomy in the pediatric population and to describe risk factors for poor outcomes after tracheostomy.

<!-- GETTING STARTED -->
## Data Analysis

### Dataset Description

53 observations and 445 variables in the dataset.

### Workflow
<div align="center">
<img src="https://github.com/JILI1028/Tracheostomy-Project-/blob/main/images/workflow1.png" width="450" height="300">
</div>

### Example plots in EDA

* Heatmap
<div align="center">
<img src="https://github.com/JILI1028/Tracheostomy-Project-/blob/main/images/nas_mwphunnamed-chunk-4-2.png" width="400" height="400">
</div>
For feeding and resp, most of the patients have a moderate condition. 

* Bar plots
<div align="center">
<img src="https://github.com/JILI1028/Tracheostomy-Project-/blob/main/images/nas_mwphunnamed-chunk-10-1.png" width="400" height="400">
</div>

* Longitudinal trajactories
<div align="center">
<img src="https://github.com/JILI1028/Tracheostomy-Project-/blob/main/images/nas_mwphunnamed-chunk-13-1.png" width="400" height="400">
</div>
FSS_total stands for Functional Status Score (FSS) TOTAL. The mean of FSS_total decreases from admission to year3.

* Facet plots
<div align="center">
<img src="https://github.com/JILI1028/Tracheostomy-Project-/blob/main/images/nas_mwphunnamed-chunk-19-1.png" width="500" height="500">
</div>
In admissions, the box plot in 1-year follow up is higher than the plot for 3-year follow up. When admissions=1, FSS_total in 1-year follow up has the same median as FSS_total in 3-year follow up.

### Stepwise Model fitting with all variables
detailed tables are in the folder.[HERE][folder-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Results and Conclusions
Fifty-three patients met inclusion criteria. The mean age at tracheostomy was 73.2 days [95% Confidence Interval (CI) 30.4 – 116.0]. Average gestational age was 34.3 weeks [95% CI 32.7 – 35.9]. Thirty-four (64.2%) had a pulmonary diagnosis on admission, while 28 (52.8%) had a cardiac diagnosis. A majority (28, 52.8%) underwent tracheostomy for airway obstruction. Forty (75.5%) had complete data. Then mean age at one- and three-years post-tracheostomy were 23.2 months [95% CI 15.2 – 31.2] and 44.6 months [95% CI 34.2 – 55.0], respectively. There were no decannulations at 1 year. Nine (22.5%) were decannulated at 3 years. An abnormal motor FSS score at PICU discharge was associated with an odds ratio (OR) of 4.1 [95% CI: 1.0–16.4, p = .05] of maintaining the tracheostomy at 3 years. An abnormal 3 year FSS score in the feeding domain was significantly associated with maintaining a tracheostomy at 3 years, with an OR of 7.4 [95% CI: 1.5 – 36.6, p = .01] to maintain the appliance. An abnormal 3 year score in motor domain showed an higher odds ratio of 4.5 [95% CI: 1.0–18.2] of maintaining the tracheostomy, though this did not reach significance (p = .06). 

Pediatric tracheostomy has been associated with long term morbidity impacting multiple organ systems. Persistent abnormalities in the feeding and motor domains are negatively associated with decannulation. This information may help caregivers plan for short- and long-term resources and improve the quality of care in these patients.  

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Reports and slides
* 10.2_FSS_abstract.docx: final abstract

* Descriptive Analysis of Tracheostomy Resource Utilization Study.pdf

* Resp Support at three year.pdf: example of predicting the patient is decannulated or not. Also did at one-year and at discharge.
<!-- CONTACT -->
## Contact

Ji Li - jil1@umbc.edu

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[matplotlib-url]: https://pandas.pydata.org/](https://matplotlib.org/
[seaborn-url]: https://seaborn.pydata.org/
[seaborn.js]: https://seaborn.pydata.org/_static/logo-wide-lightbg.svg
[numpy-url]: https://numpy.org/
[heatmap.js]: https://github.com/JILI1028/bank-marketing/blob/main/images/cor1016.png
[folder-url]: https://github.com/JILI1028/Tracheostomy-Project-/blob/main/reports/trach_tables.docx
