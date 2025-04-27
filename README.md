<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>I LOVE YOU</title>
    <style>
        body {
            text-align: center;
            margin-top: 100px;
            background-color: #ffe6e6;
            font-family: 'Arial', sans-serif;
        }
        #message {
            font-size: 50px;
            color: #ff3366;
            margin-top: 30px;
        }
        #loveImage {
            margin-top: 20px;
            width: 200px;
            display: none; /* รูปจะซ่อนไว้ก่อน */
        }
        button {
            padding: 10px 20px;
            font-size: 20px;
            background-color: #ff3366;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
        }
        button:hover {
            background-color: #ff6699;
        }
    </style>
</head>
<body>

    <button onclick="showLove()">Click me ❤️</button>

    <div id="message"></div>
    <img id="loveImage" src="heart.png" alt="Love Image">

    <script>
        function showLove() {
            document.getElementById('message').innerHTML = "I LOVE YOU";
            document.getElementById('loveImage').style.display = "block";
        }
    </script>

</body>
</html>
