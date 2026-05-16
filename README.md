# Como publicar la pagina del codigo QR

Si no tienes sitio web, si puedes usar una pagina HTML generica. La idea completa queda asi:

1. Edita `index.html`.
2. Cambia `NOMBRE DE TU IGLESIA`, direccion, redes sociales y horario.
3. Publica la carpeta en un hosting gratuito para paginas estaticas.
4. Copia el enlace publico final.
5. Crea el codigo QR con ese enlace.
6. Prueba el QR con varios telefonos antes de imprimir.

## Como abrir `index.html` para editar

### Opcion facil: Bloc de notas

1. Busca el archivo `index.html`.
2. Haz clic derecho sobre el archivo.
3. Elige `Abrir con`.
4. Selecciona `Bloc de notas`.
5. Edita el texto y guarda con `Ctrl + S`.

### Opcion recomendada: Visual Studio Code

1. Abre Visual Studio Code.
2. Elige `Archivo > Abrir carpeta`.
3. Selecciona la carpeta donde esta `index.html`.
4. Haz clic en `index.html`.
5. Cambia los textos necesarios y guarda con `Ctrl + S`.

## Que cambiar dentro de `index.html`

Busca estos textos:

```text
NOMBRE DE TU IGLESIA
Av. Ejemplo 123, Ciudad
Domingos 10:00 a.m.
https://www.youtube.com/@TU_CANAL
https://www.facebook.com/TU_PAGINA
```

## Sobre no usar WhatsApp

La plantilla ya no expone un numero de WhatsApp ni telefono publico. Es una buena decision si el QR se repartira en la calle, porque evita mensajes ofensivos, bromas y spam.

Si mas adelante quieres recibir peticiones de oracion sin mostrar un telefono, puedes usar un formulario de Google Forms con moderacion.

## Opciones faciles para publicar

### Netlify Drop

Es la opcion mas rapida para empezar. Entras a Netlify Drop, arrastras la carpeta donde esta `index.html` y te entrega un enlace publico. Luego puedes cambiar el nombre del sitio desde Netlify.

### GitHub Pages

Es buena si quieres algo mas permanente. Creas una cuenta en GitHub, subes `index.html` a un repositorio y activas Pages en la configuracion del repositorio. El enlace normalmente queda parecido a:

```text
https://tuusuario.github.io/nombre-del-repositorio/
```

### Vercel

Tambien sirve para paginas HTML simples. Subes o importas el proyecto, y Vercel te da un enlace publico.

## Importante para el QR

No generes el QR con un enlace local como:

```text
file:///C:/...
localhost:3000
127.0.0.1
```

Ese enlace solo funciona en tu computadora. El QR debe apuntar al enlace publico que te da Netlify, GitHub Pages, Vercel u otro hosting.

Para imprimir, usa un QR de buen contraste, sin demasiado adorno, y de al menos 3 cm de ancho. Deja margen blanco alrededor para que el celular lo detecte bien.
