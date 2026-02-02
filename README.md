# Lista de Supermercado

Una aplicación web simple para gestionar una lista de compras, desarrollada como parte de la Actividad Integradora 1.

## Descripción

Esta aplicación permite a los usuarios crear y gestionar una lista de productos para el supermercado. Incluye funcionalidades para agregar productos con nombre y cantidad, marcarlos como comprados, eliminarlos y visualizar contadores de productos totales, comprados y pendientes. Los datos se almacenan localmente en el navegador usando localStorage.

## Características

- **Agregar productos**: Ingresa el nombre del producto y la cantidad deseada.
- **Marcar como comprado**: Cambia el estado de un producto entre pendiente y comprado.
- **Eliminar productos**: Remueve productos de la lista.
- **Contadores**: Muestra el total de productos, los comprados y los pendientes.
- **Persistencia**: Los datos se guardan automáticamente en el navegador y se cargan al recargar la página.
- **Interfaz responsiva**: Diseñada con un tema morado y adaptable a diferentes tamaños de pantalla.

## Cómo usar

1. Descarga o clona el repositorio.
2. Abre el archivo `index.html` en tu navegador web preferido (como Chrome, Firefox, etc.).
3. En la sección de formulario:
   - Ingresa el nombre del producto en el campo "Nombre del producto".
   - Ingresa la cantidad en el campo "Cantidad".
   - Haz clic en "Agregar" para añadir el producto a la lista.
4. En la lista de productos:
   - Haz clic en "Comprado" para marcar o desmarcar un producto como comprado.
   - Haz clic en "Eliminar" para quitar un producto de la lista.
5. Los contadores en la parte inferior se actualizan automáticamente.

## Tecnologías utilizadas

- **HTML**: Estructura de la página.
- **CSS**: Estilos y diseño con tema morado.
- **JavaScript**: Lógica de la aplicación, manejo de eventos y almacenamiento local.

## Requisitos

- Un navegador web moderno que soporte JavaScript y localStorage.

## Autor

Desarrollado por Angel como parte de la Actividad Integradora 1.

## Licencia

Este proyecto es de uso educativo y no tiene una licencia específica.
git add README.md
git commit -m "Merge: integrar README inicial de GitHub con versión local"