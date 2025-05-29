# Proyecto Videos de Soporte 🎥✨

¡Hola profe! Bienvenido al repositorio más entretenido de videos que no son para Netflix, sino para soporte técnico... pero con estilo.

---

## ¿Qué es este proyecto? 🤔

Este proyecto es una app que muestra una lista de videos de soporte para ayudar a los usuarios cuando se pierden (porque todos nos perdemos a veces).  
Los videos están almacenados en un backend, que devuelve una lista de URLs para que la app los pueda reproducir.

---

## ¿Cómo funciona? 🔧

- El backend expone un endpoint `GET /media` que devuelve un JSON con una lista de videos.  
- La app Android consume ese endpoint y muestra los videos para que el usuario pueda verlos y solucionar sus dudas.  
- Los videos están representados con la clase `Media` en el backend y `MediaResponse` en la app para manejar la información.

---

## Tecnologías usadas 🛠️

- Backend Java con JAX-RS (Jersey)  
- Base de datos para almacenar URLs y metadatos de los videos  
- Android para mostrar la lista y reproducir videos  
- Un poco de magia IA para ayudarte a entender este README 😎

---

## Cómo usarlo 🚀

1. Clona el repositorio:

   ```bash
   git clone https://url-de-tu-repo.git
