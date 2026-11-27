# Registro de errores

| Fecha | Clase | Qué falló | Causa | Solución | Cómo evitarlo |
| --- | --- | --- | --- | --- | --- |
| 2026-11-25 | C00 | `md5sum -c md5sum.txt` dio "933 listed files could not be read" | Usé el `md5sum.txt` interno de la ISO, que lista sus archivos, no la ISO | Bajar `SHA256SUMS` y correr `sha256sum -c SHA256SUMS --ignore-missing` | Verificar con el archivo de hashes publicado junto a la ISO |
| 2026-11-25 | C00 | `ipaddr`: command not found | Faltó el espacio | `ip addr` o `ip a` | Subcomando separado por espacio |
| 2026-11-25 | C00 | `uname .a`: extra operand | Punto en lugar de guion | `uname -a` | Las opciones empiezan con `-` |
| 2026-11-26 | C00 | Pregunta 6: respondí que `touch` vacía el archivo | Lo confundí con la redirección `>` | `touch` solo actualiza fechas | Probar: `echo hola > a; touch a; cat a` |
| 2026-11-26 | C00 | `git log –oneline` con guion largo | El procesador de texto lo convirtió | Escribir `--oneline` en la terminal | Escribir los comandos directo en el `.md` |
