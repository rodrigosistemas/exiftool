# ExifTool

ExifTool es una herramienta para leer, escribir y editar metadatos en archivos.

## Revisar información de metadatos de un archivo
```bash
exiftool nombrearchivo.jpg /ruta/archivo
```

<img src="https://github.com/rodrigosistemas/exiftool/blob/main/img/exif.png" alt="nmap" width="500"/>

## Eliminar metadatos de un archivo
```bash
exiftool -all= -r /path/to/files
```
```bash
exiftool -all= -overwrite_original nombre_del_archivo
```
