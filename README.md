# Experiencia
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Profesional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        header {
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            margin: 5px 0;
            font-size: 1.2rem;
            color: #666;
        }
        .cv-section {
            width: 80%;
            max-width: 800px;
            margin: 20px auto;
            background: #fff;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .cv-section h2 {
            margin-top: 0;
            font-size: 1.8rem;
            color: #333;
        }
        .cv-content {
            font-size: 1rem;
            line-height: 1.6;
        }
        .social-links {
            margin-top: 20px;
            text-align: center;
        }
        .social-links a {
            margin: 0 10px;
            text-decoration: none;
            font-size: 1.2rem;
            color: #0077b5;
        }
        footer {
            margin-top: 30px;
            text-align: center;
            font-size: 0.9rem;
            color: #999;
        }
        .download-btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 15px;
            font-size: 1rem;
            color: #fff;
            background-color: #0077b5;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .download-btn:hover {
            background-color: #005f8a;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tomas Armas Alvear</h1>
        <p>Ingeniero comercial U de chile</p>
    </header>

    <section class="cv-section">
        <h2>Currículum Vitae</h2>
        <div class="cv-content">
            <p><strong>Experiencia Profesional:</strong></p>
            <ul>
                <li>Posición 1 - Empresa (Año de inicio - Año de término)</li>
                <li>Posición 2 - Empresa (Año de inicio - Año de término)</li>
            </ul>
            <p><strong>Educación:</strong></p>
            <ul>
                <li>Tu título universitario - Universidad (Año de graduación)</li>
            </ul>
        </div>
        <a href="cv.pdf" class="download-btn" download>Descargar CV</a>
    </section>

    <div class="social-links">
        <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        <a href="https://www.github.com" target="_blank">GitHub</a>
    </div>

    <footer>
        <p>© 2024 Tu Nombre. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
