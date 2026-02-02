# HR-Attrition-Dashboard

HR Talent & Retention Analytics Dashboard 📊

Project Overview:
An interactive Excel Power Pivot dashboard analyzing 1,470 employees to identify who is leaving and why. This project highlights key drivers of attrition across departments, roles, and performance levels, providing actionable insights for HR leaders. Specifically focusing on the intersection of department, performance, and workplace environment.

📄 Executive Summary

This project transforms HR data into decision-ready insights on employee turnover. Key findings reveal that environment satisfaction and department pressures are stronger predictors of attrition than performance alone, while high-performing employees sometimes leave at rates higher than average performers.

Objectives:

Identify high-risk roles and departments

Understand the influence of workplace satisfaction and performance on attrition

Provide actionable insights for HR retention strategies

🚀 Key Insights

Sales Flashpoint: The Sales department shows the highest turnover at 21.0%, indicating a high-risk area for employee loss.

Performance Paradox: Top performers (Rating 4) leave at 16.4%, slightly above average performers (16.1%), signaling that key talent may be more mobile.

Environmental Impact: Employees with low environment satisfaction (Rating 1) have a 25.4% attrition rate, nearly double that of highly satisfied employees (13.5%).

🛠️ Technical Stack

Data Cleaning: Removed duplicates and converted attrition into binary logic (1/0) for accurate calculations

Data Modeling: Built a relationship-based model in Power Pivot

DAX Measures:
Total Employees = COUNTROWS('HR_Data')
Attrition Rate = DIVIDE(SUM('HR_Data'[Attrition_Binary]), [Total Employees], 0)
Visualization: Interactive dashboard with synchronized Slicers (Gender, Job Role) across 5+ charts

Design: Conditional formatting for intuitive identification of high-risk groups

💡 Business Takeaways
Pinpoints who is leaving by department, role, and performance tier

Shows why employees leave, highlighting the influence of environment satisfaction

Provides a data-driven foundation for HR to implement targeted retention strategies
