# VirtualBox - Máquinas Virtuales Debian y Windows

Proyecto educativo para aprender el uso de VirtualBox en el ciclo de Sistemas Microinformáticos y Redes (SMR).

## Descripción

Este proyecto documenta el proceso completo de trabajo con máquinas virtuales en VirtualBox, incluyendo:

- Instalación de Debian (individual)
- Instalación de Windows 11
- Configuración de Dual Boot (Debian + Windows)
- Configuración de redes
- Clonación de máquinas (completa y enlazada)
- Exportación e importación de máquinas
- Automatización con scripts PowerShell

## Contenido

### 1. Instalación de Debian
- Proceso paso a paso
- Comandos básicos (apt update, apt upgrade, ip addr)
- Instalación de GParted
- Paquetes adicionales (Vim, Git, Curl, Htop)
- Simulación de errores y restauración con instantáneas

### 2. Dual Boot (Debian + Windows)
- Instalación de Windows 11
- Particionado de discos
- Instalación de Debian en el espacio reservado
- Menú GRUB funcional

### 3. Configuración de Redes
- ip addr / ipconfig all
- Ping a Google (8.8.8.8 y google.com)
- Cambio de IP manual
- Comunicación entre máquinas
- Diagrama de red

### 4. Clones
- Clon completo
- Clon enlazado
- Comparación de tamaños
- Cálculo de ahorro en laboratorio FP

### 5. Exportación e Importación
- Exportación a OVA
- Cálculo de hash SHA256
- Verificación de tamaños

### 6. Scripts
- Script de creación automática de VM
- Script de backup/exportación
- Explicación de funcionamiento
- Programación de backup semanal

## Tecnologías

- VirtualBox
- Debian GNU/Linux
- Windows 11
- PowerShell
- GRUB

## Estructura del Proyecto
VirtualBox-VMs-Debian-Windows/
│
├── scripts/
│ ├── crear-vm.ps1 # Script creación VM
│ └── backup-vms.ps1 # Script backup
├── capturas/ # Capturas de pantalla
├── docs/
│ └── TRABAJO_WORD_VIRTUALBOX.docx
└── README.md

