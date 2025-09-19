BR Architects Website (HTML + CSS)
📌 Project Description

This is a static website built using HTML and CSS that showcases an architecture company portfolio.

It includes:

A fixed navigation bar

A hero image with text overlay

Projects section with images of houses

An About section with company details

A Team/Founders section introducing architects

A Contact section with a form

A Map and footer

This project is a practice/demo project inspired by W3Schools BR Architects template.

🖼️ Preview

(You can add a screenshot or live GitHub Pages link here.)

📂 Project Structure
.
├── index.html   # Main HTML file
├── pbr.css      # Stylesheet for layout & design
└── README.md    # Project documentation

💻 Code Explanation
1. Navigation Bar (.br)

Uses flexbox to align links (Projects, About, Contact).

Fixed at the top of the screen (position: fixed; top: 0;).

White background with black text for a clean look.

2. Hero Section (.pic)

Displays a full-width background image of architecture.

Text “BR Architects” is overlaid in the center using CSS positioning (.mat).

3. Projects Section

Contains two rows of images (.section1, .section2).

Each project image has a label (.summer) placed using position: absolute; at the top-left corner.

Layout is managed using inline-block so multiple images fit side by side.

4. About Section (.abt)

Provides a description about the architecture company.

Uses standard <p> text styling.

5. Founders/Team Section (.founders)

Displays 4 team members (CEO + 3 Architects).

Each team member has an image, role, description, and Contact button styled with background color.

6. Contact Section

Title + short description.

A form (.f) with input fields: Name, Email, Subject, Contact.

Styled with width: 99% so inputs stretch across the page.

7. Send Message Button (.send)

Black button with white text.

Positioned below the form.

8. Map Section (.road)

Shows a static map image centered.

9. Footer (.footer)

Black background footer with white text.

Credit line: Powered by @Pavani.

⚙️ How It Works

HTML (index.html) creates the structure of the page: navbar, sections, images, form, footer.

CSS (pbr.css) handles the styling and positioning:

flexbox for the navbar

inline-block for project & team images

absolute positioning for text overlays

font-size, padding, margins for clean layout

fixed navbar so it stays on top during scrolling
