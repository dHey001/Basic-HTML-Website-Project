https://roadmap.sh/projects/basic-html-website

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Basic html website</title>
    <style>
      body {
        border: 2px solid black;
        font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
        max-width: 700px;
        padding: auto;
        margin: auto;
      }

      .header {
        padding: 20px;
        display: flex;
        justify-content: space-between;
      }

      .div {
        display: block;
        margin-bottom: 60px;
      }

      .span2 {
        font-family: monospace;
        text-align: center;
        margin-top: 80px;
        display: block;
        font-size: 40px;
      }

      .span3 {
        font-family: monospace;
        text-align: center;
        display: block;
      }

      .container {
        border-top: 2px solid black;
        border-bottom: 2px solid black;
        display: flex;
      }

      .hero {
        width: 30%;
        box-sizing: border-box;
        border-right: 2px solid black;
      }

      .hero:last-child {
        border-right: none;
      }

      .type {
        font-weight: bold;
        padding-left: 20px;
      }

      .d {
        padding-left: 20px;
      }

      .w {
        border-top: 2px solid black;
        padding-top: 10px;
        padding-left: 20px;
      }

      .e {
        padding-left: 20px;
      }

      .g {
        border-top: 2px solid black;
        padding-left: 20px;
        padding-top: 15px;
        font-weight: bold;
      }

      .f {
        font-weight: bold;
        padding-left: 20px;
        margin-top: 30px;
      }

      .section {
        display: flex;
        justify-content: space-between;
        padding: 20px;
      }

      .b {
        padding: 10px;
        margin: 10px;
        border: 2px solid black;
        border-radius: 10px;
      }

      .footer {
        display: block;
        text-align: center;
        margin-top: 70px;
      }
    </style>
  </head>
  <body>
    <!-- header -->
    <header class="header">
      <span class="span">Your name</span>
      <nav class="nav">
        <a href="#home" class="a">Home</a> /
        <a href="#projects" class="a">Projects</a> /
        <a href="#articles" class="a">Articles</a> /
        <a href="#contact" class="a">Contact</a>
      </nav>
    </header>

    <!-- description -->
    <div class="div">
      <span class="span2">Frontend Developer</span>
      <span class="span3">html only with proper layout, no styling</span>
    </div>

    <!-- table -->

    <div class="container">
      <div class="hero">
        <p class="type">Projects</p>
        <p class="d">HTML Only Portfolio</p>
        <p class="w">Calculator</p>
        <p class="w">Quiz App</p>
        <p class="w">Countdown Timer</p>
        <p class="w">Product Upcoming Page</p>
      </div>

      <div class="hero">
        <p class="type">Work Experience</p>
        <p class="e">roadmap.sh</p>
        <p class="e">Solved all the frontend problems</p>
        <p><a href="" class="e">Visit my profile</a></p>
        <p class="g">Opensource Work</p>
        <p class="e">
          Contributed to 50 opensource <br />
          projects. Made my own projects with <br />
          200 Github Stars.
        </p>
        <p class="e"><a href="">Visit my Github Profile</a></p>
      </div>

      <div class="hero">
        <p class="type">Education</p>
        <p class="e">
          Graduated with 3.76 out 4 <br />
          CGPA. Won Acme Hackathon. <br />
          Organized 30 sessions.
        </p>
        <p class="e">Courses I took:</p>
        <ul>
          <li>Object Oriented Programming</li>
          <li>Data Structures and Algorithm</li>
          <li>Web Engineering</li>
          <li>Artificial Intelligence</li>
          <li>Human Computer Interation</li>
          <li>Computer Graphics</li>
          <li>Database Management Systems</li>
          <li>Distributed Database Systems</li>
          <li>Discrete Mathematics</li>
        </ul>
      </div>
    </div>

    <p class="f">Reviews from my Teachers</p>
    <section class="section">
      <div class="b">
        <p>
          John doe was brilliant student; always stood out with his assignments.
        </p>
        <p>
          Jane Doe <br />
          Assistant Professor
        </p>
      </div>

      <div class="b">
        <p>
          John doe was brilliant student; always stood out with his assignments.
        </p>
        <p>
          Jane Doe <br />
          Assistant Professor
        </p>
      </div>

      <div class="b">
        <p>
          John doe was brilliant student; always stood out with his assignments.
        </p>
        <p>
          Jane Doe <br />
          Assistant Professor
        </p>
      </div>
    </section>

    <footer class="footer">
      <p>&copy all rights reserved 2025</p>
    </footer>
  </body>
</html>
