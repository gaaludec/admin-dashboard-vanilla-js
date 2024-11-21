# Admin Dashboard

## Overview

The **Admin Dashboard** is a responsive and interactive web application designed to manage data and analytics for an organization. It features dynamic functionalities, such as light/dark mode toggling, a collapsible sidebar, and a dynamic table to display recent orders.

---

## Features

1. **Dynamic Sidebar:**
   - Open/close functionality for improved navigation.
2. **Dark/Light Mode:**

   - Toggle between themes for user preference.

3. **Recent Orders Table:**

   - Dynamically populates with course data.

4. **Reminders and User Info:**
   - Displays user profile and notifications.

---

## File Structure

1. **`index.html`:**  
   The main HTML file containing the structure of the dashboard, including the sidebar, main content, and right section.

2. **`index.js`:**  
   The JavaScript file responsible for:

   - Sidebar toggle functionality.
   - Light/Dark mode toggle.
   - Populating the recent orders table dynamically.

3. **`orders.js`:**  
   Contains the data for recent orders in the dashboard.

4. **`style.css`:**  
   Defines the dashboard's visual design, including colors, typography, responsive layout, and dark mode support.

---

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/admin-dashboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd admin-dashboard
   ```

3. Open the project in your favorite editor.

4. Launch the application by opening `index.html` in your browser.

---

## Usage

1. **Open/Close Sidebar:**

   - Click the menu icon to open the sidebar.
   - Click the close icon to hide the sidebar.

2. **Toggle Light/Dark Mode:**

   - Click the sun/moon icon to switch themes.

3. **View Recent Orders:**

   - Check the "Recent Orders" table for dynamic data.

4. **Profile and Notifications:**
   - View user info and reminders in the right section.

---

## Dependencies

- Google Fonts (Material Icons):
  ```html
  <link
    href="https://fonts.googleapis.com/icon?family=Material+Icons+Sharp"
    rel="stylesheet"
  />
  ```

---

## Sample Data (from `orders.js`)

| Course Name              | Course Number | Payment  | Status   |
| ------------------------ | ------------- | -------- | -------- |
| Health Informatics       | 85743         | Due      | Pending  |
| AI & Cognitive Processes | 97245         | Refunded | Declined |
| Design Patterns          | 36452         | Paid     | Active   |

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Enjoy managing your dashboard! 🎉
