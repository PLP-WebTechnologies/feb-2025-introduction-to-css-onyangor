# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

***The HTML file ***

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>
    <header>
        <h1 class="title">Welcome to My CSS Page</h1>
    </header>

    <section>
        <p class="description">This is a simple webpage to demonstrate CSS styling.</p>
        <img src="example.jpg" alt="Example Image" class="styled-image">
    </section>

    <footer>
        <p id="footer-text">Happy Coding! 💻✨</p>
    </footer>
</body>
</html>

*** The external CSS file **
style.css

body {
    font-family: 'Arial', sans-serif; /* Different Font */
    background-color: #f4f4f4; /* Light Gray Background */
    text-align: center;
}

/* Styling the Title */
.title {
    color: #007bff; /* Blue Color */
    font-size: 28px;
    margin-bottom: 20px;
}

/* Styling Paragraph */
.description {
    color: #333;
    font-size: 18px;
    padding: 10px;
}

/* Styling Image */
.styled-image {
    width: 300px;
    border: 5px solid #007bff; /* Blue Border */
    border-radius: 10px;
    margin-top: 10px;
}

/* Styling Footer */
#footer-text {
    color: white;
    background-color: #007bff;
    padding: 10px;
    border-radius: 5px;
}
