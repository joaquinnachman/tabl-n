# Tablón

App de fútbol para Android: partidos del día, en vivo, tablas (también en vivo), llaves de las copas, formaciones y estadísticas.

## Instalarla

1. Desde el celular, bajá **[Tablon.apk](https://raw.githubusercontent.com/joaquinnachman/tabl-n/main/Tablon.apk)**.
2. Abrí el archivo. Si Android lo pide, permití instalar apps de esa fuente (el navegador o Archivos).
3. Listo. Desde ahí, cuando haya una versión nueva la app avisa y se actualiza sola, sin desinstalar nada.

## Para el que la mantiene

- `version.json` es lo que consulta la app: si `code` es mayor que el de la app instalada, ofrece (o exige, con `"force": true`) la actualización.
- Cada versión va en `apk/Tablon-<versión>.apk`, firmada siempre con la misma clave, y `Tablon.apk` es una copia de la última para instalar por primera vez.
