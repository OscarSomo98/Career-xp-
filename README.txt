CAREER XP — V2.3

CAMBIOS DE ESTA VERSIÓN
- Nuevo estado FISIO en el calendario de Entreno.
- FISIO aparece en naranja para distinguirlo de Entreno (verde) y REST (azul).
- Los días de fisio permiten guardar:
  - Qué se trabajó en fisio
  - Sensaciones
- El resumen mensual muestra también el número de sesiones de fisio.
- El registro del mes reúne entrenos, descansos y fisio con sus notas.
- Se mantiene compatibilidad con todos los datos guardados en versiones anteriores.

DATOS
Se conserva la misma clave de almacenamiento de Career XP V1 (careerXP.v1), así que actualizar los archivos del MISMO GitHub Pages no borra tus registros del iPhone.
Los datos continúan guardándose localmente en la web app del dispositivo. Exporta un respaldo JSON de vez en cuando.

CÓMO ACTUALIZAR TU GITHUB PAGES ACTUAL
1) En tu repositorio actual de Career XP, sustituye los archivos por los de esta carpeta.
2) Como mínimo sustituye index.html y sw.js. Puedes reemplazar todos sin problema.
3) Deben quedar en la raíz: index.html, sw.js, manifest.webmanifest y los iconos.
4) Haz Commit changes.
5) No cambies Settings > Pages: debe seguir main + /(root).
6) Espera a que Actions / Pages build and deployment termine en verde.
7) Abre la URL en Safari y recarga una vez; después cierra Career XP por completo y vuelve a abrir el icono.

IMPORTANTE
No borres datos de Safari para actualizar. Esta versión usa un nombre de caché nuevo (career-xp-v2-3) para forzar la renovación del contenido sin tocar tus datos locales.
