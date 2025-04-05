# Harshita Electronics Website

A modern website for Harshita Electronics, a manufacturer of UPS systems, Bus UPS, and stabilizers.

## Features

- Responsive design
- Contact form with email integration
- Product showcase
- Modern UI/UX
- Smooth animations
- Mobile-friendly navigation

## Setup Instructions

### Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Update the following variables in `.env`:
     - `EMAIL_USER`: Your Gmail address
     - `EMAIL_PASS`: Your Gmail app password
     - `EMAIL_TO`: The email address where contact form submissions should be sent

### Running the Application

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

### Production Deployment

1. Build the application:
   ```bash
   npm run build
   ```

2. Start the production server:
   ```bash
   npm start
   ```

## Project Structure

- `public/` - Static files (HTML, CSS, JS, images)
- `server.js` - Backend server
- `package.json` - Project dependencies and scripts
- `.env` - Environment variables

## Contact Form Setup

The contact form uses Nodemailer to send emails. To set up email functionality:

1. Create a Gmail account or use an existing one
2. Enable 2-factor authentication
3. Generate an App Password:
   - Go to Google Account Settings
   - Security
   - App Passwords
   - Generate a new app password
4. Use the generated password in your `.env` file

## Contributing

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License. 