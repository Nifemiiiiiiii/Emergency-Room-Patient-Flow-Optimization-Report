# Optimizing Emergency Care Delivery: Insights from 9,216 Patient Visits

![image](https://github.com/user-attachments/assets/9a5fca35-cbb2-4314-9ac3-8729ba7c902a)

## Project Overview

This comprehensive analysis examines 9,216 ER patient records to: Identify patterns in patient volume and flow, Evaluate departmental referral efficiency, Analyze demographic disparities in care, Improve patient satisfaction and wait times

![Screenshot 2025-05-16 133233](https://github.com/user-attachments/assets/105b912b-2951-43aa-bae1-0f2e4c59ac41)

## Impact: 

Identified opportunities to reduce wait times by 22% and increase satisfaction scores by 1.8 points through data-driven interventions.

## Key Questions

1.What are the peak periods for ER visits and how does current staffing align?

2. Which departments handle the most referrals and are resources allocated optimally?

3. How do wait times and satisfaction vary by patient demographics?

4. What percentage of patients require admission versus outpatient care?

## Data Source

Dataset: 9,216 de-identified ER patient records

Time Period: Multi-year data (2019-2020)

## Key Fields:

Patient demographics (age, gender, race), Visit details (date/time, appointment type), Clinical data (referral department, wait times), Outcome metrics (satisfaction scores).

## Tools
1. Power BI (Interactive dashboards)

2. SQL (Data extraction and transformation)

3. DAX (Advanced metrics calculation)

## Data Cleaning & Preparation

#### Data Issues Resolved:
Standardized date formats across multiple source systems

Corrected department name inconsistencies (e.g., "Phyiatherapy" → "Physiotherapy")

Handled missing values (5.2% of records) using median imputation

Identified and removed duplicate records (1.3% of data)

#### Enhanced Data Structure:
Created calculated columns:

![image](https://github.com/user-attachments/assets/b9baddd0-b20d-4dc3-9c7c-5acf77df8467)

Age Group Category (Standardized age brackets Eg PatientAge is less than or equals to 2, "Infancy")

Age Bucket Category (Categorizes Age bucket with 10 years age gap)

## Exploratory Data Analysis (EDA)

Key Metrics Summary:

![image](https://github.com/user-attachments/assets/54991670-5173-4210-96d9-265a153fe570)

## Detailed Findings:

#### Patient Volume Patterns:

Weekly Trends: 69.2% of visits occurred on weekdays

![image](https://github.com/user-attachments/assets/b3e0f8c9-e3b0-4281-81c4-9dcfc3745936)

Seasonal Patterns: 18% increase in visits during winter months

![image](https://github.com/user-attachments/assets/6922fdc1-61e9-40a6-965e-3c8fd42239a2)

#### Departmental Referrals:

![image](https://github.com/user-attachments/assets/3c51feca-ea25-478f-8888-f09eb020f8cf)

General Practice: 1,840 cases (19.96% of referrals), Orthopedics: 995 cases (10.79%), Physiotherapy: 276 cases (2.99%), Cardiology: 248 cases (2.69%)

#### Demographic Insights:
###### Age Distribution:

![image](https://github.com/user-attachments/assets/cb5ae66c-787c-4f4c-82ff-31760b4d3daf)

Adults (77.1%) dominated visits, Children (22.9%) showed different visit patterns

###### Racial Breakdown:

![image](https://github.com/user-attachments/assets/e33daae7-3e15-48fa-af85-3e936d683bab)

##### Operational Metrics:

Average wait time: 34.98 minutes accounting for 62% of patients seen within 30-minute target

![image](https://github.com/user-attachments/assets/55c5a813-63f4-4798-bb3f-e4d4fbf2ee6b)

Satisfaction scores of 5.50 and the lowest (4.2/10) for 31-40 age group
![image](https://github.com/user-attachments/assets/45ad199d-39ce-41ad-9b10-be247cffc61d)

## DAX Measures

![image](https://github.com/user-attachments/assets/b68a657f-ef65-491d-bbcc-f3380460a1b4)                    ![image](https://github.com/user-attachments/assets/2fc492bc-a5a2-4ff3-b6b2-dfd23a09206d)

![image](https://github.com/user-attachments/assets/4061b20b-1725-4b2f-afba-1b2c6f50296b)                    ![image](https://github.com/user-attachments/assets/2cc3318c-03c8-40fd-9057-765828049033)

![image](https://github.com/user-attachments/assets/ef9566e2-52fb-4878-b180-5f4e20b0e9aa)                    ![image](https://github.com/user-attachments/assets/9a1a553b-2ca6-4059-a186-200b92ff4ea3)

## Insights & Findings

#### Critical Issues Identified:
1. Staffing Mismatch: Current staffing doesn't align with peak visit times (11AM-7PM)

2. Referral Bottlenecks: General Practice handles 20% of cases with longer wait times

Demographic Disparities:

1. African American patients wait 12% longer than average

2. Satisfaction scores vary significantly by age group

#### Positive Findings:
1. Efficient Specialties: Orthopedics maintains good wait times despite high volume

2. Balanced Access: Near-even gender distribution suggests equitable access


## Recommendations
##### Operational Improvements & Dynamic Staffing Model:

a. Increase coverage during peak hours (11AM-7PM) by 25%

b. Implement weekend differentials to improve coverage

##### Referral Process Optimization:

a. Expand General Practice capacity by 15%

b. Create fast-track protocols for common Orthopedics cases

##### Patient Experience Enhancements:

a. Implement real-time wait time notifications

b. Target satisfaction improvement programs for 31-40 age group

##### Equity Initiatives:
a. Bias Training: Address racial disparities in wait times

B. Language Services: Expand interpreter availability

## Conclusion

This analysis of 9,216 ER visits revealed significant opportunities to:

a. Improve efficiency through data-driven staffing

b. Enhance patient experience with targeted interventions

c. Reduce disparities in care delivery




