# Manual WebAdmin AI

---

## Índice

1. [Manual de Usuario (Gente Normal)](#manual-de-usuario)
2. [Manual Técnico (Desarrolladores)](#manual-tecnico)

---

## Manual de Usuario

### ¿Qué es WebAdmin AI Dashboard?

WebAdmin AI Dashboard es una herramienta web para gestionar y supervisar sitios web, bases de datos, recursos del servidor, modelos de inteligencia artificial, artefactos y workflows, todo desde una sola pantalla amigable y moderna.

---

### Principales Funciones

- **Dashboard visual:** Consulta rápidamente el estado de RAM, CPU, almacenamiento y red.
- **Sitios Web:** Lista, agrega y gestiona tus sitios empresariales, blogs y tiendas online.
- **Bases de Datos:** Visualiza y gestiona tus bases, copias de seguridad y acciones.
- **Área de IA:** Supervisa el estado de los modelos RAG y de Fine-tuning. Accede a logs y configuraciones.
- **Páginas IA:** Lista y genera páginas web creadas con IA.
- **Artefactos IA:** Visualiza scripts y archivos generados automáticamente.
- **Workflows:** Visualiza y gestiona flujos automatizados (como backups, despliegues, sincronizaciones).
- **Panel de usuario:** Saludo personalizado, selector de tema (oscuro/claro/sistema), notificaciones y foto de perfil.
- **Modo oscuro/claro:** Cambia el tema visual desde el menú de usuario.

---

### Cómo Navegar

- Usa el menú principal para cambiar entre secciones.
- Haz clic en los botones de cada panel para agregar, editar, eliminar o configurar elementos.
- Observa los indicadores y etiquetas para saber el estado de recursos y workflows.
- Cambia el tema visual en el icono de contraste.
- La hora se muestra y actualiza automáticamente en el panel superior.

---

### Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari).
- Acceso a la red local donde está desplegado el dashboard.

---

## Manual Técnico para Desarrolladores

### Estructura del Proyecto

- `code.html` (y derivados): Archivo principal del dashboard, incluye toda la estructura visual y lógica básica JS.
- `MANUAL.md`: Este manual.
- **Dependencias externas:** TailwindCSS (via CDN), Google Fonts (Lexend + Material Symbols).

---

### Tecnologías Usadas

- **Frontend:** HTML, CSS (Tailwind), JS básico.
- **No incluye backend:** El dashboard es una plantilla visual. Para hacerla funcional debes implementar APIs y lógica de servidor.
- **Responsivo:** Adaptado a móviles y escritorio, usa clases Tailwind para diseño adaptativo.

---

### Personalización Rápida

- **Colores y temas:** Edita el script de configuración Tailwind y los estilos CSS custom (en `<style>`).
- **Fuentes:** Cambia en los enlaces Google Fonts.
- **Íconos:** Usa Material Symbols (ver `<link>` en el `<head>`).
- **Paneles y tablas:** Agrega o modifica campos/acciones en la estructura HTML según necesidades.

---

### Cómo Conectar con Backend real

1. **Agregar lógica JS:** Usa fetch/AJAX para consumir APIs REST propias y actualizar datos en las tablas/paneles.
2. **Modales y formularios:** Puedes agregar scripts para abrir modales y gestionar formularios de alta/edición.
3. **Control de usuario:** Implementa autenticación y gestión de sesión si lo necesitas.
4. **Notificaciones:** Usa la sección correspondiente para mostrar alertas o mensajes dinámicos.

---

### Buenas Prácticas

- Mantén la estructura modular, separando estilos JS, lógica y HTML si el proyecto crece.
- Usa variables/configuración centralizada para colores y fuentes.
- Documenta tus cambios, sobre todo en el dashboard visual.

---

### Ejemplo de extensión funcional (pseudo-código JS)

```js
// Ejemplo: Actualizar tabla de sitios vía API
fetch('/api/sites')
  .then(res => res.json())
  .then(sites => {
    // Renderizar filas de la tabla con los datos reales
  });
```

---

### Notas Importantes

- Este dashboard NO incluye la lógica de backend ni la persistencia de datos.
- Para conectarlo a servicios reales necesitas implementar endpoints y controladores en el lenguaje de tu preferencia (Node, Python, PHP, etc).
- Puedes modularizar el HTML y separar en componentes si usas frameworks modernos (React, Vue, Svelte).

---

## Autor

Hecho por Luis Manuel Fajardo Rivera  
Desarrollado para administración local y pruebas.

---

## Licencia

Consulta el archivo de licencia del proyecto para más detalles.
