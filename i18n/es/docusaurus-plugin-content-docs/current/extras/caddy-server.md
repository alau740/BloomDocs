---
id: caddy-server
title: Creando un split Caddy
hide_table_of_contents: false
sidebar_label: Servidor Web Caddy
description: Esta guía te ayudará a crear un split de Caddy.
keywords:
  - Caddy
  - Caddy Server
---

Hola Bloomers! 👋

En esta guía veremos cómo crear un split Caddy para poder hostear páginas web en tu servidor de Bloom.host.

---

## Creando el split Caddy

1. Dirígete a la ventana de **Server Splitter** (División de Servidor) en el panel de control de tu servidor.
![caddyserver](/extras/caddy_server/1.PNG)

2. En **SERVER NAME** (NOMBRE DEL SERVIDOR) ingresa un nombre para tu split y en **SERVER CATEGORY** (CATEGORÍA DEL SERVIDOR)
   elige **NO SUPPORT SERVERS** (SERVIDORES SIN SOPORTE), en **SERVER TYPE** (TIPO DE SERVIDOR) elige "Caddy Server".
   Para iniciar puedes dejar **MEMORY** (MEMORIA) en 100MB y **DISK** en cuánto espacio tu servidor web necesita. Finalmente
   presiona **SPLIT SERVER** (DIVIDIR SERVIDOR).
![caddyserver](/extras/caddy_server/2.PNG)

3. Te saldrá una ventana de confirmación como la de abajo. Presiona **YES, SPLIT THIS SERVER** (SÍ, DIVIDIR ESTE SERVIDOR).
   Esto dividirá tu servidor principal y creará un split Caddy.
![caddyserver](/extras/caddy_server/3.PNG)

---

## Configurando el servidor Caddy.

Para iniciar, simplemente deja los archivos html/php en la carpeta `/public` del servidor Caddy. Ahora ya puedes iniciar el servidor!
Si quieres usar un dominio para tu servidor puedes seguir [esta guía](/es/ports-and-proxies/) para usar un
proxy inverso.
