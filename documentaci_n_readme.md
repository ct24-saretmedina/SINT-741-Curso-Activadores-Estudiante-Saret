# 🐾 RescU RefugioDigital

**RescU RefugioDigital** es una plataforma colaborativa y solidaria diseñada para conectar a refugios o asociaciones de rescate animal con personas interesadas en adoptar o ayudar a animales vulnerables en la calle.

---

## 🎯 Objetivo del Proyecto

Facilitar y acelerar el proceso de adopción de mascotas, además de proveer una herramienta rápida con **mapa en tiempo real** para que cualquier ciudadano pueda reportar un animal en situación de calle para su posterior rescate.

---

## 🚀 Estado Actual del Proyecto

Actualmente el proyecto cuenta con un **prototipo funcional** con interfaces responsivas (Web en HTML/JS y versión inicial en Flutter).

### 🛠️ Funcionalidades Implementadas (Prototipo Frontend)
- [x] **Autenticación con Roles:** Selección entre cuenta de *Persona Normal* u *Organización/Refugio*.
- [x] **Página Principal / Feed:** Exploración de mascotas en adopción con filtros por especie (perros, gatos, otros).
- [x] **Módulo de Rescate Callejero:** Captura de fotos y marcado de coordenadas geográficas en tiempo real mediante un mapa interactivo.
- [x] **Tienda Solidaria:** Catálogo de productos para apoyar financieramente a los refugios.
- [x] **Barra de Navegación Inferior (Scroll Bar / Dock):** Navegación persistente y fluida tras iniciar sesión.
- [x] **Gestión de Organización:** Panel para publicar y listar mascotas en adopción.

### ⚠️ Lo que falta por construir o pulir (Pendiente de verificación / desarrollo)
- [ ] Conexión a un **backend real** (Firebase, Supabase o Node.js/PostgreSQL) para persistir datos.
- [ ] Verificación de autenticación de seguridad (Login real con correo y contraseña).
- [ ] Guardado real de imágenes en almacenamiento en la nube (AWS S3, Cloudinary o Firebase Storage).
- [ ] Inclusión de base de datos inicial con **refugios y organizaciones reales**.
- [ ] Pulido de UI/UX y soporte para notificaciones push en móviles.

---

## 💻 ¿Cómo probar el proyecto?

### Opción 1: Probar en el Navegador Web (HTML/JS)
1. Abre el archivo `index.html` directamente en tu navegador (haciendo doble clic).
2. O ejecuta un servidor local como **Live Server** en Visual Studio Code.

### Opción 2: Versión Flutter (Móvil)
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/RescU-RefugioDigital.git
   ```
2. Entra al directorio e instala las dependencias:
   ```bash
   cd RescU-RefugioDigital
   flutter pub get
   ```
3. Ejecuta la aplicación:
   ```bash
   flutter run
   ```

---

## 🤝 ¿Quieres colaborar?

¡Todas las contribuciones son bien recibidas! Consulta nuestra guía de [CONTRIBUTING.md](./CONTRIBUTING.md) para conocer las formas en que puedes ayudar.