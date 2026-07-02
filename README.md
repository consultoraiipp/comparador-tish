# Comparador de alícuotas TISH

Sitio estático publicado con **GitHub Pages**: https://consultoraiipp.github.io/comparador-tish/

## ⚠️ Importante — NO editar `index.html` a mano

`index.html` es **generado automáticamente** por `build_comparador.py` (en el repo privado
`agentes-amba`, Municipalidad de Tres de Febrero). Este repo solo aloja el HTML publicado.

**Cualquier edición directa de `index.html` se pierde** en la próxima regeneración/publicación
(y puede pisar cambios de otros). Para modificar el comparador:

1. Editar `interfaz/build_comparador.py` (o los datos) en `agentes-amba`.
2. Regenerar: `py interfaz/build_comparador.py`.
3. Copiar el HTML resultante como `index.html` acá y `git push`.

Antes de pushear, **siempre `git pull` primero** para no pisar cambios recientes.
El propio `index.html` lleva arriba un comentario con la fecha de build (para detectar copias viejas).
