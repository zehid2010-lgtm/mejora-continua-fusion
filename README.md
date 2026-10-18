# Mejora Continua Fusion

Aplicación de coberturas comerciales de Tucumán.

Aplicación original: https://mejora-continua-fusion.cozymug8.chatgpt.site

## Contenido
- index.html: diseño y lógica de los 8 indicadores.
- data.json: reporte actual de 489 clientes, corte 16/10/2026.
- assets/: imágenes y fondo.

## Uso
Servir esta carpeta por HTTP. No requiere instalación ni compilación. Por ejemplo: python -m http.server 8000.

## Objetivos
Powerade 75%; Aquarius familiar 60%; Cepita + Ades 55%; Crush/Fanta + Fresh 35%; Benedictino + Sifón 30%; Fanta/Sprite/Aquarius CP 75%; Coca-Cola + agua 35%; Coca-Cola + otra CP 51%.

Las combinaciones requieren las dos condiciones. Las imágenes alternativas 220/375 representan la misma condición CP.

## Actualización
La aplicación consume data.json. La automatización de correo/OneDrive todavía no está conectada. No guardar credenciales en este repositorio público.
