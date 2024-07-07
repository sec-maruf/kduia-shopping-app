# Shopping Cart Application

This is a React-based Shopping Cart application. The project demonstrates the creation and management of a simple shopping cart using React and Redux for state management. 

## Objectives

- Set up a React project.
- Put UI components in place.
- Render the created components and context in `App.js`.
- View the application in the browser.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.
- A GitHub account to fork and clone the repository.

### Installation

1. **Fork the Repository**
   - Fork the project repository from [here](https://github.com/ibm-developer-skills-network/kduia-shopping-app.git).

2. **Clone the Repository**
   - Open a terminal and run the following command:
     ```sh
     git clone <your_repo_name>
     ```

3. **Install Dependencies**
   - Navigate to the project directory:
     ```sh
     cd kduia-shopping-app
     ```
   - Install the required npm packages:
     ```sh
     npm install
     ```

## Project Structure

The project is divided into several components:

- **CartValue**: Displays the total value of the items in the cart.
- **ExpenseItem**: Represents an individual item in the cart.
- **ExpenseList**: Displays a list of `ExpenseItem` components.
- **ItemSelected**: Allows users to add or reduce the quantity of items.
- **Location**: Changes the currency/location for pricing.

## Components Implementation

### AppContext.js

- Set up the initial state for expenses and location.
- Create a reducer to handle state updates based on actions (`ADD_QUANTITY`, `RED_QUANTITY`, `DELETE_ITEM`, `CHG_LOCATION`).
- Provide context to the components.

### CartValue.js

- Use context to get the total expenses and display it with the selected currency.

### ExpenseList.js

- Use context to get the list of expenses and display them using `ExpenseItem` components.

### ExpenseItem.js

- Display individual expense details.
- Handle the deletion of an item from the cart.

### ItemSelected.js

- Allow users to select an item and adjust its quantity.
- Dispatch actions to update the state based on user input.

### Location.js

- Allow users to select and change the location/currency for the cart.

## Running the Application

1. Ensure you are in the project directory:
   ```sh
   cd kduia-shopping-app
