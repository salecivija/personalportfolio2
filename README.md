Personal Landing Page
This project is a personal landing page with interactive features, including dynamically updating weather, local time, visitor IP information, and pop-up windows with social media links. The page is split into two main sections, each displaying different information and actions on click.

Features
Interactive Background: Dynamic atoms and code snippets that move around the screen.
Header and Footer: Header with a welcome message and footer displaying local time, weather, visitor IP and location, and current year.
Pop-up Windows: Social media links displayed in pop-up windows when clicking on each section.
Dynamic Updates: Weather and time updates using APIs.
Sections Explanation
1. Header
The header contains a welcome message with a custom font:

Uses the Alex Brush font from Google Fonts.
Stays fixed at the top of the page.
2. Footer
The footer displays:

Local time in the visitor's time zone.
Weather in Munich.
Visitor's IP address and location.
Current year.
3. Left Section (FOR THE RECORD)
Displays a background image.
Shows the title "FOR THE RECORD".
On click, shows a pop-up window with social media links.
4. Right Section (MY RESEARCHES AND PUBLISHING PAPERS)
Displays a background image.
Shows the title "MY RESEARCHES AND PUBLISHING PAPERS".
On click, shows a pop-up window with social media links.
5. Background
Dynamic atoms and code snippets move around the screen.
Atoms avoid the cursor.
Setup Tutorial
Prerequisites
Web server to host the HTML file.
API key from OpenWeatherMap.
Steps
Clone the Repository

sh
Copy code
git clone https://github.com/yourusername/personal-landing-page.git
cd personal-landing-page
Update Image Paths

Ensure your background images are named image1.webp and image2.webp, or update the paths in the HTML:

html
Copy code
<div class="left" onclick="showPopup('left')" style="background-image: url('path/to/your/image1.webp');">
<div class="right" onclick="showPopup('right')" style="background-image: url('path/to/your/image2.webp');">
Add Social Media Icons

Ensure your social media icons are in the project directory or update the paths in the HTML:

html
Copy code
<a href="#"><img src="path/to/your/facebook-icon.png" alt="Facebook">Facebook</a>
Update OpenWeatherMap API Key

Replace YOUR_OPENWEATHERMAP_API_KEY with your actual API key in the script:

javascript
Copy code
const apiKey = 'YOUR_OPENWEATHERMAP_API_KEY';
Test the Page

Open the index.html file in your browser or deploy it on a web server to see the changes.

Customization
Change Background Images

Replace image1.webp and image2.webp with your preferred images.

Update Social Media Links

Replace the href attributes in the social media links with your actual profile URLs:

html
Copy code
<a href="https://facebook.com/yourprofile"><img src="facebook-icon.png" alt="Facebook">Facebook</a>
Modify Fonts and Styles

Update the font and style sections in the <head> of the HTML to change the appearance:

html
Copy code
<link href="https://fonts.googleapis.com/css2?family=YourFontChoice&display=swap" rel="stylesheet">
<style>
  .your-style {
    font-family: 'YourFontChoice', sans-serif;
  }
</style>
Adjust JavaScript for More Custom Features

Modify the JavaScript functions to add more interactive features or change existing behaviors.

License
This project is free to use for any reason. Feel free to modify, distribute, or incorporate it into your own projects.
