#project name: webpage
#description: a simle webpage with css and html.

##Design:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EmpowerJobs - Inclusive Job Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #2c3e50;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .btn {
            background: #27ae60;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
        }
        .btn:hover {
            background: #219150;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>EmpowerJobs - Find Inclusive Opportunities</h1>
    </header>
    <div class="container">
        <h2>Search for Jobs</h2>
        <input type="text" placeholder="Enter job title or keyword">
        <select>
            <option>Choose Category</option>
            <option>IT & Software</option>
            <option>Customer Support</option>
            <option>Education</option>
            <option>Healthcare</option>
        </select>
        <button class="btn">Search</button>
    </div>
    <div class="container">
        <h2>Contact Us</h2>
        <input type="text" placeholder="Your Name">
        <input type="email" placeholder="Your Email">
        <textarea placeholder="Your Message" rows="4"></textarea>
        <button class="btn">Submit</button>
    </div>
</body>
</html>
