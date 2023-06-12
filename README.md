<!DOCTYPE html>
<html>
<head>
  <title>What Time Is It?</title>
</head>
<body>
  <h1>The current time is:</h1>
  <p id="time"></p>
  <script>
    var currentTime = new Date();
    document.getElementById("time").innerHTML = currentTime.toLocaleString();
  </script>
</body>
</html>
