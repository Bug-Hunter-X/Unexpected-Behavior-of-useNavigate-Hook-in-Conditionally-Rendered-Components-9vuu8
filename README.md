# React Router Dom v6 - useNavigate Hook Issue in Conditionally Rendered Components

This repository demonstrates a potential issue with the `useNavigate` hook in React Router Dom v6 when used within conditionally rendered components.  The problem arises when the component containing `useNavigate` is unmounted before the navigation action completes. This often results in the navigation failing silently or producing console warnings.

The `conditionalNavigationBug.js` file showcases the problematic code, while `conditionalNavigationSolution.js` provides a solution using a cleanup function and state management to ensure navigation reliability.

## Setup

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Run the application:
   ```bash
   npm start
   ```