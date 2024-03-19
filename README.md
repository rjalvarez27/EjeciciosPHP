<?php 
# Comentarios en PHP 

// comentario de una linea 
# comentario de una linea 

/*
EJERCICIOS SECCION 1.

1) Calcular e imprimir el area de un rectangulo.
2) Verficar si un numero es par o impar.
3) Comprobar si un estudiante aprobo o reprobo un examen.
4) Calcular e impimir la circunferencia de un circulo.
5) Determinar si un year es bisiesto o no.
6) Determinar la estacion del year segun un mes. (por numero de mes).
*/

# 1) Calcular e imprimir el area de un rectangulo.

$variable = 3;

$variable2 = 5;

$resultado = $variable * $variable2;

echo "1) El area del rectangulo es".$resultado;

# 2) Verficar si un numero es par o impar.

$numero = 33;

if($numero % 2 == 0){
    echo '<br>' ."2)" ." " . $numero . " es un numero par";
}else{
    echo  '<br>' ."2)" . " " .  $numero ."es un numero impar";
}

# 3)Comprobar si un estudiante aprobo o reprobo un examen.

$nota = 9;

if($nota < 10){
    echo "<br>" . "3)" . $nota ." ". "No paso el examen";
}else{
    echo "<br>". "3)" . $nota ." ". "Aprobo el examen";
}

# 4)Calcular e impimir la circunferencia de un circulo.

$radio = 5;

$areaC = 2*3.14*$radio;

echo "<br>"."4)"." ". "La circunferencia de circulo es". " " . $areaC;  

# 5) Determinar si un year es bisiesto o no.

$año = 2024;

/*
$prueba1 = date("o");
echo "<br>"."". $prueba1 ."";
*/
if(($año%4 == 0 and $año%100!=0 ) or $año%400 ==0){
    echo "<br>" ."4)". "". $año ." ". "es bisiesto";
}else{
    echo "<br>"."". "4)". $año ." ". "no es bisiesto";
}
   
# 6) Determinar la estacion del year segun un mes. (por numero de mes).

$mes = "noviembre";
/*
$prueba = date("F");
echo $prueba;
*/
if($mes =="diciembre" or $mes=="enero" or $mes== "febrero"){
    echo "<br>"."5)". " " .$mes ." ". " es Invierno";
}elseif($mes =="marzo" or $mes=="abril" or $mes== "mayo"){
    echo "<br>"."5)". " " .$mes ." ". " es Primavera";
}elseif($mes =="junio" or $mes=="julio" or $mes== "agosto"){
    echo "<br>"."5)". " " .$mes ." ". " es verano";
}elseif($mes =="septiembre" or $mes=="octubre" or $mes== "noviembre"){
    echo "<br>"."5)". " " .$mes ." ". " es otoño";
}
?>;



