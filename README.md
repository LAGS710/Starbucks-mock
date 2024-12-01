# Creacion de la página de starbucks para el curso frontend de Dev.F

#Objetivos 

- Leccion 1, iniciar maquetado y css de la página de inicio de [Starbucks](https://www.starbucks.com.mx/).
- Leccion 2, terminar por completo el inicio de de [Starbucks](https://www.starbucks.com.mx/).
- Leccion 3, iniciar HTML de la pagina de rewards de [Starbucks](https://rewards.starbucks.mx/).
- Leccion 4, terminar por completo la página rewards de [Starbucks](https://rewards.starbucks.mx/).

## Recursos utilizados

- HTML5
- CSS3
- Documentación [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) y [CSS](https://developer.mozilla.org/es/docs/Web/CSS) de Mozilla
- Página de [Starbucks](https://www.starbucks.com.mx/) como página objetivo

## Instalación de la página

### Instalacion local

1. Clonar repositorio (git clone https://github.com/LAGS710/Starbucks-mock.git)
2. Abrir con live server usando VCode el archivo index.html

### Sin instalación

1. Abrir el siguiente [enlace](https://lags710.github.io/Starbucks-mock/) para acceder a la vista prevía de la página.

# Descripcion de etapas

## Leccion 1
### Puntos importantes

##### Se utilizo el conocimiento de display flex para crear en forma de columnas y filas las cartas que aparecieron.

##### Por ejemplo, en lala lección 1 se utilizó `display: flex;` junto con `flex-direction: row;` en la siguiente carta:

![code](https://i.ibb.co/7vrNXBX/Captura-de-pantalla-2024-11-30-214847.png)

##### En la siguientes cartas se utilizo `display: flex;` junto con `flex-direction: column;` para colocar el contenido dentro de la sección en forma de columnas:

![code](https://i.ibb.co/TbPQNwd/Captura-de-pantalla-2024-11-30-215622.png)

## Leccion 2
### Puntos importantes

##### Se terminó el css del header y del footer

##### Para el header se usó el `display: flex;` junto con `flex-direction: row;` para hacer flexibles a los `<ul>`, y en la parte derecha, se utilizaron `<button>` para el boton Ingresar y Únete.

![code](https://i.ibb.co/S5b71WT/Captura-de-pantalla-2024-11-30-220928.png)

##### Para el footer se utilizó la pseudo clase `a:hover` para crear el efecto sobre los iconos de redes sociales:

![code](https://i.ibb.co/6gLVTmm/Captura-de-pantalla-2024-11-30-221433.png)

##### Efecto con la pseudo clase `a:hover`:

![image](https://github.com/user-attachments/assets/9857b879-6358-477e-9381-4888998bf7d6)

Para la siguiente sección se usó `display: flex;` junto con `flex-direction: row;` para posicionar a los `<li>` en forma de fila:

![code](https://i.ibb.co/bNDnffV/Captura-de-pantalla-2024-11-30-222005.png)

## Leccion 3
### Puntos importantes

##### Se hizo el HTML de la pagina rewards

##### Se rellenaron los campos de texto con sus respectivos enlaces. asi tambien como hacer la estructura de cada una de la seccions, por ejemplo, para la primer sección, este fue el HTML:

![image](https://github.com/user-attachments/assets/c89767ed-796e-4980-9d65-473cbe2ad551)

##### Es importante estructurar bien las secciones para evitar atrasos al momento de agregar el CSS. Es importante considerar como se va facilitar mas la construcción de la página.
##### En lo personal, aun me falta mas noción de buenas prácticas, pero la elaboración de esta página me esta ayudando mucho.




## Leccion 4
### Puntos importantes

##### Esta sección utilzo todos los conocimientos previos, pero algunos nuevos, entre los mas importantes son los siguientes:

- uso del `display: fixed;` para la seccion izquierda que estara fija, al igual que el header
- uso del `z-index: -1;` para llevar secciones a la parte atras del contenido
- uso del `position: absoulte;` para poder manejar la imagen de la mano

  

##### En estas apreciamos como los números aparecen por encima del header antes del uso de `z-index: -1;` y despues por abajo cuando lo implementamos:

![CSS](https://i.ibb.co/MR497Sx/Captura-de-pantalla-2024-11-30-224259.png)

![CSS](https://i.ibb.co/N6c7kxb/Captura-de-pantalla-2024-11-30-224104.png)

Aqui la parte del código donde se implementó:

![code](https://i.ibb.co/c2KpmC5/Captura-de-pantalla-2024-11-30-224514.png)

##### En la siguientes cartas se utilizo `display: flex;` junto con `flex-direction: column;` para colocar el contenido dentro de la sección en forma de columnas:

![code](https://i.ibb.co/P1w6CNh/Captura-de-pantalla-2024-11-30-223201.png)

##### Las siguiente capturas son del CSS usado para fijar a la sección izquierda y el header:

![code](https://i.ibb.co/4pZ2wvk/Captura-de-pantalla-2024-11-30-224840.png)
![code](https://i.ibb.co/17VDMTx/Captura-de-pantalla-2024-11-30-224902.png)

Por último, adjunto un video de la CSS de la página rewards debido a que las imágenes no cargan en el GitHub Pages, tambien indico los commits donde termina cada lección asi como el link del GitHub Pages:

- link del GitHub Pages: https://lags710.github.io/Starbucks-mock/
- video: https://youtu.be/-UxeJs4RnA8

## Commits

- Lección 1 Final: 697dab77199bd9935de08c6a0be8663494c4726f 
- Lección 2 Final: d7168dadcff3b8da7e1835b0181be0e977ff1ab2
- Lección 3 Final: fb178c87125b7fb92aef3cf7bf0546cefecbc9c4
- Lección 4 Final: b39bad65cde23e5e73f0eb161e596bb88f94cb2b (sujeto a cambios, como optimización de lineas de CSS)
