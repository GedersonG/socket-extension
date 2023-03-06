# Sockets para NodeJS

[![DatAge](https://raw.githubusercontent.com/GedersonG/socket-extension/main/img/Adjust-logo.png)](https://datage-production.up.railway.app/)

## Table of Contents
1. [Información general](#1--información-general)
2. [Tecnologías](#2--tecnologías)
3. [Instalación](#3-%EF%B8%8F-instalación)
4. [Preguntas frecuentes](#4--preguntas-frecuentes)
5. [Licencia](#5--licencia)

### 1. 🤔 Información general

Esta extensión está construida en JavaScript. Contiene cinco (5) snippets para NodeJS que podemos utilizar principalmente en nuestra clase que contiene la conexión y comunicaciones de Sockets cliente / servidor.

Los fragmentos de código que contienen los snippets son estructuras básicas de métodos con sockets, como la inicialización de una conexión o una función básica de los WebSockets como emitir o escuchar.

Aunque estos fragmentos contienen la estructura básica de la utilización más general de éstos métodos, no es una obligación que esa deba ser su estructura sino una sugerencia que nos ayude a redactar código de manera mas rápida.

A continuación, se detallarán los snippets que implementa esta extensión:

#### NewSocket

Inicia la conexión cliente/servidor con la sugerencia de escucha "connection", permitiendo un espacio donde podemos escribir nuestra lógica correspondiente al inicio de conexión.

Para llamar al snippet, escribimos _NewSocket_ y presionamos _Enter_ o _Tab_

```sh
export default (io) => {
    io.on("connection", (socket) => {
        //Enter your code here

    }) //End method connection
}
```

#### Socket.on

Este snippet genera el fragmento de código que permite escuchar desde la perspectiva del socket del lado del servidor.

Para llamar al snippet, escribimos _SocketOn_ y presionamos _Enter_ o _Tab_

```sh
socket.on("", async ({data}) => {
    //Enter your code here

})
```

#### Socket.emit

Este snippet genera el fragmento de código que permite emitir desde la perspectiva del socket del lado del servidor.

Para llamar al snippet, escribimos _SocketEmit_ y presionamos _Enter_ o _Tab_

```sh
socket.emit("", {data})
```

#### Socket.broadcast

Este snippet genera el fragmento de código que permite emitir a todos los oyentes a excepción de la conexión en cuestión (Everyone but me) desde la perspectiva del socket del lado del servidor.

Para llamar al snippet, escribimos _SocketBroadcast_ y presionamos _Enter_ o _Tab_

```sh
socket.broadcast.emit("", {data})
```

#### Io.emit

Este snippet genera el fragmento de código que permite emitir desde la perspectiva del socket del lado del cliente.

Para llamar al snippet, escribimos _IOEmit_ y presionamos _Enter_ o _Tab_

```sh
io.emit("", {data})
```

### 2. 🔗 Tecnologías

- [Azure DevOps](https://azure.microsoft.com/es-es/products/devops) - Suministrador de organización encargada de la administración de servicios marketplace.
- [JavaScript](https://www.javascript.com/) - Lenguaje principal utilizado para el desarrollo del plugin.
- [Marketplace Visual Studio Code](https://marketplace.visualstudio.com/vscode) - Plataforma encargada del gestionamiento de la extensión.

### 3. ⚡️ Instalación

Para instalar el plugin DatAge: Sockets, es necesario tener previamente instalado el editor de texto [Visual Studio Code](https://code.visualstudio.com/), a continuación desde la pestaña de Extensiones, o bien con el comando Crtl + Shift + X (windows) buscamos la extensión **DatAge** y presionamos _Install_.

![Extensión sockets - DatAge](https://raw.githubusercontent.com/GedersonG/socket-extension/main/img/extension-datage.PNG)

### 4. 💬 Preguntas frecuentes

- **¿Por qué usar la extensión DatAge: Sockets?**
    La extension _**DatAge:** Sockets_ permite facilitar la construcción de métodos básicos que se implementan en los sockets como emitir y escuchar por parte de los sockets en el servidor y cliente, además de iniciar la comunicación recibiendo la conexión HTTP del usuario en cuestión.

### 5. 📫 Licencia

Licencia MIT

**Free Software !!! :D**

## 👯‍♀️ Authors

- [@gederson](https://www.github.com/GedersonG)

- [@CamiloR](https://www.github.com/CamiloRamirezP)

- [@name](https://www.github.com/)

- [@name](https://www.github.com/)

- [@name](https://www.github.com/)

## Documentation

[Documentation](https://docs.google.com/document/d/1gewPhSp0FSilMlkJxB-aGiw4JRkLItmUHs6Aegr1xIM/edit?usp=sharing)
