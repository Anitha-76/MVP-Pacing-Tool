MVP: Flexible Lesson Pacing Tool - Documentation

Overview

The Flexible Lesson Pacing Tool is a web-based application designed to empower teachers to customize lesson schedules based on topic complexity, ensuring students receive adequate time to master content.

Theory of Change

“If teachers customize lesson pacing based on complexity of the topic, then students get adequate time to master content, so that their learning outcomes improve.”

This tool tests whether giving teachers the flexibility to adjust pacing by allowing them to allocate more time to complex topics and less time to simpler ones that leads to better learning outcomes

How It Works

Step 1: View the Rigid Schedule
When teachers first access the tool, they see a **rigid schedule** showing the default time allocation for all topics across three subjects:

Mathematics - Unit 1: Numbers (10 hours total)
Science – Unit 1:  Measurements Unit (10 hours total)
Social Science – Unit 1: Human Evolution Unit (10 hours total)

Step 2: Choose the Approach
Teachers have two options:

Option A: Accept the Schedule
Keep the rigid schedule as-is without any changes
Simply log in, select your subject, and accept

Option B: Customize the Schedule
Adjust the time allocated to each topic based on your assessment of topic complexity
The total must still equal 10 hours for your subject

Step 3: Teacher Login
To maintain accountability, each teacher:
Enters their name
Selects their subject (Math, Science, or Social Science)
Important: Each subject can only be assigned to ONE teacher

Step 4: Customization (If chosen)
If a teacher chooses to customize:
1. They see side-by-side comparison of:
   Rigid Schedule: Original time allocation
   Your Flexible Plan: Editable time allocation

2. They can adjust hours for each topic using input fields

3. A visual chart shows the comparison between rigid and flexible schedules

4. A total hours counter ensures the plan adds up to exactly 10 hours

Step 5: Review and Submit
Before submitting, teachers:
1. Review their complete plan in the Summary tab
2. See which topics they increased or decreased time for
3. Confirm their submission

Step 6: Consolidated Reporting
After teachers submit their plans, administrators can:
1. View a consolidated report showing all teacher submissions
2. Compare the rigid schedule vs. each teacher's customized schedule
3. See which topics teachers identified as needing more or less time
4. Export the data for analysis

Key Features

1. Subject-Based Access Control
Each subject (Math, Science, Social Science) can only have ONE teacher
Prevents conflicts and ensures clear ownership
Teachers only see and edit their own subject

2. Visual Feedback
Color-coded cells: Yellow highlight shows customized topics
Charts: Bar graphs compare rigid vs. flexible schedules
Total hours counter: Green when valid (10 hours), red when invalid

3. Data Persistence
All data is saved locally in the browser (localStorage)
Teachers can return to view or modify their submissions
Data persists across browser sessions

4. Validation
Total hours must equal 10 for each subject
Only positive numbers are allowed
Teachers receive warnings if totals don't match

5. Export Capabilities
Individual teachers can export their own plans (JSON format)
Administrators can export all consolidated data
Print-friendly views for both individual and consolidated reports

User Roles

Teachers
Access: Login with name and subject
Permissions: View and edit only their assigned subject
Actions: Accept rigid schedule OR customize topic hours
Goal: Create a pacing plan that gives students adequate time to master content

Administrators / School Leader
Access: View consolidated report after teachers submit
Permissions: See all teacher submissions across all subjects
Actions:
  Compare rigid vs. flexible schedules
  Analyze which topics teachers prioritized
  Export data for further analysis
  Clear all data to start fresh

Testing the Theory of Change

This MVP allows you to test the theory of change by:

Collecting Data: Capturing which topics teachers believe need more or less time
Comparing Approaches: Seeing who accepts rigid schedules vs. who customizes
Analyzing Patterns: Identifying if multiple teachers make similar adjustments
Measuring Impact: (Future) Comparing student outcomes between rigid and flexible pacing
Syllabus correction: (Future) Comparing the teachers’ modification, administrators can revisit the default schedule and change it accordingly

Sample Use Case

Scenario: Three teachers (one per subject) use the tool for Unit 1 planning

1. Math Teacher (X):
   Logs in and selects Mathematics
   Customizes the schedule:
   Increases time for "Rational Numbers" from 2 to 3 hours (more complex)
   Decreases time for "Introduction" from 1 to 0.5 hours (simpler)
   Submits customized plan
   Rationale: (Future) Can provide the rationale to the administrators/school leaders why modification
was needed

2. Science Teacher (Y):
   Logs in and selects Science
   Accepts the rigid schedule as-is
   Rationale: Believes the default schedule is well-balanced

3. Social Science Teacher (Z):
   Logs in and selects Social Science
   Customizes the schedule:
   Increases time for "Human Evolution Theory" from 2 to 3 hours
   Decreases time for "Tools and Weapons" from 2 to 1 hour
   Submits customized plan
   Rationale: (Future explanation): Evolution concepts are abstract and need more discussion time

4. Administrator/School Leader reviews the consolidated report and sees:
   2 out of 3 teachers customized their schedules
   Both customizers added time to conceptually complex topics
   Can create a district wide report for the State to revisit the schedule provided
   This suggests teachers value flexibility for adjusting to topic complexity

Technical Details

1. Technology Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla JS)
Charting: Chart.js library for visualizations
Storage: Browser local Storage for data persistence
Deployment: GitHub Pages (static hosting)

2. Browser Compatibility
Works on all modern browsers (Chrome, Firefox, Safari, Edge – *tested in Chrome, Edge)
Requires JavaScript enabled
Responsive design works on desktop 

3. Future Enhancements
Multi-Unit Support: Extend beyond Unit 1 to Units 2, 3, 4, etc.
Student Outcome Tracking: Link pacing decisions to student performance data
Analytics Dashboard: Visualize trends across multiple classes/years
Mobile App: Native mobile application for on-the-go access
Authentication: Add proper user authentication and server-side storage

Getting Started

For Teachers:
1. Open the tool URL: `https://anitha-76.github.io/MVP-Pacing-Tool/mvp_pacing_tool.html`
2. Review the rigid schedule
3. Click "Accept Schedule" or "Customize Schedule"
4. Enter your name and select your subject
5. (If customizing) Adjust topic hours as needed
6. Review your summary and submit

For Administrators:
1. Wait for teachers to submit their plans
2. Click "View Detailed Consolidated Report"
3. Review all teacher submissions
4. Export data for analysis
5. Use "Clear All Data" to reset for next unit

Support & Questions

For technical issues or questions about using the MVP:
Check that JavaScript is enabled in your browser
Try clearing browser cache if data doesn't appear
Use the "Clear All Data" button to reset if needed
Credits

Tool Name: MVP: Flexible Lesson Pacing Tool
Purpose: Testing Theory of Change for flexible lesson pacing
Target Users: Grade 6 teachers (Math, Science, Social Science)
Development: Ed.M T522 Course Deliverable

