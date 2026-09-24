# Power BI Row-Level Security (RLS) Using Sales

## Project Overview
This project was completed as part of my IFEXA Academy data analytics training. Using a retail sales dataset,I built a Power BI report and implemented both static and dynamic RLS to ensure users can only view the data they are authorized to access.
## Problem Statement
The business needs to ensure that sales representatives and managers can access only the sales information relevant to their assigned states, while management maintains a centralized Power BI report.
## Project Objectives
- Build an interactive sales dashboard in Power BI.
- Implement static RLS for state-based access.
- Implement dynamic RLS using USERPRINCIPALNAME().
- Create a user-security mapping between users and sales representatives.
- Test RLS using different user accounts.
- Demonstrate access for a manager responsible for multiple states.
- Ensure sensitive sales information is restricted to authorized users.

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Microsoft Excel
  ## Dataset
The dataset contains retail sales information including:
- Order ID
- Sales Representative
- State
- City
- Sales Amount
- User email and state assignments
  ## RLS Implementation
The project covers:
- Static RLS — restricting users to a specific state.
- Dynamic RLS — using the logged-in user's email to determine access.
- User Testing — testing different users through Power BI's View As feature.
- Multi-State Access — demonstrating a manager with access to more than one state.
  ## Key Insights
- RLS allows different users to work with the same Power BI report while seeing different data based on their permissions.
- Static RLS is useful when access requirements are fixed for specific roles or locations.
- Dynamic RLS provides a more scalable approach because access can be determined automatically from the user's email.
- The relationship between the security table and the Sales table is critical for ensuring that RLS filters the report correctly.
- The exercise demonstrated that a single report can serve multiple users without creating separate dashboards for each user.
- The multi-state manager scenario shows how one user can be assigned access to more than one state through a security mapping table.
  ## Business Value
Implementing RLS helps the business:
- Protect sensitive sales information.
- Reduce unauthorized access.
- Maintain one centralized reporting system.
- Simplify report management.
- Give managers access to the information relevant to their responsibilities.
  ## Conclusion
This project demonstrated how Power BI Row-Level Security can be used to build a secure and user-specific reporting environment. By combining data modeling, static RLS, dynamic RLS, and user testing, the report allows different users to access the information relevant to their roles while maintaining a single centralized dashboard.
The project strengthened my understanding of Power BI security, data modeling, DAX, relationships, and controlled data access.
