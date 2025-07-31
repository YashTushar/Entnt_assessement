# ENTNT Assignment


<img width="1539" height="862" alt="image" src="https://github.com/user-attachments/assets/a68e7bd9-1639-4376-a501-29e5b7befbb0" />




This is a React-based web application built to assist businesses in efficiently managing and monitoring their interactions with different companies. It offers features such as logging communication records, scheduling follow-ups, maintaining a detailed company database, and sending notifications for overdue communications.

## Technology Stack
* React.js
* React Router
* Context API for state management
* Lucide React for icons
* CSS for styling
* used react-big-calendar for calendar view

## Prerequisites
* Node.js (v16.0.0 or later)

* npm (v8.0.0 or later)

* A modern web browser

## Setup and Installation

Use the package manager npm to install Communication Tracker.

## 1. Clone the Repository

bash
git clone https://github.com/YashTushar/Entnt_assessement


## 2. Install Dependencies

bash
npm install

## 3. Run the Application
bash
# Development Mode
npm start

# Production Build
npm run build


## Deployment

*Netlify*

To deploy this project run
bash
npm run build


Then Upload build file to Netlify

## Application Functionality

*Key Features*

* *Dashboard Views*
    * Overview of communication status for each company
    * Users can select a specific company or multi-select multiple companies to log communication and 
    * When hovering over a completed communication, a tooltip will display the notes or comments recorded for that communication.

* *Admin Module*
    * Add new companies
    * Manage communication methods


* *Calendar View*
    * View Past Communications
    * View and manage Upcoming Communications

   
* *Company List*
    * View All the companies
    * Edit and delete companies


* *Notification*
    * View all overdue and due communications 


## Known Limitations
* No built-in authentication system
* Relies on client-side state management
* No persistent data storage (requires backend integration)



## Future Roadmap
* Implement user authentication
* Add backend database integration
* Develop reporting and analytics features


## License
This project has been build by Yash Singhal from IIIT Sonepat.

## Contact
YASH SINGHAL - yash.singhal1112@gmail.com

Deployed Project Link: https://incomparable-granita-2c186c.netlify.app/
