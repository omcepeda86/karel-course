# Karel Web — primera versión

Aplicación web sencilla para trabajar con mundos Stanford Karel (.w) sin instalar Python.

## Uso local
1. Sirve esta carpeta con un servidor HTTP (por ejemplo VS Code Live Server).
2. Abre `index.html` desde el servidor, no con doble clic.
3. El mundo inicial se busca en `worlds/Ejercicio4Clase5.w`.

## GitHub Pages
Sube todo el contenido de esta carpeta a un repositorio y activa Pages desde:
Settings → Pages → Deploy from a branch → main → /(root).

## Nota
Esta primera versión interpreta:
- move()
- turn_left()
- pick_beeper()
- put_beeper()

Todavía no implementa procedimientos, if, while o for. Es deliberadamente una base para probar la carga y ejecución de mundos `.w`.
