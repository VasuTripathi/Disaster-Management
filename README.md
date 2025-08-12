**Calamity Compass - Disaster Management & Volunteer Coordination Platform**

Project Link :- https://disaster-management-one.vercel.app/

Overview

The Disaster Management & Volunteer Coordination Platform is a web-based application designed to support efficient disaster response through crowdsourcing. It bridges the gap between affected individuals, volunteers, and coordinators, enabling faster rescue, resource allocation, and real-time communication during emergencies. The platform was conceptualized to ensure that aid reaches those in need in the shortest possible time while optimizing available resources.

Key Features

Help Request Submission

Affected individuals can raise location-based help requests during emergencies.

The form captures details such as name, contact information, type of emergency, and location.

Real-Time Location Tracking

Location data is shared with rescue teams for quick response.

Google Maps API is integrated for accurate location visualization.

Volunteer Registration and Coordination

Volunteers can register with their skillsets and availability.

Coordinators can assign volunteers to specific rescue operations.

Disaster Mapping

Dynamic disaster maps showing affected zones, active rescue missions, and relief supply locations.

Safety Alerts and Notifications

Real-time broadcasting of safety alerts to affected areas.

Relief Material Tracking

Tracks supply distribution and ensures resources are directed where needed most.

Help Request Status Tracking

Victims can track the progress of their requests (Pending, In Progress, Resolved).

Technology Stack

Frontend: HTML, CSS, JavaScript, React (or other chosen framework)

Backend: Java (Servlets/Spring Boot) or Node.js

Database: MySQL/PostgreSQL

APIs: Google Maps API for disaster mapping and location tracking

Hosting: Options include Vercel, Netlify, Render, or AWS

Project Structure

Disaster-Management/
│
├── frontend/        # UI components, pages, styling files
├── backend/         # API endpoints, services, controllers
├── database/        # SQL scripts, database schema
├── assets/          # Static files, icons, and images
└── README.md        # Project documentation

Installation & Setup

Backend Setup

Install dependencies:

npm install

or (Java backend) import into an IDE and configure Maven/Gradle.

Create a .env file with database credentials and API keys.

Start the backend:

npm start

or (Java)

mvn spring-boot:run

Frontend Setup

cd frontend
npm install
npm start

Database Setup

Create a new database in MySQL/PostgreSQL.

Import the SQL schema from /database/schema.sql.

Screenshots

Below are some screenshots of the application:

Home Page


Help Request Form


Volunteer Registration Page


Disaster Map View


Relief Tracking Dashboard


Use Cases

Government disaster management agencies

NGOs and community rescue organizations

Volunteer networks

Individuals in disaster-prone regions

Future Enhancements

AI-powered disaster prediction and automated alerts.

Multi-language support for accessibility in diverse regions.

Offline capabilities using SMS-based systems.

Role-based access control for admin, volunteers, and victims.


Authors

Your Name – Full Stack Developer

Contributions from Team Members (if applicable)

