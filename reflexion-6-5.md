Rebase interactivo que permite reescribir el historial de commits.
Ventaja: Puedes reordenar, combinar, modificar o eliminar commits para mantener un historial más limpio y lógico.

reword:

Uso: Cambiar el mensaje de un commit sin modificar su contenido.
Cuándo usarlo: Cuando el mensaje de un commit es confuso o tiene errores.

squash:

Uso: Combina múltiples commits en uno solo.
Cuándo usarlo: Cuando tienes varios commits pequeños relacionados que deberían ser un solo cambio.

drop:

Uso: Elimina un commit del historial.
Cuándo usarlo: Cuando un commit es innecesario o erróneo.

Riesgos de usar mal git rebase -i:

Reescritura del historial: Si haces un rebase en ramas compartidas, puedes causar conflictos y problemas de sincronización.
Pérdida de trabajo: Puedes eliminar commits accidentalmente al usar drop u otros comandos.
Confusión para otros colaboradores: Si otros ya basaron su trabajo en esos commits, tendrán problemas para integrar sus cambios.

Precaución:
Usar rebase solo en ramas no compartidas o asegúrate de que todos los colaboradores estén al tanto para evitar conflictos. En ramas compartidas, prefiera git merge para no reescribir el historial.
