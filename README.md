# Encriptador de Textos

Este es un proyecto de sitio web que permite encriptar y desencriptar textos utilizando un conjunto específico de reglas de sustitución de letras. El propósito principal de esta aplicación es permitir a los usuarios intercambiar mensajes secretos utilizando un sistema de encriptación simple.

## Tabla de Contenidos
- [Descripción](#descripción)
- [Funcionalidades](#funcionalidades)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Cómo Usar](#cómo-usar)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Descripción

Este sitio web encripta textos reemplazando las vocales según las siguientes reglas:

- **e** -> "enter"
- **i** -> "imes"
- **a** -> "ai"
- **o** -> "ober"
- **u** -> "ufat"

Y permite desencriptar cualquier texto que haya sido encriptado siguiendo las mismas reglas.

## Funcionalidades

- **Encriptar Texto**: Convierte un texto dado en su forma encriptada.
- **Desencriptar Texto**: Convierte un texto encriptado de vuelta a su forma original.
- **Copiar Texto**: Permite copiar el texto encriptado/desencriptado al portapapeles.
- **Validación de Entrada**: Acepta solo letras minúsculas, espacios y signos de exclamación.

## Tecnologías Utilizadas

- **HTML5**: Para la estructura del sitio web.
- **CSS3**: Para el diseño y el estilo de la página.
- **JavaScript**: Para la lógica de encriptación/desencriptación y las validaciones.
- **SweetAlert**: Para mostrar alertas personalizadas.

## Cómo Usar

1. **Encriptar Texto**:
   - Escribe el texto que quieres encriptar en el área de texto.
   - Haz clic en el botón "Encriptar".
   - El texto encriptado se mostrará en el área designada.

2. **Desencriptar Texto**:
   - Escribe o pega el texto encriptado en el área de texto.
   - Haz clic en el botón "Desencriptar".
   - El texto desencriptado se mostrará en el área designada.

3. **Copiar Texto**:
   - Después de encriptar o desencriptar el texto, haz clic en el botón "Copiar" para copiar el resultado al portapapeles.

## Estructura del Proyecto

- **index.html**: Contiene la estructura HTML del sitio.
- **styles.css**: Archivo CSS que define el estilo de la página.
- **script.js**: Archivo JavaScript que maneja la lógica de encriptación/desencriptación y validación de entrada.
- **Assets/**: Carpeta que contiene imágenes y otros recursos multimedia utilizados en el sitio.
---
