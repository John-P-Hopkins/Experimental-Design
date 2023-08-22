# Overview 

This project aims to analyze the Household Pulse Survey data to determine if any factors such as location (FL versus AL & GA), sex, or age have an impact on unmet mental health needs. The survey was designed to gauge the impact of the pandemic (COVID-19) on employment status, consumer spending, food security, housing, education disruptions, and dimensions of physical and mental wellness.

## Data

The dataset contains key data regarding the unmet mental health needs of American households. Data collection began on April 23, 2020.
The survey shows estimated percentages of adults aged 18 and over who in the past four weeks  a) took prescription medication for their mental health, b) received counseling or therapy from a mental health professional, or c) needed counseling or therapy from a mental health professional but did not get it.


I will focus on (c) an unmet mental health need.
The dataset is available for public access and use (see link below). The dataset contains 10404 rows and 15 columns.

Link - https://catalog.data.gov/dataset/mental-health-care-in-the-last-4-weeks

### Data Source 

The U.S. Census Bureau, in collaboration with five federal agencies, launched the Household Pulse Survey to produce data on the social and economic impacts of Covid-19 on American households. The Household Pulse Survey was designed to gauge the impact of the pandemic on employment status, consumer spending, food security, housing, education disruptions, and dimensions of physical and mental wellness.

The survey was designed to meet the goal of accurate and timely weekly estimates. It was conducted by an internet questionnaire, with invitations to participate sent by email and text message. The sample frame is the Census Bureau Master Address File Data. Housing units linked to one or more email addresses or cell phone numbers were randomly selected to participate, and one respondent from each housing unit was selected to respond for him or herself. Estimates are weighted to adjust for nonresponse and to match Census Bureau estimates of the population by age, sex, race and ethnicity, and educational attainment. (cdc.gov/hchs/covid19/pulse/mental-health-care.htm)

## Research Design

### Dataset Features 

Currently, the dataset contains the following features to be used during this research:
- Sex: Indicates if respondent is male or female.
- Age: Indicates the age range of the respondent.
- State: Indicates the respondent's location.
- Indicator: Response to the survey question “At any time in the last 4 weeks, did you need counseling or therapy from a mental health professional, but did not get it for any reason?”
- Value: Weighted % of subject population.

### Limitations 

Nonsampling errors for the Household Pulse Survey may include:
- Measurement error: The respondent provides incorrect information, or an unclear survey question is misunderstood by the respondent. The Household Pulse Survey schedule offered only limited time for testing questions.
- Coverage error: Individuals who otherwise would have been included in the survey frame were missed. The Household Pulse Survey only recruited households for which an email address or cell phone number could be identified.
- Nonresponse error: Responses are not collected from all those in the sample or the respondent is unwilling to provide information. The response rate for the Household Pulse Survey was substantially lower than most federally sponsored surveys.
- Processing error: Forms may be lost, data may be incorrectly keyed, coded, or recoded. The real-time dissemination of the Household Pulse Survey provided limited time to identify and fix processing errors. (cdc.gov/hchs/covid19/pulse/mental-health-care.htm)

## Business Questions

Within this research, the following business questions will be answered:
- Is there a difference between Florida and its bordering states (AL & GA) for an unmet mental health need?
- Is there a difference between the sexes for an unmet mental health need?
- Is there a difference between age groups for an unmet mental health need?

### Hypothesis Testing

The following hypothesis testing will be conducted:
- Hypothesis testing based on respondent’s location (FL versus AL & GA).
  - H0 (NULL): There is no difference in the percentages having an unmet mental health need based on their location (FL versus AL & GA).
  - H1 (Alternate): Significant difference exists in the percentage having an unmet mental health need based on their location (Fl versus AL & GA).
  - The above hypothesis will be tested using the Kruskal-Wallis test, Tukey HD test and One-way ANOVA test.

- Hypothesis testing based on respondent’s sex.
  - H0 (NULL): There is no difference in the percentages having an unmet mental health need based on their sex.
  - H1 (Alternate): Significant difference exists in the percentage having an unmet mental health need based on their sex.
  - The above hypothesis will be tested using a t-test.

- Hypothesis testing based on respondent’s age.
  - H0 (NULL): There is no difference in the percentages having an unmet mental health need based on their age.
  - H1 (Alternate): Significant difference exists in the percentage having an unmet mental health need based on their age.
  - The above hypothesis will be tested using the Kruskal-Wallis test.

## Audience

I believe the research will be useful to managers and therapists. It provides a valuable snapshot of the current state of mental health needs in our nation and the state of Florida. The results can lead to mental health services reaching those with the greatest unmet needs.