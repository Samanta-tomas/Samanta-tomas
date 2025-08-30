# Guía rápida para publicar esto en GitHub

1) Crear cuenta en https://github.com y definir tu **username**.
2) Si querés que sea tu **Profile README**: creá un repo con el mismo nombre que tu usuario (ej: `samantatomas`).
3) Subir archivos:
   - Opción A (web): Entrá al repo → Add file → Upload files → Arrastrá el ZIP y descomprimí en tu PC para subir los archivos sueltos.
   - Opción B (git):
     ```bash
     git init
     git add .
     git commit -m "Portfolio inicial"
     git branch -M main
     git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
     git push -u origin main
     ```
4) Fijá (pin) los proyectos de `projects/` como repos separados cuando tengas código/prototipos.
5) Agregá tu **CV en PDF** dentro de `docs/` y tu **foto** en `assets/`.