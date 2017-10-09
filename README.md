# **Cifrado César**
## 1.Iniciamos determinando una variable  que contenga un _string_ .
## 2.Tenemos que transformar nuestro _string_ a un _array_,<br/>para con ello poder evaluar cada una de las letras que se encuentre.
## 3. Tendremos que crear otra variable que<br/>contenga __la palabra o frase__ que se introducirá. <br/> var word=prompt('Ingrese frase');

## 4. mediante el while identificaremos la longitud de **word** y <br/>que no se reconozca a un Number dado que nos<br/> piden no considerar números y espacios vacios.

## 5. Mediante un for(var i=0;i<word.length;i++){ encontraremos el index de cada letra.

## 6. Mediante el charAt obtendremos el caracter de la palabra que ingrese y con charCodeAt nos proporciona el número que posee en ACSSI  num=(word.charAt(i)).charCodeAt();

## 7. empleando la formula para decifrar seria:<br/>newposition=(position+num)%26;<br/>newLetter+=letter[newposition-1];
