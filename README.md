# CURSOR AI - FIX TOO MANY TRIALS

## 1. Desinstalar completamente cursor
Para desinstalar completamente **Cursor**, sigue estos pasos según tu sistema operativo:

   ### 1.1 **En Windows:**
      1.1.1. **Desinstalar desde el Panel de Control:**
         - Ve a **Panel de Control > Programas > Programas y características**.
         - Busca **Cursor** en la lista de programas instalados.
         - Haz clic derecho sobre Cursor y selecciona **Desinstalar**.
         - Sigue las instrucciones para completar la desinstalación.

      1.1.2. **Eliminar archivos residuales:**
         - Abre el Explorador de archivos y navega a:
         ```
         C:\Users\<TuUsuario>\AppData\Local\
         ```
         - Busca y elimina la carpeta **Cursor** si existe.
         - También revisa en:
         ```
         C:\Program Files\ o C:\Program Files (x86)\
         ```
         y elimina cualquier carpeta relacionada con Cursor.

      1.1.3. **Eliminar entradas del registro (opcional):**
         - Presiona `Win + R`, escribe `regedit` y presiona Enter.
         - Navega a:
         ```
         HKEY_CURRENT_USER\Software\
         ```
         y busca una clave llamada **Cursor**. Elimínala si existe.
         - Repite el proceso en:
         ```
         HKEY_LOCAL_MACHINE\Software\
         ```

      1.1.4. **Reiniciar el sistema:**
         - Reinicia tu computadora para asegurarte de que todos los cambios surtan efecto.

   ### 1.2 **En macOS:**
      1.2.1. **Mover a la Papelera:**
         - Abre la carpeta **Aplicaciones**.
         - Busca **Cursor** y arrástralo a la Papelera.

      1.2.2. **Eliminar archivos residuales:**
         - Abre el Finder y presiona `Cmd + Shift + G`.
         - Ingresa las siguientes rutas y elimina las carpetas relacionadas con Cursor:
         ```
         ~/Library/Application Support/
         ~/Library/Preferences/
         ~/Library/Caches/
         ~/Library/Logs/
         ```

      1.2.3. **Vaciar la Papelera:**
         - Haz clic derecho en la Papelera y selecciona **Vaciar Papelera**.


   ### 1.3 **En Linux:**
      1.3.1. **Desinstalar desde la terminal:**
         - Si instalaste Cursor usando un paquete `.deb` o `.rpm`, desinstálalo con:
         ```bash
         sudo apt remove cursor # Para distribuciones basadas en Debian/Ubuntu
         sudo dnf remove cursor # Para distribuciones basadas en Fedora
         ```

      1.3.2. **Eliminar archivos residuales:**
         - Elimina la carpeta de configuración de Cursor:
         ```bash
         rm -rf ~/.config/Cursor
         ```

      1.3.3. **Reiniciar el sistema:**
         - Reinicia tu sistema para asegurarte de que todos los cambios se apliquen.


Si sigues estos pasos, Cursor debería estar completamente desinstalado de tu sistema. ¡Espero que te haya sido útil! 😊
## 2. Instalar cursor version 0.44.11 con el archivo de instalación offline para su SO
## 3. Deshabilitar internet
## 4. Abrir cursor e ir a preferences/Cursor Settings/General/Open editor settings/Application/Update/
## 5. Seleccionar Mode/Manual
## 6. Reiniciar cursor
## 7. Cerrar cursor
## 8. Aplicar parche reset_cursor_ai.sh:
```bash
chmod +x reset_cursor_ai.sh
./reset_cursor_ai.sh
```
# 9. Abrir cursor
# 10. Agregar cuenta

Link para descargar archivos de instalación de cursor 0.44.11 para Mac y Windows: https://drive.google.com/drive/folders/1Q7Popnj09lQF1Tgw1nRay82Gd8QyScyj?usp=sharing
