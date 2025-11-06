# Listado de Mejoras

## Mejora 1: Mejora de la Interfaz: Animaciones Suaves

**Descripción:**  
Se incorporaron animaciones visuales con Animate.css para mejorar la experiencia del usuario y hacer las transiciones entre secciones más fluidas y atractivas.
Estas animaciones se aplican a títulos y elementos destacados del sitio, generando una sensación de dinamismo y modernidad en la interfaz.

**Animación 1:**
Deslizamiento lateral del menú (Sidebar) con efecto slideInLeft

### Antes
El menú lateral (sidebar) aparecía de forma instantánea, sin ninguna animación.
![Sidebar antes](https://github.com/user-attachments/assets/338b2eb1-c18b-4992-a217-0dc61663aef1)

### Después
Ahora, cuando se despliega el sidebar, los elementos del menú aparecen con un efecto slideInLeft.
![Sidebar después](https://github.com/user-attachments/assets/6ad65af6-595c-494f-b499-5b559a52e97f)

**Animación 2:**
Aparición de los elementos de la bitácora con efecto zoomInDown 

### Antes
Los elementos de la bitácora aparecían todos al instante, sin ningún tipo de animación.
La transición entre las distintas entradas era brusca y no ofrecía una sensación visual fluida.
![Bitácora antes](https://github.com/user-attachments/assets/42611d92-4a89-409d-8bc8-8362aa095cde)

### Después
Los elementos ahora aparecen con una animación tipo zoomInDown, generando un efecto visual más dinámico y agradable.
Al cambiar de entradas, las tarjetas se animan nuevamente, reforzando la sensación de interacción fluida.
![Bitácora después](https://github.com/user-attachments/assets/7f370549-37ee-4394-bdcc-5b47be008287)

**Animación 3:**
Aparición del título con efecto fadeInDown 

### Antes
El título aparecía de forma estática, sin ningún tipo de animación o transición visual.
![Títulos antes](https://github.com/user-attachments/assets/cad9e0cb-50c2-4466-9943-d61840c47d07)

### Después
El título ahora se muestra con un efecto de entrada suave desde arriba (fadeInDown) al cargar la sección.
![Títulos después](https://github.com/user-attachments/assets/8b332370-0a9d-438e-a757-f446928f2cc7)


**Animación 4:**
Aparición progresiva de los diagramas con efecto fadeIn

### Antes
Los diagramas aparecían de forma instantánea al cambiar entre uno y otro, sin ningún tipo de transición o animación.
![Diagramas antes](https://github.com/user-attachments/assets/e9fbfd6d-961e-4194-95f3-228698b5fd2b)

### Después
Al cambiar de diagrama o cargar la sección, la imagen se muestra con una animación suave de aparición (fadeIn), lo que mejora la experiencia visual del usuario.
![Diagramas después](https://github.com/user-attachments/assets/626a6d1b-81ec-4d6f-ba52-f696658da1b6)

**Animación 5:**
Aparición lateral de las tarjetas de directores con efecto bounceInRight

### Antes
Las tarjetas de directores aparecían de manera estática y simultánea, sin ningún tipo de animación o transición visual al cargar o filtrar resultados.
![Directores antes](https://github.com/user-attachments/assets/e8af7d5d-13d6-45ba-b3d2-96381d43865d)

### Después
Ahora, al cargar la sección o aplicar un filtro, las tarjetas aparecen con una animación de entrada lateral (bounceInRight), aportando dinamismo y una sensación más fluida a la experiencia visual.
![Directores después](https://github.com/user-attachments/assets/3342fd7a-9c21-4759-bda8-c0030dec87fb)

**Animación 6:**
Aparición de las tarjetas de películas con efecto bounceInUp

### Antes
Las películas se mostraban instantáneamente al cargar la página o cambiar de filtro, sin ningún tipo de transición ni animación visual.
![Películas antes](https://github.com/user-attachments/assets/e1428240-ef41-497b-882a-07be2cda1654)

### Después
Ahora, las tarjetas de películas aparecen suavemente desde abajo mediante el efecto bounceInUp, logrando una transición más fluida al cargar los resultados o al cambiar entre búsquedas y géneros.
![Películas después](https://github.com/user-attachments/assets/4b38c798-729d-4a3d-a981-2ec8b6624ee0)

**Animación 7:**
Aparición de los pósters de estrenos con efecto bounceInUp

### Nueva implementación
En esta entrega se incorporó la nueva sección Estrenos, ausente en el trabajo anterior.
Se muestran con una animación bounceInUp, la misma utilizada en la sección de Películas, este efecto genera una entrada suave desde la parte inferior, transmitiendo dinamismo y manteniendo coherencia visual con el resto del sitio.
![Estrenos](https://github.com/user-attachments/assets/7ed1d16a-5254-4c59-b042-190d26d08fc8)

## Mejora 2: Búsqueda/Filtrado en JSON Local

**Descripción:**  
Implementación de búsqueda por texto y filtrado por categoría en JSON local

### Antes
La sección de Directores mostraba todos los registros del archivo directors-data.json sin permitir ningún tipo de filtrado o búsqueda.
Esto hacía que el usuario tuviera que desplazarse manualmente por toda la lista para encontrar un director específico.
![Directores antes](https://github.com/user-attachments/assets/7f306bd0-c074-4df4-82d8-e251c59831b9)

### Después
Ahora, se implementó un buscador por texto y un filtro por categorías (géneros) que permite al usuario localizar rápidamente a un director en función de su nombre o del tipo de películas por las que es conocido.
Esta mejora hace la navegación mucho más dinámica e intuitiva.
![Directores después](https://github.com/user-attachments/assets/dce20656-66be-491f-b3df-b4f3281d0f57)

## Mejora 3: Paginación para la API Externa

**Descripción:**   
Se implementó paginación con botones dinámicos para mejorar el rendimiento y la navegación.

### Antes
Al final del TP2 la lista de películas se limitaba a los resultados de la página 1 de la API, lo que impedía al usuario consultar más contenido y hacía la navegación limitada.
![Paginación antes](https://github.com/user-attachments/assets/2b747ba9-1965-4b92-90bb-782330061a12)

### Después
Se añadió paginación con botones dinámicos (Anterior / Siguiente).  
Esto mejora la experiencia y el rendimiento porque la interfaz carga solo la página necesaria en cada interacción.
![Paginación después](https://github.com/user-attachments/assets/21c13687-7f40-491d-8e53-2e0ac5346d86)

## Mejora 4: Galería de Imágenes Interactiva

**Descripción:**  
En esta entrega se incorporó una galería de imágenes interactiva para la sección de Estrenos.  
Al hacer clic sobre cualquiera de los pósters, se abre un lightbox con navegación entre imágenes, soporte para zoom y la posibilidad de cerrar tanto con un botón como presionando la tecla ESC.  
Esta mejora brinda una experiencia más inmersiva e intuitiva, permitiendo explorar los estrenos de forma visual y moderna.  

![Estrenos](https://github.com/user-attachments/assets/d3547e33-0449-4608-bc5d-34b3efaf23ac)

## Mejora 5: Barras de Progreso de Habilidades

**Descripción:**  
Se añadieron barras de progreso animadas que representan visualmente el nivel de cada habilidad dentro de los perfiles de los integrantes.  

### Antes
En la entrega anterior, los perfiles mostraban únicamente una lista estática de habilidades sin ningún tipo de indicador visual o animación.
Esto hacía difícil percibir el nivel de dominio de cada habilidad.
  
**Tarjeta Ávalos:**  
![Habilidades antes Ávalos](https://github.com/user-attachments/assets/0e7f627f-9fae-43a5-8cef-1741b78bccff)

**Tarjeta Paguaga:**  
![Habilidades antes Paguaga](https://github.com/user-attachments/assets/a402b0fc-8a99-4d64-9266-fc416664f9cb)

### Después
Ahora, las habilidades se representan con barras de progreso animadas, transmitiendo de forma clara y visual el nivel de competencia de cada integrante.  

**Tarjeta Ávalos:**  
![Habilidades después Ávalos](https://github.com/user-attachments/assets/bebc0909-6f92-4483-a058-599dca82aee0)

**Tarjeta Paguaga:**  
![Habilidades después Paguaga](https://github.com/user-attachments/assets/964ae710-d15b-4908-bb95-e67fb7b10a02)

