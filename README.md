# HolaMundoApp 🚀

Este es un proyecto Android básico en **Kotlin** que muestra un simple "Hola Mundo".  
Está configurado con **GitHub Actions** para compilar automáticamente el APK sin necesidad de Android Studio en tu computadora.

## 📦 Cómo usarlo

1. **Clona este repositorio** o sube el contenido a tu propio GitHub.

```bash
git clone https://github.com/tuusuario/HolaMundoApp.git
```

2. Asegúrate de que tu rama principal se llame **main**.

3. Cada vez que hagas un **push**, se ejecutará el workflow de GitHub Actions.

## ⚙️ GitHub Actions

- El archivo del workflow está en: `.github/workflows/android.yml`  
- Se encarga de:  
  1. Descargar dependencias.  
  2. Configurar JDK 17.  
  3. Compilar el APK en modo **debug**.  
  4. Subir el APK como **Artifact** descargable.

## 📲 Descargar el APK

1. Ve a la pestaña **Actions** en tu repositorio de GitHub.  
2. Selecciona el último workflow exitoso.  
3. En la parte inferior, busca la sección **Artifacts**.  
4. Descarga el archivo llamado **app-debug** → contiene tu APK (`app-debug.apk`).  

## ✅ Requisitos

- Una cuenta en GitHub.  
- Hacer commit/push al repositorio para disparar el workflow.  

¡Listo! Ahora tendrás siempre disponible tu **APK de Hola Mundo** compilado automáticamente. 🎉
