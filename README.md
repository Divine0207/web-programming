# web-programming
lab1 intro.html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First HTML Page</title>
</head>
<body>
    <h1>Welcome to My First HTML Page!</h1>

    <p>I am learning the basics of web development and how to create a webpage using HTML.</p>

    <p>This is an <strong>exciting</strong> start to building websites.</p>

    <a href="https://www.tri-c.edu/IT" target="_blank">Visit Tri-C IT Homepage</a>

    <br><br>

    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/512px-HTML5_logo_and_wordmark.svg.png" 
         alt="HTML Logo" width="200">
</body>
</html>

lab 2 home
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lab 2 - Home</title>
</head>
<body>
    <h1>Welcome to Lab 2</h1>
    <p>This lab demonstrates how to create navigation using tables and both relative and absolute links.</p>

    <h2>Navigation Table</h2>
    <table border="1" cellpadding="8">
        <tr>
            <td><a href="lab2-about.html">About Page (Relative Link)</a></td>
            <td><a href="https://www.mozilla.org" target="_blank">Mozilla Homepage</a></td>
            <td><a href="https://www.tri-c.edu" target="_blank">Tri-C Homepage</a></td>
            <td><a href="https://www.tri-c.edu/IT" target="_blank">Tri-C IT Page</a></td>
        </tr>
    </table>
</body>
</html>

lab 2 about 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lab 2 - About</title>
</head>
<body>
    <h1>About Lab 2</h1>
    <p>This page provides information about Lab 2, which focuses on creating tables with navigation links using both relative and absolute paths.</p>

    <h2>Navigation Table</h2>
    <table border="1" cellpadding="8">
        <tr>
            <td><a href="lab2-home.html">Home Page (Relative Link)</a></td>
            <td><a href="mailto:zdobariya2@gmail.com">Email Me</a></td>
        </tr>
    </table>
</body>
</html>

Lab 3 
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Coffee Order Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #F5F5F5, #F5F5F5 );
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .form-container {
      background: #D1D0ce;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.2);
      max-width: 500px;
      width: 100%;
      animation: fadeIn 1s ease-in-out;
    }

    h1 {
      text-align: center;
      color: #6f4e37;
      margin-bottom: 20px;
    }

    label {
      font-weight: bold;
      display: block;
      margin: 10px 0 5px;
      color: #333;
    }

    input[type="text"],
    input[type="email"],
    select,
    textarea {
      width: 100%;
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 14px;
      margin-bottom: 15px;
    }

    textarea {
      resize: vertical;
    }

    .options {
      margin-bottom: 15px;
    }

    .options p {
      font-weight: bold;
      margin-bottom: 5px;
    }

    input[type="radio"],
    input[type="checkbox"] {
      margin-right: 8px;
    }

    button {
      width: 100%;
      background-color: #6f4e37;
      color: #fff;
      font-size: 16px;
      padding: 12px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: #5a3d2b;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-10px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <div class="form-container">
    <h1>☕ Coffee Order Form</h1>
    <form action="https://www.w3schools.com/action_page.php" method="get">
      
      <!-- Customer Name -->
      <label for="name">Customer Name</label>
      <input type="text" id="name" name="customer_name" required>
      
      <!-- Email Address -->
      <label for="email">Email Address</label>
      <input type="email" id="email" name="customer_email" required>
      
      <!-- Coffee Type -->
      <label for="coffee">Coffee Type</label>
      <select id="coffee" name="coffee_type" required>
        <option value="">--Select a coffee--</option>
        <option value="latte">Latte</option>
        <option value="cappuccino">Cappuccino</option>
        <option value="americano">Americano</option>
        <option value="espresso">Espresso</option>
      </select>
      
      <!-- Size -->
      <div class="options">
        <p>Size</p>
        <input type="radio" id="small" name="size" value="Small" required>
        <label for="small">Small</label><br>
        <input type="radio" id="medium" name="size" value="Medium">
        <label for="medium">Medium</label><br>
        <input type="radio" id="large" name="size" value="Large">
        <label for="large">Large</label>
      </div>
      
      <!-- Extras -->
      <div class="options">
        <p>Extras</p>
        <input type="checkbox" id="whipped" name="extras" value="Whipped Cream">
        <label for="whipped">Whipped Cream</label><br>
        <input type="checkbox" id="shot" name="extras" value="Extra Shot">
        <label for="shot">Extra Shot</label><br>
        <input type="checkbox" id="almond" name="extras" value="Almond Milk">
        <label for="almond">Almond Milk</label>
      </div>
      
      <!-- Special Instructions -->
      <label for="instructions">Special Instructions</label>
      <textarea id="instructions" name="special_instructions" rows="4"></textarea>
      
      <!-- Submit -->
      <button type="submit">Submit Order</button>
    </form>
  </div>

</body>
</html>

LAB4
<!doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lab 4 - CSS Formatting Basics</title>
    <link rel="stylesheet" href="lab4-styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Lab 4</h1>
    </header>
    <main>
        <p>This is the first paragraph. It contains some placeholder text for styling practice.</p>
        <p>This is the second paragraph. Feel free to add more content if you'd like.</p>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
            <li>Item 3</li>
        </ul>
        <a href="https://www.tri-c.edu">Visit Cuyahoga Community College</a>
        <div class="styled-box">
            <p>This is a styled box. Add your CSS rules to make it look great!</p>
        </div>
    </main>
</body>
</html>

Lab5 styles
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styling Text and Fonts</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif;
    }

    h1 {
      font-size: 3rem;
      font-weight: bold;
      text-align: center;
      text-shadow: 2px 2px 4px red;
    }

    h2 {
      font-size: 2rem;
      font-weight: 300;
      text-transform: uppercase;
    }

    p {
      text-align: justify;
      line-height: 1.6;
    }

    section:nth-of-type(3) p {
      text-transform: capitalize;
    }

    section:nth-of-type(4) p {
      text-shadow: 1px 1px 2px gray;
    }

    footer {
      text-align: center;
    }

    ul {
      list-style-type: square;
      padding-left: 1.5rem;
    }

    ol {
      list-style-type: upper-roman;
      padding-left: 1.5rem;
    }

    li {
      margin: 1rem 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Welcome to Text Styling Lab</h1>
  </header>
  <main>
    <section>
      <h2>Font Properties</h2>
      <p>This paragraph demonstrates the use of font-family, font-size, and font-weight properties.</p>
    </section>
    <section>
      <h2>Text Alignment</h2>
      <p>This paragraph demonstrates how to align text using the text-align property.</p>
    </section>
    <section>
      <h2>Transforming Text</h2>
      <p>This paragraph demonstrates text transformation with uppercase, lowercase, and capitalization.</p>
    </section>
    <section>
      <h2>Text Shadow</h2>
      <p>This paragraph demonstrates how to add shadow effects to text.</p>
    </section>
    <section>
      <h2>Lists</h2>
      <ul>
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
      </ul>
      <ol>
        <li>First Step</li>
        <li>Second Step</li>
        <li>Third Step</li>
      </ol>
    </section>
  </main>
  <footer>
    <p>Styling Text and Fonts Lab © 2025</p>
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Box Model Lab</title>
<style>
.box { 
     border: 5px solid blue;
     padding: 20px;
     margin: 20px;
     box-sizing: border-box;
     height: 150px;
     width: 300px;
     background-color: lightgray;
     }

  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    padding: 20px;
  }   

h1 {
    color: #333;
}
</style>
</head>
<body>
<h1>CSS Box Model Lab</h1>
<div class="box">
<p>This is a demonstration of the CSS Box Model.</p>
</div>

<div class="box">
    <p> This is another box to show how margin spacing works between elements.</p>
</div>
</body>
</html>
lab 7 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Java Haven</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header class="header">
    <h1>Java Haven</h1>
    <p>Your daily dose of caffeine and comfort.</p>
  </header>

  <!-- Navigation -->
  <nav class="nav">
    <ul>
      <li><a href="#menu">Menu</a></li>
      <li><a href="#about">About Us</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Main Content -->
  <main class="main-content">

    <!-- Menu Section -->
  <section id="menu">
      <h2>Featured Coffees</h2>
      <div class="flex-container">
        <div class="flex-item">Espresso</div>
        <div class="flex-item">Cappuccino</div>
        <div class="flex-item">Latte</div>
        <div class="flex-item">Mocha</div>
      </div>
      
</section>

    <!-- About Us Section -->
<section id="about">
      <h2>About Us</h2>
      <p>Java Haven is your cozy coffee shop for the best brews in town! We serve freshly roasted coffee and create a welcoming space for all coffee lovers.</p>
  </section>

<!-- Contact Section -->
 <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: info@javahaven.com</p>
      <p>Phone: (555) 123-4567</p>
      <p>Address: 123 Coffee Lane, Brewtown</p>
 </section>

  </main>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2025 Java Haven. All Rights Reserved.</p>
  </footer>
</body>
</html>
<style>/* Grid layout for overall page structure */
body {
  display: grid;
  grid-template-areas:
    "header"
    "nav"
    "main"
    "footer";
  grid-template-rows: auto auto 1fr auto;
  min-height: 100vh;
  margin: 0;
  font-family: "Segoe UI", Arial, sans-serif;
  background-color: #f5f0e6; /* warm coffee-inspired background */
  color: #3b2f2f;
}

/* Semi-transparent sections */
.header, .nav, .main-content, .footer, section {
  background-color: rgba(255, 250, 240, 0.9);
  padding: 20px;
  border-radius: 10px;
  margin: 10px;
}

/* Header */
.header {
  grid-area: header;
  text-align: center;
}

/* Navigation */
.nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 0;
  margin: 0;
}

.nav a {
  text-decoration: none;
  color: #3b2f2f;
  font-weight: bold;
}

.nav a:hover {
  color: #6f4e37;
}

/* Flexbox for coffee cards */
.flex-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  margin-top: 20px;
}

.flex-item {
  background-color: rgba(111, 78, 55, 0.85);
  color: #fff;
  padding: 30px;
  border-radius: 12px;
  width: 150px;
  text-align: center;
  font-weight: bold;
  font-size: 1.2em;
  box-shadow: 0 2px 5px rgba(0,0,0,0.3);
  transition: transform 0.2s ease;
}

.flex-item:hover {
  transform: scale(1.05);
}

/* Footer */
.footer {
  grid-area: footer;
  text-align: center;
}

/* Responsive Design */
@media (max-width: 600px) {
  .flex-container {
    flex-direction: column;
    align-items: center;
  }

  .flex-item {
    width: 80%;
  }
}
</style>
lab 8
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Button</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
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
    <button id="nameButton">Click Me!</button>
    <script>        
        
// Output your name using document.write
        document.write("Created by: Zeny Dobariya <br><br>");

// Select the button using its ID
        const button = document.getElementById("nameButton");

  // Add a click event listener to the button
        button.addEventListener("click", () => {
            // Prompt the user to enter their name
            const user = prompt("What is your name?");
            
  // If a name is entered, update the button text
            if (user) {
                button.textContent = `Hello, ${user}!`;
            } else {
                button.textContent = "Click Me!";
            }
        });
</script>
</body>
</html>

