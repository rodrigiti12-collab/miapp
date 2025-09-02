# MiApp Python con Kivy

Proyecto básico en **Python + Kivy** para generar un **APK en Android** usando Buildozer.

## Archivos incluidos
- `main.py` → código principal de la app.
- `buildozer.spec` → configuración de Buildozer.
- `README.md` → explicación del proyecto.

## Cómo compilar el APK
1. Instalar dependencias en Linux:
   ```bash
   sudo apt update
   sudo apt install -y python3-pip git zip unzip openjdk-17-jdk
   pip install --upgrade pip
   pip install buildozer cython
   ```

2. Inicializar buildozer (ya tienes el archivo `buildozer.spec`):
   ```bash
   buildozer -v android debug
   ```

3. El APK se generará en la carpeta `bin/`.
