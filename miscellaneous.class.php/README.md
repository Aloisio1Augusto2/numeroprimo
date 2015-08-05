# numeroprimo
numeros primos em php


<?php

$numero = 10;

if (gmp_prob_prime($numero)) {
	print 'É primo';
} else {
	print 'Não é primo';
}

?>
