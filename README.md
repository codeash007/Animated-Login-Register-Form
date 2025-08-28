# Animated Login & Register Form

This project features a modern and animated login and registration form, designed to provide a smooth and engaging user experience. The form includes interactive transitions between login and registration views, enhancing the visual appeal and usability.




## Tech Stack

This project is built using fundamental web technologies:

*   **HTML5**: For structuring the form and its elements.
*   **CSS3**: For styling, animations, and responsive design, creating the visual effects and transitions.
*   **JavaScript (ES6+)**: For handling the interactive logic, such as switching between login and registration forms.
*   **Boxicons**: A free collection of high-quality SVG icons, used for the input field icons.




## Professional Setup and Usage

To set up and run this project professionally, follow these steps:

### 1. Project Structure

The project has a simple structure:

```
animated-login-register_form_tcw/
├── index.html
├── script.js
└── style.css
```

- `index.html`: The main HTML file containing the form structure.
- `style.css`: The CSS file for styling and animations.
- `script.js`: The JavaScript file for interactive logic.

### 2. Running the Project

This is a client-side web application and does not require a backend server. You can open the `index.html` file directly in your web browser.

**Option 1: Directly Open `index.html`**

Navigate to the project directory and open `index.html` with your preferred web browser.

```bash
# For macOS/Linux
open index.html

# For Windows
start index.html
```

**Option 2: Using a Local Web Server (Recommended)**

For professional development, it is recommended to serve the files using a local web server.

#### Using Python's Built-in HTTP Server

```bash
cd animated-login-register_form_tcw
python3 -m http.server 8000
```

Then, open your web browser and go to `http://localhost:8000`.

#### Using Node.js `http-server`

```bash
npm install -g http-server
cd animated-login-register_form_tcw
http-server
```

This will typically serve the application on `http://localhost:8080`.

### 3. Interacting with the Form

- **Switch between Login and Register**: Click the "Sign Up" or "Sign In" links to trigger the animation and switch between the login and registration forms.
- **Form Fields**: The form includes fields for username, email (for registration), and password, with icons from Boxicons.



