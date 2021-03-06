# Riesgos Inform谩ticos 馃攼

Dentro del 谩rea de TI se encuentran las siguientes categor铆as de riesgos por los cuales debe velar el auditor.

* Integridad de la informaci贸n: Parte de los pilares de la seguridad de la informaci贸n.
* Acceso.
  * Segregaci贸n de funciones.
* Disponibilidad: Disponibilidad de la infraestructura, como serian los datos, sistemas y comunicaciones.
* Infraestructura: Infraestructura tecnol贸gica de toda organizaci贸n.
* Externalizaci贸n de Servicios: Externalizar procesos o servicios.

## Riesgos de Integridad de la Informaci贸n

Agrupa a todos los riesgos asociados con la **autorizaci贸n, integridad y exactitud** de las transacciones, las cuales se originan de los siguientes componentes:

* **Interfaz Usuaria:** Hace referencia a las restricciones de las personas y que acciones pueden realizar, junto a la segregaci贸n de funciones. Esto es conocido como la *necesidad del saber* donde una persona solo debe acceder a la infraestructura que necesita 煤nicamente.
* **Procesamiento:** Controles sobre el procesamiento de informaci贸n y su salida, que aseguran su cumplimiento y realizaci贸n a tiempo.
* **Interfase:** Se basa controles preventivos y detectivos sobre la transmisi贸n adecuada y completa de los datos o informaci贸n que han sido procesados en la interfaz usuaria.
* **Administraci贸n del Cambio:** Riesgos asociados a la ineficiente administraci贸n del cambio, as铆 como el entrenamiento del usuario en el nuevo proceso, sobre todo que estos cambios sean comunicados oportunamente y que sean implementados.
* **Error de Procesamiento:** Se refiere a la revisi贸n de excepciones en el procesamiento de datos, que estas puedan ser capturadas y reprocesadas nuevamente.

  Digamos un error de procesamiento en la actualizaci贸n del stock despu茅s de una compra, en donde el reproceso se encarga de arreglar el cambio en el stock.
* **Datos:** Hace referencia a errores en la programaci贸n, errores de procesamiento (verificaci贸n de puertas externas, donde se apliquen pr谩cticas de desarrollo seguro en las plataformas, donde [OWASP](https://en.wikipedia.org/wiki/OWASP) define un conjunto de normas al respecto.) y errores de administraci贸n de sistemas.

## Riesgos de Acceso

Pueden ocurrir a cualquier nivel digamos:

* Red: Generado por riesgo de acceso inapropiado a la red de pc's y servidores.
* Ambiente de Procesamiento: Generado por el acceso indebido al ambiente de procesamiento, a los programas y datos que est谩n almacenados dentro de este.
* Sistemas de Aplicaci贸n: Inadecuada segregaci贸n de funciones, que podr铆a ocurrir si el acceso a los sistemas estuviese concedido a personas con necesidades de negocio sin definiciones claras.
* Acceso Funcional: Dentro del c贸digo fuente.
* Acceso con respecto a campo o dato (Base de Datos).

Estos 5 niveles de acceso deben ser verificados por el auditor.

### Segregaci贸n de Funciones

Control sobre las funciones que caen sobre una sola persona, as铆 evitar la comisi贸n de *fraudes, sabotajes o errores internos*.

> Se busca que una persona no pueda hacerlo todo.

## Riesgo de Disponibilidad

Todo relacionado ante una **eventual ca铆da de un servicio**, sistema, equipo o todo aquello relacionado con la interrupci贸n del flujo normal del negocio.

Se busca que ante un proceso disruptivo es posible continuar con los procesos o la operaci贸n b谩sica que generan ganancia y cumplimiento de objetivos.

**Es importante** que se haga una clasificaci贸n de los sistemas que maneja una empresa, puesto que no es id贸neo invertir esfuerzos durante una crisis sobre procesos que no aportan nada al negocio.

* \*\*Para la UH \*\*si se cae el sistema de cr茅dito y cobro, y el correo el茅ctrico, obviamente seria de mayor prioridad sin la necesidad de un estudio el sistema de cr茅dito y cobro, puesto que existen otros medios de comunicaci贸n aparte del correo electr贸nico.
* **En un Call Cente**r un sistema de correo, chat y tel茅fono son sistemas cr铆ticos seg煤n su contexto.

### Cyber Resilencia

Reemplaza el t茅rmino de *cyber seguridad*, que es la combinaci贸n entre continuidad de la operaci贸n y cyber seguridad. Atiende eventos disruptivos en la operaci贸n donde se garantiza que la empresa est谩 preparada para atender esos eventos y continuar con su operaci贸n. Tiene aproximadamente 2 a帽os de ser utilizada en el mercado, siendo el Banco Nacional una entidad que cuenta con una metodolog铆a de cyber resilencia para hacer frente a dichos eventos disruptivos ante los cuales puede ver expuesto.

La [NISP](https://en.wikipedia.org/wiki/National_Industrial_Security_Program) establece un conjunto de elementos para verificar que tan cyber resilente se es en un producto, servicio o sistema.

## Riesgo de Infraestructura

Se refiere a infraestructura con respecto a *hardware, software, personas y procesos* para darle soporte a todos estos sistemas automatizados, apoya todas las necesidades actuales y futuras para ser competitiva, generar utilidades y crecer como empresa. Esta infraestructura debe ser eficiente y eficaz.

Se encuentra relacionada con los siguientes:

* **Planificaci贸n Organizacional:** Las necesidades por de medio de la empresa y como estas alteran al proceso de *toma de decisiones y planificaci贸n*, estos dos 煤ltimos deben de ser racionales, objetivos y orientados al negocio.
* **Definici贸n y despliegue de sistemas de aplicaci贸n:** El proceso de desarrollo, integraci贸n e implementaci贸n no est茅n correctamente focalizadas de tal manera que no es posible medir la satisfacci贸n del usuario final, intermedio o de negocio. Incluso viene un tema de capacitaci贸n del personal, donde la adquisici贸n de una soluci贸n en software donde la infraestructura es SAAS, pero no se incluye el tema de capacitaci贸n en su uso y nadie sabe como hacer uso de esta.
* **Seguridad L贸gica y Administrativa de Seguridad:** Donde se garantiza que no hay perdida de datos o mal uso de los datos por parte del acceso del personal interno de la compa帽铆a.
* **Operaciones con computador y red:** Que no existan problemas de desempe帽o, procesamiento u capacitaci贸n sobre su uso.
* **Administraci贸n de Bases de Datos:** Que las bases de datos carezcan de la integridad necesaria para apoyar a las decisiones de negocio.
* **Recuperaci贸n del centro de proceso de datos:** Que los sistemas, procesos y datos/informaci贸n no puedan ser restablecidos despu茅s de una interrupci贸n del servicio de manera oportuna para las necesidades del negocio.

Tambi茅n hace referencia a la transferencia de conocimiento, seguridad l贸gica, administraci贸n de la seguridad (que no se d茅 la perdida de informaci贸n ni el mal uso de este), administraci贸n de bases de datos.

## Riesgos de Externalizaci贸n de Servicios

Generar e implementar una metodolog铆a de an谩lisis de riesgos que permita evaluar los procesos y recursos, su vulnerabilidad y las amenazas para el proceso que la organizaci贸n externaliza (digamos proveedores), se eval煤a la dependencia con este.

Integrar el tema de que el **proveedor** puede reducir su exposici贸n al riesgo y que estos tambi茅n aplican su propia metodolog铆a de an谩lisis de riesgos.

![Mapa_Ideas_Riesgo_Informatica](resources/Mapa_Ideas_Riesgo_Informatica.png)

## Otros Aspectos a Considerar

La gesti贸n de riesgos debe considerar los siguientes aspectos

* Identificaci贸n del Sistema o Proceso.
* Identificaci贸n de las Amenazas.
* Identificaci贸n de las Vulnerabilidades.
* Controles (cu谩les, tipo, medici贸n de efectividad y seguimiento).
* Determinar la Probabilidad de ocurrencia.
* An谩lisis de Impacto.
* Determinaci贸n del Riesgo.
* Recomendaci贸n de Controles.
* Documentar los Resultados, **esto es lo m谩s dif铆cil.**

### Encriptaci贸n de Datos

Tecnolog铆a que asegura la transmisi贸n segura de informaci贸n, utiliza una llave p煤blica para codificar los datos, y una llave privada para des-encriptar datos.

### Aspectos a Considerar en la Seguridad de Informaci贸n.

* **Desde el Punto de Vista de Servidores**
  * Pruebas de penetraci贸n, estr茅s y extracci贸n de datos.
  * Antivirus instalado y actualizado en los servidores que dar谩n servicio.
  * Obsolescencia tecnol贸gica.
  * Parches de seguridad evaluados e instalados seg煤n corresponda en los servidores que dar谩n el servicio.
* **Transferencia de la Informaci贸n.**
  * Encriptaci贸n de la comunicaci贸n entre la organizaci贸n y la empresa prestadora de servicios.
* **Continuidad Operacional.**
  * Servidores de Respaldo
    * Sitio de respaldo.
    * Tecnolog铆as de respaldo, digamos en espejo sincr贸nico.
    * Pruebas de contingencia.
    * M谩quina especializada de respaldo.
    * Continuidad geogr谩fica.