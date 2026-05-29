
## 🔗 Enlaces del Proyecto
* **Repositorio GitHub:https://github.com/miguelitox20/myteacher-platform.git
* **Demo en vivo (Vercel/Railway):[myteacher-platform.vercel.app](https://myteacher-platform.vercel.app/)

# ConectaEstudia (Demo web)

Página web demo (HTML + React 18 vía Babel standalone) para presentar oportunidades laborales/estudios y simular un flujo de:

**Inicio → Oportunidades → Detalle → Aplicar → Mis Aplicaciones**

## Estructura
- `index.html`: contiene la app completa (datos mock + componentes React + estilos base dentro del archivo).
- `styles.css`: estilos globales (en esta demo, gran parte del CSS también vive dentro de `index.html`).
- `TODO.md`: checklist de mejoras realizadas.

## Funcionalidades principales
- Navegación entre páginas (Home, Oportunidades, Detalle, Perfil, Aplicaciones).
- Filtros y ordenamiento en la lista de oportunidades.
- Modal de confirmación al aplicar.
- Toast de confirmación al aplicar.
- Modo oscuro (tema) desde el navbar.
- Guardar oportunidad (estado local de la sesión) con feedback en el botón.

## Mejoras UX/Accesibilidad realizadas
- Botón **Guardar oportunidad** funcional (alternar guardado) con `aria-pressed`.
- Botones del navbar con `aria-label` (tema, notificaciones, perfil).
- Modal con `role="dialog"` y `aria-modal="true"`.
- Cerrar modal con **Escape**.
- Ajuste del componente `Icon` para soportar `style`.
- Nombre de perfil y archivo del CV ajustados a **Miguel Rodríguez**.

## Cómo ejecutar
1. Abre `index.html` directamente en tu navegador.
2. (Opcional) Si quieres evitar problemas por CORS/caché en algunos navegadores, usa un servidor estático simple.

Ejemplos (si tienes Python):
```bash
python -m http.server 5500
```
Luego entra a: `http://localhost:5500/index.html`

## Notas
- Los datos son **mock** dentro de `index.html`.
- El guardado y aplicaciones se manejan en **estado en memoria** (no persiste tras recargar la página).
