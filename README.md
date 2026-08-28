
░█████╗░██████╗░███████╗░█████╗░████████╗███████╗██████╗░  ██████╗░██╗░░░██╗
██╔══██╗██╔══██╗██╔════╝██╔══██╗╚══██╔══╝██╔════╝██╔══██╗  ██╔══██╗╚██╗░██╔╝
██║░░╚═╝██████╔╝█████╗░░███████║░░░██║░░░█████╗░░██║░░██║  ██████╦╝░╚████╔╝░
██║░░██╗██╔══██╗██╔══╝░░██╔══██║░░░██║░░░██╔══╝░░██║░░██║  ██╔══██╗░░╚██╔╝░░
╚█████╔╝██║░░██║███████╗██║░░██║░░░██║░░░███████╗██████╔╝  ██████╦╝░░░██║░░░
░╚════╝░╚═╝░░╚═╝╚══════╝╚═╝░░╚═╝░░░╚═╝░░░╚══════╝╚═════╝░  ╚═════╝░░░░╚═╝░░░

███████╗░█████╗░░█████╗░██╗░░██╗░█████╗░░░░░░░░░░░░░███████╗███████╗
██╔════╝██╔══██╗██╔══██╗██║░░██║██╔══██╗░░░░░░░░░░░░╚════██║╚════██║
█████╗░░███████║██║░░╚═╝███████║███████║░░░░░░░░░░░░░░███╔═╝░░███╔═╝
██╔══╝░░██╔══██║██║░░██╗██╔══██║██╔══██║░░░░░░░░░░░░██╔══╝░░██╔══╝░░
██║░░░░░██║░░██║╚█████╔╝██║░░██║██║░░██║██╗██╗██╗██╗███████╗███████╗
╚═╝░░░░░╚═╝░░╚═╝░╚════╝░╚═╝░░╚═╝╚═╝░░╚═╝╚═╝╚═╝╚═╝╚═╝╚══════╝╚══════╝



Para aclarar ciertas cosas y que todos entiendan bien cómo funciona el programa, quiero dejarles esto detallado:


El programa puede llegar a dar 2 falsos positivos en VirusTotal (2/69 motores de seguridad):


1 - Microsoft:
Trojan:Win32/Wacatac.B!ml (Falso positivo por empaquetado en Go/Wails)


2 - Trapmine:
Malicious.moderate.ml.score (Falso positivo por análisis heurístico de Machine Learning)


Solo 2 de 69 antivirus lo marcan, y en ambos casos son falsos positivos comunes al compilar ejecutables en Go que manejan procesos locales.


Si todavía tenés dudas o desconfianza, podés probarlo tranquilamente en una máquina virtual como VirtualBox, VMware o Windows Sandbox y revisar cada proceso por tu cuenta.

Por ahora voy a seguir metiendo updates enfocadas en mejoras visuales, optimización de rendimiento y cositas de personalización.


Nota sobre el uso de comandos y el sistema:


El programa ejecuta comandos internos de CMD y llamadas al sistema únicamente para tareas locales necesarias:

1 - Descargar e instalar las actualizaciones manualmente, (Solo si vos lo actualizas.)

2 - Crear las carpetas de "games" y "FakeExe" si no existen en tu PC.

3 - Mover y organizar los ejecutables correspondientes en sus carpetas ("games" y "FakeExe").

4 - Abrir, cerrar, pausar y gestionar temporizadores del "FakeExe.exe" mediante 25 niveles de algoritmos de variación de milisegundos (MS), para que Discord registre actividad humana natural y no patrones de bot.


Obtener tu usuario de Windows: 


El programa usa la API nativa de Windows llamada "GetUserNameW" (a través de la función estándar del sistema operativo). Esto sirve únicamente para mostrarte en tiempo real tu nombre de usuario en la interfaz del launcher.




Nota de privacidad:

El programa no envía, no guarda, no copia archivos de tu PC ni se comunica con ningún servidor externo o base de datos ajena. Todo se ejecuta de forma 100% local en tu computadora.