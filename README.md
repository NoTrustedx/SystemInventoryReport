## 🧾 SystemInventoryReport.bat

Este script por lotes (batch) para Windows permite recolectar rápidamente información técnica del sistema, incluyendo datos del CPU, memoria, disco, BIOS, motherboard y sistema operativo. Toda la información se almacena en un archivo de texto plano para facilitar el análisis o la documentación.

## 🔍 ¿Qué hace este script?

Genera un archivo `reporte_sistema.txt` con la siguiente información:

- 📌 Información general del sistema (`systeminfo`)
- 💽 Información de discos desde el Registro
- 🖥️ Nombre del host y GUID de la máquina
- 🧠 CPU y capacidad máxima de memoria
- 🧱 Placa base (motherboard): modelo y versión
- 🔐 Versión del BIOS
- 🪟 Detalles del sistema operativo (nombre, arquitectura y versión)
- 📂 Detalles de unidades físicas de disco

## 🚀 Cómo usar

1. Descarga o clona este repositorio.
2. Ejecuta el script **haciendo doble clic** o desde CMD:

```cmd
Recolectar-InfoSistema-Windows.bat
````

> 📌 **Nota:** se recomienda ejecutarlo con permisos de administrador para asegurar acceso completo a todas las claves del registro.


## 📄 Archivo generado

Al finalizar, el script genera un archivo llamado:

```
reporte_sistema.txt
```

Puedes abrirlo con cualquier editor de texto (Notepad, VS Code, etc.).

## 📦 Requisitos

* Sistema operativo Windows (7, 10, 11 o Server)
* Símbolo del sistema (`cmd.exe`)
* Acceso a herramientas como `wmic`, `reg`, `systeminfo`, etc.

## 🎯 Casos de uso

* Documentación rápida de sistemas
* Auditorías básicas en entornos corporativos o domésticos
* Análisis previo a clonación, respaldo o actualización de hardware/software
* Inventariado de equipos para soporte técnico

## 🧑‍💻 Autor

Erick O.
🔗 GitHub: [@NoTrustedx](https://github.com/NoTrustedx)

## 📄 Licencia

Este script se distribuye bajo la **Licencia MIT**, lo que permite su uso, modificación y distribución libre.
