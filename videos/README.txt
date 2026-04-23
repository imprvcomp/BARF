ESTA CARPETA ES SOLO PARA VIDEOS PESADOS
=========================================

Los videos de la sección "Explicaciones" deben subirse acá por separado
para no inflar la carpeta /assets/.

Archivos esperados (subirlos manualmente a esta carpeta):

1. explain-problem.mp4   → aparece arriba del label "El problema"
2. explain-solution.mp4  → aparece arriba del label "La solución"

Cómo subirlos:
- Desde GitHub web: entrá a esta carpeta "videos" en tu repo,
  click "Add file" → "Upload files", arrastrá los 2 .mp4 y commit.
- Desde local: copiá los archivos a esta carpeta y hacé git add videos/*.mp4

La página ya está configurada para leerlos desde /videos/.
No hace falta tocar el index.html.

TAMAÑO RECOMENDADO: cada mp4 debe pesar menos de 25 MB para que
GitHub los acepte por web upload. Si son más grandes, usá Git LFS
o hospedalos en Cloudinary / Vimeo / un GitHub Release.

Alternativa: podés hospedar los videos en cualquier CDN externo
(Cloudinary, Bunny, Vimeo Pro, Mux) y cambiar el <source src="...">
en index.html por la URL absoluta.
