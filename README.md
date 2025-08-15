# JWT-Based Login Page Project

This project is a login page built using **HTML**, **CSS**, and **JavaScript** with authentication handled via **JWT (JSON Web Token)**.

The backend is developed with **Flask**, and the application also includes a **registration feature** accessible from the login page. 

## Features

- **JWT Authentication:** Secure login using JSON Web Tokens.
- **User Registration:** Users can create a new account directly from the login page.
- **Password Complexity Validation:** The backend checks the strength of passwords to prevent weak passwords from being used.
- **Password Hashing:**
  - Implemented using Werkzeug's security utilities (`werkzeug.security`)
  - Utilized `generate_password_hash()` for secure password storage
  - Used `check_password_hash()` for password verification during authentication


## Technologies Used

- Frontend: HTML, CSS, JavaScript  
- Backend: Flask  
- Authentication: JWT
