<!--@author:Erick14911-->
# TypeScript

## 1. Instalacion de Node.js

## 2. Comprueba Node y npm

    >>>node -v
    >>>npm -v

## 3. Abre terminal en Visual Studio Code

    >>>tsc -init 

## 4. Cambiar configuración del archivo **typescript**

    tsconfig.json{
    "targe":"ES5",
    "strict":false
    }

## 5. Crear archivo con extención `.ts` **main.ts**

## 6. Editarlo

~~~

  let mi_variable:string="Hola mundo";
  let numero:number=12;
  let verdadero:boolean=true;
  let cualquier:any=" ";
  const nombre:string="Visctor";
  console.log(texto,numero,verdadero);
// arays
  let personas:string[]=["Paco","Juan","Maria","Luis"];
// 
 let div_persona:HTMLElement or null=document.querySelector("#personas");
// 
 div_personas.innerHTML += "<ul>"; 
  
 personas.map((personas)=>{
    div_personas.innerHTML+="<li>"+persona+"</li>"; //'<li>${persona}</li>'
  })
 
 div_personas.innerHTML += "</ul>"; 
///////////////////////////////////////////////////////
 div_personas.innerHTML += "<ul>"+
 personas.map((personas)=>{
   return '<li>${persona}</li>';
 }).join("")
 +"</ul>";

~~~

## 7. Compilar **main.ts**

    >>>tsc main.ts -w

## 8. Etiqueta `<script>` en Index.html
    
    <script src="main.js" defer></script>
