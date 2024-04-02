
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Eid Mubarak 3D Animated Text</title>
<style>
  /* Style for the 3D text */
  .text-3d {
    font-family: Arial, sans-serif;
    font-size: 50px;
    text-align: center;
    color: #ffffff;
    text-transform: uppercase; /* Convert text to uppercase */
    animation: rotateText 5s infinite linear; /* Apply animation */
  }
  
  @keyframes rotateText {
    0% {
      transform: rotateX(0deg) rotateY(0deg) rotateZ(0deg); /* Initial rotation */
    }
    100% {
      transform: rotateX(360deg) rotateY(360deg) rotateZ(360deg); /* Rotate 360 degrees on all axes */
    }
  }
</style>
</head>
<body>
<h1 class="text-3d">Eid Mubarak</h1>
</body>
</html>
