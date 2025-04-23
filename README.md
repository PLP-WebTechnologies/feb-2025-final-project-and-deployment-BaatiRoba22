# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.



```html
<!DOCTYPE html>
<html>
<head>
  <title>My Simple Page</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f4;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    .container {
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      margin: 20px auto;
      max-width: 600px;
    }

    button {
      background-color: #4CAF50;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Page</h1>

  <div class="container">
    <p>This is a simple webpage with some basic styling.</p>
    <button id="myButton">Click Me</button>
  </div>

  <script>
    const myButton = document.getElementById("myButton");

    myButton.addEventListener("click", () => {
      alert("You clicked the button!");
    });
  </script>

</body>
</html>
```

This code creates a webpage with:

- A title ("My Simple Page")
- A heading ("Welcome to My Page")
- A paragraph of text
- A button that displays an alert when clicked.








```html
<!DOCTYPE html>
<html>
<head>
  <title>My Stylish Page</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f4;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    h1 {
      color: #333;
      text-align: center;
      margin-bottom: 20px;
    }

    .container {
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      max-width: 800px;
      text-align: center;
    }

    .content {
      margin-bottom: 20px;
    }

    .image {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    button {
      background-color: #4CAF50;
      color: white;
      padding: 15px 30px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Stylish Page</h1>

  <div class="container">
    <img src="https://via.placeholder.com/600x300" alt="Placeholder Image" class="image"> 
    <div class="content">
      <p>This is a more styled webpage with a placeholder image, some content, and a button.</p>
    </div>
    <button id="myButton">Click Me</button>
  </div>

  <script>
    const myButton = document.getElementById("myButton");

    myButton.addEventListener("click", () => {
      alert("You clicked the button!  This is a more stylish alert!");
    });
  </script>

</body>
</html>
```

Here's what I've changed:

- Styling:
    - Added a more visually appealing font ('Arial').
    - Centered the content on the page.
    - Used box shadows to give the container a more 3D effect.
    - Added a placeholder image with a border radius.
    - Improved the button's styling with a hover effect and a transition.
- Content:
    - Added a placeholder image using a URL for a placeholder image service.
    - Expanded the paragraph with more content.
    - Updated the button's text and the alert message.


- Adding your own images: Replace the placeholder image with a relevant one.
- Writing more content: Add more paragraphs, headings, or lists to your page.
- Changing the colors and fonts: Experiment with different color palettes and fonts to match your style.
- Adding more JavaScript:  Implement interactive elements like forms, animations, or data manipulation.











Good luck and happy coding! 🚀💻
