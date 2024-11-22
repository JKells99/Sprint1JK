# Restaurant Menu Generator - Template Repository

This repository is a template for a restaurant menu generation project. Use this project as a starting point to build an Express-based web application that generates random restaurant menus based on different cuisines.

## How to Use This Template

1. **Create Your Own Repository**:
   - Click the "Use this template" button at the top of the repository page to create your own copy of the repository.

2. **Clone Your Repository**:
   - After creating your repository, clone it to your local machine:
     ```bash
     git clone https://github.com/yourusername/your-repository-name.git
     cd your-repository-name
     ```

3. **Install Dependencies**:
   - Install the necessary npm packages by running:
     ```bash
     npm install
     ```

4. **Run the Application**:
   - Start the development server:
     ```bash
     npm start
     ```
   - The application will run locally at `http://localhost:3000`.

## Project Overview

This project generates random restaurant menus for various cuisines. Your task is to complete the functionality and write unit tests for the required features.

### Key Features:

- Display a list of restaurant names for users to choose from.
- Generate a random cuisine type for a selected restaurant.
- Generate a random menu (5 to 10 items) from the selected cuisine.
- Display the generated restaurant menu in the browser.

## Tasks to Complete

1. **Add Functions to `restaurantData.js`**:
   - You will need to complete functions to:
     - Generate a random menu item from a given cuisine.
     - Select a random cuisine type.
     - Generate a menu (5 to 10 items) from the selected cuisine.
     - Generate a full restaurant report with the selected cuisine and menu.

2. **Write Unit Tests**:
   - You are required to write unit tests to verify:
     - A random menu item can be generated with the correct attributes.
     - A random cuisine type can be selected.
     - A full menu for a restaurant can be generated.

3. **Add missing routes and templates**:
   - Refer to the assignment page for full instructions
   - The home page still needs to be finished
   - All other pages need templates and their routes defined.

## Running Unit Tests

To run your unit tests, use the following command:

```bash
npm test
```

Ensure your tests are comprehensive and verify the core functionality of the application.

## Next Steps

- Build out the logic inside the routes.
- Refine the UI by improving the EJS templates and CSS styles.
- Test your project thoroughly before submission.