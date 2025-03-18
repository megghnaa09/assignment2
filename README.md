#name: WEBPAGE
#description: a simple webpage using html and css.
## design:

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
        nav {
            background: #0d47a1;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
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
        .jobs {
            text-align: left;
        }
        .job-listing {
            border: 1px solid #ccc;
            padding: 15px;
            border-radius: 6px;
            margin: 10px 0;
        }
        .footer {
            background: #0d47a1;
            color: white;
            padding: 15px;
            margin-top: 20px;
        }
        .footer a {
            color: #ffcc80;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>InclusiveHire - Empowering Careers</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Jobs</a>
        <a href="#">Contact</a>
    </nav>

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

    <div class="container jobs">
        <h2>Latest Job Listings</h2>
        <div class="job-listing">
            <h3>Web Developer</h3>
            <p>Company: Tech Solutions</p>
            <p>Location: Remote</p>
            <button class="btn">Apply Now</button>
        </div>
        <div class="job-listing">
            <h3>Customer Support</h3>
            <p>Company: CareCorp</p>
            <p>Location: New York, NY</p>
            <button class="btn">Apply Now</button>
        </div>
        <div class="job-listing">
            <h3>Graphic Designer</h3>
            <p>Company: Creative Agency</p>
            <p>Location: Los Angeles, CA</p>
            <button class="btn">Apply Now</button>
        </div>
    </div>

    <div class="container">
        <h2>Get in Touch</h2>
        <input type="text" placeholder="Your Full Name">
        <input type="email" placeholder="Your Email Address">
        <textarea placeholder="Your Message" rows="5"></textarea>
        <button class="btn">Send Message</button>
    </div>

    <div class="footer">
        <p>Contact us at <a href="mailto:support@inclusivehire.com">support@inclusivehire.com</a></p>
        <p>Follow us on <a href="#">Facebook</a> | <a href="#">Twitter</a> | <a href="#">LinkedIn</a></p>
    </div>

</body>
</html>
