# RMI_Hospital
Desarrollar los conceptos teóricos del desarrollo de aplicaciones distribuidas implementado un sistema de gestión de un hospital haciendo uso de RMI.

La idea es crear un objeto remoto que contenga todos los métodos necesarios para la gestión de un hospital. De este modo todos lo clientes comparten la referencia al objeto que hace las veces de “repositorio” de la información.

Se crearán:
 
 Una clase servidor que instancie y registre la clase que gestiona el hospital.
 Una clase, con o sin interfaz gráfica, que obtenga la referencia al objeto remoto e invoque los métodos necesarios para su gestión.

1. El servidor registra el objeto remoto.
2. El cliente muestra un menú de consola con las opciones y obtiene una referencia al objeto remoto para trabajar con él.
3. Se gestionan expedientes y pacientes. 
