# 🔍 OSINT Finding: Impresoras 3D (OctoPrint) expuestas en Shodan

## Descripción

Durante una investigación personal motivada por mi interés en la impresión 3D, utilicé **Shodan** para identificar dispositivos IoT relacionados expuestos públicamente en internet. El hallazgo principal fueron instancias de **OctoPrint** (interfaz de control remoto para impresoras 3D) accesibles sin autenticación, permitiendo su manipulación directa desde cualquier parte del mundo.

Este contenido tiene **fines exclusivamente educativos y de concientización** sobre la exposición de dispositivos IoT mal configurados en internet. No se realizó ninguna acción no autorizada ni se explotó ninguna vulnerabilidad; toda la información documentada es de acceso público.

## 🎥 Video

📺 Ver video completo: https://youtu.be/x4QMOMYFnQ4?si=u2ViEZi9gE3McJy7

![Portada del video](portada.png)

...

## 🛠️ Dorks / Filtros utilizados en Shodan

\`\`\`
title:"OctoPrint" true
\`\`\`

![Hallazgo en Shodan - impresora OctoPrint expuesta](shodan-hallazgo1.jpg)
![Hallazgo en Shodan - panel de control accesible](shodan-hallazgo2.jpg)

## 🛠️ Dorks / Filtros utilizados en Shodan

\`\`\`
title:"OctoPrint" true
\`\`\`

## ⚠️ Disclaimer

Este research fue realizado con fines educativos, sin interactuar de forma maliciosa con ningún dispositivo. Se recomienda a los propietarios de instancias OctoPrint expuestas:

- Configurar autenticación obligatoria
- No exponer el servicio directamente a internet sin VPN o túnel seguro
- Revisar la configuración de red y firewall de sus impresoras

## 📌 Tags

`#OSINT` `#Shodan` `#IoT` `#OctoPrint` `#Ciberseguridad` `#InfoSec`
