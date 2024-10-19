<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Change</title>
    <style>
        img {
            width: 100%;
            height: auto;
            cursor: pointer;
        }
    </style>
</head>
<body>

<img id="image" src="https://cloud-dso8iy25z-hack-club-bot.vercel.app/07777777777777.png" alt="Image" onclick="changeImage()">
<a href="https://hack.club/boba-manor" target="_blank">Open the door</a>

<script>
    function changeImage() {
        const image = document.getElementById('image');
        image.src = image.src === 'https://cloud-dso8iy25z-hack-club-bot.vercel.app/07777777777777.png' 
            ? 'https://cloud-oaah7vz1l-hack-club-bot.vercel.app/0capture999999.png'
            : 'https://cloud-dso8iy25z-hack-club-bot.vercel.app/07777777777777.png';
    }
</script>

</body>
</html>
