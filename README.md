# club-management-system
A web-based application designed to streamline club activities, manage events, delegate tasks, track sales, and enhance communication between members, leads, and board members.

Features:
-
1. User Roles and Authentication:
Role-based access control with three user types:
Members: Submit proposals, view tasks, and contact leads.
Leads: Assign tasks, manage events, view member contributions, and track sales.
Board Members: Oversee leads, manage events, view sales analytics, and contact other board members.
Secure authentication using hashed passwords with Flask-Login.
2. Task Assignment:
Leads can assign tasks to members, which are visible on their dashboards.
Tasks can include descriptions and are organized by deadlines.
3. Event Management:
Plan, update, and delete events for the club.
View all upcoming and past events in a structured format.
4. Sales Tracking:
Manage product sales and view a real-time pie chart of sales distribution.
Add new products and track sales data for each product.
5. Member Contributions:
Members can submit proposals, and leads can review them.
6. Communication Tools:
Members can contact leads, and board members can communicate with each other.
Email notifications (optional).

Tech Stack:
-
Backend
Python: Core programming language.
Flask: Framework for routing and backend logic.
SQLAlchemy: ORM for database operations.
Frontend
HTML5 and CSS3: Structure and styling.
Bootstrap 5: Responsive design.
JavaScript: Dynamic content updates.
Database
SQLite: Lightweight and easy-to-setup database.
Others
Flask-Mail: Email notifications.
Matplotlib: Sales chart generation.
dotenv: Secure environment variable management.

Usage:
-
1. Create Users
Sign up users with different roles (Member, Lead, Board).
Use the lead or board dashboards for managing tasks, events, and sales.
2. Assign Tasks
Leads can assign tasks to members, which will appear on the members’ dashboards.
3. Manage Events
Add, update, and view club events.
4. Track Sales
View product sales analytics and add new products.
5. Monitor Member Contributions
Review proposals submitted by members.

Screenshots:
-
1. Member Dashboard

2. Lead Dashboard

3. Task Assignment

4. Sales Chart

Testing:
-
1. Functional Testing
Used Selenium to automate testing of key user flows (e.g., task assignment, sales management).
2. Performance Testing
Simulated 50 concurrent logins using JMeter to test server resilience.
Contributing
Fork the repository.
Create a new branch: git checkout -b feature-name.
Commit your changes: git commit -m "Add a new feature".
Push to the branch: git push origin feature-name.
Submit a pull request.

Acknowledgments:
-
Flask Documentation for backend inspiration.
Bootstrap for frontend styling.
Selenium and JMeter for testing frameworks.
