```markdown
# Power BI Dashboard for Tracking Student Progress and Performance

## Overview
This Power BI dashboard is built for **Global Careers**, a business offering training in Power BI and AWS Cloud. The dashboard helps program managers and trainers track student progress, monitor performance trends, and identify learners at risk. It includes metrics such as attendance, participation, assessments, graduation rates, and certification outcomes.

---

## Features

### Page 1: Overall Performance Metrics
Provides a high-level summary of learner performance for stakeholders.

#### Visuals
- **Bar Charts**:
  - **Graduation Rates**: Percentage of learners who graduated from each cohort.
  - **Certification Rates**: Percentage of learners who achieved certification.
  - **Dropout Rates**: Percentage of learners who dropped out of the program.
  - **Average Attendance**: Average percentage of total class time attended by learners.
  - **Average Participation**: Average engagement score based on daily participation.
  - **Average Assessment Scores**: Average quiz and lab scores for each cohort.

- **Cards (Summary Figures)**:
  - **Total Certifications**: Total number of learners who achieved certification.
  - **Total Learners**: Total number of learners enrolled across all cohorts.
  - **Total Dropouts**: Total number of learners who dropped out.
  - **Total Graduations**: Total number of learners who successfully graduated.

#### Filters
- Cohort: Choose specific cohorts to view their performance.
- Track: Filter by different tracks (Power BI, AWS Cloud).
- Certification Type: Filter by the type of certification.
- Learner Status: Filter by learners who are Certified or Not Certified.

---

### Page 2: Detailed Learner Insights
Provides granular details of individual learner progress for trainers and program managers.

#### Visuals
- **Table**: Displays all learners with their respective tracks and key metrics (attendance, participation, assessment scores).
- **Cards (Summary Figures)**:
  - **Count of Labs**: Total number of labs completed by all learners.
  - **Average Labs Completed**: Average number of labs completed per learner.
  - **Total Hours Spent in Class**: Total number of hours each learner spent attending class sessions.
  - **Average Attendance Rate**: Average attendance rate per learner.
  - **Average Participation Rate**: Average participation rate based on daily engagement.
  - **Average Assessment Scores**: Average score of all quizzes and labs for each learner.

#### Filters
- Cohort: Filter by individual cohorts to monitor specific groups.
- Track: Filter by track (Power BI or AWS Cloud).
- Month: Filter metrics by the month within the 10-week program.
- Week: Filter by specific weeks to analyze performance trends.
- Learner Status: Filter by learners who are Certified or Not Certified.
- Program Status: Filter by program completion status (Ongoing or Completed).

---

## Data Preparation
1. **Class Attendance**:
   - A learner is marked as "attended" if they spend more than **30 minutes** in a Zoom session.
   - Attendance calculations are based on this condition.

2. **Cleaning and Structuring Data**:
   - Ensure daily attendance records, participation records, lab and quiz grades, and learner status data are cleaned before importing into Power BI.
   - Aggregate weekly lab and quiz scores for averages and totals.

3. **Modeling and DAX**:
   - Use DAX to calculate averages, percentages, and other performance metrics dynamically.
   - Define relationships between attendance, participation, labs, quizzes, and learner status tables.

---

## Additional Notes
- Ensure slicers are implemented to provide interactivity and flexibility in exploring data.
- Background design images (`Dashboard.png` and `Overview.png`) are included for visual enhancement.
- Creativity in designing the layout and visuals is encouraged.

---

## Submission Details
- **Due Date**: Monday, 9th December 2024 revised to Tuesday, 10th December 2024.
- **Purpose**: Provide a comprehensive dashboard to track and visualize learner progress and outcomes.
```