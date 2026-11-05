# P01 - Laboratorio profesional de desarrollo

## Proposito del proyecto

Crear un entorno profesional reproducible para desarrollar, probar y versionar
los proyectos del programa. El repositorio incluye terminal configurada,
Git/GitHub, VS Code y una coleccion Postman documentada.

## Tecnologias utilizadas

- Windows 11 (sistema principal)
- WSL2 + Ubuntu (entorno Linux complementario)
- VS Code + extension WSL
- Git y GitHub (autenticacion por SSH)
- Postman

## Requisitos previos

- Windows 11 con virtualizacion habilitada
- Conexion a internet
- Cuenta de GitHub

## Pasos de instalacion del entorno

### 1. Instalar WSL2 + Ubuntu

En PowerShell **como administrador**:

```powershell
wsl --install