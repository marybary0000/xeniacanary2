================================================================================
                    XENIA CANARY WEBSITE - README
================================================================================

Welcome to the Xenia Canary website project!

This is a professional, responsive, multi-page website built with HTML, CSS, 
and JavaScript for the Xenia Canary Xbox 360 emulator.

================================================================================
                           FILE STRUCTURE
================================================================================

xeniacanary2/
│
├── index.html          - Home page with hero section and focus keywords
├── about.html          - About page with mission, vision, and project info
├── contact.html        - Contact page with Google Form integration
├── download.html       - Download page with download button
├── style.css           - Main stylesheet (responsive design)
├── script.js           - JavaScript for interactivity and animations
└── README.txt          - This file

================================================================================
                        HOW TO RUN THE WEBSITE
================================================================================

OPTION 1: OPEN DIRECTLY IN BROWSER
-----------------------------------
1. Navigate to the project folder: D:\xeniacanary2\
2. Double-click on "index.html" to open it in your default web browser
3. Navigate through pages using the menu

OPTION 2: USE A LOCAL WEB SERVER (RECOMMENDED)
-----------------------------------------------
For better performance and to avoid CORS issues:

Using Python (if installed):
1. Open Command Prompt or PowerShell
2. Navigate to the project folder:
   cd D:\xeniacanary2
3. Run one of these commands:
   - Python 3: python -m http.server 8000
   - Python 2: python -m SimpleHTTPServer 8000
4. Open browser and go to: http://localhost:8000

Using VS Code Live Server Extension:
1. Install "Live Server" extension in VS Code
2. Right-click on index.html
3. Select "Open with Live Server"

Using Node.js http-server:
1. Install: npm install -g http-server
2. Navigate to project folder
3. Run: http-server
4. Open browser and go to the provided URL

================================================================================
                        WEBSITE FEATURES
================================================================================

✓ Fully Responsive Design (mobile, tablet, desktop)
✓ Modern UI with smooth animations and transitions
✓ SEO-optimized with proper meta tags and keywords
✓ Mobile-friendly navigation with hamburger menu
✓ Interactive elements (hover effects, scroll animations)
✓ Back-to-top button for easy navigation
✓ Smooth scrolling and page transitions
✓ Professional color scheme (#FFFFFF, #BDD0EA, #004AAC)

================================================================================
                        PAGES OVERVIEW
================================================================================

1. INDEX.HTML (HOME PAGE)
   - Hero section with call-to-action buttons
   - Features grid showcasing key benefits
   - Focus keywords integrated for SEO
   - Official site link button (https://xeniacanary.org/)
   - Download section

2. ABOUT.HTML
   - About Us section with project description
   - Mission statement with detailed objectives
   - Vision for the future
   - Community-driven development info
   - Project statistics

3. CONTACT.HTML
   - Contact information cards
   - Google Form integration for messages
   - Link: https://docs.google.com/forms/d/e/1FAIpQLSeQ1peOAUw7VAcqiYNlE6hgaQxBsk_ZkeOc9iX7oxP4PygZ-A/viewform
   - GitHub and official site links
   - FAQ section

4. DOWNLOAD.HTML
   - Featured download section
   - System requirements (minimum & recommended)
   - Installation guide
   - Download button linking to: https://xeniacanary.org/downloads/
   - Additional resources section

================================================================================
                        HOW TO EDIT THE WEBSITE
================================================================================

EDITING CONTENT:
----------------
1. Open any HTML file in a text editor (VS Code, Notepad++, Sublime, etc.)
2. Find the section you want to edit
3. Modify the text between HTML tags
4. Save the file and refresh your browser to see changes

CHANGING COLORS:
----------------
1. Open style.css in a text editor
2. Find the :root section at the top (lines 5-12)
3. Modify these CSS variables:
   - --primary-color: #004AAC    (Main blue)
   - --secondary-color: #BDD0EA  (Light blue)
   - --accent-color: #0066FF     (Bright blue)
   - --white: #FFFFFF            (White)
4. Save and refresh to see changes

CHANGING LINKS:
---------------
1. Open the HTML file containing the link
2. Find the <a href="..."> tag
3. Replace the URL in the href attribute
4. Save and refresh

ADDING NEW PAGES:
-----------------
1. Create a new HTML file (e.g., newpage.html)
2. Copy the structure from an existing page
3. Modify the content as needed
4. Add a link to the new page in the navigation menu
5. Update all HTML files' navigation to include the new page

MODIFYING STYLES:
-----------------
1. Open style.css
2. Find the section you want to modify (use comments as guide)
3. Change CSS properties as needed
4. For responsive design, check media queries at the bottom

CUSTOMIZING JAVASCRIPT:
-----------------------
1. Open script.js
2. Each section is clearly labeled with comments
3. Modify or add new functionality as needed
4. Common modifications:
   - Animation speeds (duration values)
   - Scroll thresholds
   - Menu behavior

================================================================================
                        CUSTOMIZATION TIPS
================================================================================

CHANGING FONTS:
- Update font-family in style.css (body selector)
- Consider using Google Fonts for more options

ADDING IMAGES:
1. Create an "images" folder in the project directory
2. Add your images to this folder
3. Reference them in HTML: <img src="images/yourimage.jpg" alt="Description">

MODIFYING NAVIGATION:
- Edit the <nav> section in each HTML file
- Keep navigation consistent across all pages

UPDATING FOOTER:
- Edit the <footer> section in each HTML file
- Update copyright year, links, and social media

================================================================================
                        IMPORTANT LINKS
================================================================================

Official Site:      https://xeniacanary.org/
Downloads:          https://xeniacanary.org/downloads/
GitHub:             https://github.com/xeniacanaryhub
Contact Form:       https://docs.google.com/forms/d/e/1FAIpQLSeQ1peOAUw7VAcqiYNlE6hgaQxBsk_ZkeOc9iX7oxP4PygZ-A/viewform

================================================================================
                        SEO KEYWORDS USED
================================================================================

The following focus keywords are integrated throughout the site:
- xenia
- xenia-canary
- xenia_canary
- xenia canary download
- xenia canary compatibility list

These appear in:
- Page titles (<title> tags)
- Meta descriptions
- Headings (H1, H2, H3)
- Content text
- Image alt attributes

================================================================================
                        BROWSER COMPATIBILITY
================================================================================

This website is compatible with:
✓ Google Chrome (latest)
✓ Mozilla Firefox (latest)
✓ Microsoft Edge (latest)
✓ Safari (latest)
✓ Opera (latest)

Mobile browsers:
✓ Chrome Mobile
✓ Safari Mobile
✓ Samsung Internet
✓ Firefox Mobile

================================================================================
                        RESPONSIVE BREAKPOINTS
================================================================================

The website adapts to different screen sizes:
- Desktop:  > 968px
- Tablet:   600px - 968px
- Mobile:   < 600px

To test responsiveness:
1. Open the site in a browser
2. Press F12 to open Developer Tools
3. Click the device toolbar icon
4. Select different device sizes

================================================================================
                        TROUBLESHOOTING
================================================================================

ISSUE: Styles not loading
SOLUTION: Ensure style.css is in the same folder as HTML files

ISSUE: Menu not working on mobile
SOLUTION: Ensure script.js is loading properly

ISSUE: Links not working
SOLUTION: Check that all href attributes have correct URLs

ISSUE: Page looks broken
SOLUTION: Clear browser cache (Ctrl+F5) and reload

ISSUE: Images not showing
SOLUTION: Check image paths and ensure images exist

================================================================================
                        PERFORMANCE TIPS
================================================================================

1. Optimize images before adding them (compress for web)
2. Minimize CSS and JavaScript for production
3. Use a CDN for Font Awesome icons (already included)
4. Enable browser caching if hosting online
5. Test on multiple devices and browsers

================================================================================
                        DEPLOYMENT
================================================================================

To deploy this website online:

GITHUB PAGES (FREE):
1. Create a GitHub repository
2. Upload all files
3. Enable GitHub Pages in repository settings
4. Your site will be live at: username.github.io/repo-name

NETLIFY (FREE):
1. Create a Netlify account
2. Drag and drop the project folder
3. Your site will be live instantly

TRADITIONAL WEB HOSTING:
1. Choose a hosting provider
2. Upload all files via FTP/SFTP
3. Set index.html as the default page

================================================================================
                        SUPPORT & CREDITS
================================================================================

Design Inspiration: https://xeniacanary.org/
Color Scheme: #FFFFFF, #BDD0EA, #004AAC
Icons: Font Awesome 6.4.0
Fonts: Segoe UI (system font)

For questions or issues with this website, please refer to:
- GitHub: https://github.com/xeniacanaryhub
- Official Site: https://xeniacanary.org/

================================================================================
                        VERSION INFORMATION
================================================================================

Website Version: 1.0
Created: 2024
Last Updated: 2024

================================================================================
                        LICENSE & USAGE
================================================================================

This website template is created for Xenia Canary project.
Feel free to modify and customize as needed for your purposes.

================================================================================
                              END OF README
================================================================================

Thank you for using the Xenia Canary website template!
For the best experience, run the site through a local web server.

Enjoy! 🎮
