## Juan Hernández Cañaveras 
## Introducción a la infraestructura virtual: concepto y soporte físico 

Ejercicio 1:Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar este artículo en Infoautónomos sobre el tema.
**Respuesta:** Basandome en el siguiente producto: [PRODUCTO](https://www.mercadoactual.es/ordenador-servidor-lenovo-thinkserver-ts150.html?colabG=2&gclid=Cj0KCQjwgIPOBRDnARIsAHA1X3Qxoynd-fEG2KhrXhrGdCtXhJHR4-gI4Dwp9ZpY6HJu6hy5Z1ogTQsaAq31EALw_wcB) , el cual cuesta: 393,37€ y 310,76 sin iva.Y he hecho los siguientes cálculos: 

 1- Amortización en 4 años: Como en España puedes imputar anualmente como gasto deducible en concepto de amortización un máximo del 25% de la base imponible, la amortización sería:
 * 2017: 77,69€ (25%)
 * 2018: 77,69€ (25%)
 * 2019: 77,69€ (25%)
 * 2020: 77,69€ (25%)

 2- Amortización en 7 años:
 * 2017: 77,69€ (25%)
 * 2018: 62,15€ (20%)
 * 2019: 46,61€ (15%)
 * 2020: 46,61€ (15%)
 * 2021: 31,07€ (10%)
 * 2022: 15,53€ (5%)
 * 2023: 15,53€ (5%)

Ejercicio 2: Usando las tablas de precios de servicios de alojamiento en Internet “clásicos”, es decir, que ofrezcan Virtual Private Servers o servidores físicos, y de proveedores de servicios en la nube, comparar el coste durante un año de un ordenador con un procesador estándar (escogerlo de forma que sea el mismo tipo de procesador en los dos vendedores) y con el resto de las características similares (tamaño de disco duro equivalente a transferencia de disco duro) en el caso de que la infraestructura comprada se usa sólo el 1% o el 10% del tiempo.
**Respuesta:** Servidor dedicado --> [dedicado](https://www.ovh.es/servidores_dedicados/) "EG-32" y servidor virtual --> [virtual](https://www.hostalia.com/servidor-cloud/) "servidor cloud L"
	
DEDICADO VS VIRTUAL
RAM-> 32GB vs 16GB
Procesador->Intel  Xeon E3-1270v6 vs Procesador Intel® Xeon® (2 GHz)
Precio-> 94,99€/mes vs 199,9€/mes

Precios al año:
Dedicado--> 94,99*12=1139,88€
Virtual-->199,9*12=2398,8€

Si usamos el 1%:
 * Dedicado: No podemos usar solo el 1% --> 1139,88€
 * Virtual: 2389,8*0,01=23,98€

Si usamos el 10%:
 * Dedicado: No podemos usar solo el 10% --> 1139,88€
 * Virtual: 2389*0,1=238,98€

Ejercicio 3: En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags.¿Qué modelo de procesador es?¿Qué aparece como salida de ese orden? Si usas una máquina virtual,¿qué resultado da?¿Y en una Raspberry Pi o,si tienes acceso, el procesador del móvil?

**Respuesta:** Usamos la siguiente orden: "cat /proc/cpuinfo" y nos aparece información sobre el procesador(tipo,marca,rendimiento...). En concreto el modelo de procesador es: Intel(R) Core(TM) i3-2328M CPU @ 2.20GHz.

Ejercicio 4: 1-Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok. 2-Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.

**Respuesta:** 1-Ejecutando la orden "kvm-ok" nos da como resultado:

INFO: /dev/kvm exists
KVM acceleration can be used

Lo cual nos indica que si tenemos el nucleo instalado.

2- En cuanto al hipervisor, ya tengo instalado VirtualBox.

Ejercicio 5: Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.

**Respuesta:** Me he dado de alta en azure con los códigos pasados por el profesor:

![5IV](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/5IV.png)


Ejercicio 6: Darse de alta en una web que permita hacer pruebas con alguno de los sistemas de gestión de nube anteriores.

![6IV](https://github.com/MagicJHC10/Ejercicios/blob/master/IV_Fotos/6IV.png)







