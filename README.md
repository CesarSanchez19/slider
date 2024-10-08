### Galería Dinámica: Carrusel de Imágenes Responsivo con Bootstrap.

Este proyecto es una página web simple que implementa un **carrusel de imágenes responsivo** utilizando el framework **Bootstrap**. El objetivo principal es mostrar una secuencia de imágenes de forma atractiva, proporcionando una experiencia visual fluida en cualquier dispositivo.

### Descripción técnica:
1. **Estructura HTML**:
   - Se utiliza el estándar HTML5, con etiquetas como `<!DOCTYPE html>` para asegurar compatibilidad con navegadores modernos.
   - La página incluye un carrusel, que es un componente interactivo de Bootstrap, y está envuelto en un `div` con el ID `fullWidthSlider`. Este carrusel tiene tres imágenes que se deslizan automáticamente, con botones de navegación que permiten al usuario moverse hacia adelante y hacia atrás entre las imágenes.

2. **Estilo CSS**:
   - Se han aplicado estilos personalizados para definir el ancho completo del carrusel (`100%`) y una altura fija de `500px`. Las imágenes dentro del carrusel también están configuradas con `object-fit: cover` para asegurar que siempre se muestren correctamente, ajustando su tamaño al contenedor sin distorsionarse.

3. **Integración con Bootstrap**:
   - El proyecto utiliza **Bootstrap 5.3.3**, un popular framework de diseño web que facilita la creación de páginas responsivas. Esto se logra enlazando las hojas de estilo y los scripts de Bootstrap desde un **CDN** (Content Delivery Network), lo que asegura una carga rápida y eficiente de los recursos.
   - Los botones de navegación del carrusel (previo y siguiente) y el deslizamiento automático de las imágenes son proporcionados por Bootstrap, lo que hace que el proyecto sea interactivo sin necesidad de agregar código JavaScript personalizado.

4. **Recursos externos**:
   - Las imágenes utilizadas en el carrusel están almacenadas localmente en el proyecto dentro de una carpeta denominada `img`, mientras que los estilos personalizados se encuentran en un archivo CSS externo dentro de la carpeta `css`.

### Finalidad:
Este proyecto es ideal para implementarse en páginas que requieren mostrar una galería de imágenes de forma dinámica, como sitios de portafolios, presentaciones de productos, o landing pages que busquen una manera atractiva de presentar contenido visual. La simplicidad de Bootstrap y el diseño limpio aseguran que el proyecto pueda ser fácilmente ampliado o adaptado según las necesidades del usuario.