# weight-tracker
Weight Tracking System - Track your weight loss journey with friends &amp; detailed analytics

# Weight Tracking System

A comprehensive weight tracking application that allows multiple users to track their weight loss journey with detailed analytics and visualizations.

## Features

- 📊 Interactive weight progress charts
- 👥 Multi-user support with password protection
- 📈 Trend line analysis with linear regression
- 🏷️ Weight loss labels on data points
- 📱 Responsive design for mobile and desktop
- 📋 Detailed personal statistics
- 📤 Data export functionality
- 🔒 Admin panel with data management

## Live Demo

Visit: [https://yourusername.github.io/weight-tracker](https://yourusername.github.io/weight-tracker)

## Setup Instructions

### For Personal Use

1. Clone this repository
2. Set up Google Apps Script backend (see Backend Setup below)
3. Update the `SCRIPT_URL` in `index.html` with your Google Apps Script URL
4. Open `index.html` in your browser

### Backend Setup (Google Apps Script)

This application requires a Google Apps Script backend for data storage. Follow these steps:

1. Go to [Google Apps Script](https://script.google.com)
2. Create a new project
3. Replace the default code with the backend script (contact developer for script)
4. Deploy as web app with public access
5. Copy the deployment URL and update `SCRIPT_URL` in `index.html`

## Usage

1. **Adding Users**: Select "新增用戶" and enter a username with 4-digit password
2. **Recording Weight**: Choose your username, enter password and current weight
3. **Viewing Analytics**: Click on chart points or select users from the statistics panel
4. **Display Options**: 
   - Show Weight Loss Labels: Displays weight change from initial weight
   - Show Trend Line: Shows linear regression trend analysis

## Technologies Used

- HTML5/CSS3/JavaScript
- Chart.js for data visualization
- Google Apps Script for backend
- Responsive CSS Grid and Flexbox

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License - Feel free to use and modify for personal or commercial use.
