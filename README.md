<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mcdonald's</title>
    <link rel="stylesheet" href="bootstrap.min.css" />
    <script src="bootstrap.bundle.min.js"></script>
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Ubuntu:ital@1&display=swap");
      * {
        font-family: "Ubuntu", sans-serif;
        margin: 0;
        padding: 0;
        
        
      }
      #header {
        display: flex;
        flex-wrap: wrap;
        text-align: right;
        text-decoration: none;
      }
      #partie {
        height: 30%;
        padding: 10%;
        text-align: center;
        font-size: 30px;
        color: black;

        border: 1px solid darkslategrey;
        border-radius: 10%;
        box-shadow: 2px 2px 2px;
      }
      a:hover {
        color: darkgoldenrod;
      }
      #partie:hover {
        color: white;
        background-color:black;
        
      }
      a {
        text-decoration: none;
        color: white;
        font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
      }
      ul {
        display: inline-block;
        list-style-type: none;
      }
      ul li {
        display: inline-block;
        margin-right: 30px;
      }
      
      .photo{
        background-color: rgba(0, 0, 0, 0.596);
        background-image: url(images/photomcd.jpg);
        margin: 0;
        padding: 0;
        background-size: cover; /* Pour s'assurer que l'image de fond couvre l'ensemble du corps */
        background-position: center; /* Pour centrer l'image de fond */
         background-repeat: no-repeat;/* Pour éviter la répétition de l'image de fond */ 
        height: 100vh;
       
      }
      .class{
        padding-left: 5%;
        padding-top: 10%;
        color: white;
    }
    #mac {
        text-align: center;
        font-size: smaller;
        color: gray;
      }
      .vid{
        height: 200px;
      }
    </style>
  </head>
  <body>
    <div class="container-fluid">
      <header>
        <div id="header" class="row bg-warning">
          <nav class="col-sm-3" style="text-align: left">
            <img
              src="images/logo mcd.png"
              width="15%"
            />
          </nav>
          <ul>
            <li><a class="col-sm-2" href="principal.html">homme</a></li>
            <li><a class="col-sm-2" href="#">contact</a></li>
            <li><a class="col-sm-2" href="help.html">help</a></li>
          </ul>
        </div>
      </header>
      <div class="photo">
        <h1 class="class">Bienvenue...</h1>
      </div>
      
      <tbody>
        <div class="row m-5">
          <a href="sandwitch.html" id="partie" class="col-sm-5 m-4">
            BURGERES
            <img
            src="images/c1aca198154ca8f23f650718bbdf867f5a85602a5f4af9cd12f2b2be2cfa7196.png"
              width="50%"
              alt="logo sandwitch"
            />
          </a>
          <a href="menus.html" id="partie" class="col-sm-5 m-4">
            MENUS UP
            <img
            src="images/1224169bcd7786a7247a21d1f3f66249f06df79c8c748828bc95d0a56c9aaa40.png"
              width="50%"
              alt="logo menu"
            />
          </a>
          <a href="biosson.html" id="partie" class="col-sm-5 m-4">
            BOISONS
            <img
              src="images/mlkchifraise.png"
              width="50%"
              alt="logo boisons"
            />
          </a>
          <a href="glace.html" id="partie" class="col-sm-5 m-4">
            GLACES
            <img
              src="images/kitkat.png"
              width="50%"
              alt="logo Glaces"
            />
          </a>
          <a href="salades.html" id="partie" class="col-sm-5 m-4">
            SALADES
            <img
              src="images/saladepechereur.png"
              alt="logo salade"
              width="50%"
            />
          </a>
          <a href="snakes.html" id="partie" class="col-sm-5 mt-3">
            snakes
            <img
              src="images/chickenbox.png"
              alt="logo"
              width="50%"
            />
          </a>
        </div>
      </tbody>
      <div class="vid">

      </div>
      <footer>
        <div>
          <p id="mac">Macdonald1@gmail.com</p1>
          <p id="mac">We have condition in our society....we respect that</p1>
          <p id="mac">thank you for reading</p1>
          <p id="mac">2023 Your Website. All rights reserved. | Inspired by
            McDonald's</p>
        </div>
      </footer>
    </div>
  </body>
</html>
