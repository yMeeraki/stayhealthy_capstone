# StayHealthy Inc.

**StayHealthy Inc.** is a web platform for a non-profit organization dedicated to enhancing healthcare access and quality in remote areas. The platform allows users to easily book medical appointments, browse health blogs, write reviews about their consultation experiences, and more. This project was developed using HTML, CSS, Figma designs, and React for a seamless and responsive user experience.

---

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [General Notes](#general-notes)
- [Contributing](#contributing)
- [License](#license)

---

## Features

### 1. Navigation Bar
- Clean, responsive navigation with links to main sections: **Home**, **Appointments**, **Health Blog**, **Reviews**, **Sign-up**, and **Login**.
- Interactive hover and active states to improve usability.

### 2. Sign-Up and Login Forms
- **Sign-Up Form**: Users can sign up by entering their role (Doctor, Patient, Admin), name, email, and password.
- **Login Form**: Simple login form with email and password fields, password visibility toggle, and error validation.

### 3. Appointment Booking
- **Search Doctor** layout enables users to search by specialty.
- **Doctor Card** displays the doctor's name, specialty, experience, and rating with an option to book an appointment.

### 4. Reviews Section
- Allows patients to write reviews about their consultation experiences with doctors.
- Displays reviews along with doctor name, specialty, and feedback.
- Includes an option for patients to provide star ratings and written feedback.

---

## Technologies Used
- **Frontend**: React.js, HTML, CSS, Figma (for design)
- **Styling**: Custom CSS with colors for branding
  - **Cyan Blue (#00BBFF)**: Main UI elements, buttons, and highlights.
  - **Charcoal Black (#2C3E50)**: Text, navigation, and backgrounds.
  - **Soft Gray (#F0F0F0)**: Backgrounds, cards, and secondary elements.

---

## Setup Instructions

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/medical-appointment-booking.git
    cd medical-appointment-booking
    ```

2. **Install Dependencies**:
    ```bash
    npm install
    ```

3. **Run the Development Server**:
    ```bash
    npm start
    ```
   

## Usage

- **Sign-Up/Login**: New users can sign up, while returning users can log in.
- **Book an Appointment**: Use the "Search Doctor" feature to find a doctor by specialty, view the doctor card, and book an appointment.
- **Review a Consultation**: After a consultation, patients can provide feedback and rate their experience.

## General Notes

- Ensure form validation for sign-up, login, and review forms.
- Use error messages to improve user experience in cases of invalid input.
- Keep components modular and reusable for scalability.

## Contributing

We welcome contributions! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

