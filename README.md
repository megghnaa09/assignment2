#project name: Webpage
##design: 


<!DOCTYPE html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>InclusiveHire - Job Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e3f2fd;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #1565c0;
            color: white;
            padding: 20px;
            font-size: 26px;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        .btn {
            background: #ff7043;
            color: white;
            padding: 12px 24px;
            border: none;
            cursor: pointer;
            font-size: 18px;
            border-radius: 5px;
        }
        .btn:hover {
            background: #e64a19;
        }
        input, select, textarea {
            width: 100%;
            padding: 12px;
            margin: 12px 0;
            border: 1px solid #ccc;
            border-radius: 6px;
        }
    </style>
</head>
<body>
    <header>
        <h1>InclusiveHire - Empowering Careers</h1>
    </header>
    <div class="container">
        <h2>Find Your Dream Job</h2>
        <input type="text" placeholder="Enter job title or keyword">
        <select>
            <option>Select Industry</option>
            <option>Technology</option>
            <option>Healthcare</option>
            <option>Education</option>
            <option>Finance</option>
        </select>
        <button class="btn">Search Jobs</button>
    </div>
    <div class="container">
        <h2>Get in Touch</h2>
        <input type="text" placeholder="Your Full Name">
        <input type="email" placeholder="Your Email Address">
        <textarea placeholder="Your Message" rows="5"></textarea>
        <button class="btn">Send Message</button>
    </div>
</body>
</html>
