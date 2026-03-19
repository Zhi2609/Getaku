# GeoOtaku: Explorer & Weather Dashboard 🌍✨

**GeoOtaku** es una aplicación web interactiva que permite a los usuarios explorar datos globales de una manera única. El proyecto conecta la información geográfica de diversos países con reportes meteorológicos en tiempo real y, para añadir un toque de cultura pop, ofrece recomendaciones aleatorias de anime para cada destino.

---

## 🚀 Características principales

* **Exploración de Países:** Visualización de los primeros 10 países de habla hispana con datos clave como capital, región y población.
* **Consulta Climática:** Integración con servicios meteorológicos para obtener temperatura, humedad, presión y estado del viento.
* **Conexión Cultural (Anime):** Un botón especial que consulta una base de datos de animación japonesa para sugerir una serie al azar.
* **Diseño Adaptable:** Interfaz limpia basada en tarjetas dinámicas generadas con JavaScript.

---

## 🛠️ Tecnologías utilizadas

Este proyecto fue construido utilizando tecnologías web estándar para garantizar ligereza y velocidad:

* **HTML5 & CSS3:** Estructura y diseño visual (Grid Layout).
* **JavaScript (ES6+):** Manipulación del DOM y consumo de APIs mediante `fetch` (Asincronía).
* **APIs Externas:**
    * *Información Geográfica:* Consulta de países por idioma.
    * *Weatherstack API:* Datos meteorológicos en tiempo real.

---

## ⚙️ Configuración e Instalación

Para ejecutar este proyecto localmente, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/geootaku-explorer.git](https://github.com/tu-usuario/geootaku-explorer.git)
    ```
2.  **Obtén tu API Key:**
    * Regístrate en [Weatherstack](https://weatherstack.com/) para obtener una clave gratuita.
3.  **Configura el código:**
    * Abre el archivo `index.html` (o tu archivo JS).
    * Busca la variable `WEATHERSTACK_KEY` y reemplaza el valor con tu clave personal.
4.  **¡Lánzalo!**
    * Simplemente abre el archivo `index.html` en cualquier navegador moderno.

---

## 📝 Notas de Desarrollo

* El proyecto utiliza programación asíncrona (`async/await`) para manejar múltiples peticiones simultáneas sin bloquear la interfaz de usuario.
* Se implementó el manejo de errores básico para notificar al usuario en caso de que alguna API presente fallas de conexión.

---

¡Disfruta explorando el mundo y descubriendo tu próximo anime favorito! 🗺️📺