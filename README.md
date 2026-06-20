<h1 align = "center " >Laboratorio de Virtualización con VirtualBox </h1> 

Debian, Windows 11 y automatización con PowerShell

Proyecto técnico de virtualización orientado a la administración de sistemas, basado en el uso de VirtualBox para la creación, configuración y gestión de entornos completos con sistemas operativos Linux y Windows.

El objetivo del proyecto es simular un entorno de laboratorio real de sistemas, incluyendo instalación de sistemas, redes, automatización y gestión de máquinas virtuales.
<br><br>
🎯 Objetivos del proyecto
Implementar entornos virtualizados con sistemas operativos reales
Configurar escenarios de red entre máquinas virtuales
Automatizar tareas de administración de VMs
Practicar gestión de almacenamiento y snapshots
Simular un entorno de laboratorio de sistemas completo

<br><br>
🧱 Contenidos del laboratorio
🐧 1. Instalación y configuración de Debian
Instalación completa de Debian GNU/Linux
Configuración del sistema base
Uso de herramientas:
apt update / upgrade
ip addr
Instalación de utilidades:
GParted
Vim, Git, Curl, Htop
Gestión de errores mediante snapshots de VirtualBox
<br><br>

🪟 2. Instalación de Windows 11 y Dual Boot
Instalación de Windows 11 en entorno virtual
Configuración de particionado de disco
Instalación de Debian en entorno dual boot
Configuración del gestor de arranque GRUB
Validación del arranque múltiple
<br><br>

🌐 3. Configuración de redes
Configuración de adaptadores de red en VirtualBox
Asignación de IP manual y dinámica
Pruebas de conectividad:
Ping a gateway
Ping a DNS (8.8.8.8)
Resolución de dominios
Comunicación entre máquinas virtuales
Diagramación de topología de red

<br><br>
📀 4. Clonación de máquinas virtuales
Clonación completa de máquinas
Clonación enlazada (linked clone)
Comparación de rendimiento y almacenamiento
Análisis de ahorro de recursos en entornos de laboratorio
<br><br>

📤 5. Exportación e importación de entornos
Exportación de máquinas en formato OVA
Importación en nuevos entornos
Verificación de integridad mediante hash SHA256
Control de versiones de entornos virtuales
<br><br>

⚙️ 6. Automatización con PowerShell
Script de creación automática de máquinas virtuales
Script de backup y exportación
Automatización de tareas repetitivas en VirtualBox
Programación de backups periódicos

<br><br>
🛠️ Tecnologías utilizadas
Oracle VirtualBox
Debian GNU/Linux
Windows 11
PowerShell
GRUB
Herramientas de red (ip, ping, etc.)

<br><br>

📁 Estructura del proyecto
VirtualBox-VMs-Debian-Windows/
│
├── scripts/
│   ├── crear-vm.ps1
│   └── backup-vms.ps1
│
├── capturas/
│   └── (screenshots del laboratorio)
│
├── docs/
│   └── TRABAJO_WORD_VIRTUALBOX.docx
│
└── README.md
