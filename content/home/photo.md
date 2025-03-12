---
widget: custom
headless: true
active: true
weight: 30  # Ajusta este número para la posición debajo de las redes
title: ""
design:
  columns: "1"
---
<!-- Contenedor de la foto -->
<div class="photo-container">
    <div class="photo-title">March's Best Photo</div>
    <img src="authors/images/bled_lake.jpeg" alt="March's Best Photo">
</div>

<style>
.photo-container {
    text-align: center;
    margin-top: 20px;
}
.photo-container img {
    width: 600px; /* Ajusta el tamaño según sea necesario */
    height: 400px; /* Ajusta el tamaño según sea necesario */
    object-fit: cover;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.photo-title {
    font-size: 1.5em;
    margin-top: 10px;
    text-align: center;
}
</style>

