## Juan Hernández Cañaveras 

Ejercicio 1:

Descargar y ejecutar las pruebas de alguno de los proyectos anteriores, y si sale todo bien, hacer un pull request a este proyecto con tests adicionales, si es que faltan (en el momento que se lea este tema).

**Respuesta:** En este ejercicio, me he basado en el repositorio [Siguiente](https://github.com/JJ/tdd-gdg/) y he añadido las siguientes funciones:



def elevadoEnteros(base,exponente):

	if(not (type(base) is int)):

		return -1

	else:

		return math.pow(base, exponente)

 def testElevadoEnteros(self):

	self.assertEqual(elevadoEnteros(2,4), 16, "2 elevado 4 es 16")

	self.assertEqual(elevadoEnteros(-1,3), -1, "No es un entero")

if __name__ == '__main__':

    unittest.main()

Ejercicio 2:

Para la aplicación que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir tests para una nueva funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo TDD).

**Respuesta:** Lo que se pide , lo he hecho en mi proyecto y es algo parecido a lo que hago en el ejercicio anterior.

Ejercicio 3:

Convertir los tests unitarios anteriores con assert a programas de test y ejecutarlos desde mocha, usando descripciones del test y del grupo de test de forma correcta.

**Respuesta:** En este ejercicio hemos usado pocha para que nos ayude a ejecutar con mayor facilidad los tests para nuestras funciones.

![pro](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/pro.png)
 
Y si lo ejecutamos con pocha:

![3IV](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/3IV.png)

Ejercicio 4: 

Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor más actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

**Respuesta:** En este ejercicio vamos a ejecutar la orden: `sudo apt-get install virtualenv python-virtualenv` para así obtener virtualend, despues para el resto haríamos lo siguiente, para instalar una version de python desde virtualenv:

![4-1](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/4-1.png)

Ejercicio 5: 

Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hacen prácticas los alumnos.

**Respuesta:** En este caso, decir que lo que nos pide el ejercicio ya lo hacemos en nuestro [Proyecto](https://github.com/MagicJHC10/Proyecto-IV)  (funcionalidades del mismo estilo); aunque aun no mucho, pero de ahora en adelante conforme se va desarrollando el proyecto,mucho mas

Ejercicio 6:

Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?

**Respuesta:** Podemos observar que el archivo en el cual, tenemos los tests funciona correctamente en las tres versiones:

![ej6](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ej6.png)

Sin embargo, en un archivo con más código, en el que tenemos funciones , python3 tiene incompatibilidades, no así python2.7

![ej6-1](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/ej6-1.png)




