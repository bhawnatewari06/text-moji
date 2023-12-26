<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div id="main">
        <h1>Text <span><img src="arrow.png" alt=""></span> Emojis</h1>
        <div id="endec-div">
            <h3 id="enc-btn"><span><img src="padlock-clipart-lock-icon-15.png" alt=""></span> Encrypt Text</h3>
            <h3 id="dec-btn"><span><img src="khula.jpeg" alt=""></span> Decrypt Emojis</h3>
        </div>
        <div id="encryption">
            <h5>1. Type a message</h5>
            <textarea placeholder="Write Something" name="" id="textmsg" cols="30" rows="10"></textarea>
            <h5>2. Set a password</h5>
            <input placeholder="eg:1234" type="password" name="" id="password">
            <h5>3. Encrypt message</h5>
            <button id="encrypt-btn"><span><img src="padlock-clipart-lock-icon-15.png" alt=""></span>Encrypt Text</button>
        </div>
        <div id="decryption">
            <h5>1. Paste encrypted message</h5>
            <textarea placeholder="Paste The Emojis" name="" id="emojimsg" cols="30" rows="10"></textarea>
            <h5>2. Type a password</h5>
            <input placeholder="eg:1234" type="password" name="" id="finalpassword">
            <h5>3. Decrypt Emojis</h5>
            <button id="decrypt-btn"><span><img src="./khula.jpeg" alt=""></span>Decrypt Text</button>
        </div>
        <div id="result">
        </div>
    </div>
    <script src="script.js"></script>
</body>

</html>

