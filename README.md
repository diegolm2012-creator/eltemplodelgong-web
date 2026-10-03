# El Templo del Gong — Web

Sitio web de **El Templo del Gong**, tienda y centro de formacion de gongs,
cuencos tibetanos, conciertos y ceremonias de sonido.

## Estado

- **Origen**: WordPress + WooCommerce alojado en Raiola Networks (Tecnocratica)
- **Destino**: Cloudflare Pages (sitio estatico)
- **Fase**: Migracion en curso — el contenido original aun esta en el hosting
  de Raiola (pendiente de reactivar)

## Stack tecnico

- Sitio estatico HTML + CSS plano
- Hosting: **Cloudflare Pages** (despliegue automatico con cada push a `main`)
- Dominio: `eltemplodelgong.com` — transferencia pendiente a Cloudflare Registrar
- Imagenes y recursos: alojados directamente en el repo (migracion manual pendiente)

## Migracion desde Raiola

1. Pagar reactivacion del hosting en Raiola (36 €)
2. Descargar contenido via FTP: `C:\Users\diego\ElCaminodelGong\web\eltemplodelgong\respaldo\`
3. Exportar base de datos MySQL/MariaDB
4. Convertir contenido estatico a HTML plano
5. Subir a este repositorio y desplegar en Cloudflare Pages
6. Transferir dominio de Tecnocratica a Cloudflare Registrar
7. Apuntar DNS a Cloudflare

## Despliegue

Cada push a `main` despliega automaticamente en Cloudflare Pages:
`https://eltemplodelgong-web.pages.dev`

&copy; 2026 El Templo del Gong — Diego Montenegro