# garrisonschool
This is a simple web application for managing student information for [Your School Name]. The website allows administrators to view and update student details, including roll numbers and marks. It also provides a login system for students to access their personal information securely.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Management System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to Our School System</h1>
    </header>
    <main>
        <h2>Student Dashboard</h2>
        <p>View your marks, attendances, and more.</p>
    </main>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
}

main {
    padding: 20px;
}

h1, h2 {
    margin: 0;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Management System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Welcome to [Your School Name]</h1>
            <p>Student Management System</p>
        </div>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Student Portal</a></li
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

/* Container to centralize the content */
.container {
    width: 90%;
    margin: 0 auto;
    max-width: 1200px;
}

/* Header Section */
header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 40px 0;
}

header h1 {
    font-size: 3rem;
}

header p {
    font-size: 1.2rem;
}

/* Navigation Bar */
nav {
    background-color: #333;
    padding: 10px 0;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style-type: none;
}

nav ul li {
    margin: 0 20px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 1.1rem;
    text-transform: uppercase;
}

nav ul li a:hover {
    color: #4CAF50;
}

/* Main Content Section */
main {
    padding: 50px 0;
    background-color: white;
}

main h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

main p {
    font-size: 1.1rem;
    margin-bottom: 20px;
}

/* Features Section */
.features ul {
    list-style-type: none;
}

.features ul li {
    font-size: 1.2rem;
    margin: 10px 0;
}

/* Footer Section */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}

footer p {
    font-size: 1rem;
}

/* Responsive Design for Mobile */
@media only screen and (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }

    header p {
        font-size: 1rem;
    }

    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin: 10px 0;
    }

    main h2 {
        font-size: 2rem;
    }

    footer p {
        font-size: 0.9rem;
    }
}
<!-- Login Form -->
<section class="login">
    <h2>Student Login</h2>
    <form id="loginForm" action="#">
        <label for="studentID">Student ID</label>
        <input type="text" id="studentID" name="studentID" required>
        
        <label for="password">Password</label>
        <input type="password" id="password" name="password" required>
        
        <button type="submit">Login</button>
    </form>
</section>

<script>
// Simple Form Validation
document.getElementById("loginForm").addEventListener("submit", function(event) {
    const studentID = document.getElementById("studentID").value;
    const password = document.getElementById("password").value;

    if (studentID === "" || password === "") {
        alert("Both fields are required!");
        event.preventDefault();
    }
});
</script>
.hero {
    position: relative;
    width: 100%;
    height: 400px;
    background: url('hero-image.jpg') no-repeat center center/cover;
}

.hero-text {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 3rem;
}

.hero p {
    font-size: 1.5rem;
}
.hero {
    position: relative;
    width: 100%;
    height: 400px;
    background: url('hero-image.jpg') no-repeat center center/cover;
}

.hero-text {
    position: absolute;
    bottom: 20px;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    color: white;
}

.hero h1 {
    font-size: 3rem;
}

.hero p {
    font-size: 1.5rem;
}
/* Global Styles */
body {
    background-color: #4CAF50; /* Green background */
    color: white;  /* Change text color to white for better contrast */
    line-height: 1.6;
    font-family: 'Arial', sans-serif;
}


