
<body>
    <img src="src/logo.png" alt="logo">
    <div>
        <!-- <Image></Image> -->
        <h1>Welkom bij OBA!</h1>
        <h3>Log in or sign up</h3>
        <form action="/action_page.php">
          <input type="text" id="fname" name="firstname" placeholder="E-mailadres of telefoonnummer...">
          <input type="text" id="lname" name="lastname" placeholder="Wachtwoord...">
      
          <a href="https://lets-jam-webapplicatie-phi.vercel.app/" type="submit1">Log in</a>
          <a href="/sign-up" type="submit2">Sign up</a>
          <!-- <a href="/Sign-up">Sign up</a> -->
        </form>
      </div>
    </body>
    
      <style>
        :root {
            --oba-blue: #3C379E;

        }

        img {
           float: right;
        }

        body {
            background-color: #E3E9F9;
        }

        h1, h3 {
            color: white;
        }

        /* a {
            text-decoration: none;
            width: 20%;
      background-color: red;
      color: white;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
        } */
    input[type=text] {
      text-align: center;
      width: 100%;
      padding: 20px 20px;
      margin: 8px 0;
      display: inline-block;
      border: none;
      border-radius: 4px;
      box-sizing: border-box;
      background-color: #F5F5F5;
    }
    
    input[type=submit1] {
      width: 20%;
      background-color: white;
      color: black;
      font-weight: bold;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      text-align: center;
    }

    a {
    text-decoration: none;
      width: 20%;
      background-color: black;
      color: white;
      font-weight: bold;
      padding: 14px 20px;
      margin: 8px 0;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      text-align: center;
    }
    
    input[type=submit1]:hover {
      background-color: black;
      color: white;
    }
    
    input[type=submit2]:hover {
      background-color: white;
      color: black;
    }

    div {
      text-align: center;
      border-radius: 10px;
      background-color: var(--oba-blue);
      padding: 80px;
      width: 40em;
      height: 20em;
      position: absolute;
      top: 50%;
      left: 50%;
      margin-right: -50%;
      transform: translate(-50%, -50%);
    }
      </style>