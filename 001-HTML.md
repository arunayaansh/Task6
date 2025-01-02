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
7.Sample Adhaar Card
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aadhaar Card</title>
    <link rel="stylesheet" href="Ques7.css">
</head>
<body>
    <div class="aadhaar-card">
        <div class="header">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Emblem_of_India.svg/376px-Emblem_of_India.svg.png" alt="Indian Emblem" class="emblem">
            <div class="govt-text">
                <p>இந்திய அரசாங்கம்</p>
                <p>Government of India</p>
            </div>
            <img src="https://upload.wikimedia.org/wikipedia/hi/thumb/c/cf/Aadhaar_Logo.svg/1200px-Aadhaar_Logo.svg.png" alt="Aadhaar Logo" class="aadhaar-logo">
        </div>
        <div class="photo-and-details">
            <div class="photo">
                <img src="https://www.shutterstock.com/image-vector/man-shirt-tie-businessman-avatar-600nw-548848999.jpg" alt="Photo">
            </div>
            <div class="details">
                <p>NAME: ArunPrakash</p>
                <p>DOB: 02/03/2001</p>
                <p>GENDER: Male</p>
            </div>
            <div class="qr-code">
                <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/QR_code_for_mobile_English_Wikipedia.svg" alt="QR Code">
            </div>
        </div>
        <div class="aadhaar-number">4444 3333 6666 8888</div>
        <div class="footer">
            <p>எனது ஆதார் எனது அடையாளம்</p>
        </div>
    </div>
</body>
</html>
```
```CSS
body {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f5f5f5;
    margin: 0;
    height: 100vh;
}

.aadhaar-card {
    width: 400px;
    border: 2px solid #000;
    border-radius: 8px;
    background-color: #fff;
    padding: 16px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.emblem {
    width: 40px;
}

.govt-text {
    text-align: center;
    font-size: 0.8rem;
}

.govt-text p:first-child {
    font-weight: bold;
}

.aadhaar-logo {
    width: 50px;
}

.photo-and-details {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 16px 0;
}

.photo img,
.qr-code img {
    width: 100px;
    height: 120px;
    border: 1px solid #000;
}

.details {
    text-align: left;
    font-size: 0.9rem;
}

.details p {
    margin: 4px 0;
}

.aadhaar-number {
    font-size: 1.2rem;
    font-weight: bold;
    margin: 16px 0;
}

.footer {
    border-top: 1px solid #000;
    padding-top: 8px;
    font-size: 0.9rem;
    color: #e53935;
    font-weight: bold;
}
```
---

8.Use the table tag and designed the given image
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Styled Table</title>
  <link rel="stylesheet" href="Ques8.css">
</head>
<body>
  <table>
    <thead>
      <tr>
        <th>Customer</th>
        <th>Item</th>
        <th>Quantity</th>
        <th>Price</th>
        <th>Date</th>
        <th>Payment</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="3">Customer Name</td>
        <td>Item1</td>
        <td>5</td>
        <td>$400.00</td>
        <td rowspan="2">12 Sep 2018</td>
        <td rowspan="2">$3,000.00</td>
      </tr>
      <tr>
        <td>Item2</td>
        <td>10</td>
        <td>$200.00</td>
      </tr>
      <tr>
        <td>Item3</td>
        <td>2</td>
        <td>$500.00</td>
        <td>18 Sep 2018</td>
        <td>$2,000.00</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
```

```CSS
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
  }
  
  table {
    width: 80%;
    margin: 20px auto;
    border-collapse: collapse;
    background: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  
  table, th, td {
    border: 1px solid black;
  }
  
  th, td {
    padding: 15px;
    text-align: center;
  }
  
  th {
    background-color: #f4f4f4;
    font-weight: bold;
  }
  
  td:first-child {
    font-weight: bold;
    text-align: left;
  }
  
  tbody tr:hover {
    background-color: #f1f1f1;
  }
  
  .split-cell {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%; 
    padding-top: 20px; 
    padding-bottom: 20px; 
  }
```
---
9/10/11. HTML input tags snippet to show default values for all Form elements also in the same HTML page add the below line and Highlight it without using any CSS
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form Elements with Default Values</title>
  <link rel="stylesheet" href="Ques9.css">
</head>
<body>
  <div class="form-container">
    <h1>Form with Default Values</h1>
    <p><mark>HTML & CSS is awesome</mark></p>  <!-- Ans for ques10 -->
    <form>

      <label for="text">Text Input:</label>
      <input type="text" id="text" name="text" value="Default Text"><br>


      <label for="password">Password:</label>
      <input type="password" id="password" name="password" value="password123"><br>


      <label for="email">Email:</label>
      <input type="email" id="email" name="email" value="example@example.com"><br>


      <label for="number">Number:</label>
      <input type="number" id="number" name="number" value="10" min="1" max="100"><br>


      <label for="date">Date:</label>
      <input type="date" id="date" name="date" value="2025-01-01"><br>


      <label for="color">Color:</label>
      <input type="color" id="color" name="color" value="#ff0000"><br>

      <label for="range">Range Slider:</label>
      <input type="range" id="range" name="range" value="50" min="0" max="100"><br>


      <label>Radio Buttons:</label>
      <div class="radio-group">
        <input type="radio" id="option1" name="radio" value="Option1" checked>
        <label for="option1">Option 1</label>
        <input type="radio" id="option2" name="radio" value="Option2">
        <label for="option2">Option 2</label>
      </div><br>


      <label>Checkboxes:</label>
      <div class="checkbox-group">
        <input type="checkbox" id="checkbox1" name="checkbox1" checked>
        <label for="checkbox1">Checkbox 1</label>
        <input type="checkbox" id="checkbox2" name="checkbox2">
        <label for="checkbox2">Checkbox 2</label>
      </div><br>

      <label for="dropdown">Dropdown:</label>
      <select id="dropdown" name="dropdown">
        <option value="Option1" selected>Option 1</option>
        <option value="Option2">Option 2</option>
      </select><br>

      <label for="textarea">Textarea:</label>
      <textarea id="textarea" name="textarea" rows="4" cols="50">Default Text in Textarea</textarea><br>

      <label for="file">File Upload:</label>
      <input type="file" id="file" name="file"><br>

      <input type="submit" value="Submit">
    </form>
  </div>
</body>
</html>
```
```css
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
  }
  
  .form-container {
    max-width: 600px;
    margin: 30px auto;
    padding: 20px;
    background: #ffffff;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  }
  
  h1 {
    text-align: center;
    color: #333;
  }
  
  form {
    display: flex;
    flex-direction: column;
  }
  
  label {
    margin: 10px 0 5px;
    font-weight: bold;
    color: #555;
  }
  
  input[type="text"],
  input[type="password"],
  input[type="email"],
  input[type="number"],
  input[type="date"],
  input[type="color"],
  input[type="range"],
  textarea,
  select {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }
  
  input[type="radio"],
  input[type="checkbox"] {
    margin-right: 5px;
  }
  
  .radio-group, .checkbox-group {
    display: flex;
    gap: 15px;
    margin-bottom: 15px;
  }
  
  input[type="submit"] {
    background-color: #4caf50;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 16px;
    cursor: pointer;
  }
  
  input[type="submit"]:hover {
    background-color: #45a049;
  }
  
  textarea {
    resize: vertical;
  }
  
  @media (max-width: 600px) {
    .form-container {
      padding: 15px;
    }
  
    input[type="text"],
    input[type="password"],
    input[type="email"],
    input[type="number"],
    input[type="date"],
    input[type="color"],
    input[type="range"],
    textarea,
    select {
      font-size: 14px;
    }
  
    input[type="submit"] {
      font-size: 14px;
    }
  }
```
---

