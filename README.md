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

/* Reset default margins and paddings */
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f2f2f2;
  color: #333;
}

/* ID selector */
#main-title {
  text-align: center;
  color: #2c3e50;
  font-size: 2.5rem;
  margin-top: 20px;
}

/* Class selector */
.card {
  background-color: #fff;
  border: 1px solid #ccc;
  border-radius: 8px;
  padding: 20px;
  margin: 20px auto;
  max-width: 600px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Element selector */
p {
  line-height: 1.6;
  font-size: 1rem;
}

/* Style image */
img.hero-image {
  width: 100%;
  height: auto;
  border: 5px solid #007BFF;
  border-radius: 10px;
  margin: 20px 0;
}

/* Button styling */
button {
  background-color: #007BFF;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #0056b3;
}


/* Reset default margin and padding */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Style for the header using ID selector */
#main-header {
  background-color: #4CAF50;
  color: white;
  padding: 20px;
  text-align: center;
  border-bottom: 3px solid #fff;
  font-family: 'Arial', sans-serif;
}

/* Style for the content section using class selector */
.content {
  margin: 20px;
  padding: 20px;
  background-color: #f4f4f4;
  border: 2px solid #ddd;
  border-radius: 8px;
  font-family: 'Verdana', sans-serif;
}

.content h2 {
  color: #333;
}

.content p {
  font-size: 1.1em;
  line-height: 1.6;
  color: #666;
}

/* Style for the footer*




