# PowerBI-Portfolio-Project2
Maintenance Operations &amp; Performance Dashboard for Tengiz Drilling Rigs (2024)


Project Documentation
Project name: Maintenance Operations Performance Dashboard
Tool: Power BI
Data: Synthetic dataset (Work Orders, Costs, Priorities, Delays, Departments, 2024)
Author: Jazz Johnston
Industry: Oil & Gas — Facilities Maintenance & Reliability
Context: The dataset simulates maintenance operations performed by the Facilities Maintenance department supporting multiple drilling rigs at the Tengiz oilfield.
FM is responsible for keeping critical rig equipment operational—pumps, compressors, electrical systems, safety equipment, mechanical assemblies, and auxiliary infrastructure.
The data includes preventive & corrective maintenance, delays, work order priorities, costs, and departmental workload distribution across FM operations on multiple rigs.

1. Report Goal
The purpose of this report is to provide a complete operational, performance, and risk overview of the Facilities Maintenance (FM) function supporting multiple drilling rigs at the Tengiz field.
The dashboards consolidate all key maintenance processes — Preventive Maintenance (PM), Corrective Maintenance (CM), Emergency Maintenance (EM), Mechanical Integrity (MI), and Project-related work — into a single analytical environment.
This report enables FM supervisors, planners, and reliability engineers to:
• monitor maintenance workload across all rigs
(requests volume, departmental load, priority distribution)
• evaluate execution discipline and delays
(on-time completion, overdue performance, trend analysis)
• assess maintenance cost patterns and financial impact
(monthly PM cost, labor vs parts cost, cost by priority)
• identify systemic root causes and operational bottlenecks
(failure code breakdown, high-impact delayed work orders)
• understand operational risk related to PM disruptions
(normalised risk score influenced by delays, priority severity, backlog pressure)
• improve planning, scheduling, and reliability strategies
through data-driven insights across the full maintenance cycle.
Together, the three dashboards — Overview, Workload & Requests Analysis, and Priority & Performance Analysis — provide a structured, end-to-end view of maintenance effectiveness, operational stability, and equipment care performance across Tengiz drilling rigs.
________________________________________
2. Data Sources
Synthetic maintenance dataset representing:
Work Orders (PM, CM, EM, MI, Project)
Priority Levels (Low, Medium, High, Urgent)
Status (Completed, Delayed, Open, In Progress, Cancelled)
Planned vs Actual Start/Finish Dates
Labor & Parts Costs
Downtime Minutes
Requests by Department (Operations, Maintenance Planner, Safety)
Failure Codes, Descriptions
Monthly maintenance activity patterns (Jan–Dec 2024)
________________________________________
3. Key Metrics
Operational Metrics
Total Work Orders (WO) – total maintenance activity across all rigs.
High & Urgent Priority WO – workload requiring immediate attention.
Delayed WO & Delayed % – indicator of operational bottlenecks.
On-Time WO Completion (%) – schedule adherence and efficiency.
Open & In-Progress WO – backlog status.
Cost Metrics
Total Maintenance Cost – overall PM/CM financial footprint.
Avg Cost per Work Order – cost efficiency metric for FM.
Labor vs Parts Cost – cost drivers and spending structure.
Monthly Maintenance Cost Trend – seasonal workload & budget impact.
Risk Metrics
PM Risk Disruptions Score (0–1) – composite score based on delays, priority severity, and backlog pressure.
Overdue % by Priority – highlights risk concentration in critical tasks.
Failure Cause Breakdown – identifies root-cause patterns behind FM issues.
________________________________________
4. Key Insights 
•	High- & Urgent-priority work orders drive most delays.
Reason: These tasks need specialized parts/technicians, and reactive failures disrupt PM schedules.
•	On-time completion is unstable (27%–58% across the year).
Reason: Workload peaks, unexpected corrective work, and manpower limits reduce schedule adherence.
•	Operations and Maintenance Planner generate most requests.
Reason: Operations report urgent issues; Planning triggers regular PM for multiple rigs.
•	Maintenance cost peaks in mid-year (up to $33K) and drops in October.
Reason: Seasonal PM cycles overlap with high drilling activity; October reflects lower load or completed PM cycles.
•	Failure causes cluster in contamination, corrosion, and fatigue.
Reason: Harsh rig conditions (dust, moisture, vibration) accelerate equipment degradation.
•	PM Risk Disruptions Score is elevated due to overdue critical work.
Reason: Accumulated delayed High/Urgent WOs increase operational risk and reactive maintenance.
•	Usage-based PM shows higher delay rates than time-based PM.
Reason: Runtime varies with drilling intensity, making those tasks harder to schedule on time.
________________________________________
5. Tools and Methods
Power BI Desktop
DAX Formulas (delay and overdue calculations, cost measures, dynamic priority metrics, normalised risk score)
Visualizations: KPI cards, line trends, matrix heatmaps, treemap cost breakdown, risk gauge

________________________________________
6. Screenshots and page descriptions 
Overview: High-level summary of equipment, PM workload, completion rates, and maintenance cost.

 <img width="975" height="546" alt="image" src="https://github.com/user-attachments/assets/a643917e-27aa-4b4d-9d2b-ff53d0cda6f2" />

Workload & Requests: Department workload, request patterns, delays, and monthly activity trends.

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/f43e1168-3395-46a6-9bb1-479086123d3a" />
 
Priority & Performance: Performance by priority, delays, cost impact, failure causes, and PM disruption risk.
 
<img width="975" height="542" alt="image" src="https://github.com/user-attachments/assets/11ff1ca9-e3a3-40ea-9fe1-f96038482189" />

________________________________________
7. Conclusion & Recommendations

Maintenance performance across the rigs shows inconsistent on-time completion, high delay concentration in High/Urgent priorities, and seasonal cost spikes driven by PM cycles and reactive failures. Failure codes repeatedly point to contamination, corrosion, and mechanical fatigue—conditions typical for rig environments. Risk remains elevated due to overdue critical work orders and unstable workload distribution between departments.
Recommendations
1.	Stabilize PM scheduling by leveling monthly workload and reducing overlap between PM cycles and high-activity drilling periods.
2.	Prioritize overdue High/Urgent WOs to reduce operational risk and dependency on reactive maintenance.
3.	Strengthen root-cause mitigation for contamination, corrosion, and fatigue through improved sealing, lubrication, inspections, and environmental controls.
4.	Improve spare parts availability for critical equipment to shorten delays driven by long lead times.
5.	Enhance coordination between Operations and Maintenance Planning to reduce last-minute urgent requests and improve resource planning.
6.	Monitor usage-based PM more closely, adjusting triggers based on real drilling intensity to avoid unexpected workload spikes.

Files Included: 
Preventive Maintenance Dashboard.pbix
Project Documentation PM.pdf

