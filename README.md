# Newen Launcher - Updates

Este repositorio contiene solo los instaladores y los archivos de update del launcher.
No es el repositorio del codigo fuente.

## Que se publica aqui
- Instaladores para Windows (MSI y EXE).
- Archivo `latest.json` para el updater de Tauri.
- Notas de version en GitHub Releases.

## Como publicar una nueva version
1. Genera el build en tu maquina.
2. Crea un nuevo Release en GitHub (tag recomendado: `vX.Y.Z`).
3. Adjunta como assets:
   - `Newen Launcher_X.Y.Z_x64_en-US.msi`
   - `Newen Launcher_X.Y.Z_x64-setup.exe`
   - `latest.json`
4. Publica el Release.

## Descargas
La forma recomendada de descargar es desde la seccion **Releases** de este repo.

## Notas
- Este repo puede ser privado. Los assets del Release quedan privados.
- Si se cambia el nombre del producto o version, actualiza el `latest.json`.

## Soporte
Si necesitas ayuda, adjunta el reporte diagnostico generado desde el launcher.
