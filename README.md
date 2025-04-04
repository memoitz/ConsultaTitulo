<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proceso de Titulación</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Proceso de Titulación</h1>
        <p>Consulta y accede a tu proceso de titulación</p>
    </header>

    <section id="formulario">
        <h2>Solicitar Titulación</h2>
        <form id="form-titulacion">
            <label for="cedula">Cédula de Identidad:</label>
            <input type="text" id="cedula" name="cedula" required>

            <label for="nombre">Nombre Completo:</label>
            <input type="text" id="nombre" name="nombre" required>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <section id="informacion">
        <h2>Más Información</h2>
        <a href="enlace_descarga.pdf" target="_blank">Descargar Instrucciones</a>
    </section>

    <script src="script.js"></script>
</body>
</html>
