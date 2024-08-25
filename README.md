HTML Files:

Each page follows a similar structure for consistency.
Navigation links on each page point to the other pages, allowing easy navigation between them.
CSS Styling:

Consistent styling across all pages.
Fixed footer at the bottom of the page.
Flexbox used for the navigation bar to center links.
Viewing Your Website
Create Files:

Save the HTML files (index.html, about.html, services.html, contact.html, blog.html) and styles.css in the same directory.
Open in Browser:

Open any of the HTML files in a web browser to view the layout and test navigation between pages.
This setup will create a simple, functional multi-page website. You can further enhance each page with more content, images


Page Layout Description
Header: Contains the website title and spans the full width of the page.
Navigation Bar: Directly below the header, this bar includes links to all pages and is centered.
Main Content Area: Each page has a different main content section, but all follow a similar structure.
Footer: Spans the full width of the page and is fixed at the bottom.
ASCII Art Representation
Here's a simplified ASCII diagram representing the layout for each page of the website:


+-------------------------------------------------------+
|                    Header (Website Title)            |
+-------------------------------------------------------+
|                   Navigation Bar                     |
| [Home] [About] [Services] [Contact] [Blog]            |
+-------------------------------------------------------+
|                    Main Content Area                  |
|                                                       |
|  +---------------------------+                        |
|  |   [Home Page Content]     |                        |
|  +---------------------------+                        |
|                                                       |
|  +---------------------------+                        |
|  |   [About Page Content]    |                        |
|  +---------------------------+                        |
|                                                       |
|  +---------------------------+                        |
|  |   [Services Page Content] |                        |
|  +---------------------------+                        |
|                                                       |
|  +---------------------------+                        |
|  |   [Contact Page Content]  |                        |
|  +---------------------------+                        |
|                                                       |
|  +---------------------------+                        |
|  |   [Blog Page Content]     |                        |
|  +---------------------------+                        |
|                                                       |
+-------------------------------------------------------+
|                      Footer (Copyright)                |
+-------------------------------------------------------+
Explanation
Header:

Displays the website title and spans the top of the page.
Navigation Bar:

A horizontal bar with links to the Home, About, Services, Contact, and Blog pages.
Main Content Area:

Divided into sections for different pages. On each page, this area will display unique content relevant to that page.
Footer:

Contains copyright information and spans the width of the page, positioned at the bottom.
Designing the Pages
Each HTML file corresponds to a specific page but follows the same layout pattern:

Home (index.html): Welcome message and introductory content.
About (about.html): Information about the website or company.
Services (services.html): Details of the services offered.
Contact (contact.html): Contact information and possibly a form.
Blog (blog.html): Latest blog posts or updates.
Example Layout in CSS
The CSS provided earlier ensures that this layout is consistently applied across all pages. Here’s a brief reminder of the CSS for styling the layout:

css
Copy code
/* Basic reset */
body, h1, h2, p {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f4f4f4;
}

/* Header styling */
header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

/* Navigation bar styling */
nav {
    background: #444;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin: 0 1rem;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

/* Main content styling */
main {
    padding: 1rem;
    max-width: 1200px;
    margin: 0 auto;
}

main section {
    margin-bottom: 2rem;
}

main h2 {
    border-bottom: 2px solid #333;
    padding-bottom: 0.5rem;
    margin-bottom: 1rem;
}

/* Footer styling */
footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
This layout design is simple and clean, ensuring that all pages are consistently styled and easy to navigate. Feel free to customize the content and styles further to match your specific needs.




