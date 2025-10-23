Organizer Tool v1.2
===================

Este paquete incluye:

📁 Carpetas:
- logs/ → Carpeta interna para registros de ejecución (no modificar)
- desorganizados/ → Carpeta destino para archivos sin clasificar
- organizados/ → Carpeta destino para archivos organizados

📄 Archivos:
- autorun.txt → Archivo de configuración de ejecución automática
- autorun.py → Script de ejecución automática (no modificar)
- organizer.py → Lógica principal de organización (no modificar)
- config.json → Configuración de rutas y parámetros (no modificar)
- config_editor.py → Interfaz gráfica para editar la configuración (no modificar)
- config_editor.exe → Ejecutable principal
- icon.ico → Ícono utilizado en accesos directos
- INSTALAR.py → Script que crea accesos directos
- INSTALAR.exe → Ejecutable principal

🖥️ Requisitos del sistema:
- Sistema operativo: Windows 10 o superior
- Python 3.10+ (solo necesario si se ejecutan los scripts `.py` directamente)
- Permisos de escritura en el escritorio y en la carpeta del programa

🔐 Permisos requeridos:
Organizer Tool no requiere permisos de administrador para funcionar, siempre que se ejecute desde una carpeta local con permisos de escritura. Si el sistema impide crear accesos directos o modificar archivos, ejecutá la aplicación desde una ubicación como "Documentos" o "Escritorio".

No se recomienda ejecutar desde carpetas protegidas como "C:\Program Files", "C:\Windows", ni desde unidades de red con restricciones. Evitá también carpetas sincronizadas con servicios como OneDrive o Google Drive, ya que pueden bloquear escritura o alterar rutas.

🧪 Verificación de entorno seguro:
Antes de ejecutar Organizer Tool, asegurate de lo siguiente:

✔ Estás ejecutando el paquete desde una carpeta local (por ejemplo, "C:\Usuarios\TuNombre\Documentos\OrganizerTool")
✔ Tienes permisos para crear accesos directos en el escritorio
✔ Las carpetas "organizados", "desorganizados" y "logs" existen y permiten escritura
✔ No estás en una carpeta protegida por antivirus, control parental o políticas corporativas
✔ No estás ejecutando desde una unidad de red, nube o carpeta sincronizada

📦 Instalación:
1. Extraiga el contenido del paquete en una carpeta local.
2. Ejecute "INSTALAR.exe" desde la raíz del proyecto.
3. Se crearán tres accesos directos en tu escritorio:
   - Organizer Tool → abre la aplicación principal
   - Organizados → acceso directo a la carpeta de archivos organizados
   - Desorganizados → acceso directo a la carpeta de archivos sin clasificar

🧼 Limpieza y regeneración:
- Si quieres regenerar los accesos directos, puedes volver a ejecutar "INSTALAR.bat".
- Para limpiar los accesos del escritorio, simplemente elimina los accesos directos manualmente.
- No borres ni edites los archivos `.json`, `.py` ni las carpetas internas sin respaldo.

Advertencias importantes:

❌ No borres ni renombres los siguientes archivos:
   - config.json
   - autorun.py
   - organizer.py
   - config_editor.py
   - icon.ico
   - INSTALAR.py

❌ No edites los archivos `.py` ni `.json` a menos que sepas exactamente lo que estás haciendo. Alterarlos puede romper la funcionalidad del programa.

❌ No borres ni renombres las carpetas "organizados", "desorganizados" o "logs". Son utilizadas por la aplicación y el script de instalación.

❌ No ejecutes "INSTALAR.exe" desde otra ubicación. Siempre debe ejecutarse desde la carpeta raíz del proyecto.

## 🆕 Cambios en la versión 1.1

- Interfaz mejorada
- Comandos con nombres legibles
- Corrección en el sistema de categorías (formato de comandos)
- Registro de movimientos más robusto para deshacer
- Manejo de codificación más seguro
- Lógica de limpieza de duplicados refinada
- Uso de `pathlib`, `argparse`, y función `main()` para mayor claridad y portabilidad

## 🆕 Cambios en la versión 1.2

- Scrollbar añadida a la interfaz
- Funcion de instalar mejorada

Autor: Fabian  
Versión: 1.2 
Fecha: Octubre 
