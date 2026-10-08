# Ejemplo original: HTML sin backend

Dos páginas HTML y una hoja CSS, sin dependencias, herramientas de construcción ni claves. Estudio Roble es ficticio y contacto@example.com es una dirección de ejemplo. `mailto` abre el cliente de correo: no envía ni guarda formularios.

Para verlo con un servidor local:

```sh
python3 -m http.server 8080 --directory . --bind 127.0.0.1
```

Abrir http://127.0.0.1:8080/ y /about.html. Comprobar estilos, enlace entre páginas, recarga y anchuras de móvil/escritorio. La web será pública solamente cuando se desplieguen esos tres archivos en un alojamiento; localhost sigue dependiendo de tu equipo.

Este ejemplo se prepara para las guías de publicación de Hostbrid. Estado: fuentes originales; publicación y prueba mediante Projects todavía pendientes. No usar `python -m http.server` como servidor de producción. Un formulario, login o pago requiere servicios adicionales que este ejemplo no implementa.

Verificación local realizada el 8 de octubre de 2026: Chromium a 390 y 1280 px,
ambas rutas abiertas directamente, hoja CSS cargada, navegación entre páginas
y ausencia de desbordamiento horizontal. La captura móvil también se revisó visualmente.
Estas pruebas no certifican todavía importación ni publicación en Projects.

Licencia MIT, incluida en LICENSE. Se puede reutilizar y adaptar el ejemplo.
