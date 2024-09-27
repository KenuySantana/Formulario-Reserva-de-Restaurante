<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reserva de Restaurante FMU</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #e9ecef;
            margin: 0;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            text-align: center;
        }
        img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        label {
            display: block;
            margin: 10px 0 5px;
            color: #555;
            text-align: left;
        }
        input, select {
            width: 100%;
            padding: 12px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            transition: border 0.3s;
        }
        input:focus, select:focus {
            border: 1px solid #5cb85c;
            outline: none;
        }
        button {
            background-color: #5cb85c;
            color: white;
            border: none;
            padding: 12px;
            cursor: pointer;
            border-radius: 5px;
            width: 100%;
            font-size: 16px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #4cae4c;
        }
        .contato {
            margin-top: 20px;
            color: #777;
        }
        .footer {
            margin-top: 30px;
            font-size: 14px;
            color: #aaa;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Reserva de Restaurante FMU</h1>
    <img src="https://servircomrequinte.francobachot.com.br/wp-content/uploads/2020/08/post_thumbnail-5119340b39b314917440ed22562078eb.jpg" alt="Restaurante">
    
    <form>
        <label for="nome">Nome</label>
        <input type="text" id="nome" name="nome" placeholder="Seu nome" required>

        <label for="data">Data da Reserva</label>
        <input type="date" id="data" name="data" required>

        <label for="hora">Hora da Reserva</label>
        <input type="time" id="hora" name="hora" required>

        <label for="pessoas">Número de Pessoas</label>
        <select id="pessoas" name="pessoas" required>
            <option value="1">1</option>
            <option value="2">2</option>
            <option value="3">3</option>
            <option value="4">4</option>
            <option value="5">5</option>
            <option value="6">6</option>
            <option value="7">7</option>
            <option value="8">8</option>
            <option value="9">9</option>
            <option value="10">10</option>
        </select>

        <label for="telefone">Telefone</label>
        <input type="tel" id="telefone" name="telefone" placeholder="(xx) xxxxx-xxxx" required>

        <button type="submit">Reservar</button>
    </form>

    <div class="contato">
        <p>Contato: (11) 1234-5678</p>
        <p>Email: contato@restauranteFMU.com</p>
    </div>

    <div class="footer">
        <p>&copy; 2024 Restaurante FMU. Todos os direitos reservados.</p>
    </div>
</div>

</body>
</html>
