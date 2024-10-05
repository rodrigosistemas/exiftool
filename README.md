```markdown
# ExifTool

## Descripción
ExifTool es una herramienta para leer, escribir y editar metadatos en archivos.

## Revisar información de metadatos de un archivo
```bash
exiftool nombrearchivo.jpg /ruta/archivo
```

<img src="https://drive.google.com/uc?export=view&id=1o3ya8VHmCFMr0GKJQ45LhDc2KdH6nXz3" alt="exiftool">

## Eliminar metadatos de un archivo
```bash
exiftool -all= -r /path/to/files
```
```bash
exiftool -all= -overwrite_original nombre_del_archivo
```
