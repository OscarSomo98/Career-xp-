CAREER XP — V2.4 — MIS AFICIONES

NOVEDAD
- Nueva pestaña Aficiones, con los 7 pilares y todas las actividades de la lista proporcionada.
- Desplegables por pilar, casillas por actividad y notas opcionales para cada registro.
- Día de la semana opcional por actividad.
- Navegación por semanas (lunes a domingo), resumen de actividades y pilares.
- Gráfico de las últimas 6 semanas y nota general semanal.
- Las aficiones se guardan en el mismo respaldo JSON que el resto de datos.
- Se mantiene Entreno / REST / FISIO y las 3 categorías de trabajo sin cambios.
- Incluye el icono dorado de progreso y tiempo elegido para la app.

DATOS Y COMPATIBILIDAD
Misma clave localStorage de las versiones anteriores: careerXP.v1.
Se añade el campo hobbyWeeks sin borrar sessions, trainingDays ni preferencias.
Antes de actualizar: Career XP > Ajustes > Exportar JSON y guardar la copia en Archivos.
NO borres el icono viejo, la web app ni los datos de Safari para forzar la actualización.

CÓMO ACTUALIZAR
1. Descomprime el ZIP en Archivos.
2. En GitHub abre el MISMO repositorio Career-xp-, rama main, raíz.
3. Sube index.html y sw.js nuevos, reemplazando los existentes; si quieres el icono dorado sube también icon-180.png, icon-192.png e icon-512.png.
4. Haz Commit changes. Pages se redesplegará automáticamente desde main y /(root).
5. Abre la URL en Safari y recarga. Cierra por completo Career XP y vuelve a abrirla.
6. La opción Aficiones debe aparecer en la barra inferior.

IMPORTANTE
Los datos se guardan localmente en el contexto de la web app instalada en tu iPhone; no se sincronizan automáticamente con otros dispositivos. Exporta JSON de forma periódica.
