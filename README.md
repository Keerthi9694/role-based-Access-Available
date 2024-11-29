This repository implements a Submission System with Role-Based Access Control (RBAC) to regulate user access and manage submissions effectively. Users are assigned specific roles (e.g., Administrator, Reviewer, Submitter, Viewer), each with distinct permissions, ensuring that they can only perform actions aligned with their role.

Role Management: Assign and manage user roles (Administrator, Reviewer, Submitter, Viewer).
Submission Workflow: Users can create, edit, view, review, or delete submissions based on their role.
Granular Access Control: Permissions are strictly enforced for secure and organized operations.
Status Tracking: Track submission status (e.g., Under Review, Accepted, Rejected).
Audit Logging: Record user activities for accountability.

Roles and Responsibilities
Role	Create Submissions	View Submissions	Edit Submissions	Delete Submissions	Review Submissions
Administrator	Yes	All	All	All	No
Reviewer	No	Assigned	No	No	Yes
Submitter	Yes	Own	Own (before review)	Own (before review)	No
Viewer	No	Public/Assigned	No	No	No

Backend: Node.js, Express.js
Frontend: React.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)
Deployment: Docker, Kubernetes (optional)

Backend: Node.js, Express.js
Frontend: React.js
Database: MongoDB
Authentication: JSON Web Tokens (JWT)
Deployment: Docker, Kubernetes (optional)
