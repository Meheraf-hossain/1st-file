# 1st-file
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="style.css" />
  <title>Browser</title>
  <style>
    @keyframes maruf{
      0% {
        background-color: green;
        left: 0px;
        top: 0px;
      }
      25% {
        background-color: red;
        left: 300px;
        top: 0px;
      }
      50% {
        background-color: yellow;
        left: 300px;
        top: 300px;
      }
      75% { 
        background-color: greenyellow;
        left: 0;
        top: 300px;
      }
      100% {
        background-color: green;
        left: 0;
        top: 0;
      }
    }
    .main {
      background-color: red;
      height: 300px; 
      width: 300px;
      margin-left:200px;
      margin-top: 30px;
      position: relative;
      animation: maruf 4s 2s infinite linear;
      box-shadow: 0px 0px 10px black;
    text-align:center;
    transition:2s;
    }
    button {
      background-color: cyan; 
      width: 100px;
      height: 40px;
      margin-left: 400px;
      margin-top: 350px;
      text-align: center;
      box-shadow: 0px 0px 2px blue;
    }
    button:hover {
      background-color: green;
    }
    .main:hover{
    transform: rotate(360deg);
    color:white;
    }
  </style>
</head>

<body>
  <div class="main"> hello i am maruf</div>
  <button onclick="showMessage()">Click Here</button>

  <script>
) {
      alert("Thanks for visiting this Web page");
    }
  </script>
</body>
</html>
