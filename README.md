# Aprender Markdown

## Formatear Texto

Estas son las posibilidades que ofrece Markdown en su forma base:

* **Texto en negrita**  
 Para mostrar texto en negrita introducimos dos asteriscos antes y después del segmento de texto que queramos formatear.

  `**Texto de ejemplo**` -> **Texto de ejemplo**

* **Texto en cursiva**  
 Para mostrar texto en custiva introducimos un guión bajo antes y después del segmento de texto que queramos formatear.

  `_Texto de ejemplo_` -> _Texto de ejemplo_

* **Combinar estilos**  
 Podemos combinar ambos estilos e incluso introducirlos en otros formatos como listas, citas, etc...

  `**_Texto de ejemplo_**` -> **_Texto de ejemplo_**  

  Aquí hemos indicado **primero la negrita** y **luego la cursiva**.

* **Cita bibliográfica**  
 Para formatear un segmento de texto como una cita antecedemos cada párrafo y salto de línea con ">".

```
> Línea de ejemplo 1
>
> Línea de ejemplo 2
```

Equivale a:

> Línea de ejemplo 1
>
> Línea de ejemplo 2
 
* **Segmento de código**  
 Para formatear un segmento de texto para que se distinga como código en general, o como código de un lenguaje concreto utilizamos acentos invertidos.

```
`Esto formatea una sola línea`
```

  ` ```c++ //Esto formatea varias líneas como C++``` `  

## Cabeceras (Headers)

Las **cabeceras** son una parte importante de Markdown ya que su principal propósito está íntegramente relacionado con el **desarrollo web**: simplificar _HTML_.

Para que una línea se muestre como una cabecera se precede de tantas almohadillas ("#") como índice de cabecera queramos.

* Cabecera de **índice 1** (`<h1></h1>`) -> `#Cabecera H1`

  # Cabecera H1

* Cabecera de **índice 2** (`<h2></h2>`) -> `#Cabecera H2`

  ## Cabecera H2

* Y así sucesivamente hasta el **índice 6**, que es el máximo.

## Enlaces e imágenes

Los **enlaces** son la base del lenguaje de marcado, puesto que un sitio web no es más que una serie de **información enlazada** en distintas páginas.

Existen dos tipos de enlaces: **en línea** y **por referencia**.

* **Enlaces en línea**  
 Consiste en insertar la dirección del enlace en la misma línea que el elemento enlazado. Este último va entre **paréntesis** y la dirección entre **corchetes**.

 `(Imágenes de gatitos lindos)[https://bit.ly/3A7LUSq]` -> [Imágenes de gatitos lindos](https://bit.ly/3A7LUSq)

 Esto es útil para **párrafos cortos** y con **enlaces breves**. Pero, ¿Y si quisiéramos enlazar varios elementos a la misma página de forma cómoda?

* **Enlaces por referencia**
 Consiste en insertar una referencia en la misma línea que el elemento a enlazar y explicar al final del documento a qué dirección apunta la referencia.

 ```
 [Imágenes de gatitos lindos 1](gatitos_img).  
 [Imágenes de gatitos lindos 2](gatitos_img).

 [gatitos_img]: https://bit.ly/3A7LUSq
 ```

 Equivale a

 [Imágenes de gatitos lindos 1](gatitos_img).  
 [Imágenes de gatitos lindos 2](gatitos_img).

 [gatitos_img]: https://bit.ly/3A7LUSq

[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5793149&assignment_repo_type=AssignmentRepo)

[Enlace a Gitpod.io](https://www.gitpod.io/#https://github.com/ULL-ESIT-DMSI-1920/markdown-Wololegend)