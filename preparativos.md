# Preparativos

## Guía de Instalación de Visual Studio Code

Visual Studio Code es un editor de código fuente ligero pero potente, que incluye soporte para depuración, control de versiones, y una amplia variedad de extensiones.

Para instalar la version apropiada de Visual Studio Code en tu máquina visita [su página web](https://code.visualstudio.com/)

## Instalando Git

Git es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente a lo largo del tiempo, colaborar con otros y gestionar versiones de sus proyectos de manera eficiente.

Para comprobar si Git está instalado en tu máquina, abre la terminal y ejecuta el siguiente comando:

### Distribuciones Linux:

- **Debian/Ubuntu**: `git --version`
- **OpenSUSE**: `git --version`
- **Fedora**: `git --version`
- **ArchLinux**: `git --version`

Si Git está instalado, deberías ver la versión instalada en la salida del comando. Si no está instalado, puedes proceder a instalarlo.

---

## Cómo instalar git en tu máquina

### Instrucciones para instalar Git

#### Debian/Ubuntu

```bash
sudo apt update
sudo apt install git
```

### OpenSuse

```bash
sudo zypper refresh
sudo zypper install git
```

### Fedora

```bash
sudo dnf install git
```

### ArchLinux

```bash
sudo pacman -S git
```

## Comandos Básicos de Git

### Comandos Básicos de Git

| **Comando**                        | **Descripción**                                                                     |
| ---------------------------------- | ----------------------------------------------------------------------------------- |
| `git init`                         | Inicializa un nuevo repositorio de Git en el directorio actual.                     |
| `git checkout -b <nombre_de_rama>` | Crea una nueva rama y cambia a ella.                                                |
| `git checkout <nombre_de_rama>`    | Cambia a una rama existente.                                                        |
| `git pull`                         | Descarga y fusiona cambios desde el repositorio remoto a la rama actual.            |
| `git push`                         | Envía los cambios locales al repositorio remoto.                                    |
| `git pull origin <nombre_de_rama>` | Obtiene y fusiona cambios de la rama específica desde el repositorio remoto.        |
| `git push origin <nombre_de_rama>` | Envía los cambios de la rama específica al repositorio remoto.                      |
| `git remote -v`                    | Muestra los repositorios remotos configurados y sus URLs.                           |
| `git diff`                         | Muestra las diferencias entre los cambios realizados y el último commit.            |
| `git add -A`                       | Agrega todos los cambios (nuevos, modificados y eliminados) al área de preparación. |
| `git commit -m "<mensaje>"`        | Guarda los cambios en el repositorio con un mensaje descriptivo.                    |
| `git status`                       | Muestra el estado de los cambios en el directorio de trabajo.                       |
| `git log`                          | Muestra el historial de commits en el repositorio.                                  |
