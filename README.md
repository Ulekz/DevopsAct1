# DevopsAct1

Este repositorio forma parte de la **Actividad 01** del curso de DevOps.  
Contiene el archivo `Figuras.java`, el cual se utiliza para probar un flujo de integración continua con **Jenkins** y **GitHub**.

---

## 📁 Contenido

- `Figuras.java`: Código fuente en Java que imprime diferentes figuras geométricas (Cuadrado, Rombo, Abeto) usando caracteres.

---

## 🚀 Jenkins Job

Este repositorio fue utilizado en Jenkins para:

1. Clonar automáticamente este repositorio desde GitHub
2. Compilar el archivo `Figuras.java`
3. Ejecutar el programa usando comandos en Shell:

```bash
javac Figuras.java
java Figuras
