# Grupo Cultivo — Landing

Landing profesional de **Grupo Cultivo** (Astro), con la misma paleta visual del dashboard CultivoApp.

## Incluye

- Hero full-bleed y secciones de producto
- Agenda embebida de Calendly: https://calendly.com/nexag/grupo-cultivo
- Formulario de contacto vía [FormSubmit](https://formsubmit.co/) → `lukassvergara@gmail.com`

## Desarrollo

Requiere Node.js 22+.

```bash
npm install
npm run dev
```

Build:

```bash
npm run build
npm run preview
```

Salida estática en `dist/`.

## Contacto / FormSubmit

La primera vez que alguien envíe el formulario, FormSubmit pide confirmar el email destino.
Revisá la bandeja de `lukassvergara@gmail.com` y aceptá el enlace de activación.

Para cambiar el destinatario, editá `contactEmail` en `src/pages/index.astro`.
