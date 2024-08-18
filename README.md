# Random Activity Generator

This is a simple web application that displays a random activity to the user when they visit the home page. The user can also filter activities based on type and number of participants.

## Features

- **Home Page:** Displays a random activity fetched from an API when the user visits the page.
- **Filter Activities:** Allows users to filter activities by type and number of participants using a form.
- **Error Handling:** If no activities match the user's criteria, a user-friendly error message is displayed.

## Technologies Used

- **Express.js:** For setting up the server.
- **Axios:** For making HTTP requests to the external API.
- **EJS:** For rendering HTML templates.
- **Body-Parser:** To parse incoming request bodies in a middleware before your handlers.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/random-activity-generator.git

2. Navigate to the project directory:  cd random-activity-generator
   
3. Install the dependencies: npm I,
npm i nodemon,
npm i axios,
npm i bodyParser

4.Start the server: nodemon index.js


# Random Activity Generator

This project is a simple web application that displays a random activity to the user when they visit the home page. The user can also filter activities based on type and number of participants.

## Usage

### Home Page
When you visit the home page, it automatically displays a random activity fetched from the Bored API.

### Filtering Activities
Use the form on the page to filter activities by type (e.g., education, recreational) and number of participants. Submit the form, and the app will display a random activity that matches the selected criteria.

### Error Handling
If no activities match the selected criteria, the app will show an error message saying, "No activities that match your criteria."

## Project Structure

- **`index.ejs`:** The main view template for rendering the home page.
- **`public/`:** Contains static assets such as CSS and JavaScript files.
- **`app.js`:** The main server file that contains the routing logic and API requests.

## API Endpoints

- **GET `/`:** Fetches a random activity and displays it on the home page.
- **POST `/`:** Fetches activities based on the selected filters and displays a random one.

## External API

This application uses the [Bored API](https://www.boredapi.com/) to fetch random activities and filter them based on user input.

This application uses the Bored API to fetch random activities and filter them based on user input.


