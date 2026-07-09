# Impulso Positivo — PWA

Este paquete convierte el HTML original en una PWA más completa.

## Archivos incluidos

- `index.html`: la app.
- `manifest.json`: nombre, iconos, color, modo standalone.
- `service-worker.js`: caché básica para que cargue como app y pueda funcionar offline.
- `icons/`: iconos para Android, iPhone y escritorio.

## Cómo subirlo a GitHub Pages

1. Crea o abre el repositorio.
2. Sube todos estos archivos a la raíz del repositorio.
3. En GitHub: Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: main / root.
6. Abre la URL pública en el móvil.
7. En Android: Chrome debería permitir “Instalar app”.
8. En iPhone: Safari > Compartir > Añadir a pantalla de inicio.

## Nota

Los datos de la app se guardan en `localStorage`, es decir, en el dispositivo del usuario.
No hay servidor, base de datos ni sincronización entre dispositivos.
