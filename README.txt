# Álvaro Balas - Práctica Git

**Práctica de gestión de ramas en Git (Realizado desde la terminal).**

Perdón por tardar tanto en realizar el trabajo, pero he estado ocupado con proyectos personales. 
GitHub lo uso a menudo, pero sobre todo para leer código de otras personas. Nunca subo nada, pero me parece muy sencillo su uso desde la terminal.

## Comandos usados en la práctica

### **Inicializar el repositorio**
```bash
git init
```
_Inicializa un nuevo repositorio Git en la carpeta actual._

### **Agregar archivos al área de staging**
```bash
git add .
```
_Añade todos los archivos nuevos o modificados al área de preparación (staging)._  

### **Realizar un commit**
```bash
git commit -m "Actualizar README.txt"
```
_Guarda los cambios en el historial del repositorio con un mensaje descriptivo._

### **Crear y cambiar de ramas**
```bash
git checkout -b nombre_rama
```
_Crea una nueva rama y cambia a ella._

### **Fusionar ramas en main**
```bash
git checkout main
git merge nombre_rama
```
_Une los cambios de una rama secundaria en la rama principal._

### **Eliminar un archivo del repositorio y hacer commit**
```bash
git rm a.txt
git commit -m "Eliminar archivo a.txt"
```
_Elimina un archivo del repositorio y registra el cambio._

### **Subir cambios al repositorio remoto en GitHub**
```bash
git push origin main
```
_Envía los cambios locales al repositorio remoto en la rama `main`._

### **Clonar un repositorio**
```bash
git clone https://github.com/usuario/repositorio.git
```
_Descarga un repositorio remoto a la máquina local._

### **Ver el historial de commits**
```bash
git log --oneline
```
_Muestra el historial de commits en una lista resumida._
