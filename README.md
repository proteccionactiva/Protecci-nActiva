# Protecci-nActiva
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protección Activa - Déjanos tus datos</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
        
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #eef1f5;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        h2 {
            font-family: 'Bebas Neue', sans-serif;
            color: #0d3b66;
            font-size: 28px;
            margin-bottom: 5px;
        }
        p {
            font-family: 'Roboto', sans-serif;
            font-size: 16px;
            color: #555;
            margin-top: 0;
        }
        input, select, button {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px auto;
            border: 1px solid #ccc;
            border-radius: 5px;
            display: block;
        }
        button {
            background-color: #0d3b66;
            color: white;
            border: none;
            cursor: pointer;
            width: calc(100% - 20px);
        }
        button:hover {
            background-color: #12507c;
        }
        .footer-text {
            font-family: 'Roboto', sans-serif;
            font-size: 14px;
            color: #0d3b66;
            font-weight: bold;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>DÉJANOS TUS DATOS</h2>
        <p>Nos contactaremos contigo a la brevedad.</p>
        <form action="https://formsubmit.co/proteccionactiva@gmail.com" method="POST">
            <input type="text" name="nombre" placeholder="Nombre" required>
            <input type="tel" name="telefono" placeholder="Número de Teléfono" required pattern="[0-9]+">
            <select name="departamento" required style="width: calc(100% - 20px);">
                <option value="">Selecciona tu departamento</option>
                <option value="Artigas">Artigas</option>
                <option value="Canelones">Canelones</option>
                <option value="Cerro Largo">Cerro Largo</option>
                <option value="Colonia">Colonia</option>
                <option value="Durazno">Durazno</option>
                <option value="Flores">Flores</option>
                <option value="Florida">Florida</option>
                <option value="Lavalleja">Lavalleja</option>
                <option value="Maldonado">Maldonado</option>
                <option value="Montevideo">Montevideo</option>
            </select>
            <button type="submit">Enviar</button>
            <div class="footer-text">PROTECCIÓN ACTIVA</div>
        </form>
    </div>
</body>
</html>
