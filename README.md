## 2. Arquitectura de la Solución Web

### Funcionalidades Principales

1. **Acceso Multiplataforma Ligero:** Optimización de carga para dispositivos con pocos recursos y conexiones 3G/4G.
2. **Repositorio de Recursos Abiertos:** Biblioteca de materiales descargables para reducir el uso de papel y la brecha digital.
3. **Interfaz de Alta Accesibilidad:** Diseño compatible con lectores de pantalla y navegación simplificada para personas con discapacidad.

### Entidades de Datos Básicas

| Entidad           | Descripción                                 | Ejemplo de datos a guardar                                 |
| :---------------- | :------------------------------------------ | :--------------------------------------------------------- |
| **Usuarios**      | Personas registradas en la plataforma       | ID_Usuario, Nombre, Email, Contraseña, Rol (Profe/Alumno). |
| **Cursos**        | Contenido didáctico organizado por materias | ID_Curso, Título, Descripción, Fecha_Creación.             |
| **Inscripciones** | Registro de alumnos apuntados a cada curso  | ID_Usuario, ID_Curso, Fecha_Inscripción.                   |

### Prototipo de Interfaz (Frontend)

A continuación se muestra el wireframe de nuestra aplicación diseñado en Excalidraw/Figma:

![Prototipo de la Interfaz Web](./images/prototipo.png)

**Breve explicación:** El diseño muestra un panel de control minimalista que facilita la navegación rápida hacia los cursos y recursos descargables. Incluye una sección de ajustes de sostenibilidad para activar el modo de bajo consumo de datos y mejorar la accesibilidad universal.
