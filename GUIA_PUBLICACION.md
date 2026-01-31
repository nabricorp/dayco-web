# Guía de Publicación: DAYCO Dental

Para que tu cliente vea la página y puedas actualizarla automáticamente desde tu computadora, la mejor opción profesional es conectar **GitHub con Netlify**.

Aquí te explico los dos métodos.

---

## Opción 1: La forma Rápida (Para mostrarla YA) ⚡
*Usa esta si quieres mandarle el link en 2 minutos, pero las actualizaciones serán manuales.*

1.  Entra a **[app.netlify.com/drop](https://app.netlify.com/drop)**.
2.  Toma la carpeta `dayco final` de tu computadora.
3.  **Arrástrala** dentro del cuadro punteado en la página.
4.  ¡Listo! Te dará un enlace (ej: `dayco-dental.netlify.app`) que puedes mandar por WhatsApp.

*Desventaja:* Si haces cambios mañana, tienes que volver a arrastrar la carpeta.

---

## Opción 2: La forma Profesional (Actualizaciones Automáticas) 🚀
*Esta es la que pediste: Haces un cambio en tu compu -> Se actualiza sola la página del cliente.*

### Paso 1: Crear el "Repositorio" (Nube)
1.  Crea una cuenta gratuita en **[GitHub.com](https://github.com/)**.
2.  Crea un "New Repository" con el nombre `dayco-web`.
3.  Sube los archivos de tu carpeta a ese repositorio (puedes usar GitHub Desktop o la web).

### Paso 2: Conectar Netlify
1.  Crea una cuenta en **[Netlify.com](https://www.netlify.com/)**.
2.  Dale clic a **"Add new site"** -> **"Import from existing project"**.
3.  Elige **GitHub** y selecciona tu repositorio `dayco-web`.
4.  Dale a **"Deploy"**.

### ¡Magia! ✨
A partir de ahora, cada vez que modifiques un archivo en tu computadora y guardes los cambios en GitHub (Push):
1.  Netlify lo detectará automáticamente.
2.  Actualizará la página web real en segundos.
3.  Tu cliente siempre verá la última versión sin que le tengas que mandar nada nuevo.

---

### Recomendación
Empieza con la **Opción 1** para mandarle el avance HOY.
Luego, tómate el tiempo de configurar la **Opción 2** para el mantenimiento a largo plazo.
