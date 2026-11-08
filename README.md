
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Collage de GIFs</title>

    <style>
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        h1 {
            color: #333;
        }

        .collage {
            display: grid;
            grid-template-columns: repeat(2, 200px);
            grid-template-rows: repeat(2, 200px);
            gap: 10px;
            justify-content: center;
        }

        .collage img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 15px;
        }
    </style>
</head>

<body>

    <h1>Hi, I'm Lucas! Thanks to Miguel and Antonio</h1>

    <div class="collage">
        <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExODZ6MmZ4ZXdnenhkbXRvOTRmbXZneGp4eWF0b2ZkaWNpcjQ4ejdqYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/FY8c5SKwiNf1EtZKGs/giphy.gif" alt="Hola 1">

        <img src="https://i.giphy.com/LPFNd1AJBoYcVUExmE.webp" alt="Hola 2">

        <img src="https://i.giphy.com/UWERvU4Nzn1ExkPKTx.webp" alt="Hola 3">

        <img src="https://i.pinimg.com/originals/37/14/5f/37145f5666dc74c3634f6ac1cb895d8a.gif" alt="Hola 4">
    </div>

</body>
</html>

