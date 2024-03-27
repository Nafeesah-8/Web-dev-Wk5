# Web-dev-Wk5
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio</title>
    <style>
      header {
        background-color: rgba(12, 228, 12, 0.5);
        margin: 0 -10px;
      }
      .padding {
        padding: 15px;
        color: #ffffff;
      }
      #nav {
        background-color: rgb(207, 199, 199);
        margin: -19px -10px;
      }
      #ul {
        padding: 5px;
        text-decoration: none;
      }
      a {
        text-decoration: none;
        color: black;
        padding: 5px;
      }
      main {
        padding: 0 60px;
      }
      .ol {
        list-style-type: circle;
        margin-left: 20px;
      }
    </style>
  </head>
  <body>
    <header>
      <nav>
        <h3 class="padding">My portfolio</h3>
      </nav>
    </header>
    <nav id="nav">
      <ul id="ul">
        <a href="#">My bio</a>
        <a href="#">Project</a>
        <a href="#Skill">Skill</a>
        <a href="#">Contact me</a>
      </ul>
    </nav>
    <main>
      <br />
      <h3>About me</h3>
      <p>
        Greeting and welcome to my portfolio. <br />
        My name is Nafisah, a student at PLP
      </p>
      <h3>Project i have worked on:</h3>
      <ol>
        <li>Document management system</li>
        <li>Conceirge service management</li>
        <li>USSD meeting attendant system</li>
        <li>Spend management solution</li>
      </ol>
      <ul class="ol">
        <li>Payment Disbursement</li>
        <li>Collections</li>
      </ul>
      <h3>My Skills</h3>
      <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>Javascript</li>
        <li>Python</li>
        <li>Dart</li>
        <li>DataBase</li>
      </ul>
      <h3>Get in touch with me.</h3>
      <p>Email:<a href="kuforijinafisat8@gmail.com">kuforijinafisat8@gmail.com</a></p>
    </main>
    <footer>
      <p
        style="
          background-color: grey;
          margin: 15px -30px -30px -30px;
          padding: 15px;
          text-align: center;
        "
      >
        &copy; 2024, Nafeesah.
      </p>
    </footer>
  </body>
</html>
