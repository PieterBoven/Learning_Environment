# Learning_Environment
## CSS Animations
<!DOCTYPE html>

<html>

  <head>

    <style>
    @keyframes  anime {
0% {background-color: white;}
25% {background-color: blue;}
50% {background-color: red;}
75% {background-color: black;}
100% {background-color: white;}
}

html {
position: relative;
background-color: white;
animation-name: anime;
animation-duration: 6s;
animation-delay: 2s;
animation-iteration-count: infinite;
}

img {
  width: 200px;
  height: 250px;
  background-color: inherit;
  animation-name: mouse;
  animation-duration: 6s;
  animation-duration: infinite;
}

    </style>

  </head>

  <body>

    <img src="Biker Mouse.jpg">

  </body>

</html>
