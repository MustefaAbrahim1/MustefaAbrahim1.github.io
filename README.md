<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Habiibi Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            display: flex;
            background-color: #f4f4f9;
        }

        /* Sidebar */
        .sidebar {
            width: 250px;
            background-color: #1e1e2f;
            color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px 20px;
            min-height: 100vh;
        }

        .sidebar img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .sidebar h2 {
            margin: 10px 0;
            font-size: 1.5em;
        }

        .sidebar p {
            font-size: 0.9em;
            text-align: center;
        }

        .sidebar a {
            color: #00d4ff;
            text-decoration: none;
            margin: 5px 0;
            font-size: 0.95em;
        }

        .sidebar a:hover {
            text-decoration: underline;
        }

        /* Main Content */
        .main-content {
            flex: 1;
            padding: 40px;
        }

        .section {
            margin-bottom: 50px;
        }

        .section h1, .section h2 {
            color: #1e1e2f;
        }

        .projects, .experience, .education, .certifications {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .projects ul, .experience ul {
            list-style: none;
            padding-left: 0;
        }

        .projects li, .experience li {
            margin-bottom: 15px;
        }

        .section h2 {
            border-bottom: 2px solid #00d4ff;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <!-- Sidebar -->
    <div class="sidebar">
        <img src="profile.jpg" alt="Habiibi Profile Picture">
        <h2>Habiibi</h2>
        <p>Data Scientist | AI Engineer | ML & DL Expert</p>
        <a href="mailto:habibi@example.com">habibi@example.com</a>
        <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
    </div>

    <!-- Main Content -->
    <div class="main-content">
        <!-- About Me -->
        <div class="section" id="about">
            <h1>About Me</h1>
            <p>I am a Data Scientist and AI Engineer specializing in Machine Learning, Deep Learning, Big Data Analytics, and software development. I build intelligent systems and derive actionable insights from complex datasets.</p>
        </div>

        <!-- Research / Projects -->
        <div class="section" id="research">
            <h2>Research & Projects</h2>
            <div class="projects">
                <ul>
                    <li><strong>Stock Market Data Analysis Using ML Algorithms</strong> (Feb 2022 - May 2023) – Predicted stock market trends using Random Forest and SVM.</li>
                    <li><strong>Predictive Analytics for Health Insurance Sales</strong> (Jan 2023 - Mar 2023) – ML model predicting customer behavior using sentiment analysis.</li>
                    <li><strong>COVID-19 Detection from Radiological Images</strong> (Jan 2021 - Jun 2022) – Deep learning models (VGG16, ResNet50) achieving 98% accuracy.</li>
                    <li><strong>Kidney Stone Detection from CT scans</strong> (Jun 2023 - Jun 2024) – CNN ensemble model achieving 99.8% accuracy.</li>
                    <li><strong>NYC Parking Tickets Prediction (Big Data)</strong> (Feb 2023 - May 2023) – Spark & PySpark based predictive modeling.</li>
                </ul>
            </div>
        </div>

        <!-- Professional Experience -->
        <div class="section" id="experience">
            <h2>Professional Experience</h2>
            <div class="experience">
                <ul>
                    <li><strong>Business Data Analyst – Finlatics, India</strong> – Data analysis & visualization for strategic insights.</li>
                    <li><strong>Data Analysis & Visualization – RBCDSAI, India</strong> – Maternal health analytics & Power BI dashboards.</li>
                    <li><strong>Energy Mentors – US & IIT Ropar</strong> – Digital twin & hybrid energy modeling.</li>
                    <li><strong>Credit Card Fraud Detection – CodeClause, India</strong> – Logistic Regression with SMOTE, reduced false negatives.</li>
                    <li><strong>Software Development Intern – Internshala, India</strong> – JavaFX quiz game development.</li>
                    <li><strong>Web Development Intern – Internshala, India</strong> – Responsive HTML/CSS web development.</li>
                </ul>
            </div>
        </div>

        <!-- Education -->
        <div class="section" id="education">
            <h2>Education</h2>
            <div class="education">
                <ul>
                    <li>Master in Data Science and AI</li>
                    <li>Bachelor (Honours) in Computer Science</li>
                </ul>
            </div>
        </div>

        <!-- Certifications -->
        <div class="section" id="certifications">
            <h2>Certifications</h2>
            <div class="certifications">
                <ul>
                    <li>Google Data Analytics Professional Certificate</li>
                </ul>
            </div>
        </div>
    </div>

</body>
</html>
