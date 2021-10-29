<style>


.jc , #lgerie { fill: lightgreen; }
#Mali, #Colombie, #honduras, 	#Algerie { fill: lightblue; }

.jtMaroc {
   fill: black;
   stroke: black;
z-index: 99;
z: -199;
}

#aljc a:link,
#aljc a:visited,
#aljc a:hover {
   color: black;
   fill: blue;
}

notext:hover  {
   fill: white;
   stroke: yellow;
}


.jc:hover { 
  jcfill: brown; 
  stroke: yellow; 
  jc: solostrok }

svg path:hover  {  
   stroke: white;
   fill: purple;
     nocursor:pointer; /*to change the cursor*/
   jc: ok;
}


#Algerie:hover{
     fill:yellow;
  stroke: #00f;
    }

// svg:hover { fill: brown; }

svg text {display: none;}
//ok svg g:hover text {display: block;}
 svg a:hover text {display: block;} //cool



.bglogo path:hover{
  stroke: #00f;
}
.bglogo{
z-index: 99;
}
p { color: darkblue; }


</style>

# Map3

-  hay carpetas dobles entre busquedas y la base:  colombia , honduras, ...
  -  desaparecieron otros paises que antes habia: argelia y paraguay
  - en seguridad:
  
 | opciones de rapidez vs. seguridad | positivo? | negativo?
 |:---------- |:----------- |:------------- |
 | modo gdrive actual : cualquiera accede solo con la URL | anonymo rapido sin-login | no puedes dejar de darle acceso a alguien <br> (complejo copiar y borrar el doc y reenviar el nuevo URL al resto)  
 | o cambiar en gdrive: restringe a un grupo google  | +seguro, controlando el grupo sabes  quien lee o quien YA no | para ver necesitas o ya estar logeado el dato (o hacer login)
 

<h1> Map3.  </h1> 


## simpler0
<svg fill="none" viewBox="0 0 120 120" width="120" height="120" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
@keyframes bounce {
  0%   { transform: scale(1,    1)   translateY(0)     skew(0deg,  0deg); }
  3%   { transform: scale(1,    1)   translateY(0)     skew(0deg,  0deg); }
  5%   { transform: scale(1.1,  .9)  translateY(5px)   skew(0deg,  0deg); }
  12%  { transform: scale(.9,   1.1) translateY(-70px) skew(25deg, 5deg); }
  13%  { transform: scale(.9,   1.1) translateY(-70px) skew(25deg, 5deg); }
  20%  { transform: scale(1.05, .95) translateY(0)     skew(0deg,  0deg); }
  22%  { transform: scale(1,    1)   translateY(-7px)  skew(0deg,  0deg); }
  27%  { transform: scale(1,    1)   translateY(0)     skew(0deg,  0deg); }
  100% { transform: scale(1,    1)   translateY(0)     skew(0deg,  0deg); }
}
h1 {
  width: 120px;
  line-height: 20px;
  padding-top: 70px;
  text-align: center;
  font: 400 16px/1.5 Helvetica ,Arial ,sans-serif;
  color: rgb(52, 73, 94);
  transform-origin: bottom;
  animation: 4s cubic-bezier(.5, 0, .5, 1.2) 1s infinite bounce;
}
      </style>
      <h1>Hello, world</h1>
    </div>
  </foreignObject>
</svg>
