<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>León Oftalmólogos</title>

    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", sans-serif;
            background: #f8f9fb;
            color: #1a1a1a;
        }

        header {
            background: linear-gradient(135deg, #0a2540, #133b63);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header img.logo {
            width: 140px;
            margin-bottom: 15px;
        }

        h1 {
            font-size: 2.3rem;
            margin: 10px 0;
            color: #f5d173;
        }

        h2 {
            color: #0a2540;
        }

        .btn-group {
            margin-top: 15px;
        }

        .btn {
            display: inline-block;
            background: #f5d173;
            color: #0a2540;
            padding: 12px 20px;
            border-radius: 8px;
            margin: 5px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .services-grid {
            display: grid;
            gap: 20px;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
        }

        .team-card {
            display: flex;
            gap: 20px;
            align-items: center;
        }

        .team-card img {
            width: 130px;
            height: 130px;
            border-radius: 100%;
            object-fit: cover;
            border: 3px solid #f5d173;
        }

        footer {
            background: #0a2540;
            color: white;
            padding: 25px;
            text-align: center;
            margin-top: 40px;
        }

        .social a {
            color: #f5d173;
            text-decoration: none;
            margin: 0 10px;
            font-weight: bold;
        }

        iframe {
            width: 100%;
            height: 350px;
            border: none;
            border-radius: 12px;
        }
    </style>
</head>
<body>

<header>
    <img src="logo.png" alt="Logo León Oftalmólogos" class="logo">
    <h1>León Oftalmólogos</h1>
    <p>Especialistas en salud visual para toda la familia</p>

    <div class="btn-group">
        <a class="btn" href="tel:+51997093598">📞 Llamar Ahora</a>
        <a class="btn" href="http://wa.me/51997093598">💬 WhatsApp</a>
    </div>
</header>

<section>
    <h2>Servicios Oftalmológicos</h2>
    <div class="services-grid">
        <div class="card">👁️ Consulta Oftalmológica Integral</div>
        <div class="card">🧒 Oftalmología Pediátrica</div>
        <div class="card">🎯 Tratamiento de Estrabismo</div>
        <div class="card">🧪 Exámenes Especializados</div>
        <div class="card">👓 Refracción y Medida de Vista</div>
        <div class="card">🌟 Salud Visual Preventiva</div>
    </div>
</section>

<section>
    <h2>Nuestro Especialista</h2>
    <div class="card team-card">
        <img src="doctor.jpg" alt="Dr. Henry Cadillo León">
        <div>
            <h3>Dr. Henry Cadillo León</h3>
            <p><strong>Oftalmólogo Pediatra y Especialista en Estrabismo</strong><br>
            Médico Especializado en Cuba 🇨🇺<br>
            CMP: 75812 — RNE: 43407</p>

            <p style="margin-top:10px;">
                El Dr. Cadillo es reconocido por su trato cálido, su precisión diagnóstica y 
                su dedicación a brindar una atención visual segura, humana y centrada en cada paciente. 
                Su experiencia internacional y su enfoque amable generan un ambiente de confianza 
                ideal para niños, adultos y familias que buscan un cuidado visual de excelencia.
            </p>
        </div>
    </div>
</section>

<section>
    <h2>Encuéntranos</h2>
    <p><strong>Dirección:</strong> Trujillo — Calle Los Zafiros 158, Santa Inés</p>

    <iframe 
        src="https://www.google.com/maps?q=Calle%20Los%20Zafiros%20158%20Santa%20In%C3%A9s%20Trujillo&output=embed"
        allowfullscreen>
    </iframe>
</section>

<footer>
    <h3>Contáctanos</h3>
    <p>📞 +51 997 093 598 — ✉️ leonoftalmologos@gmail.com</p>

    <div class="social">
        <a href="https://www.instagram.com/leon_oftalmologos?igsh=cmNiaXFvMWk0MmQ4&utm_source=qr">Instagram</a> |
        <a href="https://www.facebook.com/profile.php?id=61580275032246">Facebook</a> |
        <a href="https://www.tiktok.com/@leonoftalmologos?_r=1&_t=ZS-924GlaxpxFk">TikTok</a>
    </div>

    <p style="margin-top:15px;">© 2025 León Oftalmólogos — Todos los derechos reservados</p>
</footer>

</body>
</html>
