# Manual Básico de GitHub para Proyectos

## Introducción a GitHub

### ¿Qué es GitHub?

GitHub es una plataforma en internet que permite guardar y organizar proyectos, especialmente proyectos de programación. Está basado en una herramienta llamada **Git**, que ayuda a guardar diferentes versiones de los archivos de un proyecto. 

### ¿Para qué sirve GitHub?

GitHub sirve principalmente para:
- **Trabajar en equipo**: Varias personas pueden trabajar en el mismo proyecto sin estorbarse unas a otras. GitHub guarda los cambios de cada persona de forma ordenada.
- **Guardar versiones**: Si haces cambios en un archivo y luego quieres volver a una versión anterior, GitHub te permite hacerlo. Es como tener un historial de todos los cambios que se han hecho.
- **Compartir con otros**: Puedes compartir tus proyectos con otros usuarios de GitHub. Ellos pueden ver tu trabajo o incluso proponer mejoras.

### Ventajas de usar GitHub

1. **Colaboración fácil**: Es ideal para trabajar con otras personas, ya que todos pueden aportar al mismo proyecto.
2. **Historial de cambios**: Puedes ver qué cambios se han hecho en un archivo, quién los hizo y cuándo.
3. **Seguridad y respaldo**: Al estar en la nube, tus proyectos están seguros. Puedes acceder a ellos desde cualquier dispositivo con internet.
4. **Herramienta gratuita**: GitHub ofrece planes gratuitos para proyectos pequeños y medianos.
---

## **Cómo acceder a GitHub**

### Creación de una cuenta en GitHub

1. Abre el navegador de internet y ve a la página [https://github.com](https://github.com).
![gh1](https://hackmd.io/_uploads/HyZbb8Bl1e.png)

2. Haz clic en el botón "Sign up" o "Registrarse" que aparece en la página principal.
![gh2](https://hackmd.io/_uploads/HkQOZUrgkg.png)

3. Completa la información que se te pide en el sitio web (correo electrónico, contraseña y nombre de usuario)

4. GitHub te mandará un codigo de verificación al correo electrónico,ingresalo en la pantalla correspondiente.
![image](https://hackmd.io/_uploads/SkaQX8rxkl.png)
![image](https://hackmd.io/_uploads/S1oPQIHlke.png)


5. Una vez que confirmes tu correo, tendrás acceso a tu cuenta de GitHub. También podrás iniciar sesión con tus credenciales.

---

## **Explorando la página de GitHub**

Una vez que inicias sesión en GitHub, verás su interfaz principal. Los elementos más importantes son:

1. **Barra de búsqueda**: Está en la parte superior y te permite buscar proyectos, usuarios o cualquier cosa dentro de GitHub.
![image](https://hackmd.io/_uploads/rJq1NUHeyx.png)

3. **Tu perfil**: A la derecha de la barra superior, verás tu nombre de usuario y un ícono. Aquí puedes ver tus proyectos, tus configuraciones, y más.
![image](https://hackmd.io/_uploads/SJsfN8Heyl.png)
![image](https://hackmd.io/_uploads/S1WB4Irgye.png)

4. **Repositorios**: Un repositorio es como una carpeta donde guardas tu proyecto. Puedes tener varios repositorios dentro de tu cuenta.
![image](https://hackmd.io/_uploads/SyKPNLSxJe.png)
![image](https://hackmd.io/_uploads/SJcYNIHxyg.png)



---

## **Usando GitHub desde la consola (terminal)**


### **Usar GitHub desde la consola en Linux**

#### Instalación de Git

Para trabajar con Git en Linux, primero debes instalarlo. Abre la consola y escribe el siguiente comando:

```bash
sudo apt-get install git
```

Este comando le dice a tu sistema que instale Git.

#### Configuración inicial

Después de instalar Git, necesitas configurarlo con tu nombre y correo electrónico (los mismos que usaste en GitHub). Esto se hace con los siguientes comandos:

```bash
git config --global user.name "Nelson Mejía"
git config --global user.email "nelsonchiquito@gmail.com"
```

#### Clonar un repositorio (traer un proyecto de GitHub a tu computadora)

1. Entra en la página de GitHub y busca el proyecto que te interesa.
2. Copia el enlace del proyecto (haz clic en el botón que dice "Code" y copia el enlace HTTPS).
3. En tu consola, ve a la carpeta donde quieres guardar el proyecto y escribe el siguiente comando:

```bash
git clone [enlace-del-proyecto]
```

Por ejemplo:

```bash
git clone https://github.com/usuario/proyecto.git
```

Esto descargará el proyecto en tu computadora.

#### Subir cambios a GitHub

Una vez que hayas hecho cambios en tu proyecto y quieras subirlos a GitHub, sigue estos pasos:

1. **Añadir archivos**:

```bash
git add .
```
Con este comando añadirás todos los cambios que haz realizado en el proyecto en el repositorio en linea.

2. **Confirmar cambios**:

```bash
git commit -m "Descripción de los cambios"
```
Escribe una descripción para que los demás sepan que cambios hiciste.

3. **Subir a GitHub**:

```bash
git push origin main
```

---

### **Usar GitHub desde la consola en Windows**

#### Instalación de Git en Windows

1. Ve al sitio web oficial de Git: [https://git-scm.com/](https://git-scm.com/) y descarga la versión de Git para Windows.
2. Instálalo siguiendo los pasos en pantalla. Una vez instalado, puedes usar la consola de Git, llamada **Git Bash**, para ejecutar comandos.

#### Configuración inicial

Al igual que en Linux, debes configurar Git con tu nombre y correo. Abre Git Bash (lo encontrarás en el menú de inicio) y escribe los siguientes comandos:

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@ejemplo.com"
```

#### Clonar un repositorio

1. Copia el enlace del proyecto en GitHub.
2. Abre **Git Bash** y escribe:

```bash
git clone [enlace-del-proyecto]
```

Esto descargará el proyecto en tu computadora.

#### Subir cambios

Para subir cambios a GitHub desde Windows:

1. **Añadir archivos**:

```bash
git add .
```

2. **Confirmar cambios**:

```bash
git commit -m "Descripción de los cambios"
```

3. **Subir a GitHub**:

```bash
git push origin main
```

---

## **Comandos básicos de Git**

Aquí tienes un resumen de los comandos que más usarás:

- `git clone [enlace]`: Copia un proyecto de GitHub a tu computadora.
- `git add [archivo]`: Añade un archivo para que Git lo rastree.
- `git add .`: Añade todos los archivos nuevos o modificados.
- `git commit -m "mensaje"`: Guarda una versión del proyecto con un mensaje que describa los cambios.
- `git push`: Sube los cambios a GitHub.
- `git pull`: Trae los últimos cambios desde GitHub a tu computadora.

