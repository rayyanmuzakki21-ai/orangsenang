
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perkenalan Diri</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(135deg, #672020, #030038);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: rgb(255, 255, 255);
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            padding: 30px;
            border-radius: 20px;
            backdrop-filter: blur(10px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            text-align: center;
            width: 300px;
            animation: fadeIn 1.5s ease-in-out;
        }

        .card img {
            width: 100px;
            border-radius: 50%;
            border: 3px solid white;
            margin-bottom: 15px;
        }

        h1 {
            margin: 10px 0;
        }

        p {
            font-size: 14px;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: white;
            color: #150404;
            border-radius: 20px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }

        .btn:hover {
            background: #ff0000;
            color: white;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>

    <div class="card">
        <img src="https://id.pinterest.com/pin/1140466305654496751/" alt="Foto Profil">
        <h1>Hey Hey, Saya Faiz Rayyan</h1>
        <p>Saya seorang pelajar di SMK Nasional Depok.</p>
        <p>Hobi: Traveling | Riding | Belajar bahasa baru</p>
        <a href="https://www.instagram.com/_ymzki?igsh=N29qemViYjhtNnN3" class="btn" target="_blank">Instagram</a>
    </div>

</body>
</html>
