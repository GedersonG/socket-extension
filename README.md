# Sockets para NodeJS

[![](./img/datage-icon.png)](https://datage-production.up.railway.app/)

## Table of Contents
1. [Informacion general](#general-info)
2. [Tecnologías](#technologies)
3. [Instalación](#installation)
4. [Preguntas frecuentes](#faqs)
5. [Licencia](#license)

### 1. Información general

Esta extensión está construida en JavaScript. Contiene cinco (5) snippets para NodeJS que podemos utilizar principalmente en nuestra clase que contiene la conexión y comunicaciones de Sockets cliente / servidor.

Los fragmentos de código que contienen los snippets son estructuras básicas de métodos con sockets, como la inicialización de una conexión o una función básica de los WebSockets como emitir o escuchar.

Aunque estos fragmentos contengan la estructura básica de la utilización más general de éstos métodos, no es una obligación que esa deba ser su estructura sino una sugerencia que nos ayude a redactar código de manera mas rápida.

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

### 2. Tecnologías

- [Azure DevOps](https://azure.microsoft.com/es-es/products/devops) - Suministrador de organización encargada de la administración de servicios marketplace.
- [JavaScript](https://www.javascript.com/) - Lenguaje principal utilizado para el desarrollo del plugin.
- [Marketplace Visual Studio Code](https://marketplace.visualstudio.com/vscode) - Plataforma encargada del gestionamiento de la extensión.

## 3. Instalación

Para instalar el plugin DatAge: Sockets, es necesario tener previamente instalado el editor de texto [Visual Studio Code](https://code.visualstudio.com/), a continuación desde la pestaña de Extensiones, o bien con el comando Crtl + Shift + X (windows) buscamos la extensión **DatAge** y presionamos _Install_.

![Extensión sockets - DatAge](img/extension-datage.png)

### 4. Preguntas frecuentes

Licencia MIT

**Free Software !!! :D**