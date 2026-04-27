# Web-Technology-And-Mobile-Application
<!DOCTYPE html>
<html>
<head>
    <title>Chennai Map with Hotspots</title>

    <!-- External CSS -->
    <link rel="stylesheet" href="style.css">

    <!-- Embedded CSS -->
    <style>
        h1 {
            text-align: center;
            color: darkblue;
        }

        img {
            border: 3px solid black;
        }

        iframe {
            margin-top: 20px;
        }
    </style>
</head>

<body>

<h1>Chennai Map with Hotspots, Frames & Links</h1>

<!-- Inline CSS -->
<p style="color:green; font-size:18px;">Click the highlighted areas on the map.</p>

<!-- Map Image -->
<img src="https://upload.wikimedia.org/wikipedia/commons/3/32/Chennai_Map.png"
     usemap="#chennai" width="500">

<!-- Image Map -->
<map name="chennai">
    <area shape="rect" coords="50,50,150,150"
          href="https://en.wikipedia.org/wiki/Marina_Beach"
          target="frame">

    <area shape="rect" coords="200,50,300,150"
          href="https://en.wikipedia.org/wiki/T._Nagar"
          target="frame">
</map>

<br><br>

<!-- Links -->
<a href="https://www.chennaicorporation.gov.in" target="frame">Open Chennai Corporation Website</a>

<!-- Frame using iframe -->
<iframe name="frame" width="600" height="300"></iframe>

</body>
</html>
