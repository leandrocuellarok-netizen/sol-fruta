# Arquitectura técnica

## Estado observado

El repositorio `leandrocuellarok-netizen/sol-fruta` estaba vacío al iniciar la tarea: no había archivos, commits previos ni ramas adicionales. Rama por defecto: `main`.

## Decisión

Primera entrega como sitio estático autocontenido en `index.html`, sin framework ni dependencias de terceros. Motivo: el repositorio no tenía arquitectura preexistente y el alcance inicial es corporativo, informativo y de captación comercial.

## Componentes

- Header sticky con navegación responsive.
- Hero de posicionamiento.
- Historia y cronología empresarial.
- Tres unidades comerciales.
- Catálogo de productos y presentaciones.
- Modal de consulta por producto.
- Módulo de calidad.
- Formulario comercial segmentado.
- Footer con datos de contacto.

## Interacciones

Navegación móvil, enlaces de canal que preseleccionan el formulario, modal de producto y formulario que prepara un correo usando `mailto:`. No existe API, base de datos, CRM ni envío servidor.

## Seguridad y privacidad

No se solicitan credenciales ni se almacenan datos en el sitio. El formulario transfiere la consulta a la aplicación de correo del visitante. No hay scripts de terceros ni dependencias instaladas.

## Evolución recomendada

Si el cliente aprueba una segunda etapa: separar páginas por unidad comercial, incorporar activos oficiales optimizados, implementar endpoint seguro para formularios, analítica con consentimiento cuando corresponda, sitemap y pruebas automatizadas.