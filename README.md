# Ex01 Portfolio
## Date:02/02/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(120deg, #f6f9ff, #e9f0ff);
        }

        /* Header */
        .header {
            text-align: center;
            padding: 30px;
            background-color: #2b3cff;
            color: white;
        }

        /* Tabs */
        .tabs {
            display: flex;
            justify-content: center;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .tabs button {
            background: none;
            border: none;
            padding: 15px 30px;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s;
        }

        .tabs button:hover {
            color: #2b3cff;
        }

        .tabs button.active {
            border-bottom: 3px solid #2b3cff;
            color: #2b3cff;
            font-weight: bold;
        }

        /* Content cards */
        .content {
            display: none;
            max-width: 800px;
            margin: 40px auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
        }

        .content h2 {
            color: #2b3cff;
        }

        .content.active {
            display: block;
        }

        footer {
            text-align: center;
            padding: 15px;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Abisheik Raj</h1>
        <p>Student | AI & Data Science</p>
    </div>

    <div class="tabs">
        <button class="tab-btn active" onclick="openTab('home', this)">Home</button>
        <button class="tab-btn" onclick="openTab('about', this)">About</button>
        <button class="tab-btn" onclick="openTab('contact', this)">Contact</button>
    </div>

    <div id="home" class="content active">
        <h2>Welcome</h2>
        <p>
            Hi! 👋  
            This is my personal portfolio website where I showcase my skills and interests.
        </p>
    </div>

    <div id="about" class="content">
        <h2>About Me</h2>
        <p>
            I am a B.Tech AI & Data Science student.  
            Currently learning programming, data science, and web development.
        </p>
    </div>

    <div id="contact" class="content">
        <h2>Contact</h2>
        <p>Email: abisheikjar@email.com</p>
        <p>LinkedIn: linkedin.com/in/AbisheikRaj</p>
    </div>

    <footer>
        © 2026 My Portfolio
    </footer>

    <script>
        function openTab(tabName, element) {
            let contents = document.getElementsByClassName("content");
            let buttons = document.getElementsByClassName("tab-btn");

            for (let i = 0; i < contents.length; i++) {
                contents[i].classList.remove("active");
                buttons[i].classList.remove("active");
            }

            document.getElementById(tabName).classList.add("active");
            element.classList.add("active");
        }
    </script>

</body>
</html>

```
## OUTPUT
<img width="1902" height="1084" alt="Screenshot 2026-02-02 113444" src="https://github.com/user-attachments/assets/3acba6ee-6511-4191-a116-20ccf578ee36" />
<img width="1915" height="1085" alt="Screenshot 2026-02-02 113455" src="https://github.com/user-attachments/assets/31602cc7-21dd-478e-8c25-f219e8c2380e" />
<img width="1906" height="1082" alt="Screenshot 2026-02-02 113515" src="https://github.com/user-attachments/assets/89b3e1cf-7c23-4a5c-b4c0-49b1653ccabd" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
