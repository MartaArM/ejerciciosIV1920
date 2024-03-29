# Ejercicios resueltos tema 1 (introducción a la infraestructura virtual: concepto y soporte físico)

## Ejercicio 1

**Consultar en el catálogo de alguna tienda de informática el precio de un ordenador tipo servidor y calcular su coste de amortización a cuatro y siete años. Consultar [este articulo](https://infoautonomos.eleconomista.es/consultas-a-la-comunidad/988/) en Infoautónomos sobre el tema.**

Para saber como calcular la amortización, he leído [este artículo](https://www.ionos.es/startupguide/gestion/calculo-de-la-amortizacion/) en el que viene la siguiente formula:

*Cuota de amortización = (Valor de adquisición – Valor residual) / Años de vida útil*

En nuestro caso, el valor residual es 0.

El servidor que he escogido es [este](https://www.pccomponentes.com/servidor-hp-proliant-ml110-gen10-intel-xeon-3106-16gb). Su precio (sin IVA) es de 1057,02€. Por tanto: 

1. Para 4 años: 

       1057,02€ &divide; 4 = 264,25€
       
2. Para 7 años:

    1057,02€ &divide; 7 = 151€

## Ejercicio 3
**En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?**

El procesador de mi ordenador es un *Intel(R) Core(TM) i5-4200M CPU @ 2.50GHz*

En la salida, aparece: 

![Sin titulo](./images/flags_tema_1.png)

## Ejercicio 4

**Comprobar si el núcleo instalado en tu ordenador contiene este módulo del kernel usando la orden kvm-ok. Alternativamente (o además), usar lscpu como se indica arriba. **

**Instalar un hipervisor para gestionar máquinas virtuales, que más adelante se podrá usar en pruebas y ejercicios.**

Con la orden kvm-ok:

![Sin titulo](./images/kvm-ok.png)

compruebo que puedo utilizar la aceleración por hardware del procesador.

El hipervisor que utilizo es *VirtualBox* ya que lo he estado utilizando en varias asignaturas de la universidad.

## Ejercicio 5

**Darse de alta en servicios de nube usando ofertas gratuitas o cupones que pueda proporcionar el profesor.**

Me he dado de alta en *Heroku*, ya que es un servicio gratuito.
