## HTML Task to know usage of basic tags.

1. Fixed the bugs in give code snippet
```HTML
 <html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </div>
    </div>
</body>
</html>
```
---


2. Tried and Fixed the bugs in give code snippet

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<body>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </div>
    </div>
</body>
</html>
```
---


3. Designed a contact us form with all fields as required.
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <h1>Contact Us</h1>
        <form action="#" method="POST" class="contact-form">
            <div class="form-group">
                <label for="first-name">First Name:</label>
                <input type="text" id="first-name" name="first-name" required placeholder="Enter your first name">
            </div>
            <div class="form-group">
                <label for="last-name">Last Name:</label>
                <input type="text" id="last-name" name="last-name" required placeholder="Enter your last name">
            </div>
            <div class="form-group">
                <label for="email">Email Address:</label>
                <input type="email" id="email" name="email" required placeholder="Enter your email">
            </div>
            <div class="form-group">
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required placeholder="Enter your phone number">
            </div>
            <div class="form-group">
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required placeholder="Write your message here"></textarea>
            </div>
            <button type="submit" class="submit-btn">Submit</button>
        </form>
    </div>

</body>
</html>
```

```css

/* style.css */

body {
    font-family: Arial, sans-serif;
    background-color: #f4f7fc;
    margin: 0;
    padding: 0;
}

.container {
    width: 100%;
    max-width: 600px;
    margin: 50px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h1 {
    text-align: center;
    color: #333;
    margin-bottom: 30px;
}

.form-group {
    margin-bottom: 20px; 
}

label {
    font-weight: bold;
    color: #333;
    display: block;
    margin-bottom: 8px; 
}

input[type="text"],
input[type="email"],
input[type="tel"],
textarea {
    width: 100%;
    padding: 5px; 
    margin: 5px 0;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 14px;
}

::placeholder {
    color: #888;
}

.submit-btn {
    background-color: #4CAF50;
    color: white;
    padding: 12px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    width: 100%;
}

.submit-btn:hover {
    background-color: #45a049;
}
```
---

4.Used a certain HTML elements to display the following mentioned in question on a HTML page

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Programming Languages and Databases</title>
</head>
<body>
    <h1>Topics</h1>
    <ul>
        <li>Programming Language
            <ul>
                <li>JavaScript
                    <ol type="a">
                        <li>Angular</li>
                        <li>React</li>
                        <li>Vue.js</li>
                    </ol>
                </li>
                <li>Python
                    <ol type="a">
                        <li>Django Framework</li>
                        <li>Flask Framework</li>
                    </ol>
                </li>
                <li>Java
                    <ol type="a">
                        <li>Spring</li>
                        <li>Maven</li>
                        <li>Hibernate</li>
                    </ol>
                </li>
            </ul>
        </li>
        <li>Database
            <ul>
                <li>MySQL</li>
                <li>MongoDB</li>
                <li>Cassandra</li>
            </ul>
        </li>
    </ul>
</body>
</html>

```
---
5.Created an element that helps to open the https://google.com in separate new tab.

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Google in New Tab</title>
</head>
<body>
    <h1>Open Google</h1>
    <a href="https://google.com" target="_blank">Click here to open Google in a new tab</a>
</body>
</html>
```
---
6.Created a page and added two radio buttons with grouping them for employee type(Salaried and own business).

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Type Form</title>
</head>
<body>
    <h1>Employee Type Form</h1>
    <form>
        <label for="salaried">
            <input type="radio" id="salaried" name="employeeType" value="Salaried">
            Salaried
        </label>
        <br>
        <label for="ownBusiness">
            <input type="radio" id="ownBusiness" name="employeeType" value="OwnBusiness">
            Own Business
        </label>
        <br>
        <button type="submit">Submit</button>
    </form>
</body>
</html>
```
---
