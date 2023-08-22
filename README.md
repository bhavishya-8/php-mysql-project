# Goal Tracker Web Application

   - [OpenAI Python](https://github.com/openai/openai-python)

This repository contains a simple web application that allows users to track their daily goals. Users can add new goals to a to-do list, mark goals as completed, and remove completed goals from the list.

## Features

- Add new goals with categories, descriptions, and due dates.
- Mark goals as completed.
- Remove completed goals from the list.
- Separate display of incomplete and completed goals.

## How to Use

1. Clone or download this repository to your local machine.

2. Ensure you have a web server and a database setup. You'll need to create a MySQL database and update the `connect.php` file with your database details.

3. Open `index.php` in a web browser to access the goal tracking interface.

4. To add a new goal, fill in the goal details and click the "Submit Goal" button.

5. In the interface, you'll see two sections: "Incomplete Goals" and "Complete Goals." Incomplete goals can be marked as completed using the "Complete" button. Completed goals can be removed using the "Delete" button.

## Requirements

- A web server (e.g., Apache, Nginx) with PHP support.
- A MySQL database.

## Important Notes

- This application is intended as a basic example and may not have full security measures implemented. It's recommended to implement proper security practices before deploying to production.
- Make sure to update the database connection settings in the `connect.php` file to match your own database setup.
- Be cautious when deploying web applications that interact with databases and user inputs.

![Running GIF](  https://raw.githubusercontent.com/trinib/trinib/82213791fa9ff58d3ca768ddd6de2489ec23ffca/images/footer.svg)
