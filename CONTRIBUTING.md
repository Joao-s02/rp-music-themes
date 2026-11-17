# Proponer un tema

Crea una rama y añade un archivo .rptheme dentro de themes/. Parte de templates/mi-tema.rptheme o de Minimalista y sigue docs/CREAR-TEMAS.md.

Incluye en la solicitud de cambios el nombre del tema, la versión de RP Music utilizada y una captura de la biblioteca y del reproductor. Prueba en modo claro y oscuro, con texto ampliado y en las plataformas que tengas disponibles. Indica las plataformas pendientes.

Describe la autoría y el permiso o licencia que permite redistribuir cada imagen. Aporta recursos propios o cuya licencia permita incluirlos y compartirlos en este catálogo. La contribución debe identificar los términos de redistribución de su paquete.

El mantenimiento del catálogo revisa el archivo, la legibilidad de textos y estados de botones, las capturas y los permisos declarados. Después de aceptar el tema se añade su nombre, ruta y SHA-256 a catalog.json. Mantén el catálogo en version 1. Las rutas se resuelven desde el propio índice.

Para obtener el hash en Windows puedes usar Get-FileHash con el algoritmo SHA256. En Linux o macOS puedes usar sha256sum o shasum -a 256. Usa el hash de los bytes finales del archivo y minúsculas al editar el catálogo.

La plantilla y Minimalista sirven para aprender el formato. La licencia general del proyecto está pendiente de elección. Los recursos de terceros deben conservar sus créditos y sus términos específicos.
