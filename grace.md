<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
  <meta name="description" content="">
  <meta name="author" content="">
  <title>VIM PingPong</title>
  <link rel="icon" type="image/png" sizes="32x32" href="images/favicon.png">
  <style>
    body {
      font-family: monospace;
      background-color: lightgray;
    }
    .border-bottom,
    .border-left {
      position: fixed;
      background: grey;
      z-index: 5;
    }
    .border-bottom {
      left: 0;
      right: 0;
      height: 30px
    }
    .border-left {
      top: 0;
      bottom: 0;
      width: 30px
    }
    .border-bottom {
      bottom: 0
    }
    .border-left {
      left: 0
    }
    ul {
      list-style-type: none;
      padding: 10px;
      margin: 0;
      color: white;
    }
  </style>
</head>

<body>
  <span class="border-left">
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
      <li>4</li>
      <li>5</li>
    </ul>
  </span>
  <span class="border-bottom"></span>
</body>

</html>