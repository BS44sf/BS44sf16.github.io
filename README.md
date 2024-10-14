<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bairon Suarez</title>
    <link rel="shortcut icon" href="favicon-32x32.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-image: url(fondo.jpg);
            color: #e0e0e0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1e1e1e;
            color: #00ffcc;
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            font-size: 3em;
        }
        nav {
            background-color: #00ffcc;
            padding: 10px 0;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #121212;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffcc00;
        }
        section {
            margin: 20px auto;
            padding: 20px;
            max-width: 900px;
            background-color: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.5);
        }
        section img {
            width: 100%;
            border-radius: 10px;
        }
        h2 {
            color: #00ffcc;
            font-size: 2em;
            margin-bottom: 10px;
        }
        p, li {
            font-size: 1.2em;
            line-height: 1.6em;
            color: #e0e0e0;
        }
        ul {
            list-style-type: square;
            margin-left: 20px;
        }
        .contact {
            text-align: center;
            margin-top: 20px;
        }
        .contact a {
            text-decoration: none;
            color: #00ffcc;
            font-weight: bold;
            border: 2px solid #00ffcc;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }
        .contact a:hover {
            background-color: #00ffcc;
            color: #121212;
        }
        .social-media {
            margin-top: 20px;
        }
        .social-media a {
            margin: 0 15px;
            text-decoration: none;
            color: #00ffcc;
            font-size: 2em;
            transition: color 0.3s;
        }
        .social-media a:hover {
            color: #ffcc00;
        }

    </style>
</head>
<body>

    <header>
        <h1>Bienvenido a mi portafolío</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre-mi">Sobre mí</a></li>
            <li><a href="#hobbies">Hobbies</a></li>
            <li><a href="#proyectos">Proyectos</a></li>
            <li><a href="#habilidades">Habilidades</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section id="sobre-mi">
        <h2>Sobre mí</h2>
        <img src="" alt="Imagen personal">
        <p>Hola, soy Bairon Suarez. Estudio desarrollo de aplicaciones multiplataforma en La Salle, y he decidido estudiar este grado superior con el objetivo de desarrollar una habilidad que me será útil para el cumplimiento de mis metas. Pero bueno así como tengo unas metas tambien tengo una pasiones, como lo es la pasión por la tecnología, la astronomía y el automovilismo.</p>
    </section>

    <section id="hobbies">
        <h2>Hobbies e intereses</h2>
        <img src="Imagen de WhatsApp 2024-10-04 a las 16.34.28_53f126aa.jpg" alt="Imagen sobre tus hobbies">
        <ul>
            <li>Programación</li>
            <li>Videojuegos</li>
            <li>Deportes</li>
            <li>Lectura</li>
        </ul>
    </section>

    <section id="proyectos">
        <h2>Proyectos</h2>
        <img src="DALL·E 2024-09-30 17.46.38 - A futuristic technology company headquarters in a vast metropolis. The building is ultra-modern, made of sleek glass and metal, with futuristic hologr.webp" alt="Imagen de proyecto">
        <p>Aquí puedes ver algunos de los proyectos que tengo a futuro</p>
        <ul>
            <li><strong>Proyecto 1:</strong>Crear una empresa dedicada a mejorar la vida de las personas</li>
            <li><strong>Proyecto 2:</strong></li>
        </ul>
    </section>

    <section id="habilidades">
        <h2>Habilidades</h2>
        <img src="" alt="">
        <p>Actualmente me encuentro en la fase de apredizaje de 3 lenguajes y esos son: java, html, css</p>
    </section>

    <section id="contacto" class="contact">
        <h2>Contacto</h2>
        <p>Si deseas contactarme, puedes enviarme un correo o llamarme a:</p>
        <a href="suarezbairon37@gmail.com">suarezbairon37@gmail.com</a>
        <a href="+34 643 14 68 42">+34 643 14 68 42</a>
    </section>
   
    <section class="social-media"></section>
        <h2>Sígueme en redes sociales</h2>
        <p>
            <a href="https://www.facebook.com/bairon.suarez.44?mibextid=ZbWKwL"><img src="https://cdn-icons-png.flaticon.com/256/124/124010.png" alt="HTML facebook" style="width:42px;height:42px;"></a>
            <a href="https://www.instagram.com/baironsv?utm_source=qr&igsh=MXJ1djd2bms4cnExag=="><img src="https://cdn-icons-png.flaticon.com/512/4138/4138124.png" alt="HTML instagram" style="width:42px;height:42px;"></a>
            <a href="https://x.com/Bairon_44?t=ptaRVtG5egAbhqr4HGsefg&s=08"><img src="https://img.freepik.com/vector-gratis/nuevo-diseno-icono-x-logotipo-twitter-2023_1017-45418.jpg" alt="HTML x" style="width:42px;height:42px;"></a>
        </p>
    </section>

    <footer>
        <p>&copy; 2024 - Bairon Suarez</p>
    </footer>

</body>
</html>
