# technical-documental-page-project
# Product Landing Page Project

This project is a **Product Landing Page**, built as part of the freeCodeCamp Responsive Web Design certification. It is designed to showcase a product with an interactive, responsive, and visually appealing layout.

### Features of the Page:
- **Header Section**:
  - A `header` element with the `id="header"`, which contains an image representing the product logo (`id="header-img"`).
  - A `nav` element within the header (`id="nav-bar"`) that includes three clickable elements with the class `nav-link`. These links navigate the user to different sections of the page: Products, About, and Contact.
  - The navbar remains fixed at the top of the viewport as the user scrolls through the page.

- **Product Section**:
  - The `products` section introduces the product with a title, description, and a gallery of images.
  - The images in the gallery are arranged using **CSS Flexbox** to create a responsive layout, adapting the display based on screen size.
  
- **About Section**:
  - The `about` section contains a video about the product with an embedded video player (`id="video"`), offering the user an introduction to the brand.
  - A brief description follows the video, providing more context and insight into the company.

- **Contact Section**:
  - The contact form allows users to submit their email address along with a message, providing interaction with the site.
  - The form uses HTML5 validation to ensure that the email entered is in a correct format (`type="email"`), and a placeholder text prompts the user for input.
  - A static form submission is handled via a `POST` request to a mock URL: `https://www.freecodecamp.com/email-submit`.

### Code Highlights:
- **HTML Structure**: 
  - The page consists of semantic HTML5 elements such as `header`, `nav`, `article`, `section`, `form`, and `footer`.
  - Media queries are used to ensure that the page is fully responsive across various screen sizes.
  
- **CSS Styling**:
  - Flexbox is used to align and distribute items within the layout, particularly for the gallery and the navbar.
  - The page is styled with a clean, modern look, with ample white space, centered text, and a color palette that reflects the aesthetic of a flower shop.
  - A gradient shadow line is applied at the top of the header for an elegant visual effect.

### Key Features and Elements:
- **Fixed Navbar**: The navigation bar stays at the top of the page as users scroll.
- **Image Gallery**: Showcases various flower arrangements and their descriptions. The gallery is responsive and adjusts its layout based on screen size.
- **Embedded Video**: A video in the About section introduces the company, providing more insight into the business.
- **Responsive Design**: The page layout adjusts to different screen sizes with a media query, ensuring usability on both desktop and mobile devices.
- **Form Submission**: Users can submit their email and a message through the contact form.
