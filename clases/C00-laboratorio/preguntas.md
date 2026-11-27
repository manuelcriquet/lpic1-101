# C00 · Preguntas de autoevaluación
**Puntaje:** 7/8 · **Fecha:** 2026-11-26 · **Tiempo:** 10 min

1. ¿Qué comando muestra los discos y particiones como árbol?
   <details><summary>Respuesta</summary>`lsblk`</details>

2. ¿Qué archivo contiene el nombre y la versión de la distribución? A) `/etc/os-release` B) `/proc/version` C) `/etc/hostname` D) `/boot/grub/grub.cfg`
   <details><summary>Respuesta</summary>A</details>

3. ¿Qué comando muestra en una línea el nombre del kernel, su versión y la arquitectura?
   <details><summary>Respuesta</summary>`uname -a`</details>

4. ¿Qué comando calcula el hash SHA-256 de un archivo? A) `hash -s` B) `sha256sum` C) `checksum` D) `sum256`
   <details><summary>Respuesta</summary>B (`sha256sum`)</details>

5. ¿Qué comando crea `/a/b/c` junto con los directorios padre que falten?
   <details><summary>Respuesta</summary>`mkdir -p /a/b/c`</details>

6. Si `archivo` ya existe, `touch archivo`: A) lo borra B) lo vacía C) actualiza sus fechas sin tocar el contenido D) da error
   <details><summary>Respuesta</summary>C. Fallé: respondí B. `touch` no modifica el contenido.</details>

7. ¿Qué comando de git muestra el historial con un commit por línea?
   <details><summary>Respuesta</summary>`git log --oneline` (dos guiones)</details>

8. ¿Qué archivo le indica a git qué archivos y carpetas no versionar?
   <details><summary>Respuesta</summary>`.gitignore`</details>
