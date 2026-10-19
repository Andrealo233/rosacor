# rosacor
html, css, python
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rosa Milena Hinestroza Córdoba - Automatización y Software</title>
    <style>
        :root {
            --bg-color: #12100e;
            --card-bg: #1a1714;
            --accent-color: #d4a373;
            --text-main: #f5f3ef;
            --text-muted: #b0a89f;
        }
        body {
            margin: 0;
            padding: 0;
            background-color: var(--bg-color);
            color: var(--text-main);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .container {
            max-width: 1000px;
            width: 100%;
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            display: grid;
            grid-template-columns: 1fr 1.5fr;
            overflow: hidden;
            border: 1px solid rgba(212, 163, 115, 0.2);
        }
        .left-column {
            background: linear-gradient(135deg, #1f1b17, #12100e);
            padding: 40px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            border-right: 1px solid rgba(212, 163, 115, 0.1);
        }
        .profile-img {
            width: 160px;
            height: 160px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid var(--accent-color);
            margin-bottom: 20px;
        }
        .left-column h1 {
            font-size: 1.4rem;
            margin: 10px 0 5px;
            color: var(--text-main);
            letter-spacing: 1px;
        }
        .left-column h2 {
            font-size: 0.85rem;
            color: var(--accent-color);
            text-transform: uppercase;
            margin-bottom: 20px;
        }
        .contact-info, .skills-section {
            width: 100%;
            text-align: left;
            margin-top: 20px;
        }
        .contact-info h3, .skills-section h3 {
            font-size: 0.9rem;
            color: var(--accent-color);
            border-bottom: 1px solid rgba(212, 163, 115, 0.3);
            padding-bottom: 5px;
            margin-bottom: 10px;
        }
        .contact-info p, .skills-section ul {
            font-size: 0.85rem;
            color: var(--text-muted);
            margin: 5px 0;
        }
        .skills-section ul {
            padding-left: 15px;
        }
        .right-column {
            padding: 40px;
        }
        .section-title {
            font-size: 1.1rem;
            color: var(--accent-color);
            text-transform: uppercase;
            letter-spacing: 1.5px;
            margin-bottom: 10px;
            border-bottom: 2px solid var(--accent-color);
            padding-bottom: 5px;
        }
        .right-column p {
            font-size: 0.9rem;
            color: var(--text-muted);
            line-height: 1.6;
            margin-bottom: 25px;
        }
        .experience-item, .education-item {
            margin-bottom: 20px;
        }
        .experience-item h4, .education-item h4 {
            margin: 0 0 5px;
            font-size: 0.95rem;
            color: var(--text-main);
        }
        .experience-item span, .education-item span {
            font-size: 0.8rem;
            color: var(--accent-color);
        }
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Columna Izquierda: Foto, Contacto y Habilidades -->
        <div class="left-column">
            <!-- Imagen de perfil mejorada -->
            <img src="watermarked_img_13617571865711772578.jpg" alt="Rosa Milena Hinestroza" class="profile-img">
            <h1>ROSA MILENA HINESTROZA CÓRDOBA</h1>
            <h2>Automatización Industrial & Software</h2>

            <div class="contact-info">
                <h3>CONTACTO</h3>
                <p><strong>Teléfono:</strong> 300 779 7981</p>
                <p><strong>Correo:</strong> rosimilec@hotmail.com</p>
                <p><strong>Ubicación:</strong> Medellín, Colombia</p>
            </div>

            <div class="skills-section">
                <h3>HABILIDADES TÉCNICAS</h3>
                <ul>
                    <li>PLC (Siemens, Delta, Xinje)</li>
                    <li>AutoCAD 2D y 3D</li>
                    <li>Sensores industriales</li>
                    <li>Variadores de velocidad</li>
                    <li>Python & Lógica de Programación</li>
                </ul>
            </div>

            <div class="skills-section">
                <h3>HABILIDADES BLANDAS</h3>
                <ul>
                    <li>Trabajo en equipo</li>
                    <li>Resolución de problemas</li>
                    <li>Adaptabilidad</li>
                    <li>Orientación a resultados</li>
                </ul>
            </div>
        </div>

        <!-- Columna Derecha: Sobre mí, Experiencia y Formación -->
        <div class="right-column">
            <div class="section-title">Sobre Mí</div>
            <p>Tecnóloga en Mantenimiento Electrónico e Instrumental Industrial con amplia experiencia en programación de PLC, soporte técnico, automatización industrial y AutoCAD. Actualmente curso Tecnología en Análisis y Desarrollo de Software, fortaleciendo mis habilidades tecnológicas y de soluciones digitales. Me caracterizo por mi responsabilidad, aprendizaje continuo y capacidad para trabajar orientada a resultados.</p>

            <div class="section-title">Experiencia Laboral</div>
            
            <div class="experience-item">
                <h4>Mecatrónico | IoT Mecatronic</h4>
                <span>Marzo 2025 – Abril 2026</span>
            </div>

            <div class="experience-item">
                <h4>Auxiliar de Mantenimiento Eléctrico | Ciudad Don Bosco</h4>
                <span>Septiembre 2021 – Enero 2024</span>
            </div>

            <div class="experience-item">
                <h4>Operaria de Producción | Superarchivo S.A.</h4>
                <span>Septiembre 2018 – Junio 2021</span>
            </div>

            <div class="section-title" style="margin-top: 30px;">Formación Académica</div>
            
            <div class="education-item">
                <h4>Tecnología en Análisis y Desarrollo de Software | SENA</h4>
                <span>En curso</span>
            </div>

            <div class="education-item">
                <h4>Tecnólogo en Mantenimiento Electrónico e Instrumental Industrial | SENA</h4>
                <span>Año de Finalización: 2011</span>
            </div>

            <div class="section-title" style="margin-top: 30px;">Certificaciones</div>
            <div class="education-item">
                <h4>Programación - Introducción a la Lógica y Algoritmos con Python (66 horas)</h4>
                <span>Alcaldía de Medellín y Cymetria Group S.A.S. (2026)</span>
            </div>
        </div>
    </div>

</body>
</html>
