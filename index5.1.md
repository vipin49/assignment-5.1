## 1. Objective

The objective of this assignment is to convert a basic HTML webpage into an attractive and well-designed webpage using CSS. An external stylesheet named `style.css` is used to style the background, text, headings, paragraphs, links, and navigation bar.

## 2. Requirements

- Visual Studio Code
- HTML
- CSS
- Google Chrome
- Chrome DevTools
- Live Server extension (optional)

## 3. Project Folder Structure

Create a folder named `Assignment-5.1` and add the following files:

```text
Assignment-5.1/
│
├── index.html
└── style.css
```

## 4. HTML Code (index.html)

Create a file named `index.html` and write the following complete code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My College Website</title>

    <!-- Link External CSS File -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Welcome to My College Website</h1>
        <p class="tagline">Learn Today, Lead Tomorrow</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#courses">Courses</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <main>

        <!-- Home Section -->
        <section id="home" class="content-section">
            <h2>Home</h2>
            <p>
                Welcome to my college website. This webpage provides
                information about college life, courses, and education.
                It is created using HTML and CSS.
            </p>
        </section>

        <!-- About Section -->
        <section id="about" class="content-section">
            <h2>About My College</h2>
            <p>
                My college provides students with opportunities to learn
                new skills, develop knowledge, and prepare for their
                future careers.
            </p>
        </section>

        <!-- Courses Section -->
        <section id="courses" class="content-section">
            <h2>Courses Offered</h2>
            <ul>
                <li>Bachelor of Technology (B.Tech)</li>
                <li>Bachelor of Computer Applications (BCA)</li>
                <li>Master of Computer Applications (MCA)</li>
            </ul>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="content-section">
            <h2>Contact Information</h2>
            <p>Email: student@example.com</p>
            <p>Website: <a href="https://www.example.com">Visit Website</a></p>
        </section>

    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2026 My College Website. All rights reserved.</p>
    </footer>

</body>
</html>
```

## 5. CSS Code (style.css)

Create another file named `style.css` in the same folder and write the following complete code:

```css
/* General Page Styling */
* {
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    margin: 0;
    padding: 0;
    background-color: #f0f4f8;
    color: #263238;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    line-height: 1.7;
}

/* Header Styling */
header {
    background-color: #1565c0;
    color: white;
    text-align: center;
    padding: 35px 20px;
}

header h1 {
    margin: 0;
    font-size: 32px;
}

.tagline {
    margin: 8px 0 0;
    font-size: 18px;
    color: #e3f2fd;
}

/* Navigation Bar Styling */
nav {
    background-color: #0d47a1;
    padding: 14px 10px;
    text-align: center;
}

nav a {
    display: inline-block;
    color: white;
    text-decoration: none;
    font-weight: bold;
    padding: 8px 18px;
    margin: 3px 5px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

/* Navigation Hover Effect */
nav a:hover {
    background-color: #1976d2;
    color: #ffffff;
}

/* Main Content Styling */
main {
    max-width: 1000px;
    margin: 30px auto;
    padding: 0 20px;
}

/* Section Styling */
.content-section {
    background-color: white;
    margin-bottom: 22px;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
}

/* Heading Styling */
h2 {
    color: #1565c0;
    font-size: 25px;
    margin-top: 0;
    margin-bottom: 12px;
    border-bottom: 2px solid #bbdefb;
    padding-bottom: 8px;
}

/* Paragraph Styling */
p {
    margin-bottom: 12px;
}

/* List Styling */
ul {
    padding-left: 25px;
}

li {
    margin-bottom: 8px;
}

/* Link Styling */
a {
    color: #1565c0;
}

main a {
    font-weight: bold;
    text-decoration: none;
}

main a:hover {
    color: #0d47a1;
    text-decoration: underline;
}

/* Footer Styling */
footer {
    background-color: #263238;
    color: white;
    text-align: center;
    padding: 18px;
    margin-top: 30px;
}

footer p {
    margin: 0;
}

/* Responsive Design */
@media (max-width: 600px) {
    header h1 {
        font-size: 25px;
    }

    nav a {
        padding: 8px 12px;
        margin: 3px;
    }

    main {
        padding: 0 12px;
    }

    .content-section {
        padding: 18px;
    }

    h2 {
        font-size: 22px;
    }
}
```

## 6. Explanation of CSS Properties

| CSS Property | Purpose |
|---|---|
| `background-color` | Sets the background color of an element. |
| `color` | Changes the text color. |
| `font-family` | Defines the font used on the webpage. |
| `font-size` | Controls the size of the text. |
| `text-align` | Aligns text horizontally. |
| `padding` | Adds space inside an element. |
| `margin` | Adds space outside an element. |
| `border-radius` | Makes the corners rounded. |
| `box-shadow` | Adds a shadow around an element. |
| `text-decoration` | Adds or removes link underlines. |
| `:hover` | Applies styles when the pointer moves over an element. |
| `@media` | Applies CSS rules according to screen size. |

## 7. Steps to Run the Website

1. Open Visual Studio Code.
2. Create a folder named `Assignment-5.1`.
3. Create `index.html` and paste the HTML code.
4. Create `style.css` and paste the CSS code.
5. Save both files using `Ctrl + S`.
6. Make sure both files are in the same folder.
7. Right-click `index.html` and select **Open with Live Server**. If Live Server is unavailable, open `index.html` directly in Google Chrome.
8. Check that the background, headings, navigation bar, links, and footer are styled correctly.

## 8. Inspect CSS Using Chrome DevTools

1. Open the webpage in Google Chrome.
2. Right-click any heading or paragraph.
3. Select **Inspect**.
4. Open the **Elements** panel.
5. Select an HTML element.
6. In the **Styles** panel, inspect the CSS rules applied to it.
7. Temporarily change a property, such as `color` or `background-color`, to observe the effect.
8. Check the Console panel for errors if the stylesheet does not load.
9. Use the device toolbar to check the webpage on different screen sizes.

**Note:** Changes made directly in DevTools are temporary. To save permanent changes, update the `style.css` file in Visual Studio Code.

## 9. Expected Output

The webpage should have the following features:

- A blue header with a white heading.
- A dark-blue navigation bar with readable links.
- A light-colored page background.
- White content sections with rounded corners and shadows.
- Blue section headings.
- Properly styled paragraphs, lists, and hyperlinks.
- A dark footer with white text.
- A responsive layout for smaller screens.
- Smooth scrolling when navigation links are clicked.

## 10. Result

The basic HTML webpage was successfully converted into a styled webpage using an external CSS file. The background, text colors, fonts, headings, paragraphs, links, and navigation bar were styled to improve the appearance and readability of the website. Chrome DevTools was used to inspect and test the applied CSS rules.

## 11. Submission

Submit the following files:

1. `index.html` — HTML webpage.
2. `style.css` — External CSS stylesheet.
3. `Assignment-5.1.md` — Assignment documentation.

