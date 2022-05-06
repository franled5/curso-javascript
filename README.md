# curso-javascript
figuras geometricas (cuadrado , triangulo , circulo )


calcular las figuras geometricas 
//codigo del cuadrado 
console.group("cuadrado");
const ladocuadrado = 5;
console.log("los lados del cuadrado miden:" + ladocuadrado + "cm");

const perimetroCuadrado = ladocuadrado * 4;
console.log("el perimetro del cuadrado es :" + perimetroCuadrado + "cm");

const areaCuadrado = ladocuadrado * ladocuadrado;
console.log("el area del cuadrado es :" + areaCuadrado + "^2");

console.groupEnd();
//codigo del triangulo
console.group("triangulo");
const ladotriangulo1 = 6;
const ladotriangulo2 = 6;
const basetriangulo = 4;

console.log("los lados del triangulo miden:" 
 + ladotriangulo1 
 + "cm, "
 + ladotriangulo2 
 +"cm, "
 + basetriangulo 
 + "cm"
);
const alturatriangulo = 5.5;
console.log("la altura del triangulo es de :" + alturatriangulo + "cm");
const perimetrotriangulo = ladotriangulo1 + ladotriangulo2 + basetriangulo;
console.log("el perimetro del triangulo es :" + perimetrotriangulo + "cm");

const areatriangulo = (basetriangulo * alturatriangulo)/ 2 ;
console.log("el area del triangulo es :" + areatriangulo + "cm" + "^2");

console.groupEnd();
//codigo de circulo
console.group("circulos");
//radio 
const radiocirculo = 3;
console.log("el radio del circulo es :" + 3 + " cm, " );
//diametro
const diametrocirculo = radiocirculo * 2 ;
console.log("el diametro del circulo es:" + diametrocirculo + " cm ");
//PI
const PI = Math.PI;
console.log("el PI de el circulo es :" + PI + " cm");
//circunferencia
const perimetrocirculo =diametrocirculo * PI;
console.log("el perimetro del circulo es:" + perimetrocirculo + " cm");
//area
const areacirculo =(radiocirculo * radiocirculo) * PI;
console.log("el area del circulo es:" + areacirculo + " cm" + "^2");



console.groupEnd();
