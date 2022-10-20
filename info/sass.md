<!--@author:Erick14911-->
# SASS - Super CSS

### 1. Instalar rubyinstaller

### 2. Correr en terminal

    gem install sass
    sass -v

### 3. Crear una carpeta _sass_ a la altura de la carpeta _css_

### 4. Crear el documento con la extencion `.scss` *nameStyle.scss* 

### 5. Crear archivos auxiliares

**_variables.scss** _llamar este archivo:_

    @import "variables";

### 6. Compilar

    sass --watch sass:css

## Caracteristicas de edición

### Declaracion de variables

$color:yellow;
$hover-color:color-contrast($hover-background);
-#{hover-color}:#{color};


### Anidamiento en la declaracion de style

footer{
    background:#444
    h4{color:#7774
    a{color:#847
    }
    }

}
### Control if

    @if $state == "valid" {
        z-index:1;
    } @else if $state == "incvalid" {
        z-index:2;
    } 
    &:focus{
        z-index:3;
    }
    $active-border: if($color == $color-contrast-light, shade-color($border, $btn-active-border-shade-amount), tint-color($border, $btn-active-border-tint-amount));

### Mixin es una class de estilo:

    @mixin cuadrado($fondo:#999){
        background-color:$fondo;
    }

    .nameClass{
        @include cuadrado(#333)
    }

**quiebres**

    @media(mn-width:640px){
    }
    @media(mn-width:768px){
    }
    @media(mn-width:1024px){}
    @media(mn-width:1280px){}

**Bootstrap**

source files=dist-scss-index.html
ctr-f:

**tailwind css = link CDM usa clases**
