# Imagen del servidor con contenido Season 8

Compila en GitHub la imagen de OpenMU con el contenido S8 (Acheron y Debenter con sus bichos, spawns,
NPC y terreno; los ítems de equipo nuevos; las puertas; y el tope de master level en 330).

**Nunca se compila en la máquina de Mundy.** La receta deja la imagen como artefacto; en el lab solo se
hace `docker load`.

- `s8-servidor.patch`: el parche, generado sobre el commit `9693f8f6` de MUnique/OpenMU.
- `.github/workflows/imagen-s8.yml`: la receta.
