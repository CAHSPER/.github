# Guides
[Guides to using RIS services](https://github.com/CAHSPER/.github/wiki)  

# Requesting Data Sets
[Data Request Form](https://forms.office.com/r/StKkLuj0VD)
(requires WUSTL Office login)

# Available Data Sets

## NEDS (HCUP)
* **Lab Sources**: Brown Lab (2006-2022), Johnston Lab (2017-2021)
* **Limited Data Set**  
* **Unit of Analysis**: ED Visit/Discharge  
* **Use Case**: for ED visit analysis
* **Other Information**: Uses national survey weights
* **Description**: The National Emergency Department Sample is part of the Healthcare Cost and Utilization Project (HCUP) developed by the Agency for Healthcare Research and Quality
* **Source**: https://hcup-us.ahrq.gov/nedsoverview.jsp
* **Also See**:https://github.com/CAHSPER/HCUP/tree/main/NEDS

## NIS (HCUP)
* **Lab Sources**: Joynt Maddox Lab (2012-2022), Johnston Lab (2017-2021)
* **Limited Data Set**  
* **Unit of Analysis**: Inpatient Stay/ Discharge  
* **Use Case**: for inpatient hospital analysis
* **Other Information**: Uses national survey weights
* **Description**: The National Inpatient Sample is part of the Healthcare Cost and Utilization Project (HCUP) developed by the Agency for Healthcare Research and Quality
* **Source**: https://hcup-us.ahrq.gov/nisoverview.jsp
* **Also See**: https://github.com/CAHSPER/HCUP/tree/main/NIS

## State Inpatient Database (SID)
* **Lab Sources**: Mobley Butler Lab (FL: 2015-2021), Brown Lab (AZ: 2016-2021; CA: 2005-2011; FL: 2005-2021; MD: 2005-2021; NC: 2016-2020; NJ: 2005-2020; NY: 2016-2020)
* **Limited Data Set**  
* **Unit of Analysis**: Inpatient Stay/ Discharge (Patient-linkable)
* **Use Case**: for inpatient hospital analysis
* **Other Information**: links to AHA annual survey
* **Description**: The State Inpatient Databases (SID) are part of the family of databases and software tools developed for the Healthcare Cost and Utilization Project (HCUP). The SID includes inpatient discharge records from community hospitals in that State. The SID files encompass all patients, regardless of payer, providing a unique view of inpatient care in a defined market or State over time.  
* **Source**: https://hcup-us.ahrq.gov/sidoverview.jsp

## State Emergency Department Database (SEDD)
* **Lab Sources**: Brown Lab (AZ: 2016-2021; CA: 2005-2011; FL: 2005-2021; MD: 2005-2021; NC: 2016-2020; NJ: 2005-2020; NY: 2016-2020)
* **Limited Data Set**  
* **Unit of Analysis**: ED Visit/ Discharge (Patient-linkable)  
* **Use Case**: for ED visit analysis
* **Other Information**: links to AHA annual survey
* **Description**: The State Emergency Department Databases (SEDD) are a set of longitudinal State-specific emergency department (ED) databases included in the HCUP family. The SEDD capture discharge information on all emergency department visits that do not result in an admission.  
* **Source**: https://hcup-us.ahrq.gov/db/state/sedddbdocumentation.jsp

## Missouri Hospital Association/ Hospital Industry Data Institute (MHA/HIDI)
* **Lab Sources**: McBride Lab (2015-2023)
* **Limited Data Set**  
* **Unit of Analysis**: Hospital (facility level) encounter claims
* **Use Case**:  
* **Other Information**:  
* **Description**: like SID and SEDD from MO in one file
* **Source**: https://web.mhanet.com/affiliates-business-services-partnerships/hospital-industry-data-institute/

## MCBS
* **Lab Sources**: Johnston Lab (2015-2022)
* **Limited Data Set**  
* **Unit of Analysis**: Beneficiary and Claims for Medicare Administrative Data Linked to Patient Surveys
* **Use Case**:  Comparison of Quality of Care in Medicare Advantage vs Traditional Medicare
* **Other Information**: Links to Medicare Plan-level Data
* **Description**: The Medicare Current Beneficiary Survey is a continuous, multipurpose survey of a nationally representative sample of the Medicare population.
* **Source**: https://www.cms.gov/data-research/research/medicare-current-beneficiary-survey

## Medicare Master Beneficiary Summary Files  
* **Lab Sources**: Joynt Maddox Lab (2012-2018; MBSF A/B/C/D, 27 CCW, Other Chronic or Potentially Disabling Conditions, Cost and Use)
* **Identifiable Data Set**  
* **Unit of Analysis**:  Medicare Beneficiary    
* **Use Case**:  Compare beneficiary characteristics by Medicare plan type
* **Other Information**:  Medicare data summarized at beneficiary level
* **Description**:  See CCW data dictionaries below for MBSF A/B/C/D
* **Source**: https://www2.ccwdata.org/web/guest/data-dictionaries  
* **Also See**: https://resdac.org/cms-data?tid_1%5B1%5D=1&tid%5B6046%5D=6046

## Area Health Resource Files
* **Lab Sources**: Johnston Lab (2006-2022)
* **Public Data Set**   
* **Unit of Analysis**: County level  
* **Use Case**: for geographic supply of medical providers
* **Other Information**: Links to patient/provider county of residence
* **Description**: The AHRF is released annually by the Bureau of Health Workforce. M.D. County Level File includes M.D. with active or inactive status, classified or not classified status, and employed by federal government or non-federal industry.
* **Source**: https://data.hrsa.gov/topics/health-workforce/ahrf

## United State Renal Data System (USRDS)
* **Lab Sources**: Mobley Butler Lab (2005-2020)
* **Limited Data Set**  
* **Unit of Analysis**: CKD/ESRD Patient Claims, Provider Data
* **Use Case**:  
* **Other Information**: can link with patient cohorts by USRDS
* **Description**: 
* **Source**: https://www.niddk.nih.gov/about-niddk/strategic-plans-reports/usrds/for-researchers/researchers-guide 
* **Also See**: https://gowustl-my.sharepoint.com/:x:/g/personal/tabman_wustl_edu/EYI62RFMKgpFug-_KV007VkBNkZ3-Zhd9sJ77e6idTMnCg?e=MOKqAO   

## Medical Expenditure Panel Survey
* **Lab Sources**: McBride Lab (1996-2023)
* **Public and Restricted Data Sets**  
* **Unit of Analysis**: families and individuals, medical providers, and employers
* **Use Case**:  Analysis of use and cost of services
* **Other Information**:  
* **Description**: MEPS collects data on the specific health services that Americans use, how frequently they use them, the cost of these services, and how they are paid for, as well as data on the cost, scope, and breadth of health insurance held by and available to U.S. workers.  
* **Source**: https://meps.ahrq.gov/mepsweb/data_stats/data_overview.jsp

## Market Scan
* **Lab Sources**: Mobley Butler Lab (Commercial: 2006-2022; Multi-state Medicaid: 2010-2022)
* **Limited Data Set**  
* **Unit of Analysis**: Patient claim level 
* **Use Case**: Comprehensive health care claims data for inpatient and outpatient provider and facility claims and prescription drug claims 
* **Other Information**: 
    * Need to go through ADCS and complete DUA for access
    * Need project-level permission to report on geographic unit smaller than US census region or division (i.e., state level analysis)
    * Multiple states of Medicaid data, but names of states are unknown; no geography provided
* **Description**: 
* **Source**: https://www.merative.com/documents/brief/marketscan-explainer-general
  
##  Merit-based Incentive Payment System (MIPS)
* **Lab Sources**: Johnston (2017-2022)
* **Public Data Set**  
* **Unit of Analysis**: Clinician
* **Use Case**: Medicare physician quality and performance measurement 
* **Other Information**: 
* **Description**: Clinicians that bill Medicare Part B  
* **Source**: (for most recent year) https://data.cms.gov/provider-data/search?theme=Doctors%20and%20clinicians
* **Also See**: https://qpp.cms.gov/mips/mvps/learn-about-mips

## American Hospital Association (AHA) Survey
* **Lab Sources**: Center, Lin Lab (AHA Annual Survey: 2005-2023, AHA IT Survey: 2008-2023)
* **Limited Data Set**  
* **Unit of Analysis**: Hospital
* **Use Case**: Survey of US hospitals on structural characteristics, vertical and horizontal integration/affiliations, services offered, IT capabilities, revenue sources, etc.; also can be linked to other datasets (e.g., Claims)
* **Other Information**:
    * Accessible through Wharton Data Services
* **Description**: https://www.ahadata.com/aha-data-resources for survey instruments and file layouts
* **Source**: https://wrds-www.wharton.upenn.edu/register/
* **Also See**: https://wrds-www.wharton.upenn.edu/pages/about/data-vendors/american-hospital-association/ (Requires registration with WashU ID to access)

## Medicare Health Outcomes Survey (MHOS)
* **Lab Sources**: Johnston (2015-2023)
* **Limited Data Set**  
* **Unit of Analysis**: Medicare Advantage beneficiary
* **Use Case**: Longitudinal patient-reported outcomes survey assessing physical and mental health status of Medicare Advantage enrollees; useful for evaluating health-related quality of life, program effectiveness, disparities in health outcomes, and linking to MA plan characteristics or claims data
* **Other Information**:
   * Includes baseline and follow-up surveys; beneficiaries are followed for 2 years; survey administered by CMS
* **Description**:   
* **Source**: CMS
* **Also See**: https://www.hosonline.org/en/data-dissemination/research-data-files/ 
