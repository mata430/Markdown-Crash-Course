# Markdown Crash Course

- [Markdown Crash Course](#markdown-crash-course)
  - [Basic Syntax](#basic-syntax)
    - [Headings](#headings)
- [Heading 1](#heading-1)
  - [Heading 2](#heading-2)
    - [Heading 3](#heading-3)
      - [Heading 4](#heading-4)
        - [Heading 5](#heading-5)
          - [Heading 6](#heading-6)
    - [Horizontal Rule](#horizontal-rule)
    - [Text formating](#text-formating)
    - [Lists](#lists)
    - [Code formating](#code-formating)
    - [Blockquote](#blockquote)
    - [Links](#links)
    - [Images](#images)
  - [Extended Syntax](#extended-syntax)
    - [Table](#table)
    - [Task List](#task-list)
    - [Emoji](#emoji)
    - [Comments](#comments)
    - [Toggle](#toggle)
    - [Callouts](#callouts)
    - [Color en texto](#color-en-texto)
    - [Citas](#citas)
    - [Texto preformateado](#texto-preformateado)
    - [CONBINACION DE MD Y HTML](#conbinacion-de-md-y-html)
    - [Con html podemos modificar el tamano d la imagen](#con-html-podemos-modificar-el-tamano-d-la-imagen)
    - [VIDEOS](#videos)
    - [Hacks de texto usando html](#hacks-de-texto-usando-html)
    - [Enlace abriendo una nueva pagina](#enlace-abriendo-una-nueva-pagina)
    - [DIAGRAMAS](#diagramas)
    - [Crear graficas circulares](#crear-graficas-circulares)
    - [Crear diagramas entidad relacion](#crear-diagramas-entidad-relacion)
    - [crear diagramas Journey](#crear-diagramas-journey)
    - [Como crear diagramas Git](#como-crear-diagramas-git)
    - [Como crear diagramas Gant](#como-crear-diagramas-gant)
    - [Como crear diagramas de requerimientos](#como-crear-diagramas-de-requerimientos)
    - [Como personalizar diagramas mermaind](#como-personalizar-diagramas-mermaind)
    - [Añadir ecuaciones LaTex](#añadir-ecuaciones-latex)
    - [**Fuentes**](#fuentes)

## Basic Syntax

### Headings

Below are 6 heading variations.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Horizontal Rule

3 dashes creates a horizontal line.

### Text formating

Paragraph line spacing is important.
This sentence is on the same line even though it's on the next line of the editor because there's no separation of content.

Add an empty line between elements.

_italic text_ and _more italic text_

**bold text** and **more bold text**

**_bold and italic text_**

**mix _and_ match**

~~strikethrough text~~

### Lists

Ordered List

1. Item 1
1. Item 2
1. Item 3

Unordered List

- Item
- Item
- Item

### Code formating

Inline: Use JavaScript `map()` on arrays.

Fenced code block:

```js
const sum = (a, b) => a + b;

sum(2, 2);
```

### Blockquote

> This is a blockquote
>
> more text
>
> > Nexted blockquote

### Links

[codeSTACKr](https://youtube.com/codeSTACKr "codeSTACKr YouTube")

[Headings](#headings)

[codeSTACKr][cs]

[cs]: https://youtube.com/codeSTACKr "codeSTACKr YouTube"

<claudio@gmail.com>

![Imagen de prueba](https://images.unsplash.com/photo-1618329027137-a520b57c6606?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTB8fGVkaXRvcnxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60 "cursor")

![Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)

![Mis seguidores en github](https://img.shields.io/github/followers/mata430?style=social "mis seguidores")

![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=mata430&theme=blue-green)](https://github.com/anuraghazra/github-readme-stats)

### Images

![alt text](/codecat.png)

[![alt text](/codecat.png)](https://codecats.xyz)

## Extended Syntax

Not all extended syntax features work in all markdown applications.

### Table

| Packages |     Description      | Version |
| :------- | :------------------: | ------: |
| React    | JavaScript Framework |   v18.0 |
| Next.js  |   React Framework    |   v12.0 |

### Task List

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

### Emoji

Emoji's are fun! :joy:

los podemos copiar de la [pagina de emojis](https://gist.github.com/rxaviers/7360908)

:snowman:  
:imp:

### Comments

[this is a hidden comment.]: #

### Toggle

<details>
  <summary>:zap: This is a toggle!</summary>

Contents of toggle.

</details>

### Callouts

> :bulb: **Tip:** Here's an important tip to remember!

### Color en texto

<span style="color:red"> **some emphasized markdown text**</span>

### Citas

Se abre con un signo mayor que > y el autor se inicia con dos --

> A la vista de suficientes ojos, todos los errores resultan evidentes. -- Linus Torval

### Texto preformateado

Daremos 4 espacios antes de lo escrito.

    Daremos 3 espacios antes de lo escrito.

### CONBINACION DE MD Y HTML

<H1> HTML TITULO ETIQUETA H1</H1>

![texto alternativo](https://images.pexels.com/photos/1647976/pexels-photo-1647976.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

### Con html podemos modificar el tamano d la imagen

<img src= "https://images.pexels.com/photos/1647976/pexels-photo-1647976.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" width=200px>


### VIDEOS

para poner la miniatura usaremos (https://img.youtube.com/vi/1BzzckYqT9w/maxresdefault.jpg)despues del // lleva img. y luego /vi/ des pues copiar el v= copiar el codigo sin el &. y al final maxresdefault.jpg

[![VIDEO](https://img.youtube.com/vi/1BzzckYqT9w/maxresdefault.jpg)](https://www.youtube.com/watch?v=1BzzckYqT9w&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=9&ab_channel=ProgramaTutos)

### Hacks de texto usando html

<ins> Texto subrayado usando etiqueta ins</ins>

<center>Texto aliniado al centro</center>

<center><ins>Texto aliniado al centro y subrayado</ins></center>

<p style="color:blue">Texto de color</p>

### Enlace abriendo una nueva pagina

<a href="htpps://github.com/mata430" target="_blank"> Perfil de github </a>

### DIAGRAMAS

Diagrama de secuencia video

[![VIDEO](https://img.youtube.com/vi/q6BDbKGrPx0/maxresdefault.jpg)](https://www.youtube.com/watch?v=q6BDbKGrPx0&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=13&ab_channel=ProgramaTutos)

### Crear graficas circulares

[![VIDEO](https://img.youtube.com/vi/Fv-YXoas5MY/maxresdefault.jpg)](https://www.youtube.com/watch?v=Fv-YXoas5MY&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=14&ab_channel=ProgramaTutos)

### Crear diagramas entidad relacion

[![VIDEO](https://img.youtube.com/vi/V5GdRPIJ4-c/maxresdefault.jpg)](https://www.youtube.com/watch?v=V5GdRPIJ4-c&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=15&ab_channel=ProgramaTutos)

### crear diagramas Journey

[![VIDEO](https://img.youtube.com/vi/XUps5u8MCnY/maxresdefault.jpg)](https://www.youtube.com/watch?v=XUps5u8MCnY&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=16&ab_channel=ProgramaTutos)

### Como crear diagramas Git

[![VIDEO](https://img.youtube.com/vi/xkEnbtk61Xw/maxresdefault.jpg)](https://www.youtube.com/watch?v=xkEnbtk61Xw&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=17&ab_channel=ProgramaTutos)

### Como crear diagramas Gant

[![VIDEO](https://img.youtube.com/vi/u4QjLkOXq-0/maxresdefault.jpg)](https://www.youtube.com/watch?v=u4QjLkOXq-0&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=18&ab_channel=ProgramaTutos)

### Como crear diagramas de requerimientos

[![VIDEO](https://img.youtube.com/vi/bSyP7O4uask/maxresdefault.jpg)](https://www.youtube.com/watch?v=bSyP7O4uask&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=19&ab_channel=ProgramaTutos)

### Como personalizar diagramas mermaind

[![VIDEO](https://img.youtube.com/vi/qYuL_cIFvPo/maxresdefault.jpg)](https://www.youtube.com/watch?v=qYuL_cIFvPo&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=20&ab_channel=ProgramaTutos)

### Añadir ecuaciones LaTex

[![VIDEO](https://img.youtube.com/vi/9eaA1-U3Nyk/maxresdefault.jpg)](https://www.youtube.com/watch?v=9eaA1-U3Nyk&list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ&index=21&ab_channel=ProgramaTutos)

### **Fuentes**

[![Thumbnail](https://img.youtube.com/vi/ftOBvusMHjQ/maxresdefault.jpg)](https://youtu.be/ftOBvusMHjQ)

> Tambien podemos usar esta pagina como editor de codigo de markdown [dilliger](https://dillinger.io/fff "clik")
