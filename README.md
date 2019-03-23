# TAREA1
TAREA1 PROGRAMACIÓN 

// 2. La función CheckScrabble es una función que debe permitir descubrir si dos palabras están escritas con las mismas letras pero
// en distinto orden, ejemplos: "#Colombia" y "Boci#loam", "Z4PotlaN3jo" y "Pozjotlan43". Usted debe codificar esta funcionalidad usando
// operadores y estructuras de control de C++.
// En caso de que las palabras cumplan con la caracteristica de estar escritas con las mismas letras (¡la misma cantidad de letras obviamente!)
// se debe asignar el valor True a la variable ok_chscrb.
// Las palabras pueden estar formadas indistintamente por letras, números y caracteres raros, tal como vio en los ejemplos.
// Dato1: Lo primero que se debe verificar es si las palabras tienen el mismo número de letras, recuerde el operador size() del ejercicio anterior
// Dato2: Preguntele al buen Google por la representación en ASCII de las letras del abecedario (mayusculas y minusculas)
// Dato3: Puede utilizar directamente las variables palabra1 y palabra2 para implementar su codigo
// Pista esencial: NO es necesario que compare letra por letra individualmente.
//                 Reduzca el problema a un dominio común.

void CheckScrabble (string &palabra1, string &palabra2)
{
	ok_chscrb = False; /*Por favor NO borre esta linea de codigo*/
	
	//De aqui en adelante se debe implementar la lógica en código de C++
	
	
	/*************************************************************/
	/*Por favor NO borre las lineas de codigo siguientes */	
	if(ok_chscrb)
		cout<<"Tienen las mismas letras"<<endl;
	else
		cout<<"No tienen las mismas letras"<<endl;	
}
