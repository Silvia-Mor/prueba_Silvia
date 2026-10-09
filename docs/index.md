# Creando una guía sintáctica de MarkDown

  (Nota mía, he desabilitado markdownlint Toggle linting (escribiendo en la barra de arriba > para buscarlo)).
  Siempre van dos espacios.
  Hay qye dejar siempre un espacio entre los símbolos y lo que escribes.
  
  Enlaces de momento de los otros dos archivos .md

  [Archivo instalación](instalacion.md)
  [Archivo uso](uso.md)

# PROBANDO MODIFICAR EL FICHERO INDEX.MD MIENTRAS SE EJECUTA MKDOCS SERVE, (APARTADO 6)

  ESTA ES LA PRUEBA DE ACTUALIZACIÓN AUTOMÁTICA (P6)

### **Títulos**

  Las almohadillas (#) se utilizan para los títulos, van desde 1 hasta 6. Cuantas más pongas más pequeño se hace el texto.

### **Párrafos**

  No hace falta poner nada delante, si quieres separarlos simplemente le das a intro y sigues escribiendo.

  Por ejemplo este párrafo se ha hecho simplemente dando intro, es recomendable en el código separarlo para tener buenas prácticas.

### **Salto de línea**

  Esto es una línea.
  Esta segunda línea es simplemente escribiendo abajo.

### **Texto en negrita**

  El texto en **negrita** va entre dobles asteriscos. (** palabra **).

### **Cursiva**

  Para poner una palabra en *cursiva* va entre asteriscos simples. (* palabra *).

### **Negrita y cursiva**

  Para ***negrita y cursiva*** a la vez simplemente entre 3 asteriscos. (*** palabra ***).  

### **Bloque de código(Citas)**

  >Para poner un bloque de código hay que utilizar la tecla >.
  >
  >Si quieres seguir haciendo párrafos vas intercalando el símbolo mayor qué.
  >>Si lo que quieres es anidar las citas o bloques simplemente pones 2 >>.

### **Citas en bloque con otros elementos**

  Se utiliza > al principio y vas añadiendo lo que necesites (###, -(lista), ** negrita **)

  > ##### Título
  >
  > - Primer apartado
  > - Segundo apartado
  >
  > *Cursiva* y **negrita** dentro de un bloque

### **Listas ordenadas**  

  Se pone el número seguido de un punto 1.
  Puedes escribirlos desordenados o el mismo número, markdown siempre los pondrá consecutivamente... 1,2,3...
  1. Primero
  2. Segundo
  4. Aquí he escrito 4. y sin embargo pone el 3

### **Listas no ordenadas**

  Se pone un guión delante.
  - Primero
  - Segundo
  - Tercero  

### **Agregar elementos a las listas** 

  Hay que marcar 4 espacios.

  - Primero
  - Segundo
    2 espacios más para añadir un párrafo después del segundo.
  - Tercero  

### **Citas en bloque dentro de una lista desordenada**  

  - Primer elemento de la lista
  - Segundo elemento de la lista
    > Línea de bloque
  - Tercer elemento de la lista

### **Bloque de código dentro de marktdown**

  1. Primer elemento
  2. Segundo elemento, aquí vamos a poner bloque de código HTML, se tiene que sangrar 4 espacios.

    <html>
      <head>
       <title>Título</title>
      </head>
    </html> 

  3. Tercer elemento  

### **Imágenes**

  Para añadir una imagen se pone el símbolo de exclamación cerrado, corchetes y paréntesis. ![]()
  
  Dentro de los corchetes va el texto, dentro de los paréntesis va la ruta.

![Luna saliendo](img/influencia-luna.webp)
  
 ### **Lista ordenada dentro de lista desordenada y viceversa**

   1. Uno
   2. Dos
   3. Tres
      - tres y medio
      - tres y tres cuartos
   4. Cuatro  
 
### **Palabra o frase como código**

  Va entre comillas invertidas.

  Érase una vez un `gato` blanco.

### **Líneas horizontales**

  Para crear una línea horizontal, se ponen 3 o más asteriscos, guiones o guiones bajos. (***) (---) (___)

  ***

  ---

  ___

### **Crear un enlace**

  Igual que la imagen pero sin la exclamación delante.

  El texto del enlace entre corchetes [], la URL entre paréntesis()

  La página web que más utilizo es [Aules](https://portal.edu.gva.es/aules/es/inicio/)


### **Tablas**

  | Encabezado | Encabezado |
  | ---------- | ---------- |
  | cuerpo 1   | cuerpo 2   |
  | cuerpo 3   | cuerpo 4   |

### **Tablas alineadas**

  | Encabezado              | Encabezado  |           Encabezado |
  | :---                    |    :---:    |                 ---: |
  | Pegado a la izquierda   | centrado    | pegado a la derecha  |
  | izquierda               | centro      | derecha              |

### **Lista de tareas**

  - [x] Este sí lo marco
  - [ ] Este no lo marco
  - [ ] Este tengo dudas

### **Destacar(fofi)**

  Para resaltar una palabra o varias se pone ==dos guiones== delante y detrás == palabra ==.



    