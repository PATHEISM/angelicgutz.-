<h1 align="center">______๑♡⁠๑______</h2>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=flohwalzer&label=ೀ&color=D93B50&style=square" alt="Profile Views"/>






![Profile GIF](https://cdn.imageurlgenerator.com/uploads/2f01b1c0-5b88-470d-b257-ab624a37413c.gif)




<p align="center">
  <a href="https://guns.lol/kittenclaws">GUNS</a> &nbsp;‎𔘓&nbsp; 
  <a href="https://en.pronouns.page/@puppydxlls">PRNS</a> &nbsp;‎𔘓&nbsp; 
  <a href="https://cybrangel.atabook.org/">ATA</a>

</p>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

  <meta name="viewport"
        content="width=device-width, initial-scale=1.0">

  <title>oomfs</title>

  <style>
    * {
      box-sizing: border-box;
    }

    html, body {
      margin: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;

      background: #000;
      color: white;

      font-family: Arial, sans-serif;
    }

    /* Whole game */
    #game {
      width: 100vw;
      height: 100vh;

      display: flex;
      justify-content: center;
      align-items: center;
    }

    /* --------------------
       START SCREEN
       -------------------- */

    #start {
      display: flex;
      align-items: center;

      gap: 40px;

      font-size: 72px;

      cursor: pointer;

      user-select: none;
    }

    /* White play triangle */
    .play {
      width: 0;
      height: 0;

      border-top: 28px solid transparent;
      border-bottom: 28px solid transparent;
      border-left: 48px solid white;
    }

    /* --------------------
       OOMF SCREEN
       -------------------- */

    #oomfs {
      display: none;

      width: 90%;
      max-width: 900px;

      text-align: center;

      font-size: 28px;

      line-height: 2;
    }

    /* GitHub mentions */
    #oomfs a {
      color: white;

      text-decoration: none;

      margin: 0 10px;
    }

    #oomfs a:hover {
      text-decoration: underline;
    }

    /* Little instruction */
    #message {
      display: none;

      position: absolute;

      bottom: 25px;

      width: 100%;

      text-align: center;

      color: #777;

      font-size: 14px;
    }
  </style>
</head>

<body>

  <div id="game">

    <!-- TAP SCREEN -->

    <div id="start" onclick="startGame()">

      <div class="play"></div>

      <span>tap</span>

    </div>


    <!-- OOMFS -->

    <div id="oomfs"></div>

    <div id="message">
      click a username to visit their GitHub
    </div>

  </div>


  <script>

    /*
      PUT YOUR OOMFS HERE.

      Only use their GitHub usernames.
      Don't include the @.
    */

    const oomfs = [
      "username1",
      "username2",
      "username3",
      "username4",
      "username5"
    ];


    function startGame() {

      // Hide the tap screen
      document.getElementById("start").style.display = "none";


      // Get the oomfs container
      const container = document.getElementById("oomfs");


      // Show it
      container.style.display = "block";


      // Add every oomf
      oomfs.forEach(function(username) {

        const link = document.createElement("a");


        // What people see
        link.textContent = "@" + username;


        // Where the link goes
        link.href = "https://github.com/" + username;


        // Open GitHub in a new tab
        link.target = "_blank";


        // Security
        link.rel = "noopener noreferrer";


        // Put the username on the page
        container.appendChild(link);

      });


      // Show instruction
      document.getElementById("message").style.display = "block";
    }

  </script>

</body>
</html>

<p align="center"><img width="74" height="18" alt="Hello-IMG1721006664316" src="https://github.com/user-attachments/assets/46bc3476-891b-4c90-88f7-cb328ff3bc77" /></p> 

<h1 align="center">︵︵︵ ๑ ♡ ๑ ︵︵︵</h2>


