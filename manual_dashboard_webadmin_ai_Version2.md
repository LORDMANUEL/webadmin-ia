# Manual de Usuario: WebAdmin AI Dashboard

## Introducción

WebAdmin AI Dashboard es una interfaz web administrativa que permite gestionar sitios web, bases de datos, recursos del servidor, modelos de inteligencia artificial, artefactos y workflows desde un solo lugar.

## Características principales

- **Visualización del consumo de recursos:** RAM, CPU, SSD y Ethernet.
- **Gestión de sitios web:** Ver, agregar y administrar sitios corporativos, blogs y tiendas online.
- **Gestión de bases de datos:** Consultar bases, ver copias de seguridad y realizar acciones.
- **Área de IA:** Supervisar el estado de modelos RAG y de Fine-tuning, ver logs y configurar.
- **Páginas generadas por IA:** Listar y crear páginas IA para tus sitios.
- **Artefactos generados por IA:** Administrar scripts y archivos generados automáticamente.
- **Workflows (n8n):** Ver el estado y las acciones de flujos de trabajo automatizados.
- **Modo oscuro/claro:** Cambia el tema visual desde el menú de usuario.
- **Panel de usuario:** Muestra saludo personalizado y la hora actual.

## Estructura del Dashboard

1. **Barra superior (Header):**
   - Logo y nombre del sistema.
   - Menú de navegación: Sitios Web, Bases de Datos, Área de IA, Páginas IA, Workflows.
   - Panel de usuario: nombre, hora, selector de tema, notificaciones, foto de perfil.

2. **Panel principal (Main):**
   - Dashboard de administración.
   - Panel de recursos del servidor.
   - Listado y gestión de sitios web.
   - Gestión de bases de datos.
   - Área de IA: estado de modelos, logs y configuración.
   - Páginas IA y artefactos: listado y generación.
   - Estado y acciones de workflows automatizados.

3. **Pie de página (Footer):**
   - Autor del sistema.
   - Indicador de entorno local.

## Cómo usar el Dashboard

- **Navegación:** Usa el menú principal para ir a la sección deseada.
- **Agregar nuevo elemento:** Haz clic en los botones "Añadir Nuevo Sitio Web", "Generar Nueva Página", "Generar Nuevo Artefacto" según el panel.
- **Ver estado:** Observa los indicadores circulares y etiquetas de estado (Activo, Inactivo, Error) para saber el estado de recursos y workflows.
- **Realizar acciones:** Usa los botones de acciones en cada fila de las tablas para editar, eliminar, configurar o ver logs de cada elemento.
- **Cambiar tema:** Haz clic en el icono de contraste en el panel de usuario y selecciona "Oscuro", "Claro" o "Sistema".
- **Ver hora actual:** La hora se actualiza automáticamente cada minuto en el panel de usuario.

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari).
- Acceso a la red local donde el dashboard está desplegado.

## Notas

- Este dashboard es una plantilla visual. Para conectarlo a tus servicios y bases de datos reales, necesitas implementar la lógica de backend y las APIs correspondientes.
- Puedes personalizar los estilos, colores y textos editando el archivo HTML y la configuración de Tailwind.

---