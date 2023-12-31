## Summary for the Angular project:
## Project Name: Restaurant Management System (Admin Side)

## Utsav Patel 



The Home component is an Angular component that serves as the landing page for the Restaurant Management System application. This component displays a welcoming title and provides options for user interaction, including signing up and logging in.

**Key Features:**
1. **Title and Introduction:**
   - The page starts with a welcoming title: "Welcome to the Restaurant Management System!"
   - This title effectively communicates the purpose of the application and creates a welcoming atmosphere
2. **User Interaction:**
   - The Home component offers user interaction sections where users can choose to sign up or log in.
3. **Sign Up Option:**
   - A card titled "Get Started!" encourages users to take action.
   - The "Sign Up Here!" subtitle motivates users to create an account.
   - A link labeled "Sign Up" redirects users to the sign-up page when clicked.
   - Users can seamlessly navigate to the sign-up section for account creation.

**Technologies:**
- The Home component is developed using Angular, utilizing its framework and routing capabilities.

**Usage:**
- The Home component serves as the entry point for users accessing the Restaurant Management System application.
- It offers clear options for users to sign up or log in, guiding them toward their desired interactions and contributing to a user-friendly experience.





## Abhi Priyadarshi 




## Key Components and Features:
The LoginPage component is a key component within the Angular application, designed to handle user authentication processes. Users can log in using their credentials, and upon successful login, they receive a welcome message and can choose to log out.

**Authentication Context Creation:**
- The code establishes an authentication context, AuthContext, using Angular's dependency injection mechanism.
- AuthContext encapsulates authentication-related state and methods.

**Login Page (LoginPage Component):**
- The LoginPage component manages the login process, utilizing Angular's reactive forms for user input.
- It uses reactive forms to manage input fields (username and password), isLoggedIn state, and error handling.
- Upon successful login, the user's token is stored, and the isLoggedIn state is updated.
- In the case of login failure, appropriate error messages are displayed.

**Authentication Status Display (AuthStatus Component):**
- AuthStatus component displays a personalized welcome message to authenticated users.
- It reads the authentication status from the authentication context, providing an engaging user experience.

**Login Form (LoginForm Component):**
- The LoginForm component renders the login form, utilizing Angular's reactive forms.
- It provides input fields for username and password, along with a submission button.
- Users are guided through the process of entering their credentials, and the form manages login attempts and error display.
**Logout Button (LogoutButton Component):**
- The LogoutButton component renders a button allowing users to log out.
- Upon clicking the button, the user's token is removed, and the isLoggedIn state is reset





## Akshay Gajera





The provided code showcases an Angular component named MenuComponent, serving as a dynamic menu management system. This component empowers users to perform actions like viewing, editing, adding, and deleting menu items. Angular's framework, along with RxJS and HttpClientModule, are used for handling asynchronous operations and API requests.

**Key Features:**

**Fetching Menu Data:**
- The MenuComponent employs Angular's lifecycle hook to fetch menu data from a RESTful API during component initialization.
- Fetched menu items are stored within the menuItems property.

**Menu Item Management:**
- Users can add new menu items using an add-menu form.
- Upon submission, the new menu item is added to the menuItems array and displayed in the menu list.
- Editing and updating existing menu items is facilitated by an edit form.
- Users can delete menu items, which removes them from the menuItems array.

**Add to Cart Functionality:**
- A "Add to Cart" button enables users to add menu items to their cart.
- When clicked, this button triggers the addition of the selected menu item to the cart.

**User Feedback:**
- A success message, "Item added successfully!", momentarily appears after a new item is added.





## Dhruvi Rajput





The Orders component in Angular handles customer orders within the application. Users can customize orders by adjusting quantities and either confirming or canceling orders. The component utilizes Angular's reactive forms for input handling and communicates with an API using HttpClientModule.

**Key Features:**

**Order Initialization:**
- The component initializes order details using query parameters extracted from the URL, including name, price, and description of the selected menu item.
- The `initialState` object establishes initial quantity and saved status for the order.

**Quantity Management:**
- Users can increment or decrement the order quantity using dedicated buttons.
- A quantity input field allows users to directly input a specific quantity.

**Order Confirmation:**
- Users confirm orders by clicking the "Confirm Order" button.
- An HTTP POST request sends order details to an API endpoint for processing.
- A success message is displayed upon successful confirmation.

**Order Cancellation:**
- The "Cancel Order" button allows users to cancel their orders.
- An HTTP DELETE request is sent to the API endpoint to remove the order.
- A cancellation message is displayed upon successful cancellation.

**Styling:**
- The component's visual styling is managed through the included external CSS file named `Order.css`.


The Contact component in Angular provides a contact form for users to input their name, email, and message. Upon submission, the form data is logged to the console. Angular's reactive forms are employed to manage form inputs and facilitate submission.

**Key Features:**

**Form Inputs:**
- The component offers input fields for users to provide their name, email, and message.
- Each input field corresponds to its own form control and reactive state variables.

**Form Submission:**
- Upon form submission, an event handler (`handleSubmit`) is triggered.
- The handler prevents the default form submission behavior, controlling the submission process.

**Console Logging:**
- Form data is logged to the console upon submission, showcasing captured values.
- This logging mechanism acts as a placeholder for more advanced actions like sending data to a server.

**Clearing Form Fields:**
- After successful submission, input fields are cleared by resetting the reactive state variables.

