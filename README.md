# Microinversiones con IA 🌐⚙️🧠

Bienvenido al proyecto **Microinversiones con Sugerencias IA** — una plataforma innovadora que utiliza Inteligencia Artificial para brindar recomendaciones de inversiones accesibles a todos. A través de este sistema, los usuarios pueden descubrir oportunidades de microinversión respaldadas por análisis automatizados y sugerencias inteligentes.

---

## 📸 Capturas de Pantalla del login del proyecto 

### Página Principal del login
![image](https://github.com/user-attachments/assets/1f663052-755a-4392-9ae9-36e39a192315)
![image](https://github.com/user-attachments/assets/171590e7-8b1e-4a0d-8895-ec64d59d2464)


### Página Principal del registro
![image](https://github.com/user-attachments/assets/f6ce1ed0-0be2-49a5-9e16-f61fb9bca58f)
![image](https://github.com/user-attachments/assets/91e61cf4-7bfe-4bde-8f5a-318d42bf9454)
![image](https://github.com/user-attachments/assets/e0c54607-643c-4ed6-a67e-9d11b3fe1096)


## 🚀 Características Principales

- 🧠 **Sugerencias Inteligentes de Inversión** basadas en algoritmos de IA.
- 📊 **Análisis de Riesgos**: evaluación automática de riesgos en cada microinversión.
- 🛠️ **Panel de Usuario** con seguimiento de inversiones.
- 👋 **Interfaz amigable y moderna** para facilitar el uso.
- 💻 **Registro e inicio de sesión** integrados, incluyendo proveedores sociales (Facebook y Google).

## 🛠️ Tecnologías Utilizadas

Este proyecto está construido usando las siguientes tecnologías:

- **Laravel** (🚀 [documentación](https://laravel.com/docs)) — framework de backend que nos permite construir lógica robusta y escalable.
  - 🎉 Laravel Jetstream para la autenticación y manejo de sesiones.
- **Inteligencia Artificial (IA)**: para sugerencias de inversión y predicciones basadas en datos.
  - 🧠 Modelos de IA entrenados para entender patrones de mercado.
- **HTML5 y CSS3** — para la estructura y el estilo de la aplicación.
  - 💄 Tailwind CSS para una estilización moderna y rápida.
- **JavaScript** ⭐️ — para agregar interactividad en el frontend.
- **MySQL** 📁 — base de datos utilizada para almacenar información de usuarios e inversiones.

## 🤓 Sobre Laravel

Laravel es un framework para aplicaciones web con una sintaxis expresiva y elegante. Creemos que el desarrollo debe ser una experiencia agradable y creativa para ser verdaderamente satisfactorio. Laravel elimina las dificultades del desarrollo al facilitar tareas comunes utilizadas en muchos proyectos web, tales como:

- 🚀 Motor de enrutamiento simple y rápido.
- 💡 Contenedor de inyección de dependencias potente.
- 🔄 Soporte para múltiples back-ends para almacenamiento de sesiones y caché.
- 📦 ORM de base de datos expresivo e intuitivo.
- 🗄️ Migraciones de esquema independientes de la base de datos.
- 🔧 Procesamiento robusto de trabajos en segundo plano.
- 📡 Transmisión de eventos en tiempo real.

Laravel es accesible, potente y proporciona herramientas necesarias para aplicaciones grandes y robustas.

### Aprender Laravel

Laravel tiene la documentación más extensa y completa y una biblioteca de tutoriales en video de todos los frameworks modernos para aplicaciones web, lo que facilita comenzar con el framework.

También puedes probar el Laravel Bootcamp, donde te guiarán a través de la construcción de una aplicación moderna de Laravel desde cero.

Si prefieres no leer, Laracasts puede ayudarte. Laracasts contiene miles de tutoriales en video sobre una variedad de temas, incluidos Laravel, PHP moderno, pruebas unitarias y JavaScript. Mejora tus habilidades explorando nuestra completa biblioteca de videos.

### Patrocinadores de Laravel

Nos gustaría extender nuestro agradecimiento a los siguientes patrocinadores por financiar el desarrollo de Laravel. Si estás interesado en convertirte en patrocinador, por favor visita el programa de [Partners de Laravel](https://laravel.com/partners).

#### Premium Partners

- Vehikl
- Tighten Co.
- WebReinvent
- Kirschbaum Development Group
- 64 Robots
- Curotec
- Cyber-Duck
- DevSquad
- Jump24
- Redberry
- Active Logic
- byte5
- OP.GG

## 🚼 Contribuir

Gracias por considerar contribuir al framework Laravel. La guía de contribución se encuentra en la [documentación de Laravel](https://laravel.com/docs/contributions).

### Código de Conducta

Para garantizar que la comunidad de Laravel sea acogedora para todos, por favor revisa y cumple con el [Código de Conducta](https://laravel.com/docs/contributions#code-of-conduct).

### Vulnerabilidades de Seguridad

Si descubres alguna vulnerabilidad de seguridad en Laravel, por favor envía un correo a Taylor Otwell a [taylor@laravel.com](mailto:taylor@laravel.com). Todas las vulnerabilidades serán abordadas de manera inmediata.

### Licencia

El framework Laravel es software de código abierto bajo la licencia [MIT](https://opensource.org/licenses/MIT).

---

## 🌐 Despliegue del Proyecto

### 🤖 Requisitos Previos

- **PHP >= 8.1** ⚡️
- **Composer** (para manejar dependencias) ⭐️
- **MySQL** (base de datos) 📁
- **Node.js & npm** (para construir assets del frontend) 🌟

### 🚀 Pasos para Instalar

1. **Clonar el Repositorio**

   ```sh
   git clone https://github.com/tu-usuario/microinversiones-ia.git
   cd microinversiones-ia
   ```

2. **Instalar Dependencias de Backend**

   ```sh
   composer install
   ```

3. **Instalar Dependencias del Frontend**

   ```sh
   npm install && npm run dev
   ```

4. **Configurar Variables de Entorno**
   
   Copia el archivo `.env.example` y renomámalo a `.env`. Luego, configura las siguientes variables de entorno:

   ```
   APP_NAME=Microinversiones
   APP_URL=http://127.0.0.1:8000
   DB_DATABASE=microinversiones
   DB_USERNAME=root
   DB_PASSWORD=tu_contraseña
   ```

5. **Generar la Clave de Aplicación**

   ```sh
   php artisan key:generate
   ```

6. **Migrar la Base de Datos**

   ```sh
   php artisan migrate
   ```

7. **Ejecutar el Servidor de Desarrollo**

   ```sh
   php artisan serve
   ```

   Luego, visita `http://127.0.0.1:8000` en tu navegador.

---

## 🔧 Comandos útiles de Artisan

- `php artisan route:list` 🏦 para ver todas las rutas disponibles.
- `php artisan migrate` 🛠️ para correr migraciones.
- `php artisan tinker` 🤯 para interactuar con la aplicación desde la línea de comandos.

---

## 💻 Autenticación con Laravel Jetstream

Se implementó **Laravel Jetstream** para la autenticación. Incluye:

- 🔒 **Inicio de sesión y registro** con verificación de email.
- 🛡️ **Protección de sesiones** y autenticación de dos factores.
- 🌍 **Opciones de inicio de sesión social** (Google, Facebook).

---

## ✍️ Autor
- Romina Jacqueline Aguirre Velazco
- 📧 romina.aguirre8841@alumnos.udg.mx
- Desarrollado con ❤️ por Romina Aguirre. 


---

## 🙌 Agradecimientos

Gracias a todos los desarrolladores de Laravel y a la comunidad de código abierto por su continuo soporte y aportes.

👏🏻👏🏻👏🏻

---


