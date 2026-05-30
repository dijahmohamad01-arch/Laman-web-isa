<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isa Wiring | Pakar Servis Elektrik, Aircond & CCTV</title>
    <style>
        :root { --primary: #2563eb; --secondary: #1e293b; --accent: #f59e0b; --light: #f8fafc; }
        body { font-family: 'Segoe UI', Tahoma, sans-serif; margin: 0; line-height: 1.6; color: var(--secondary); background: var(--light); }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        header { background: white; padding: 20px; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        .hero { padding: 50px 20px; background: linear-gradient(135deg, #2563eb, #1d4ed8); color: white; text-align: center; }
        .btn { display: inline-block; padding: 15px 30px; background: var(--accent); color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin-top: 20px; }
        
        .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 15px; padding: 30px 0; }
        .card { background: white; padding: 15px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }

        /* Galeri Swipe */
        .gallery-container { display: flex; overflow-x: auto; scroll-snap-type: x mandatory; gap: 15px; padding: 20px 0; }
        .gallery-item { flex: 0 0 80%; scroll-snap-align: center; background: #ddd; height: 200px; display: flex; align-items: center; justify-content: center; border-radius: 10px; font-weight: bold; color: #555; border: 2px dashed #aaa; }
    </style>
</head>
<body>

<header>
    <h2>ISA WIRING</h2>
</header>

<section class="hero">
    <h1>Servis Profesional Isa Wiring</h1>
    <p>Elektrik, Aircond, CCTV & Autogate</p>
    <a href="https://wa.me/60123456789" class="btn">WhatsApp Sekarang</a>
</section>

<section class="container">
    <div class="services">
        <div class="card">⚡ Elektrik</div>
        <div class="card">❄️ Aircond</div>
        <div class="card">📹 CCTV</div>
        <div class="card">🚪 Autogate</div>
    </div>

    <h3>Hasil Kerja Kami</h3>
    <div class="gallery-container">
        <div class="gallery-item">Foto Projek 1</div>
        <div class="gallery-item">Foto Projek 2</div>
        <div class="gallery-item">Foto Projek 3</div>
        <div class="gallery-item">Foto Projek 4</div>
    </div>
    <p style="text-align: center; font-size: 0.8rem; color: #888;">*Tolak ke tepi untuk melihat gambar seterusnya</p>
</section>

</body>
</html>
