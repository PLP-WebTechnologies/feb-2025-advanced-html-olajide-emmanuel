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
- 

Happy Coding! 💻✨


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment Page</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Python</li>
        <li>SQL</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>External Image from Pexels</h2>
    <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Scenery from Pexels" width="500">

    <!-- Table of Contacts -->
    <h2>Contact Information Table</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St, NY</td>
            <td>+1234567890</td>
            <td>john.doe@email.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>45 Elm St, CA</td>
            <td>+1987654321</td>
            <td>jane.smith@email.com</td>
        </tr>
        <tr>
            <td>Michael Brown</td>
            <td>78 Oak Ave, TX</td>
            <td>+1122334455</td>
            <td>michael.brown@email.com</td>
        </tr>
        <tr>
            <td>Emily White</td>
            <td>90 Pine Rd, FL</td>
            <td>+6677889900</td>
            <td>emily.white@email.com</td>
        </tr>
        <tr>
            <td>David Johnson</td>
            <td>32 Maple Ln, WA</td>
            <td>+5544332211</td>
            <td>david.johnson@email.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="submit.php" method="post">
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" minlength="6" required><br><br>

        <!-- Date of Birth Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown (Gender) -->
        <label for="gender">Gender:</label>
        <select id="gender" name="gender" required>
            <option value="">Select</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="other">Other</option>
        </select><br><br>

        <!-- Radio Buttons (Subscription Type) -->
        <p>Subscription Type:</p>
        <input type="radio" id="free" name="subscription" value="free" required>
        <label for="free">Free</label>

        <input type="radio" id="premium" name="subscription" value="premium" required>
        <label for="premium">Premium</label><br><br>

        <!-- Checkboxes (Interests) -->
        <p>Select Your Interests:</p>
        <input type="checkbox" id="coding" name="interests" value="coding">
        <label for="coding">Coding</label>

        <input type="checkbox" id="design" name="interests" value="design">
        <label for="design">Design</label>

        <input type="checkbox" id="marketing" name="interests" value="marketing">
        <label for="marketing">Marketing</label><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>

</body>
</html>

