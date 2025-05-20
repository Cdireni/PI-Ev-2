# Evidencia 2 - Proyecto Integrador
Direni Carlos - DNI 28117281


Este proyecto es una práctica de React con Vite, Tailwind CSS y consumo de API con Axios.

### Estadísticas agregadas

Se incorporaron las siguientes estadísticas en la sección de estadísticas de la aplicación:

- Producto más caro (nombre y precio)
- Producto más barato (nombre y precio)
- Cantidad de productos cuyo título tiene más de 20 caracteres
- Precio total de todos los productos filtrados
- Promedio de descuento (`discountPercentage`) de los productos filtrados

### División del código en componentes

El código se dividió en los siguientes componentes funcionales:

- **StatsPanel**: Componente encargado de mostrar todas las estadísticas. Recibe la lista de productos por props y no maneja estado interno.
- **ProductList**: Componente encargado de mostrar la lista de productos en tarjetas. También recibe los productos por props y no maneja estado interno.

El componente principal (App.jsx) se encarga de obtener los datos, gestionar el estado y pasar la información filtrada a ambos componentes.

---
## Instrucciones para ejecutar el proyecto

1. Abre una terminal y navega a la carpeta del proyecto:
   ```
   cd Evidencia2
   ```
2. Instala las dependencias:
   ```
   npm install
   ```
3. Inicia el servidor de desarrollo:
   ```
   npm run dev
   ```
4. Abre el navegador en la URL que aparece en la terminal (por ejemplo, http://localhost:5173).

