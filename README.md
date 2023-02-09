<?php
$var1=20;
$var2=10;
$var3=28;
$var4=12;
switch($var1>$var2 && $var1>$var3 && $var1>$var4){
    case 1:
         echo "$var1 is greater";
         break;
    case 0: switch($var2>$var1 && $var2>$var3 && $var2>$var4)
    {
        case 1:
          echo "$var2 is greater";
          break;
        case 0: switch($var3>$var1 && $var3>$var2 && $var3>$var4){
          case 1:
            echo "$var3 is greater";
            break;
          case 0:
              echo "$var4 is greater";
                
          } 
        } 
        default : "all variable are equal";    
    }
?>
