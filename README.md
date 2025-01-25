# Helvora-Survey-Analysis
This report provides an in-depth analysis of survey data collected from a personal group on an online medical healthcare platform, Helvora. The data focused on demographic insights, challenges in healthcare accessibility, preferences for telemedicine

Demographic Dashboard                                                                 |  App Fearures Dashboard
:------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------:
![](https://github.com/Olowookere-Abidemi/Helvora-Survey-Analysis/blob/main/Demographic%20Dashboard.png) | ![](https://github.com/Olowookere-Abidemi/Helvora-Survey-Analysis/blob/main/App%20fatures%20Dashboard.png)


## Introduction
This report provides an in-depth analysis of survey data collected from a personal group on an online medical healthcare platform, **Helvora**. The data focused on demographic insights, challenges in healthcare accessibility, preferences for telemedicine, and recommendations for improving healthcare experiences. 

The data underwent a meticulous cleaning and restructuring process, ensuring clarity and usability, as outlined in the cleaning report. The insights and recommendations presented aim to enhance Helvora’s platform and user experience.

---

## 1. Data Cleaning Process

### Overview of the Dataset
The dataset comprised survey responses related to:
- **Demographics**
- **Healthcare challenges**
- **App feature preferences**
- **Open-ended feedback**

However, it included inconsistencies and irrelevant information that required cleaning to enable effective analysis.

### Cleaning Steps
1. **Removal of Irrelevant Columns:**
   - Removed “Date” and “State” columns as they were irrelevant to the analysis.
2. **Deleting Initial Rows:**
   - Removed the first seven rows, which contained form adjustment details, for proper formatting.
3. **Renaming Columns:**
   - Renamed column headers for improved clarity and consistency.
4. **Splitting Combined Responses:**
   - Used the “Text-to-Columns” feature to split responses in columns like “Features” and “Improvements” for detailed analysis.
5. **Categorizing Open-Ended Questions:**
   - Grouped responses to open-ended questions into thematic categories (e.g., “Affordability,” “Feedback and Ratings”) for easier interpretation.
6. **Adding Serial Numbers:**
   - Added a new column to assign serial numbers to each row for easier referencing.
7. **Creation of Additional Sheets:**
   - **Features and Improvements:** Separate sheets for split responses.
   - **Categories:** Thematic groupings for open-ended questions.
   - **Survey Data:** The cleaned dataset with irrelevant columns and rows removed.

### Integration with Power BI
- Imported the cleaned dataset into Power BI for visualization.
- Unpivoted columns like “Features” and “Improvements” to enable better analysis of responses.

### Outcome
The data cleaning process resulted in a well-structured and consistent dataset, laying a solid foundation for meaningful insights and recommendations.

---

## 2. Demographic Analysis

### Respondents by Gender
- **Male:** 40 respondents (56%)
- **Female:** 32 respondents (44%)

### Respondents by Age Range
- **Top Age Group:** 25–39 (51 respondents, 71%)
- **Other Groups:**
  - 18–24 (22%)
  - 40–59 (17%)
  - 60+ (10%)

### Respondents by Location
- **Urban:** 55 respondents (76%)
- **Suburban:** 10 respondents
- **Rural:** 7 respondents

### Recommendations
1. Focus on marketing healthcare solutions to urban residents and the 25–39 age group.
2. Address accessibility challenges for respondents in rural areas.

---

## 3. Healthcare Accessibility & Challenges

### Accessibility Challenges
- **Top Challenges:**
  - Long wait times: 31 respondents
  - High costs: 18 respondents
  - Distance to healthcare facilities: 11 respondents

### Ease of Access
- **Somewhat easy:** 29 respondents
- **Neutral:** 19 respondents
- **Very difficult:** 1 respondent

### Recommendations
1. Optimize scheduling and facility operations to reduce wait times.
2. Introduce telemedicine solutions to address distance barriers.
3. Provide affordable care packages or financial assistance options.

---

## 4. Telemedicine Interest

### Interest in Telemedicine
- **Yes:** 53 respondents (74%)
- **Maybe:** 15 respondents (21%)
- **No:** 4 respondents (5%)

### Insight
A large majority (95%) of respondents are either fully or partially open to telemedicine.

### Recommendations
1. Launch a telemedicine service and promote its benefits through educational campaigns.
2. Provide incentives such as free first-time consultations to encourage adoption.

---

## 5. Preferred App Features

### Top Features for a Healthcare App
- **Virtual consultations:** 51 votes
- **Appointment scheduling:** 36 votes
- **Educational materials:** 24 votes
- **Emergency response tools:** 21 votes
- **Medication reminders:** 17 votes

### Open-Ended Suggestions
- **Categories:**
  - Others: 28 votes
  - Hospitality: 10 votes
  - Affordability: 5 votes
  - Feedback mechanisms: 5 votes

### Recommendations
1. Prioritize virtual consultations and appointment scheduling.
2. Include user-friendly features such as medication reminders and emergency response tools.
3. Address affordability and hospitality concerns to enhance satisfaction.

---

## 6. Healthcare Experience Improvements

### Key Improvements Suggested
- **Shorter wait times:** 51 respondents
- **More digital health tools:** 29 respondents
- **Better communication with doctors:** 24 respondents
- **Improved insurance coverage:** 16 respondents

### Recommendations
1. Implement workflow optimizations to reduce wait times.
2. Enhance doctor-patient communication through features like instant messaging or feedback tools.
3. Expand insurance partnerships to improve coverage options.

---

## 7. Insurance Access

### Insurance Status
- **Yes:** 36 respondents (50%)
- **No:** 36 respondents (50%)

### Recommendations
1. Promote insurance plans to the uninsured respondents.
2. Collaborate with insurers to provide affordable and flexible coverage options.

---

## Conclusion
The Helvora survey has highlighted critical areas for improvement in healthcare accessibility and the features users value most in a digital healthcare platform. 

### Key Takeaways:
- High interest in telemedicine and virtual consultations.
- A strong demand for shorter wait times and better insurance options.
- Preference for user-friendly app features like appointment scheduling and medication reminders.

By addressing these findings and implementing the recommended actions, Helvora can position itself as a leading solution in digital healthcare, meeting user needs effectively while enhancing overall healthcare experiences.

