# SOF-releases

Aquí se publican **las versiones jugables** de *Sense of Fiction*, un juego 2D de acción y plataformas hecho con Godot. el proyecto esta expuesto a cambios. Este repositorio solo contiene descargas 0_O

## Versiones

**[v0.0.1-dev — versión preliminar](https://github.com/Nikheling/SOF-releases/releases/tag/v0.0.1-dev)** · Windows de 64 bits - unos 35 MB

Todas las versiones están en la sección [**Releases**](https://github.com/Nikheling/SOF-releases/releases).

## Cómo jugar

1. Entra en la versión que quieras y descarga el archivo `.zip` que aparece en **Assets**.
2. Descomprímelo.
3. Ejecuta `SenseOfFiction.exe`.

## Dato no tan importante:
Usa la tecla R para reiniciar toda la actividad del juego

No hay instalación: el motor viene incluido en el ejecutable.

## Si Windows muestra una advertencia

Es normal en juegos independientes sin firma digital. Si aparece **"Windows protegió su PC"**, pulsa **Más información → Ejecutar de todas formas**.

## Estado del juego

Las versiones marcadas como **Pre-release** son de desarrollo: pueden tener errores y contenido incompleto, y todo está sujeto a cambios.

## Tus partidas

Se guardan en tu carpeta de usuario: `%APPDATA%\Godot\app_userdata\Sense of Fiction`.

## Verificar una descarga

Cada versión publica en sus notas la huella **SHA-256** de su `.zip`. Para comprobarla en PowerShell:

```
Get-FileHash .\SenseOfFiction-v0.0.1-dev-windows.zip -Algorithm SHA256
```

## Créditos

Hecho con [Godot Engine](https://godotengine.org).
