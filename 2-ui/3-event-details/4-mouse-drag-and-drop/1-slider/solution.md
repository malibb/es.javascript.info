Como podemos ver en HTML/CSS, el control deslizante es un `<div>` con un fondo de color, que contiene un corredor -- otro `<div>` con `position:relative`.

Para posicionar el corredor usamos `position: relative`, para proporcionar las coordenadas relativas a su padre, aquí es más conveniente que `position:absolute`.

Luego implementamos horizontal-only Drag'n'Drop con limitación de ancho.
