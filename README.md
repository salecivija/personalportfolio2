<h1>Personal Landing Page</h1>

<p>This project is a personal landing page with interactive features, including dynamically updating weather, local time, visitor IP information, and pop-up windows with social media links. The page is split into two main sections, each displaying different information and actions on click.</p>

<h2>Features</h2>
<ul>
    <li><strong>Interactive Background</strong>: Dynamic atoms and code snippets that move around the screen.</li>
    <li><strong>Header and Footer</strong>: Header with a welcome message and footer displaying local time, weather, visitor IP and location, and current year.</li>
    <li><strong>Pop-up Windows</strong>: Social media links displayed in pop-up windows when clicking on each section.</li>
    <li><strong>Dynamic Updates</strong>: Weather and time updates using APIs.</li>
</ul>

<h2>Sections Explanation</h2>

<h3>1. Header</h3>
<p>The header contains a welcome message with a custom font:</p>
<ul>
    <li>Uses the <code>Alex Brush</code> font from Google Fonts.</li>
    <li>Stays fixed at the top of the page.</li>
</ul>

<h3>2. Footer</h3>
<p>The footer displays:</p>
<ul>
    <li>Local time in the visitor's time zone.</li>
    <li>Weather in Munich.</li>
    <li>Visitor's IP address and location.</li>
    <li>Current year.</li>
</ul>

<h3>3. Left Section (FOR THE RECORD)</h3>
<ul>
    <li>Displays a background image.</li>
    <li>Shows the title "FOR THE RECORD".</li>
    <li>On click, shows a pop-up window with social media links.</li>
</ul>

<h3>4. Right Section (MY RESEARCHES AND PUBLISHING PAPERS)</h3>
<ul>
    <li>Displays a background image.</li>
    <li>Shows the title "MY RESEARCHES AND PUBLISHING PAPERS".</li>
    <li>On click, shows a pop-up window with social media links.</li>
</ul>

<h3>5. Background</h3>
<ul>
    <li>Dynamic atoms and code snippets move around the screen.</li>
    <li>Atoms avoid the cursor.</li>
</ul>

<h2>Setup Tutorial</h2>

<h3>Prerequisites</h3>
<ul>
    <li>Web server to host the HTML file.</li>
    <li>API key from <a href="https://home.openweathermap.org/users/sign_up">OpenWeatherMap</a>.</li>
</ul>

<h3>Steps</h3>
<ol>
    <li><strong>Clone the Repository</strong>
        <pre>
<code>git clone https://github.com/yourusername/personal-landing-page.git
cd personal-landing-page</code>
        </pre>
    </li>

    <li><strong>Update Image Paths</strong>
        <p>Ensure your background images are named <code>image1.webp</code> and <code>image2.webp</code>, or update the paths in the HTML:</p>
        <pre>
<code>&lt;div class=&quot;left&quot; onclick=&quot;showPopup('left')&quot; style=&quot;background-image: url('path/to/your/image1.webp');&quot;&gt;
&lt;div class=&quot;right&quot; onclick=&quot;showPopup('right')&quot; style=&quot;background-image: url('path/to/your/image2.webp');&quot;&gt;</code>
        </pre>
    </li>

    <li><strong>Add Social Media Icons</strong>
        <p>Ensure your social media icons are in the project directory or update the paths in the HTML:</p>
        <pre>
<code>&lt;a href=&quot;#&quot;&gt;&lt;img src=&quot;path/to/your/facebook-icon.png&quot; alt=&quot;Facebook&quot;&gt;Facebook&lt;/a&gt;</code>
        </pre>
    </li>

    <li><strong>Update OpenWeatherMap API Key</strong>
        <p>Replace <code>YOUR_OPENWEATHERMAP_API_KEY</code> with your actual API key in the script:</p>
        <pre>
<code>const apiKey = 'YOUR_OPENWEATHERMAP_API_KEY';</code>
        </pre>
    </li>

    <li><strong>Test the Page</strong>
        <p>Open the <code>index.html</code> file in your browser or deploy it on a web server to see the changes.</p>
    </li>
</ol>

<h2>Customization</h2>

<ol>
    <li><strong>Change Background Images</strong>
        <p>Replace <code>image1.webp</code> and <code>image2.webp</code> with your preferred images.</p>
    </li>

    <li><strong>Update Social Media Links</strong>
        <p>Replace the <code>href</code> attributes in the social media links with your actual profile URLs:</p>
        <pre>
<code>&lt;a href=&quot;https://facebook.com/yourprofile&quot;&gt;&lt;img src=&quot;facebook-icon.png&quot; alt=&quot;Facebook&quot;&gt;Facebook&lt;/a&gt;</code>
        </pre>
    </li>

    <li><strong>Modify Fonts and Styles</strong>
        <p>Update the font and style sections in the <code>&lt;head&gt;</code> of the HTML to change the appearance:</p>
        <pre>
<code>&lt;link href=&quot;https://fonts.googleapis.com/css2?family=YourFontChoice&amp;display=swap&quot; rel=&quot;stylesheet&quot;&gt;
&lt;style&gt;
  .your-style {
    font-family: 'YourFontChoice', sans-serif;
  }
&lt;/style&gt;</code>
        </pre>
    </li>

    <li><strong>Adjust JavaScript for More Custom Features</strong>
        <p>Modify the JavaScript functions to add more interactive features or change existing behaviors.</p>
    </li>
</ol>

<h2>License</h2>

<p>This project is free to use for any reason. Feel free to modify, distribute, or incorporate it into your own projects.</p>
