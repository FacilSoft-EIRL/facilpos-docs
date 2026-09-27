# Documentation project instructions

## About this project

- Documentación de uso de FacilPOS ([https://pos.facilerp.com](https://pos.facilerp.com)), el punto de venta de FacilERP.
- Sitio construido con [Mintlify](https://mintlify.com): páginas MDX con frontmatter YAML; configuración en `docs.json`.
- La navegación sigue el menú de la aplicación: Primeros pasos, Comprobantes, Mantenimiento, Reportes, Configuración y Ayuda.

## Terminology

- Use los nombres exactos de la interfaz en **negrita**: **Registrar**, **\+ Añadir Item**, **Seleccionar Cliente**, **Grabar**.
- "Variedad" es el nombre que usa FacilPOS para un producto o servicio.
- "Comprobante" = Factura, Boleta de Venta o Ticket. La "Nota de Pedido" es un documento interno que no se registra en contabilidad.
- Rutas de menú con flecha: **Comprobantes → Ventas**.

## Style preferences

- Español, tratamiento de "usted".
- Oraciones cortas, una idea por oración.
- Procedimientos con `<Steps>`; advertencias con `<Warning>`, notas con `<Note>`, consejos con `<Tip>`; preguntas frecuentes con `<AccordionGroup>`.
- Capturas en `/images/<sección>/`, recortadas al área relevante, con un recuadro rojo en el campo o botón clave. No se capturan listas desplegables: se mencionan sus opciones en el texto.

## Content boundaries

- Documente solo lo que existe en la aplicación; no invente funciones.
- Para ejemplos de ventas use una **Nota de Pedido** a FACILSOFT E.I.R.L. (RUC 20601863228), nunca un comprobante real.
- Los errores de la aplicación se reportan al equipo de desarrollo; en la documentación solo se incluyen si el usuario necesita una solución temporal.
