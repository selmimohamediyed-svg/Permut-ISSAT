# Permut’ISSAT 🎓

**A student group-exchange platform for ISSAT Sousse.**

🌐 **Live demo:** [permutissat.hatchable.site](https://permutissat.hatchable.site/)

## About the Project

Permut’ISSAT is a web application designed to help students at ISSAT Sousse find reciprocal group exchanges.

Students who want to change groups often have to search through informal networks and social media to find someone willing to make the opposite exchange. Permut’ISSAT centralizes this process and automatically checks for compatible requests.

The project was initiated to solve a practical problem in the student community and turn it into a simple, accessible digital solution.

## ✨ Features

- **Group-exchange requests:** Submit your academic cycle, year, program, current group, desired group(s), and contact details.
- **Automatic reciprocal matching:** Find a student whose requested exchange is compatible with yours.
- **Multiple target groups:** Select up to three desired groups in a single request.
- **Request tracking:** Use a unique tracking code to check whether a request is waiting or matched.
- **Duplicate prevention:** Validate requests and prevent duplicate active exchanges.
- **Contact exchange:** Reveal the matching student's contact details when a reciprocal match is found.
- **Admin dashboard:** View and manage exchange requests, remove requests, and monitor site-visit analytics.
- **Responsive interface:** A modern interface designed to make the process straightforward.

## 🔄 How It Works

1. Select your academic cycle, year, and program.
2. Choose your current group and up to three target groups.
3. Provide a contact method and consent to sharing it if a match is found.
4. The backend searches for a compatible reciprocal request.
5. If a match exists, the application links the two requests and reveals the counterpart's contact details. Otherwise, the request remains pending.
6. Use the tracking code to check the request status later.

### Example

A student in Group 1 wants to move to Group 3.

Another student in Group 3 wants to move to Group 1.

Permut’ISSAT detects the reciprocal exchange and marks both requests as matched.

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | JavaScript API endpoints |
| Database | PostgreSQL |
| Hosting and backend platform | Hatchable |
| Database versioning | SQL migrations |
| Analytics | Custom site-visit tracking and admin dashboard |

## 🧠 Key Technical Concepts

- **Matching logic:** Compare academic cycle, year, program, current group, and desired group(s) to find compatible requests.
- **Data validation:** Validate submitted fields and reject invalid group selections.
- **Database integrity:** Use database constraints and indexes to support duplicate prevention and efficient matching.
- **Request lifecycle:** Track the transition from `waiting` to `matched`.
- **Tracking tokens:** Generate unique codes that allow students to retrieve their request status.
- **Administrative access:** Separate request-management and analytics endpoints from public request-submission endpoints.

## 🤖 Development Approach

Permut’ISSAT was developed using Hatchable and AI-assisted development.

AI tools helped accelerate implementation and iteration. The project was driven by a practical problem, with attention to the user workflow, matching requirements, validation, database structure, and deployment.

The project also provided an opportunity to explore how frontend interfaces, backend endpoints, relational databases, and hosting work together in a deployed application.

## 🚧 Future Improvements

- Add automated tests for reciprocal matching and edge cases.
- Improve rate limiting and abuse prevention.
- Review tracking-token handling and contact-data access controls.
- Improve accessibility and mobile usability.
- Add clearer error handling and operational monitoring.
- Explore a documented deployment workflow and a more portable development setup.

## 👨‍💻 Author

**Mohamed Iyed Selmi**

Student at ISSAT Sousse, interested in software development, problem-solving, and building useful digital products.

## 📌 Project Status

Live and deployed.

Permut’ISSAT is an independent student project and is not an official ISSAT Sousse administrative platform.

