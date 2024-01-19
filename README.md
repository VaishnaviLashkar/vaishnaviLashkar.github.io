<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lashkar Vaishnavi - Professional Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 20px;
            line-height: 1.6;
            background: linear-gradient(to right, #4cb8c4, #3cd3ad, #28a19f);
            color: #333;
        }

        header {
            text-align: center;
            padding: 20px;
        }

        h1 {
            color: #007BFF;
            margin-bottom: 10px;
        }

        p {
            font-size: 16px;
            margin-bottom: 20px;
            text-align: left; /* Align the text to the left */
        }

        section {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            text-align: center; /* Center the content in the section */
        }

        .btn {
            display: inline-block;
            padding: 10px 15px;
            font-size: 16px;
            font-weight: bold;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px;
            transition: background-color 0.3s;
            position: relative;
        }

        .btn-primary {
            background-color: #007BFF;
            color: #fff;
            border: none;
        }

        .btn-secondary {
            background-color: #333;
            color: #fff;
            border: none;
        }

        .btn img {
            width: 100%; /* Set the width to 100% of the container */
            max-height: 40px;
            display: block;
            margin: 0 auto;
        }

        .btn:hover {
            background-color: #0056b3;
            border-color: #0056b3;
        }

        .btn-large {
            padding: 25px 40px;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            padding: 10px;
            background-color: #333;
            color: #fff;
            border-radius: 5px;
        }

        .transparent-bg {
            background: rgba(0, 0, 0, 0); /* Transparent background */
        }
    </style>
</head>

<body>
    <header>
        <h1>Lashkar Vaishnavi</h1>
        <p style="text-align: center;">Master's in Computer Science | Data Science Enthusiast</p>
    </header>
    <section class="transparent-bg">
        <img src="https://raw.githubusercontent.com/VaishnaviLashkar/vaishnaviLashkar.github.io/main/20231030_173646.jpg" alt="Image Description" style="width: 25%; max-height: 800px; margin-bottom: 10px; margin-left: 10px; margin-right: 10px;">
    </section>
    <section>
        <p>
            Hello Everyone,<br>

            I am Lashkar Vaishnavi, currently pursuing a master's degree in Computer Science at Old Dominion University. Hailing from the culturally rich city Hyderabad in southern India, known for its heritage, famous monuments, and thriving trade and commerce, I am proud to bring a diverse perspective to my academic journey. Completing my undergraduate studies, I come with three years of valuable experience as a System Engineer, contributing significantly to top multinational corporations.

            My professional odyssey has involved shaping technological landscapes, and I am thrilled to embark on this new academic venture. The decision to enroll in this course stems from my eagerness to delve into the realm of Data Science, aiming to get a good foundation of data science through this course because it seems like a great field of work and how data analysis can be used to shape future decisions and acquire valuable skills for exciting career opportunities in this dynamic field.

            Beyond the world of technology, I find joy in reading books and dancing, indulging in diverse interests that enrich my life. I'm genuinely excited about the learning journey ahead and look forward to a great semester with all of you.<br>

            Warm regards,<br>
            Lashkar Vaishnavi.
        </p>

        <div>
            <a href="#" id="downloadResume" class="btn btn-primary">Download Resume</a>
        </div>
    </section>
    <footer>
        <p style="text-align: center;">Connect with me on social media:</p>
        <div>
            <a href="https://www.linkedin.com/in/your-linkedin-profile" class="btn btn-secondary" target="_blank">
                <img src="https://pngimg.com/d/linkedIn_PNG24.png" alt="LinkedIn Logo">
            </a>
            <a href="mailto:vaishnavilashkar27@gmail.com" class="btn btn-secondary">
                <img src="https://th.bing.com/th/id/R.a26185e75fd12b01df8e024188cfce26?rik=rz2a%2f2gDT35FWg&riu=http%3a%2f%2fwww.computersupport.gr%2fimages%2femail_icon.png&ehk=oHbHDbsw1036Ch5I%2bCuNJu2CNPgMYZB%2bD%2fa1IBvMpvY%3d&risl=&pid=ImgRaw&r=0" alt="Mail Logo">
            </a>
        </div>
        <p style="text-align: center;">&copy; 2024 Lashkar Vaishnavi. All Rights Reserved.</p>

        <script>
            document.getElementById('downloadResume').addEventListener('click', function () {
                // Replace 'your-resume-url.pdf' with the actual URL of your resume
                var resumeUrl = 'https://github.com/VaishnaviLashkar/vaishnaviLashkar.github.io/blob/main/Vaishnavi%20resume%20(1).pdf';
                var a = document.createElement('a');
                a.href = resumeUrl;
                a.download = 'Lashkar_Vaishnavi_Resume.pdf'; // Change the downloaded file name if needed
                a.click();
            });
        </script>
    </footer>
</body>

</html>
