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






<!doctype html >
    <html lang="eng">
    <html>
        <header>
            <title>Registration Form</title>
            <h1>RegForm</h1>
        </header>
        <body>
            <img src="tutorial.jpg">
            <h5>Registration Form</h5>
<form>
    <table>
        <tr>
            <td>
                Name:
            </td>
            <td>
                <input type="text" placeholder="Enter your Name">
             </td>
             </tr>
             <tr>
             <td>
                Email:
             </td>
             <td>
                <input type="text" placeholder="Enter your Email">
             </td>
        </tr>
        <tr>
            <td>
                Password:
            </td>
            <td>
                <input type="text" placeholder="Enter your Password">
            </td>
        </tr>
        <tr>
            <td>
                Date of Birth:
            </td>
            <td>
                <select type="date">
                    <option value="day">Day</option>
                </td>
                <td>
                    <select type="month">
                    <option value="month">Month</option>
                    </td>
                    <td>
                        <select type="Year">
                    <option value="year">Year</option>
            </td>
        </tr>
    </table>
</form>
<u><h5>List of learners who should not fill the above form</h5></u>
<ol>
    <li>Kudus</li>
    <li>Ziyech</li>
    <li>Hazel</li>
    <li>Kalidou</li>
    <li>Hojland</li>
    <li>Celilia</l>
</ol>
<h5>Already captured details</h5>
<table>
    <thead>
        <th>Name</th>
        <th>Email</th>
        <th>Class</th>
        <th>Address</th>
    </thead>
    <tr>
        <td>John</td>
        <td>john@gmail.com</td>
        <td>grade4</td>
        <td>Nairobi</td>
    </tr>
    <tr>
        <td>Muli</td>
        <td>muli@gmail.com</td>
        <td>grade8</td>
        <td>Thika</td>
    </tr>
    <tr>
        <td>Mbuyu</td>
        <td>mbuyu@gmail.com</td>
        <td>PP1</td>
        <td>Molo</td>
    </tr>
    <tr>
        <td>Zuku</td>
        <td>zuku@gmail.com</td>
        <td>grade6</td>
        <td>Nyando</td>
    </tr>
    <tr>
        <td>Ndelta</td>
        <td>ndelta@gmail.com</td>
        <td>PP2</td>
        <td>Kakamega</td>
    </tr>
</table>
<p>Listen to the following audio for further directives</p>
<audio controls autoplay muted>
    <source src="youtube.com" type="audio/com">
</audio>
<p>Lastly, check your prefered dish here</p>
Eggs <input type="checkbox">
Meat <input type="checkbox">
Fish <input type="checkbox">
Beans <input type="checkbox">
Pizza <input type="checkbox">
<button type="submit"> Submit</button>
        </body>
        <footer>
@2025 data collection form
        </footer>
    </html>
