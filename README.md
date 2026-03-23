# Sulfato de Magnesio CRM

Microfrontend Vite/React para el formulario de Sulfato de Magnesio consumido por `iframe` desde `crm-geofal`.

## Dominio productivo

- `https://sul.magnesio.geofal.com.pe`

## Variables

- `VITE_API_URL=https://api.geofal.com.pe`
- `VITE_CRM_LOGIN_URL=https://crm.geofal.com.pe/login`
- `VITE_MODULE_SLUG=sul-magnesio`

## Desarrollo

```bash
npm install
npm run dev
```

## Deploy Coolify

El `Dockerfile` ya compila este repo en la raiz `/` con `VITE_MODULE_SLUG=sul-magnesio`, listo para `https://sul.magnesio.geofal.com.pe`.
