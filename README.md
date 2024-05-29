# Mess Management System

This repository contains the code and resources for a mess management system, built using PHP, SQL, and CSS. The system provides a user-friendly interface for managing mess operations, including supply inventory, feedback, menu planning, and employee details.

The detailed idea of the website is provided in Website_requirements file

## Features

The Mess Management System offers the following functionalities:

**For Mess Admin:**

- **Login & Logout:** Secure authentication for mess administrators.
- **View Supply Details:** View details about available supplies, including quantity, supplier, cost, and arrival date.
- **Update Supply Details:** Update supply information, including adding, removing, or modifying supply items.
- **View Wastage Details:** Track food wastage with details of wasted recipes and quantities.
- **View Employee Details:** Manage employee details, including names, salaries, and designations.
- **Update Employee Details:** Modify employee information, including adding, removing, or changing employee data.
- **View Menu:**  View the complete mess menu for all days, including details like recipe names and meal types (lunch, dinner, breakfast).
- **Update Menu:**  Update the menu by adding, removing, or modifying recipe details.
- **View Daily Menu:**  View the menu for the current day.

**For Students & Faculty:**

- **Login & Logout:** Secure authentication for students and faculty.
- **Give Feedback:**  Submit feedback about the food, infrastructure, and other aspects of the mess experience.
- **View Feedback:** View feedback submitted by other students and faculty.
- **View Menu:** Access the current mess menu.
- **View Daily Menu:** View the menu for the current day.

## Folder Structure

The repository is structured as follows:

- **`website-images`**: Contains screenshots of the website interface showcasing various features.
- **`web`**:  Contains the source code for the website, including PHP files for logic and CSS files for styling. 
- **`database-images`**:  Contains diagrams and screenshots illustrating the database schema and structure.

## Installation

To set up the Mess Management System, follow these steps:

1. **Database Setup:** 
    - Create a new database and import the SQL schema from the `database-images` folder.
    - Configure the database credentials in the PHP configuration files.
2. **Web Server Configuration:** 
    - Set up a web server (e.g., Apache or Nginx) and configure it to run PHP applications.
    - Copy the code from the `code` folder into the web server's document root directory.
3. **Access the Website:** 
    - Open a web browser and navigate to the URL of the website (e.g., `http://localhost/mess-management-system/`).

## Contribution

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.
