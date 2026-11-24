# Tablón

App de fútbol para Android: partidos del día, en vivo, tablas (también en vivo), todas las categorías del fútbol argentino (de la Liga Profesional al Promocional Amateur y el Federal A), cuadros de llaves de playoffs y copas, reglamentos de ascenso y descenso, historial de campeones y tablas desde 1891, formaciones, estadísticas, planteles, promedios del descenso, tabla anual, videos, marcador en vivo en la notificación y dos widgets (partidos de hoy y próximo partido con cuenta regresiva).

## Instalarla

1. Desde el celular, bajá **[Tablon.apk](https://raw.githubusercontent.com/joaquinnachman/tabl-n/main/Tablon.apk)**.
2. Abrí el archivo. Si Android lo pide, permití instalar apps de esa fuente (el navegador o Archivos).
3. Listo. Desde ahí, cuando haya una versión nueva la app avisa y se actualiza sola, sin desinstalar nada.

## Para el que la mantiene

- `version.json` es lo que consulta la app: si `code` es mayor que el de la app instalada, ofrece (o exige, con `"force": true`) la actualización.
- `"pmver"` (opcional) es la versión que se le informa a la API de Promiedos (header `X-VER`); si un día deja de responder por versión vieja, se cambia acá sin sacar un APK nuevo.
- Cada versión va en `apk/Tablon-<versión>.apk`, firmada siempre con la misma clave, y `Tablon.apk` es una copia de la última para instalar por primera vez.
