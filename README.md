<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
</head>
<body>
    <h1>Formulario de Contacto</h1>
    <form action="procesar.php" method="post">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <label for="correo">Correo electrónico:</label>
        <input type="email" id="correo" name="correo" required>
        <label for="asunto">Asunto:</label>
        <input type="text" id="asunto" name="asunto" required>
        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" rows="5" required></textarea>
        <button type="submit">Enviar</button>
    </form>
</body>
</html>
