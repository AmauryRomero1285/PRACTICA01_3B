 
# PRACTICA01_3B
En esta practica aprenderemos a utilizar las herramientas GIT y GITHUB para el control de Versiones,Documentación, Desarrollo colaborativo y Respaldo del proyecto integrador para la asignatura de Integradora

## comandos basicos pasa la documentacion, utilizando el estandar de Markerdown(md)
Markdown es el estandar utilizado por GIT y GITHUB, para maquetar la documentacion de proyectos, lo que
permite a usuarios y colaboradodres del proyecto entender el contexto y operacion del mismo

### 1.Encabezado o Titulos(HEADERS)
Para poder realizar una buena documentacion del proyecto debemos, ditribuir correctamente los contenidos, para poder delimitar o hacer enfasís(enfatizar), es decir las sesiones importantes, podemos utilizar los siguientes:
# Encabezado de nivel 1- similar a h1 en HTML
## Encabezado de nivel 2- similar a h2 en HTML
### Encabezado de nivel 3- similar a h3 en HTML
#### Encabezado de nivel 4- similar a h4 en HTML
##### Encabezado de nivel 5- similar a h5 en HTML
###### Encabezado de nivel 6- similar a h6 en HTML
####### Encabezado de nivel 7- solo 6 son los niveles permitidos, a partir de este enmaquetado será ignorado.

### 2.Separadores(SEPARATORS)

Si deseas marcar una separacion mas visual de contenidos podemos utilizarlos indicando 3 caracteres de "-" continuamos, en el maquetado
EJEMPLO:

---
"Esto es similar a un tag de <HR> en HTML"

### 3.Parrafos(PARAGRAPHS)
Son utilizados para predsentar grandes sesiones de texto que describen detalladamente las sesiones de la documentacion del proyecto.
EJEMPLO:
Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1Este texto corresponde al parrafo 1

Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2Este texto corresponde al parrafo 2

lo que en una pagina utilizaremos la etiqueta<p>.
Tambien podemos aplicar estilos básicos de alineación:
Este parrafo está alineado a la izquierda por defecto Este parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defectoEste parrafo está alineado a la izquierda por defecto

<p align="right">
Este parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defectoEste parrafo está alineado a la derecha por defecto
<p>

<p align="center">
Este parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineaciónEste parrafo esta centrado usando la propiedad de alineación
</p>

<p align="justify">
Este parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificadoEste parrafo esta justificado
</p>

### 4. Texto enfatizado(BOLD, ITALIK,BOLD/ITALIK)
Si el texto que deseamos enfatizar se encuentra de un parrafo, podemos utilizar algunos trucos para ubicarlos en la documentacion 

##### Texto en negrita(BOLD)
Para poder poner el texto en negrita, este debera ser encerrado entre "** **"
EJEMPLO:

**Texto importante**TextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTextoTexto
#### Texto en cursiva(ITALIK)
Para poder poner el texto en cursiva, este debera estar encerrado entre "* *"
EJEMPLO:

*TEXTO IMPORTANTE*textotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotexto
#### Texto negrita/cursiva (BOLD/ITALIK)

Para poner el texto negrita/cursiva, este debera estar encerrado entre "*** ***"
EJEMPLO:


***TEXTOIMPORTANTE***textotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotextotexto

### Texto subrayado(underline)
Algunas veces es necesario subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificacion rápida podemos utilizar el estilo que usa el estándar HTML usando el tag \<ins> y cerrando con \</ins>.

**Ejemplo**

texto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto  <ins>texto Importante</ins>  texto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto textotexto texto


# Integradora-Practica 03

Continuamos con los cambios básicos de Git y GitHub para el maquetado de la documentación.

### 5.Cuadros para codigo o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o inicialización de código fuente. Se maqueta iniciando el texto con un simbolo de menor que (\<)

**Ejemplo**

Para listar las carpetas y archivos en donde una terminal de sistema operativo Windows debemos ingresar el comando:

>C:/dir

 Despues oprimimos la tecla "Enter"

 También podemos ingresar el texto multilinea

 **Ejemplo**

 >Aquí se ingresan un conjunto de intrucciones
>para explicar al usuario, como instalar el
>software que hemos diseñado.

Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

**Ejemplo**
**Pasos para instalar la base de datos**

>- Descargar MySQL Server del sitio oficial
>- Instalar el sistema gestor  de base de datos, definiendo el puerto y contraseña para el usuario ***root***
>- descargamos el archivo de respaldo de la base de datos (.sql)
>- Restauramos la base de datos usando el comando *mysql*
>
>> C:/Program Files/MySQL Server 8.0/bin/mysql- u root-password< respaldo.sql

### 6.Listas Ordenadas y Listas Desordenadas

Si en nuestra documentacion necesitamos incluir información en modo de lista, un elemento tras otro, podemnos hacerlo utilizando los numeros con un punto decimal, si lasm deseseamos ordenadas o un guión medio si solo queremos una viñeta.

**Ejemplo**

Para crear tu primer repositorio en GitHub deberás:
1. Contar con cuenta de GitHub.
2. Dar click en el boton ****Nuevo Repositiorio****
3. Asignarle un Nombre a tu repositoprio, por ejemplo: *Practica-3b*
4. Asignarle un nivel de privacidad entre
   - **Público:** Si quieres que este disponible para todos los usuarios.
   - **Privado:** Si deseamos que solo a quien tu decidas que puedan colaborar con tu proyecto.
10. Definir si incluye un archivo de descripción llamada: *READ.md*
11. Definir si habrá exclusiones de archivo a través del archivo *.gitgnore*
12. Guardar los cambios.

### 7.Ligas (Hipervinculos)

Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositoriop o fuera de el, se enmaquetan utilizando los corchetes \[\], inmediatamente despues pondremos la referencia entre parentesis ()

**Ejemplo**

Mi buscador favorito es: [Google](https://www.google.com)

Pero si deseamos poner solo las ligas directas o un orreo electrónico podemos utilizar los simbolos \<\>

**Ejemplo**

Documentación creada poir: ***T.S.U Yáred Amaury Romero Martínez***

<230190@utxicotepec.edu.mx>

<http://www.utxicotepec.edu.mx>

### 8.Imagenes 

Para poner una imagen en nuestro repositorio, es necesario agregarla antes de editar el codigo.

**Pasos a seguir**

>-Buscar el boton "**Add file**"

>-Abrir en "**Upload files**"

>-Añadir la imagen que deseamos subir.

>>Para referenciarla en el documento README.md se utiliza la siguente sitaxis ![*descripcion del archivo*](*ruta a la imagen*)

**Ejemplo:**

![Imagen](Logo-UTXJ.png)

