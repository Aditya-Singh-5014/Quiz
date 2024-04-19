# React Quiz Application

This is a simple quiz application built with React that allows users to sign in, answer quiz questions, and see their results.

## Features

### Sign In Page

- Access the sign-in page (`/signin`) to provide your username.
- If no username is entered, an error message prompts you to provide a username and same goes for the password.

### Navbar

- The navbar displays the signed-in username once signed in.
- Initially shows "Sign In" until a username is provided and signed in.

### Quiz

- The quiz consists of 5 random questions chosen from a set of 10 questions stored in `Questions.json`.
- Navigate between questions using both previous and next buttons.
- You can change your answers before submitting the quiz.

### Submit and Result

- Submit the quiz to see your score.
- If you answered any questions correctly, a "Good Job" image is displayed.
- If you answered all questions incorrectly, a "Duck" image is displayed.

## Responsiveness

This React quiz application is designed to be responsive and accessible on various devices, including desktops, tablets, and mobile phones.

### Supported Devices

- **Desktop**: Modern desktop browsers (e.g., Chrome, Firefox, Safari) with responsive layout adjustments.
- **Tablet**: Optimized for tablet devices with medium-sized screens.

- **Mobile Phones**: Designed for usability on popular smartphones like iPhone 10 Pro Max, iPhone X, and Android devices.

### Design Features

- **Media Queries**: Adjusts layout and styling based on screen width.
- **Flexbox and Grid**: Ensures flexible component positioning.
- **Viewport Meta Tag**: Utilizes `<meta name="viewport" content="width=device-width, initial-scale=1">` for proper scaling on mobile.

### Testing

Responsive design tested on various devices using browser tools and physical devices.

### Usage Tips

- Use on devices with screen sizes similar to iPhone 10 Pro Max or smaller for optimal experience.
- Resize browser window to test responsiveness on desktop.

## Usage

1. **Sign In**

   - Navigate to the `/signin` route.
   - Enter your username and click "Sign In".

2. **Quiz**

   - Navigate to the root (`/`) route to start the quiz.
   - Answer each question and use the navigation buttons to move between questions.

3. **Submit**
   - Once all questions are answered, click "Submit" to see your score.

## Installation

To run this project locally:

1. Clone the repository:

   git clone https://github.com/your-username/react-quiz-app.git

2. Install Dependencies

   cd react-quiz-app
   npm install

3. Start the development server:

   npm start

4. Open your browser and navigate to "http://localhost:3000" to view the application.

5. You can also use the github pages link "https://aditya-singh-5014.github.io/Quiz/"

Technologies Used

React
React Router
JavaScript (ES6+)
HTML
CSS
