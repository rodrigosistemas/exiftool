# ExifTool

ExifTool is a tool to read, write, and edit metadata in files.

<img src="https://github.com/rodrigosistemas/exiftool/blob/main/img/exif.png" alt="exif" width="500"/>

## View metadata information of a file

```bash
exiftool filename.jpg /path/to/file
```

## Remove metadata from a file

```bash
exiftool -all= -r /path/to/files
```

```bash
exiftool -all= -overwrite_original filename
```
