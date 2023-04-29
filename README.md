# exerciciosphp


<?php
$valor=20;
if ($valor%2 == 0){
 for($i=0;$i<$valor;$i++)
     echo $i."<br>";
}else{
  echo "o valor é impar";
}
?> 

raiz quadrada

<?php 
$a=2;
$b=5;
$c=2;
$delta=($b*$b)-4* $a*$c;
if ($delta>=0){
$x1= ($b*(-1)+ sqrt($delta))/(2* $a);
$x2= ($b*(-1)- sqrt($delta))/(2*$a);
 echo $x1." ".$x2;
}else {
 echo "delta negativo";
}
 ?>
