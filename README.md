# WebPersonal

Blog personal desarrollado con HTML y CSS.

## Ejecutar localmente
Abre `home.html` en un navegador web. La fotografía se carga desde Unsplash y requiere conexión a Internet.

## Personalización
- Cambia la biografía y los intereses por tu información.
- Sustituye `tu-correo@ejemplo.com` por tu correo real.
- Cambia el nombre del título si lo deseas.

## Publicar en GitHub
Crea un repositorio público llamado `WebPersonal` en GitHub (sin README, si ya tienes esta carpeta preparada). Desde Git Bash, dentro de esta carpeta, ejecuta:

```bash
git init
git add home.html estilos.css README.md
git commit -m "Crear blog personal con HTML y CSS"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/WebPersonal.git
git push -u origin main
```

Reemplaza `TU-USUARIO` por tu nombre de usuario de GitHub. Para subir cambios posteriores:

```bash
git add .
git commit -m "Actualizar blog personal"
git push
```
