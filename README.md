# Task-6
# Contact Form with Validation

This repository contains a simple, responsive contact form built using HTML, CSS, and JavaScript. The form validates user input for *name, **email, and **message* fields before submission.

### Features

- Responsive design for desktop and mobile
- Real-time input validation (name, email format, message)
- Clear error messages for invalid fields
- Success message and automatic form reset on valid submission

***

## Folder Structure


/project-root
  └── index.html
  └── styles.css   // If styles separated
  └── README.md    // This readme file


***

## Setup & Usage

1. *Download/Clone the repository*  
   Clone using git clone <repo-url> or download as a ZIP file and extract.

2. *Open the form*  
   Open index.html directly in your web browser.

3. *Customize*  
   - To update styles, edit the <style> section inside index.html or modify styles.css if separated.
   - You can change the validation logic in the <script> block to fit other requirements.

***

## Code Overview

- *index.html*  
  Contains the complete markup for the form, all CSS for styling, and JavaScript for validation and message handling.
- *Validation Process*  
  - Name: Required (cannot be empty)
  - Email: Required and must match standard email format
  - Message: Required (cannot be empty)
  - Error messages are shown under each invalid field.
  - On success, a green confirmation message appears and the form resets.

***

## Customization & Extension

- To extend validation (e.g., add phone number), duplicate the code pattern for other fields.
- For backend integration, modify the submit logic to send data using AJAX/fetch where needed.

  OUTPUT:

  <img width="602" height="353" alt="image" src="https://github.com/user-attachments/assets/53667d7c-0354-42c6-8b8b-ecf8207512b3" />


