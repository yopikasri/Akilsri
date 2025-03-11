


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Akil & Yopi's Wedding Invitation</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Akil & Yopi's Wedding Invitation</h1>
        <p>You are cordially invited to the wedding of</p>
        <h2>Akil & Yopi</h2>
        <p>Date: [Insert Date]</p>
        <p>Time: [Insert Time]</p>
        <p>Location: [Insert Location]</p>
        <button id="rsvp-button">RSVP</button>
    </div>
    <script src="script.js"></script>
</body>
</html>
```

CSS (in style.css file):
```
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

.container {
    width: 80%;
    margin: 40px auto;
    text-align: center;
}

h1 {
    font-size: 36px;
    color: #333;
}

h2 {
    font-size: 24px;
    color: #666;
}

button {
    background-color: #4CAF50;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #3e8e41;
}
```

JavaScript (in script.js file):
```
document.getElementById("rsvp-button").addEventListener("click", function() {
    alert("Thank you for RSVPing! We look forward to seeing you at the wedding.");
});
