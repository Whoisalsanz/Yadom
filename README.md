# Yadom
Crear una tienda onlines
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yadom Oficial España</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; text-align: center; background: #f9f9f9; }
        
        /* SECCIÓN PRINCIPAL CON TU FOTO */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), url('URL_DE_LA_FOTO_DE_LA_CHICA'); 
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 20px;
        }

        .container { max-width: 600px; margin: -50px auto 40px; background: white; padding: 30px; border-radius: 20px; shadow: 0 10px 30px rgba(0,0,0,0.1); position: relative; }
        
        .pack-ahorro {
            background: #e8f5e9;
            border: 2px solid #2e7d32;
            padding: 20px;
            margin: 20px 0;
            border-radius: 15px;
        }

        .precio-grande { font-size: 32px; color: #2e7d32; font-weight: bold; }
        
        .btn-ws {
            display: block;
            background: #25D366;
            color: white;
            text-decoration: none;
            padding: 18px;
            border-radius: 10px;
            font-weight: bold;
            font-size: 18px;
            margin-top: 15px;
        }

        .opciones { display: flex; gap: 10px; margin-top: 20px; }
        .card-pequena { border: 1px solid #ddd; padding: 15px; border-radius: 10px; flex: 1; font-size: 14px; }
    </style>
</head>
<body>

<div class="hero">
    <h1 style="font-size: 40px; margin: 0;">YADOM OFICIAL</h1>
    <p style="font-size: 20px;">Frescura tailandesa en tu bolsillo</p>
</div>

<div class="container">
    <p>🍃 100% Natural | Alivia estrés y mareos</p>
    
    <div class="pack-ahorro">
        <span style="background:#2e7d32; color:white; padding:5px 10px; border-radius:5px; font-size:12px;">EL MÁS VENDIDO</span>
        <h3>📦 Pack de 2 Unidades</h3>
        <p>Elige Original + Limón o repite tu favorito</p>
        <div class="precio-grande">24€</div>
        <a href="https://wa.me/34tu_numero?text=Hola! Quiero el pack ahorro de 24€" class="btn-ws">Pedir Pack por WhatsApp</a>
    </div>

    <div class="opciones">
        <div class="card-pequena">
            <strong>🌿 Original</strong><br>15€<br>
            <a href="https://wa.me/34tu_numero?text=Hola! Quiero 1 Yadom Original" style="color:#25D366; text-decoration:none; font-weight:bold;">Comprar ></a>
        </div>
        <div class="card-pequena">
            <strong>🍋 Limón</strong><br>15€<br>
            <a href="https://wa.me/34tu_numero?text=Hola! Quiero 1 Yadom de Limón" style="color:#25D366; text-decoration:none; font-weight:bold;">Comprar ></a>
        </div>
    </div>
</div>

<p style="color: #999; font-size: 12px;">© 2026 Yadom España - Envíos rápidos</p>

</body>
</html>
