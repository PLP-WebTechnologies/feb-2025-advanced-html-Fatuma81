# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    
    <!-- Navigation Section -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <!-- Main Content Section -->
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of our website, where we introduce our content.</p>
        </section>
        
        <section id="about">
            <h2>About Us</h2>
            <p>Learn more about our mission and values.</p>
        </section>

        <!-- Ordered List with Roman Numerals -->
        <section>
            <h2>Ordered List</h2>
            <ol type="I">
                <li>First Item</li>
                <li>Second Item</li>
                <li>Third Item</li>
                <li>Fourth Item</li>
            </ol>
        </section>

        <!-- External Image from Pexels -->
        <section>
            <h2>Beautiful Scenery</h2>
            <img src="https://images.pexels.com/photos/1234567/pexels-photo-1234567.jpeg" alt="Scenic Landscape from Pexels" width="600">
        </section>

        <!-- Table of Contacts -->
        <section>
            <h2>Contact List</h2>
            <table border="1">
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
                <tr>
                    <td>John Doe</td>
                    <td>123 Main St</td>
                    <td>123-456-7890</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St</td>
                    <td>987-654-3210</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>Mike Johnson</td>
                    <td>789 Pine St</td>
                    <td>555-555-5555</td>
                    <td>mike@example.com</td>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>321 Oak St</td>
                    <td>444-444-4444</td>
                    <td>alice@example.com</td>
                </tr>
                <tr>
                    <td>Robert Green</td>
                    <td>654 Maple St</td>
                    <td>333-333-3333</td>
                    <td>robert@example.com</td>
                </tr>
            </table>
        </section>

        <!-- Registration Form -->
        <section>
            <h2>Registration Form</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>
                
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Enter a password" required><br><br>
                
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br><br>
                
                <label for="gender">Gender:</label><br>
                <input type="radio" id="male" name="gender" value="male" required>
                <label for="male">Male</label>
                <input type="radio" id="female" name="gender" value="female">
                <label for="female">Female</label>
                <input type="radio" id="other" name="gender" value="other">
                <label for="other">Other</label><br><br>
                
                <label for="country">Country:</label>
                <select id="country" name="country" required>
                    <option value="">Select your country</option>
                    <option value="usa">USA</option>
                    <option value="uk">UK</option>
                    <option value="canada">Canada</option>
                </select><br><br>
                
                <label>Interests:</label><br>
                <input type="checkbox" id="travel" name="interests" value="travel">
                <label for="travel">Travel</label>
                <input type="checkbox" id="sports" name="interests" value="sports">
                <label for="sports">Sports</label>
                <input type="checkbox" id="music" name="interests" value="music">
                <label for="music">Music</label><br><br>
                
                <input type="submit" value="Register">
            </form>
        </section>
    </main>
    
    <!-- Footer Section -->
    <footer>
        <p>Contact us at: <a href="mailto:info@example.com">info@example.com</a></p>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
</html>

