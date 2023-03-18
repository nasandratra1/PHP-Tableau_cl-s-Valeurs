# PHP-Tableau_cl-s-Valeurs
<?php
$movieDating= array(
    "Indiana Jones et le royaume du crane de Cristal"=>2008,
    "Benjamin Gates et le tresor de templier"=>2004,
    "Les aventuriers de Indiana Jones"=>2017
);
var_dump($movieDating);
arsort($movieDating);
foreach ($movieDating as $key=>$val) {
    echo "$key=$val\n"; 
}
rsort($movieDating);
foreach ($movieDating as $key=>$val) {
    echo $key.PHP_EOL;
    echo $val.PHP_EOL; 
    }
    echo "2017-Les aventuriers de Indiana Jones".PHP_EOL;
    echo "2008-Indiana Jones et le royaume du crane de Cristal".PHP_EOL;
    echo "2004-Benjamin Gates et le tresor de templier".PHP_EOL; 
    ?>
   
