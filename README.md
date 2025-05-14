<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio Baginda Nasution</title>
    <style>
      body {
        font-family: sans-serif;
        padding: 40px;
        text-align: center;
        background-color: #f5f5f5;
      }
      h1 {
        color: #333;
      }
      .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        margin-top: 30px;
      }
      .gallery img {
        width: 300px;
        border-radius: 12px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        transition: transform 0.3s;
      }
      .gallery img:hover {
        transform: scale(1.05);
      }
    </style>
  </head>
  <body>
    <h1>Selamat Datang di Website Portofolio Baginda Nasution</h1>
    <p>Halo! Saya Baginda Nasution, selamat datang di website portofolio saya.</p>

    <div class="gallery">
      <img src="1.jpg" alt="Foto Baginda 1" />
      <img src="2.jpg" alt="Foto Baginda 2" />
      <img src="3.jpg" alt="Foto Baginda 3" />
      <img src="4.jpg" alt="Foto Baginda 4" />
      <img src="5.jpg" alt="Foto Baginda 5" />
      <img src="6.jpg" alt="Foto Baginda 6" />
    </div>
  </body>
</html>
