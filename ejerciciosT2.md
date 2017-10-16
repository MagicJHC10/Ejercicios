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
