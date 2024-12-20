<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tahmid Ramim</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .container {
            text-align: center;
            width: 80%;
            max-width: 800px;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        h1 {
            margin-bottom: 20px;
        }

        img {
            border-radius: 50%;
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 15px;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .social-icon {
            margin: 0 10px;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }

        .skill-badge {
            margin: 5px;
        }

        .projects {
            margin-top: 30px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th, td {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: left;
        }

        th {
            background-color: #f2f2f2;
        }

        a {
            color: #007bff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Custom CSS for more styling */
        /* ... */
    </style>
</head>
<body>
    <div class="container">
        <h1>Tahmid Ramim</h1>
        <img src="your_profile_picture.jpg" alt="Profile Picture" width="150">
        <p>Web Developer from Dhaka, Bangladesh.</p>
        <p>I spend most of my time coding projects and learning new tech stacks.</p>

        <div class="social-icons">
            <a href="#" class="social-icon"><img src="facebook_icon.svg" alt="Facebook"></a>
            <a href="#" class="social-icon"><img src="youtube_icon.svg" alt="YouTube"></a>
            <a href="#" class="social-icon"><img src="linkedin_icon.svg" alt="LinkedIn"></a>
            <a href="#" class="social-icon"><img src="instagram_icon.svg" alt="Instagram"></a>
            <a href="#" class="social-icon"><img src="twitter_icon.svg" alt="Twitter"></a>
            <a href="mailto:tahmidramim0@gmail.com" class="social-icon"><img src="gmail_icon.svg" alt="Gmail"></a>
        </div>

        <p><strong>I enjoy programming and making websites.</strong></p>
        <p><strong>Most used line of code:</strong> <code>console.log("Hello")</code></p>
        <p><strong>I am trying to find a good project idea.</strong></p>
        <p><strong>Reach me at:</strong> <a href="mailto:tahmidramim0@gmail.com">tahmidramim0@gmail.com</a></p>
        <p><strong>Fun fact:</strong> I started coding at the age of 14!</p>

        <div class="skills">
            <img src="javascript_badge.svg" alt="JavaScript" class="skill-badge">
            <img src="typescript_badge.svg" alt="TypeScript" class="skill-badge">
            <img src="react_badge.svg" alt="React" class="skill-badge">
            <img src="nextjs_badge.svg" alt="Next.js" class="skill-badge">
            <img src="nodejs_badge.svg" alt="Node.js" class="skill-badge">
            <img src="expressjs_badge.svg" alt="Express.js" class="skill-badge">
            <img src="mongodb_badge.svg" alt="MongoDB" class="skill-badge">
            <img src="tailwindcss_badge.svg" alt="Tailwind CSS" class="skill-badge">
        </div>

        <div class="projects">
            <h2>My Projects</h2>
            <table>
                <thead>
                    <tr>
                        <th>Project</th>
                        <th>Description</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><a href="https://github.com/Raaaaaaamim/NoteX" target="_blank">Project 1</a></td>
                        <td>A Note taking app</td>
                    </tr>
                    <tr>
                        <td><a href="#" target="_blank">Project 2</a></td>
                        <td>Another exciting project</td>
                    </tr>
                </tbody>
            </table>
        </div>

    </div>
</body>
</html>
