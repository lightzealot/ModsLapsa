# Guía de Contribución

## Para Administradores del Servidor

### Añadir un Nuevo Mod

1. Descarga el archivo `.jar` del mod desde su fuente oficial
2. Verifica que el mod sea compatible con la versión del servidor
3. Coloca el mod en la carpeta apropiada:
   - `mods/common/` - Si el mod es requerido en cliente y servidor
   - `mods/server/` - Si el mod solo funciona en el servidor
   - `mods/client/` - Si el mod es opcional para el cliente
4. Actualiza la lista de mods si existe
5. Commit y push de los cambios

### Actualizar un Mod

1. Descarga la nueva versión del mod
2. Elimina la versión antigua del repositorio
3. Añade la nueva versión en la misma carpeta
4. Actualiza la documentación si hay cambios importantes
5. Commit y push de los cambios

### Eliminar un Mod

1. Elimina el archivo `.jar` del repositorio
2. Actualiza la documentación
3. Notifica a los jugadores sobre la eliminación
4. Commit y push de los cambios

## Convenciones de Nombres

- Mantén los nombres originales de los archivos de los mods
- Ejemplo: `JEI-1.19.2-11.5.0.297.jar`

## Versiones

- Documenta la versión de Minecraft compatible
- Documenta la versión de Forge/Fabric requerida
- Mantén todos los mods actualizados a la misma versión de Minecraft
