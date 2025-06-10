# Proyecto Maven y GitHub

Este proyecto tiene como objetivo automatizar y estandarizar el flujo de vida de la construcción de software con **Maven**, además de administrar versiones con **Git** en un repositorio remoto de **GitHub**.
Autor: Diego Hernando Chicuazuque Castiblanco

## 📌 Prerrequisitos
- Tener instalado [Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- Tener instalado [Maven](https://maven.apache.org/download.cgi)
- Tener instalado [Git](https://git-scm.com/)
- Tener una cuenta en [GitHub](https://github.com/)

---

## 🚀 Creación de un proyecto Maven
Ejecuta el siguiente comando para generar un proyecto Maven:
```sh
mvn archetype:generate -DgroupId=com.ejemplo -DartifactId=mi-proyecto -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
Esto generará una estructura básica para tu proyecto.

---

## 🔧 Inicializar Git y conectar con GitHub
1. **Navega al directorio del proyecto**:
   ```sh
   cd mi-proyecto
   ```
2. **Inicializa un repositorio Git**:
   ```sh
   git init
   ```
3. **Agrega y confirma cambios**:
   ```sh
   git add .
   git commit -m "Inicialización del proyecto Maven"
   ```
4. **Conectar con el repositorio remoto**:
   ```sh
   git remote add origin https://github.com/tu-usuario/tu-repositorio.git
   ```
5. **Subir los cambios al repositorio**:
   ```sh
   git push -u origin main
   ```

---

## 📦 Construcción y empaquetado del proyecto
Para compilar y empaquetar el código fuente en un `.jar`:
```sh
mvn package
```
El archivo resultante se encontrará en la carpeta `target/`.

---
## 📦 Evidencias
Estas estaran en un word con los pantallazos correspondientes

## ✅ Ejecutar el proyecto
Para ejecutar la aplicación generada:
```sh
java -jar target/mi-proyecto-1.0-SNAPSHOT.jar
```

---

---

## 📄 Licencia
Este proyecto está bajo la licencia GNU.

---

¡Listo! Con este README, cualquiera podrá replicar el proceso y conectar su proyecto Maven con GitHub sin problemas. 🚀
```

Espero que esto sea justo lo que necesitabas. ¡Déjame saber si quieres que agregue algo más! 😊
