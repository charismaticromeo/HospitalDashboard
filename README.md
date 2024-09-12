# HospitalERDashboard
This project is a design of a sample hospital emergency room dashboard that would help a healthcare provider have a quick status of the hospital and also help the management lay a proper plan for effectively running their hospital to ensure efficiency, proper assignment of resources and maximum patient satisfaction.

## Disclaimer
The data used in this project isn't of any real hospital because of confidentiality concerns but an RWFD (Real World Fake Data) from https://data.world a great source for data.

# The Main Dashboard view
### A video recording of the dashboard

https://github.com/user-attachments/assets/ef56de0e-a85a-40ac-a212-69a9d7bf2c11


# Discussion on the various sections of the dashboard

## Section 1: Overall Hospital Insights
![Screenshot_2024-07-21_12-22-33](https://github.com/user-attachments/assets/ad3ea4ab-9fd7-4385-9274-69c2baed04ec)

### 1.1 Overall Summary Section
The Overall Summary section provides a snapshot of hospital’s key performance indicators:
- Average Wait Time: The overall average wait time for patients.
- Satisfaction Rate: The percentage of patients who reported being satisfied with their experience.
- Total Admitted Patients: The total number of patients admitted to the hospital as inpatients.
- Total Discharged Patients: The total number of patients discharged from the hospital.
- Total Patients Attended: The total number of patients who have received care.
- Bed Capacity Tracker: The current bed occupancy rate.

### 1.2 Patients Demographic
This section presents a detailed demographic analysis of the patients:
- Gender: Distribution of patients by gender.
- Age: Age distribution of the patients.
- Race: Racial composition of the patient population.

### 1.3 Overall Satisfaction
![General Patients Satisfaction](https://github.com/user-attachments/assets/9b0b2a8e-b585-46fe-bb23-b76c1a45b71c)
Figure 1: Overall Satisfaction graph
The Overall Satisfaction section includes a bar chart showing patient satisfaction levels:
- Very Satisfied: Percentage of patients who rated their experience as very satisfied.
- Satisfied: Percentage of patients who rated their experience as satisfied.
- Neutral: Percentage of patients who rated their experience as neutral.
- Dissatisfied: Percentage of patients who rated their experience as dissatisfied.
- Very Dissatisfied: Percentage of patients who rated their experience as very dissatisfied.

### 1.4 Overall Wait Time
![overall_avg_timely_waittime](https://github.com/user-attachments/assets/2359d672-373b-4878-b0e8-b1a737825ba6)
Figure 2: Overall wait time graph
This section features a heat map illustrating patient wait times at different times of the day.
- Morning: Average wait times in the morning.
- Afternoon: Average wait times in the afternoon.
- Evening: Average wait times in the evening.
- Daily Breakdown: Wait times across various days of the week.

## Section 2: Departmental Insights
![Screenshot_2024-07-21_12-30-50](https://github.com/user-attachments/assets/4df0ecad-29f0-4532-ad8a-f0073b848635)

### 2.1 Satisfaction Score per Department

#### a. Average Satisfaction Score graph
![Average_Department_Satisfaction](https://github.com/user-attachments/assets/f1b08fad-fa61-4f1a-8e60-2900dc8f68fc)
Figure 3: Average Satisfaction Score graph
This subsection shows the average satisfaction scores for each department, highlighting areas of excellence and those needing improvement.

#### b. Departmental Satisfaction score distribution graph
![Patients_Departmental_Satisfaction](https://github.com/user-attachments/assets/d067c738-bdef-43cf-ad74-3a0b35510ec0)
Figure 4: Departmental Satisfaction score distribution graph
A stacked bar chart is used to display the distribution of satisfaction scores within each department. The scale runs from from very satisfied to very dissatisfied.

### 2.2 Departmental Wait Times

#### a. Wait Time by Time of Day
![daily_department_waittime_visual](https://github.com/user-attachments/assets/80d377b2-28d0-4b21-b037-c6c5aa3b703b)
Figure 5: Departmental wait time per day 
This subsection shows average patient wait times in each department during different times of the day (Morning, Afternoon, Evening, Night).

#### b. Wait Time by Day of the week
![department_waittime_visual](https://github.com/user-attachments/assets/93e28ab1-bdc8-4638-b41a-9774b22ed202)
Figure 6: Departmental daily wait time 
This subsection presents the average wait times for each department across different days of the week.

### 2.3 Departmental Traffic

#### a. Traffic by Time of Day
![Timely_Departmental_Traffic](https://github.com/user-attachments/assets/12f2eb80-2d26-45e4-a082-d6423552cd25)
Figure 7: Departmental traffic in a day
This subsection tracks the patients traffic in each department at different times of the day (Morning, Afternoon, Evening and Night).

#### b. Traffic by Day of the week
![Patients_Traffic_Per_Department](https://github.com/user-attachments/assets/a8951dfa-21f5-4ce9-9423-085843e5c0a3)
Figure 8: Departmental Daily Traffic 
This subsection monitors the patients traffic in each department on various days of the week.

## Section 3: Advantages and Limitation of the Dashboard

### Advantages of the dashboard
1. Improved Decision Making
The dashboard provides real-time data and insights, enabling hospital administrators to make informed decisions that enhance patient care and operational efficiency.
For instance, administrators can use insights from the dashboard to plan for shifts efficiently.
2. Enhanced Patient Satisfaction
By tracking patients satisfaction and wait times, the hospital can identify areas for improvement and implement changes that lead to higher patient satisfaction rates.
3. Efficient Resource Management
The bed capacity tracker and departmental traffic monitor allows for better allocation of resources, ensuring that the hospital operates smoothly and efficiently.
4. Comprehensive Demographic Analysis
Understanding the demographic characteristics of patients help the hospital tailor its services to meet the needs of different patient groups.

### Limitations of the Dashboard
1. Data Accuracy
The accuracy of the dashboard is dependent on the quality and timelines of the data entered into the system. Inaccurate or delayed data can lead to incorrect insights.
2. Limited Scope
While the dashboard provides valuable insights, it may not cover all aspects of hospital operations, Additional tools and data sources may be needed for a complete view.
3. Technical Challenges
Implementing and maintaining the dashboard requires technical expertise and resources, which may be a challenge for some hospitals.
4. User Adoption
The effectiveness of the dashboard depends on the willingness of hospital staff to use it consistently. Training and change management efforts are necessary to ensure widespread adoption.

## Conclusion
The Hospital Dashboard provides critical insights into hospital performance, patient satisfaction, and operational efficiency. By analyzing this data, hospital administrators can identify trends, address areas of concern, and implement strategies to enhance patient care and streamline operations. This report demonstrates the dashboard’s capability to deliver actionable information that can drive continuous improvement in healthcare delivery.
