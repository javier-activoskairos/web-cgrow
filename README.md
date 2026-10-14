# web-cgrow

Web estática de CGROW (empresa del grupo Ardeno). Réplica del sitio de GoDaddy Website Builder (`cgrow.godaddysites.com`), servida con nginx en el VPS de Ardeno (EasyPanel).

- `public/` — HTML, CSS y logos.
- `Dockerfile` + `nginx.conf` — imagen nginx:alpine, puerto interno 80.
- Formulario de contacto: abre el correo del visitante hacia lucas@cgrow.co (sin backend).
- Las fotos de stock de GoDaddy (Getty) no se reutilizan: están licenciadas solo dentro de GoDaddy. Se sustituyen por fondos CSS.
