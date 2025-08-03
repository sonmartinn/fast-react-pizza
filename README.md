Fast React Pizza - An Online Pizza Ordering Application
📝 Introduction
This is a practice web application built with React, which simulates an online pizza ordering website with basic functionalities. The project focuses on applying core concepts of modern React, from state management and routing to handling asynchronous tasks.

The goal of this project is to build an intuitive, smooth, and performance-optimized user interface (UI) that provides the best user experience.

🚀 Technologies Used
Frontend: React

State Management: Redux Toolkit & React Redux

Routing: React Router

Styling: Tailwind CSS

Asynchronous Tasks: Redux Thunk with createAsyncThunk from Redux Toolkit

Build Tool: Vite

✨ Key Features
Diverse Pizza Menu: Displays a list of available pizzas with detailed information about ingredients and prices.

--Shopping Cart:

+ Add, increase, or decrease product quantities.

+ Remove products from the cart.

+ Automatic total price calculation.

--Order Placement:

+ Simple and easy-to-use form for entering delivery information.

+ Handles order logic and submits data to a "server" (mocked or real API).

-- Order Tracking: Allows users to view the status and details of their placed orders.

-- Geolocation Integration: (If applicable) Uses the navigator.geolocation API to automatically populate the delivery address.

-- Modern State Management: Utilizes Redux Toolkit to effectively manage complex application state, avoiding "prop drilling."

🛠️ Installation and Running the Project
1. Prerequisites
Ensure you have Node.js and npm installed on your machine.

2. Installation
Open your terminal, clone the repository, and install the dependencies:

```bash
# Clone the repository
git clone [your_repository_path]

# Navigate into the project directory
cd fast-react-pizza-web
# Install dependencies
npm install
```
3. Running the application
Run the project in development mode:
`npm run dev`
The application will launch at http://localhost:5173 (or a different port if 5173 is in use).

4. Build and Deploy
To create a production-ready build:
`npm run build`      
The output will be in the dist directory.

🤝 Contributions
Contributions are always welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

📄 License
This project is licensed under the MIT License.
