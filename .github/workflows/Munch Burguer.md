<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Much Burguer - Menú Digital</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            background-color: #000; /* Fondo negro */
            overflow-x: hidden;
            scroll-snap-type: y mandatory;
            color: #fff; /* Texto blanco */
        }

        section {
            width: 100%;
            height: 100%;
            scroll-snap-align: start;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        section img {
            max-width: 100%;
            height: auto;
        }

        /* Primera página con dos imágenes */
        .first-page {
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            align-items: center;
            padding: 20px;
        }

        .first-page img {
            margin-bottom: 20px;
        }

        /* Adaptación para imágenes que ocupan la pantalla completa */
        .full-page img {
            width: 100%;
            height: 100%;
            object-fit: contain;
        }
    </style>
</head>
<body>
    <!-- Primera página con dos imágenes -->
    <section class="first-page">
        <img src="Número tarjeta.jpeg" alt="Número de tarjeta" width="1004" height="251">
    </section>

    <!-- Página de Hamburguesas -->
    <section class="full-page">
        <img src="hamburguesas.jpeg" alt="Hamburguesas" width="131" height="1408">
    </section>

    <!-- Página de Salchipapas -->
    <section class="full-page">
        <img src="salchipapas.jpeg" alt="Salchipapas" width="1080" height="1495">
    </section>

    <!-- Página de Combo -->
    <section class="full-page">
        <img src="combo.jpeg" alt="Combo" width="1200" height="1500">
    </section>
</body>
</html>