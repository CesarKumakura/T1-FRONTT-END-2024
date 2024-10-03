# T1-FRONTT-END-2024

# Integrante do Projeto 

Nome: César Shoity Kumakura
RA: 23.01564-0

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Livros</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 600px;
        }
        h1 {
            text-align: center;
            color: #333;
            border-bottom: 1px solid black;
        }
        .livro {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            padding: 10px;
            border-bottom: 1px solid #ccc;
            border: 1px solid black;
        }
        .livro:last-child {
            border-bottom: none;
        }
        .titulo {
            font-weight: bold;
            color: black; 
        }
        .autor {
            color: black;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Livros</h1>
        <div class="livro">
            <div class="titulo">Grafic Design</div>
            <div class="autor">Jenns Muller</div>
            <img src="https://images.pexels.com/photos/3747260/pexels-photo-3747260.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Livro 1"
            width="160px" height="160px">
        </div>
        <div class="livro">
            <div class="titulo">Vestules Naktssargam</div>
            <div class="autor">Sandra Vensko</div>
            <img src="https://images.pexels.com/photos/3309957/pexels-photo-3309957.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Livro 1"
            width="160px" height="160px"> 
        </div>
    </div>
</body>
</html>
