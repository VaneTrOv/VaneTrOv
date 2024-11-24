<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV de Vanessa </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 30px 10px;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 10px 0 0;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        section {
            margin-bottom: 20px;
        }
        section h2 {
            color: #4CAF50;
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 5px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            background-color: #f1f1f1;
            padding: 10px;
            margin-top: 20px;
            font-size: 0.9em;
        }
        .contact a {
            margin: 0 10px;
            text-decoration: none;
            color: #4CAF50;
        }
        .photo {
            text-align: center;
            margin-bottom: 20px;
        }
        .photo img {
            max-width: 150px;
            border-radius: 50%;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <!-- Página de Inicio -->
    <header>
        <h1>Vanessa Troche</h1>
        <p>Estudiante de Ingeniería Mecatronica</p>
    </header>
    <div class="container">
        <!-- Introducción -->
        <section class="intro">
            <h2>Sobre Mí</h2>
            <p>Estoy estudiando Ingeniería en Mecatrónica, una carrera que me apasiona porque combina muchas áreas que me interesan como la Inteligencia Artificial, la robótica, la automatización y el diseño de sistemas integrados. Lo que más me motiva es participar en proyectos donde pueda usar la tecnología de manera creativa para resolver problemas del día a día. Siempre estoy buscando aprender algo nuevo y enfrentar retos que me hagan crecer.</p>
        </section>
        <!-- Foto -->
        <section class="photo">
            <img src="https://drive.google.com/drive/u/1/home" alt="Foto">
        </section>
        <!-- Habilidades -->
        <section class="skills">
            <h2>Habilidades</h2>
            <ul>
                <li>Python, C++, Machine Learning</li>
                <li>Data Analysis, Pandas, NumPy</li>
                <li>Scikit-Learn, Optuna</li>
                <li>Git, GitHub</li>
            </ul>
        </section>
        <!-- Educación -->
        <section class="education">
            <h2>Educación</h2>
            <ul>
                <li>
                    <strong>Ingeniería Mecatronica</strong> - Universidad Nacional de Asuncion (2018 - Presente)
                </li>
                <li>
                    <strong>Bachillerato cientifico con énfasis en ciencias basicas - Centro Educativo Cristiano Canaan (2000 - 2015)
                </li>
            </ul>
        </section>
        <!-- Proyecto de IA -->
        <section class="project">
            <h2>Deteccion y clasificacion de mosquitos</h2>
            <p>Es de vital importancia para mejorar la salud pública, optimizar los programas de control, monitorear los efectos del cambio climático y comprender mejor los roles ecológicos de estas especies. Su correcta gestión puede salvar vidas y proteger ecosistemas</p>
            <ul>
                <li><strong>Dataset:</strong> Los datos utilizados fueron imágenes en formato jpg, una cantidad de 100 imagenes, y dos tipos de clases, una para los mosquitos machos y otra para los mosquitos hembra</li>
                <li><strong>Modelo:</strong> Roboflow YOLOv8</li>
                <li><strong>Visualización:</strong> 
                  <a href="https://app.roboflow.com/vane/clasificador-de-mosquitos/2" target="_blank"></a>.
                </li>
            </ul>
            <p>Ver más detalles en el repositorio: 
                <a href="https://github.com/VaneTrOv/Proyecto-IA" target="_blank">GitHub</a>
            </p>
        </section>
        <!-- Contacto -->
        <section class="contact">
            <h2>Contacto</h2>
            <p>Encuéntrame en:</p>
            <p>
                <a href="https://github.com/VaneTrOv" target="_blank">GitHub</a>
                <a href="vanessatroche08@gmail.com">Correo</a>
            </p>
        </section>
    </div>
    <!-- Pie de página -->
    <footer>
        <p>Creado con ❤️ por Vane | <a href="https://github.com/VaneTrOv" target="_blank">GitHub</a></p>
    </footer>
</body>
</html>
