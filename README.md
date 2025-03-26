# UofT Major Resource Map (INF481 Simulation)

This is an interactive web application that simulates a campus resource map for the University of Toronto's St. George campus. The project allows students to select their major and view a customized map that highlights labs, research centers, student clubs, and more, based on their Primary and Secondary Research. All of which are tailored to their field of study. Please note that this project was developed as part of the INF481 final project by Tianen (Evan) Hao, a simulation for academic purposes and it is not connected to actual University systems.

## Overview

The UTSG Major Resource Map allows students to:
- Select one of 15 majors and view a customized interactive map.
- See simulated resources tailored to their major, including Academic Facilities, Research Centres, Student Clubs, Career & Networking, Social & Cultural, and Advising & Support.
- Reserve resources and view them in the "My Reservations" section.
- Simulate a sign-in flow (displaying "Karen" with a dropdown for Settings and Log Out).

## Features

- **Interactive Map:**  
  Powered by Leaflet.js, the map displays campus boundaries (with an adjusted boundary on the right) and resource markers.
  
- **Major-Specific Resources:**  
  Each major shows 10 simulated resources distributed across six predefined categories with data tailored to each field (e.g., Computer Science, Engineering, etc.).
  
- **Reservation System:**  
  Users can simulate reserving resources and see their schedule, along with a "Recommended for Bachelor of Information" section and quick stats.
  
- **User Simulation:**  
  A basic sign-in mechanism simulates logging in. After signing in, the navigation displays "Karen" with a dropdown menu.
  
- **Responsive Design:**  
  Built using HTML, Tailwind CSS, and JavaScript to provide a modern and responsive user experience.

## Technologies Used

- **HTML, CSS, JavaScript**
- **Tailwind CSS** – For styling and responsive design
- **Leaflet.js** – For interactive maps
- **Remix Icon** – For icons

## Live Demo

The project is deployed via GitHub Pages. View the live demo here:  
[https://shadyevan4830.github.io/UofT_MajorResourceMap_INF481/)

## Getting Started

To run the project locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/utsg-major-resource-map.git
