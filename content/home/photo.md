---
widget: custom
headless: true
active: true
weight: 30  # Ajusta este número para la posición debajo de las redes
title: ""
design:
  columns: "1"
---

<div class="photo-container">
    <div class="photo-title">March's Best Photo</div>
    <img src="{{ "authors/images/bled_lake.jpeg" | relURL }}" alt="March's Best Photo">
</div>

<style>
.photo-container {
    text-align: center;
    margin-top: 20px;
}
.photo-container img {
    width: 300px;
    height: 200px;
    object-fit: cover;
}
.photo-title {
    font-size: 1.5em;
    margin-top: 10px;
}
</style>

