
Analysis of healthy individuals at risk of developing a Mild Cognitive Impairment in 3-5 years

======================

### Aim

The aim of the study was to determine which individuals are at risk of developing 
a Mild Cognitive Impairment (MCI) within 3-5 years using only demographic variables 
and neuropsychiatric questionnaires. In other words, data that is accessible and 
doesn't require brain scans or invasive procedures.


### The data

The data was downloaded as a .csv file from ADNI database. It contained over 
100 variables of demographic, psychological, genetic, neuroimaging and biospecimen
 information from 1450 participants. The dataset was removed of all variables 
 that were not generally accessible to people e.g. neuroimaging. Participants 
 were chosen who showed no cognitive impairment during their initial screening 
 visit. This was determined using the Clinical Dementia Rating (CDR) scale; a 
 semi structured interview to assess skills such as memory and judgement. 
 A follow up CDR score was collected between 3 to 5 years to determine whether 
 they had developed a Mild Cognitive Impairment (MCI).The data was processed 
 using Microsoft Excel, converting strings to integers, to use in Python.

### Description of variables

| Variable | Metric | Table Key: Value | Brief Description|
| --- | --- | --- | --- |
| Impaired | T or F | Healthy: 0, Impaired: 1 | Mild Cognitive Impairment in 3-5 years
| Apoe4 | # no. | None: 0, One: 1, Two: 2 | APOE4 gene carrier
| Age | Years | categ | Age of person
| Gender | categ | Male: 1, Female: 2 | Gender assigned at birth
| Eth | categ | Hispanic: 1, Non-Hispanic: 2 | Hispanic specific ethnicity
| Race | categ | Asian: 2, Black or African: 4, White: 5, Multiple reported: 6 | Racial Background |
| Hand | categ | Right: 1, Left: 2 | Dominant hand type 
| Marry | categ | Married: 1, Widowed: 2, Divorced: 3, Never Married: 4, Unknown: 5 | Marital status
| Home | categ | House: 1, Condo: 2, Apartment: 3, Mobile home: 4, Retirement Community: 5, other: 8 | Type of Residency
| Retired | categ | Retired: 1, Not retired: 2 | Retirement status 
| Occupation | categ | Level 1 (e.g. cleaner): 1, Level 2 (e.g. butcher): 2, Level 3 (e.g. shop manager): 3, Level 4 (e.g. secondary teacher): 4 | Occupational Complexity
| Education | Years | cont | Years of Formal Education
| Depression | Test score | cont | Geriatric Depression Scale - A measure of depression (total /15; > 5 indicates depression)
| NIQ | Test score | cont | Neuropsychiatric Inventory Questionnaire - A measure of behaviour changes consistent with Alzheimers e.g. delusions, hallucinations, agitation/aggression, dysphoria, anxiety etc. (total /36)
| FAQ | Test score | cont | Functional Activities Questionnaire - The FAQ is a test that can be used to assess a patient’s dependency on another to carry out normal daily tasks, total /30, > 9 indicates impairment/dependency
| Weight | kg | cont | Weight
| Height | cm | cont | Height
| Temp | deg c | cont | Temperature at appointment
| Systolic | mmHg | cont | Systolic Blood Pressure
| Dystolic | mmHg | cont | Diastolic Blood Pressure
| Pulse | bpm | cont | Resting pulse rate 
| Resp | rpm | cont | Respirations per minute

## Results

### Conclusions