Universidad Militar Nueva Granada

Programa: Ingeniería Biomédica

Asignatura: Instrumentación Biomédica y Biosensores

Práctica: Reconocimiento de partes y funcionamiento de una maquina de anestesia

# **Integrantes**
>
* María Angélica Vargas Saldaña 5600820
* Samuel Esteban Fonseca Luna — 5600808
* Laura Daniela Triana Molano — 5600828

<h2 align="center">I𝙣𝙩𝙧𝙤𝙙𝙪𝙘𝙘𝙞ó𝙣</h2>
 
La máquina de anestesia es uno de los equipos biomédicos más críticos del entorno quirúrgico. Su función es mantener al paciente en un estado de inconsciencia controlada, estable y reversible, mientras le suministra oxígeno, lo ventila y le administra una mezcla de gases y agentes anestésicos en concentraciones precisas [14]. Para lograrlo integra varios subsistemas que trabajan en conjunto: el sistema de suministro de gases de alta, intermedia y baja presión; los flujómetros y vaporizadores; el sistema respiratorio o circuito circular con absorbedor de CO₂; el ventilador; los sensores de presión, flujo y oxígeno, y el sistema de evacuación de gases residuales (AGSS).
 
El margen de error en estos equipos es estrecho. Administrar demasiado anestésico puede causar daño cerebral o paro cardíaco, mientras que administrar muy poco puede hacer que el paciente despierte durante la cirugía. Aunque las estaciones de anestesia modernas han reducido considerablemente estos riesgos, la mayoría de las fallas que todavía ocurren están relacionadas con el usuario: verificaciones preoperatorias omitidas, conexiones mal hechas o desconocimiento del equipo [15], [16]. Por eso, para el ingeniero biomédico es fundamental conocer la arquitectura de la máquina, sus pruebas de funcionamiento y sus alarmas, ya que es quien apoya al personal clínico en la gestión, el mantenimiento y la solución de fallas del equipo.
 
En esta práctica se estudió la máquina de anestesia Mindray WATO EX-20 disponible en el laboratorio de la universidad. A partir de la revisión de literatura y de los manuales del fabricante, se identificaron sus partes principales, se analizó el funcionamiento del sistema respiratorio y del ventilador, y se revisaron los procedimientos de verificación y las fallas más frecuentes descritas por el fabricante.
 
<h2 align="center">O𝙗𝙟𝙚𝙩𝙞𝙫𝙤𝙨</h2>
 
𝙊𝙗𝙟𝙚𝙩𝙞𝙫𝙤 𝙜𝙚𝙣𝙚𝙧𝙖𝙡: 
 
Reconocer los componentes, el funcionamiento y las labores de mantenimiento de la máquina de anestesia Mindray WATO EX-20, comprendiendo la función de cada uno de sus subsistemas dentro del procedimiento anestésico.

𝙊𝙗𝙟𝙚𝙩𝙞𝙫𝙤𝙨 𝙀𝙨𝙥𝙚𝙘𝙞́𝙛𝙞𝙘𝙤𝙨:

Identificar y ubicar las partes principales de la máquina de anestesia WATO EX-20 (vaporizador, válvula APL, recipiente absorbente de CO₂ y fuelle), explicando la función de cada una.
Comprender el funcionamiento del sistema respiratorio, del ventilador y de sus modos de operación (VCV y modo presión), así como la configuración de parámetros como la pausa inspiratoria.
Reconocer la importancia de las pruebas preoperatorias y de las labores de mantenimiento (prueba de fugas de alta y baja presión, reemplazo de la cal sodada, calibración del sensor de O₂).
Analizar las fallas más frecuentes de los subsistemas de la máquina, sus causas y su relación con la seguridad del paciente, a partir del manual del fabricante.
<h2 align="center">𝙋𝙧𝙤𝙘𝙚𝙙𝙞𝙢𝙞𝙚𝙣𝙩𝙤</h2>

La práctica fue de tipo demostrativo y se desarrolló en las siguientes etapas:

Revisión bibliográfica previa: se consultó literatura sobre tipos de anestesia, gases medicinales y sistemas respiratorios, junto con el manual de operación y el manual de servicio de la WATO EX-20 [4], [9], para responder las preguntas de la Parte A. La información obtenida con herramientas de IA generativa se verificó contra estas fuentes.
Normas de seguridad: se ingresó al laboratorio con bata, pantalón largo y cabello recogido. El equipo no se encendió ni se manipuló sin la presencia del técnico encargado.
Reconocimiento físico del equipo: con el acompañamiento del técnico se recorrió la máquina por módulos: entradas de gases y cilindros de respaldo, manómetros, flujómetros, vaporizador, botón de flujo rápido de O₂, sistema respiratorio (fuelle, válvula APL, interruptor bolsa/ventilador, absorbedor de CO₂) y pantalla del ventilador.
Registro fotográfico: se tomaron fotografías de la máquina y de sus partes principales, que se usaron para ubicar y señalar el vaporizador, la válvula APL, el recipiente absorbente de CO₂ y el fuelle (Parte B, punto 1).
Exploración de la interfaz del ventilador: se recorrieron los menús del equipo (modo de ventilación, ajuste de alarmas, ajustes de usuario y mantenimiento) y se identificaron los parámetros de ventilación, entre ellos la pausa inspiratoria (TIP:TI).
Revisión de pruebas y mantenimiento: se revisaron en el manual los procedimientos de verificación preoperatoria (fugas del sistema de alta presión, prueba de presión negativa del sistema de baja presión, prueba del sistema de control de flujo y calibración del sensor de O₂), el criterio de cambio de la cal sodada y la respuesta ante la alarma “batería en uso”, para responder la Parte B.
Análisis de fallas: se consultó el capítulo de solución de problemas del manual de servicio [9] para identificar las fallas de cada subsistema y ordenarlos según su número de fallas asociadas.
Documentación: toda la información recopilada se organizó en este repositorio de GitHub, en el que los tres integrantes figuran como colaboradores.

<h1 align="center"><i><b>𝐏𝐚𝐫𝐭𝐞 A 𝐝𝐞𝐥 𝐥𝐚𝐛𝐨𝐫𝐚𝐭𝐨𝐫𝐢𝐨</b></i></h1>

a. ¿Cuántos y cuáles son los tipos de anestesia que comúnmente se aplican
durante una cirugía? Explique cada uno.


La anestesia es un procedimiento médico que tiene como finalidad bloquear de manera temporal la habilidad del cerebro de reconocer un estímulo doloroso. Así, se pueden llevar a cabo procedimientos quirúrgicos complejos, intervenciones para controlar el dolor y otros procedimientos invasivos sin que el paciente sienta dolor. La anestesia juega un papel esencial en la medicina actual.
Normalmente se reconocen 4 (cuatro) tipos principales de anestesia, la elección del tipo de anestesia depende del procedimiento quirúrgico, las condiciones del paciente, sus antecedentes y de la valoración del anestesiólogo. Veremos los tipos de anestesia.
1.	Anestesia general: Es un estado de inconsciencia controlada reversible, ausencia de percepción del dolor y disminución o supresión de los reflejos. El paciente permanece inconsciente durante el procedimiento. Puede requerir asistencia ventilatoria. Puede durar desde unos minutos hasta varias horas, dependiendo de la duración del procedimiento o la operación. Su anestesista lo monitorizará de cerca y se asegurará de que dure el tiempo necesario

 La anestesia general es indispensable para una gran variedad de intervenciones quirúrgicas mayores, especialmente cuando el procedimiento quirúrgico es muy complejo, no siendo viable anestesiar solo una región del cuerpo como lo es el caso del abdomen, los pulmones o el corazón, así como la mayoría de las operaciones en las arterias principales o el cerebro. Las operaciones de mínima invasión (laparoscópicas) en el abdomen también generalmente lo requieren
Los anestésicos generales se administran de dos maneras diferentes:
•	Una inyección de un medicamento anestésico en una vena.
•	Inhalar un gas anestésico.

2.	Anestesia regional: Este proceso implica la inyección de anestesia local cerca de los nervios que abastecen una área más grande o profunda del cuerpo. El área del cuerpo afectada se adormece. Los anestesiólogos a menudo utilizan una máquina de ultrasonido o un estimulador de nervios para identificar la posición exacta de los nervios. 

La anestesia regional tiene varias ventajas, entre las que se incluyen la disminución de los efectos secundarios sistémicos en relación con la anestesia general y la posibilidad de recuperarse más rápido. Es especialmente ventajoso para los pacientes que presentan algunas condiciones de salud que podrían incrementar el riesgo de la anestesia general.

Este tipo de anestesia cuenta con tres tipos, en los cuales están:
•	Anestesia espinal Una sola inyección en la espalda y en la columna vertebral (en el líquido cefalorraquídeo que rodea la médula espinal), este tipo de anestesia proporciona entumecimiento y relajación muscular rápidos y profundos para procedimientos que involucran la parte inferior del abdomen, la pelvis y las extremidades inferiores, que adormece durante aproximadamente dos horas.
•	Una anestesia epidural: se utiliza una aguja para colocar un tubo muy fino (catéter epidural) en tu espalda en el espacio epidural, justo fuera de la membrana protectora de la médula espinal. Se administra anestesia local de refuerzo a través del catéter para aliviar el dolor, se utiliza habitualmente para el parto, así como para el tratamiento del dolor después de cirugías mayores de tórax o abdominal, a veces junto con anestesia general. Puede durar muchas horas o unos pocos días
•	Bloqueos de nervios periféricos: Implican inyectar anestésico local cerca de nervios o haces de nervios específicos que inervan una extremidad o parte del cuerpo en particular.  Esto puede permitirle someterse a la operación sin anestesia general. Los bloqueos nerviosos también son útiles para el control del dolor después de la operación, ya que el área permanecerá adormecida durante varias horas.
3.	Sedación (cuidado anestésico monitorizado - MAC): La sedación implica el uso de pequeñas cantidades de medicamentos anestésicos generalmente por vía intravenosa, para producir un estado similar al sueño. Te hace sentir relajado física y mentalmente, pero no inconsciente. Los niveles de sedación varían de leve a profundo:
-	Sedación leve: El paciente está despierto pero relajado, es capaz de comunicarse y seguir instrucciones.
-	Sedación moderada:  El paciente puede quedarse dormido, pero puede despertarse fácilmente. Esto se usa comúnmente para procedimientos de diagnóstico como colonoscopias
-	Sedación profunda: El paciente está profundamente dormido, pero aún puede respirar de forma independiente, sin ayuda. Este nivel está muy cerca de la anestesia general, pero normalmente no implica el mismo grado de relajación muscular o manejo de las vías respiratorias. Usada en procedimientos como la endoscopia superior.
4.	Anestesia local: Un anestésico local adormece una pequeña parte del cuerpo, se administra mediante una inyección de un agente anestésico local directamente en el tejido, o aplicándolo tópicamente en forma de crema o aerosol. Permaneces consciente, pero sin sentir dolor ya que bloquea los impulsos nerviosos en esa región localizada. Ejemplos comunes de cirugía bajo anestesia local son la extracción de dientes

b. ¿Con cuáles gases trabaja una máquina de anestesia y qué función cumple cada uno? ¿Cuáles de ellos se incorporan a la máquina mediante sistema de alta presión?
La máquina de anestesia utiliza principalmente gases medicinales para proporcionar oxígeno, preparar mezclas respiratorias y administrar agentes anestésicos.}

| Gas | Función |
| ------------- | ------------- |
| Oxígeno (O₂) | Mantiene la oxigenación del paciente y permite preparar la mezcla de gases respiratorios |
| Óxido nitroso (N₂O) | Actúa como coadyuvante anestésico y analgésico. Permite complementar la anestesia general. |
| Aire medicinal | Se mezcla con el oxígeno para ajustar la concentración de oxígeno suministrada al paciente. |

También se utilizan agentes anestésicos volátiles, como:
•	Sevoflurano: produce y mantiene la anestesia general.
•	Isoflurano: agente inhalatorio para mantener la anestesia.
•	Desflurano: anestésico inhalatorio que permite ajustes rápidos de la profundidad anestésica.
Estos últimos son agentes anestésicos líquidos que se convierten en vapor mediante vaporizadores; no son gases de suministro central como el oxígeno
Sistema de alta presión:
Los gases que ingresan mediante cilindros conectados al sistema de alta presión son principalmente:
•	Oxígeno (O₂).
•	Óxido nitroso (N₂O).
En los equipos convencionales, estos cilindros se conectan a reguladores de presión para reducirla antes de que el gas llegue al sistema de control de flujo.
El aire medicinal generalmente ingresa mediante una red central de suministro o puede obtenerse de un compresor, dependiendo del equipo.

c. ¿Qué es el sistema de respiración en la máquina de anestesia y cuál es su función? ¿Qué partes de este sistema podrían esterilizarse por medio de autoclave?

El sistema de respiración, también denominado sistema circular de anestesia o circuito circular, consiste en la agrupación de elementos que posibilitan el traslado de los gases respiratorios y anestésicos del paciente a la máquina de anestesia y viceversa.

Su función básica es posibilitar la ventilación del paciente, proveer la combinación de gases, eliminar el dióxido de carbono (CO₂) exhalado y, en caso de que se use un circuito circular con reinhalación, posibilitar la utilización de los gases que no han sido consumidos.


COMPONENTES DE LOS SISTEMAS RESPIRATORIOS Un sistema de respiración está formado por componentes que se conectan entre el paciente y la máquina de anestesia1, y está generalmente compuesto por algunos o todos de los siguientes elementos: 

1. La válvula de Limite Ajustable de Presión (APL) permite variar la presión dentro del sistema anestésico, usando una válvula unidireccional, con resorte. A una presión por encima de la presión de apertura de la válvula, se permite una fuga controlada de gas del sistema, que permite el control de presión de la vía aérea del paciente. La presión mínima requerida para abrir la válvula es de 1cm H2O. Un mecanismo de seguridad existe para evitar que la presión supere los 60cm de H2O, sin embargo, debe tomarse en cuenta que las presiones por debajo de este valor pueden llevar a baro trauma.
   
2. La bolsa de reservorio permite la colección de flujo de gas fresco durante la expiración, que a su vez reduce la cantidad de gas fresco para evitar la reinhalación. Además, permite el Anestesiólogo vigilar el patrón ventilatorio de una respiración espontáneamente. Estas suelen ser de plástico o goma y pueden venir en tamaños entre 0.5 litros a 6 litros. Sin embargo, el tamaño más común en el sistema adulto es de 2 litros. La Ley de Laplace establece que la presión es igual a dos veces el radio, dividido por el radio de la bolsa. Por lo tanto, a medida que la bolsa aumenta, reduce la presión dentro de ella. Se trata de una medida de seguridad importante como la expansión de la bolsa limita la presión de gas dentro del sistema.

4.  La rama inspiratoria permite el paso de flujo de gas fresco al paciente durante la inspiración. La rama espiratoria permite el paso de gas expirado del paciente. Aunque la longitud de la tubería varía en función del sistema empleado, el diámetro es de tamaño estándar: 22 mm para adultos y 18 mm para sistemas pediátricos.


| Componente | Función |
| ------------- | ------------- |
| Manguera inspiratoria| Transporta los gases desde la máquina hasta el paciente.|
|Manguera espiratoria | Conduce los gases exhalados desde el paciente hacia el sistema. |
| Bolsa reservorio | Almacena temporalmente los gases y permite la ventilación manual. |
| Válvula APL | Limita la presión del circuito durante la ventilación manual y permite liberar el exceso de gas.|
| Válvula inspiratoria | Permite el paso de gases hacia el paciente e impide el flujo en sentido contrario. |
| Válvula espiratoria | Permite la salida de los gases exhalados y evita su retorno por esa vía. |
| Absorbedor de CO₂ | Contiene un material absorbente, generalmente cal sodada, que elimina el CO₂ del gas exhalado. |
| Fuelle o concertina | Almacena los gases y permite su administración durante la ventilación mecánica. |


Partes que pueden esterilizarse mediante autoclave:
Que es la esterilización por autoclave: Se trata de un envase metálico de paredes gruesas y de cierre hermético que posibilita la creación de un entorno de alta presión para la esterilización o cocción con vapor de agua. La presión alta permite que el agua llegue a temperaturas más altas de 100 °C y, cuando se combinan, la presión y el vapor desnaturalizan las proteínas de los microorganismos.

Dependiendo del fabricante y de los materiales de fabricación, pueden ser esterilizados por este método las:
•	Válvulas inspiratoria y espiratoria desmontables.
•	Carcasa o conjunto del sistema respiratorio.
•	Fuelle o concertina.
•	Recipiente del absorbedor de CO₂.
•	Algunas conexiones y piezas desmontables del circuito.

No todos los componentes pueden introducirse en autoclave. Las mangueras, bolsas reservorio, sensores y piezas plásticas pueden tener restricciones de temperatura y presión. Se debe consultar el manual de limpieza y esterilización del fabricante. No se debe asumir que una pieza es autoclavable únicamente porque sea desmontable. Por ejemplo, los sistemas de respiración de Mindray A3/A5 y GE Aisys tienen instrucciones específicas para desmontar y procesar sus componentes

d. ¿Cuántos y cuáles son los submenús del ventilador? ¿En qué consiste cada uno? ¿En cuál de ellos se puede activar la pausa inspiratoria?

Esta pregunta depende del fabricante y modelo de la máquina de anestesia, porque la distribución de los menús y sus nombres no es universal.
En este modelo Mindray WATO EX-20 que encontramos en la universidad hay que distinguir entre los modos de ventilación y los menús de configuración. En el manual del equipo se identifican cuatro opciones principales relacionadas con la configuración y funcionamiento del ventilador:
1. Modo de ventilación (Modo Vent): permite seleccionar el tipo de ventilación mecánica que recibirá el paciente. Incluye:
•	VCV: ventilación controlada por volumen. Se establece un volumen corriente que el ventilador suministra en cada respiración.
•	Modo P o PCV: ventilación controlada por presión. Se establece una presión inspiratoria y el volumen suministrado depende de las condiciones pulmonares del paciente.
2. Ajuste de alarmas (Ajuste alarma): permite modificar los límites de las alarmas del ventilador y del módulo de gases. Supervisa parámetros como presión de las vías respiratorias, volumen minuto, volumen corriente, frecuencia respiratoria y concentración de oxígeno.
3. Ajustes de usuario (Ajst usrio): permite modificar configuraciones generales del equipo, como compensación del volumen corriente, supervisión de oxígeno, configuración del módulo de gases, pantalla y sonido.
4. Mantenimiento (Mantenim.): permite realizar pruebas de funcionamiento, pruebas de fugas, calibración del sensor de oxígeno y del sensor de flujo, además de configurar opciones como la hora y las unidades de presión.

¿En cuál se puede activar la pausa inspiratoria?
La pausa inspiratoria se configura en el modo VCV (ventilación controlada por volumen) mediante el parámetro TIP: TI (tiempo de pausa inspiratoria respecto al tiempo inspiratorio).
Consiste en hacer una pausa al término de la inspiración antes de comenzar la espiración. A lo largo de este periodo, se suspende momentáneamente el suministro de gas, lo que favorece la distribución del gas en los pulmones.

En el WATO EX-20:
- Es posible desactivarlo (DES).
- Puede ser ajustado entre el 5 % y el 60 %.
- Se lleva a cabo el ajuste a través de las teclas rápidas de los parámetros del ventilador.



<h1 align="center"><i><b>𝐏𝐚𝐫𝐭𝐞 B 𝐝𝐞𝐥 𝐥𝐚𝐛𝐨𝐫𝐚𝐭𝐨𝐫𝐢𝐨</b></i></h1>
1. Identifique y ubique las siguientes partes de la máquina de anestesia WATO
EX-20, explicando su función.
<img width="1920" height="750" alt="image" src="https://github.com/user-attachments/assets/368bbcce-b775-4c16-bd16-667382415d0e" />

| Componente | Ubicación en la WATO EX-20 | Función |
| :--- | :--- | :--- |
| **a. Vaporizador** | Parte frontal izquierda/central superior del cuerpo principal, montado sobre el colector tipo Selectatec. | Convierte el agente anestésico líquido volátil (como sevoflurano, isoflurano o desflurano) en vapor y lo dosifica con precisión dentro del flujo de gas fresco antes de enviarlo al circuito respiratorio del paciente. |
| **b. Válvula APL** (*Adjustable Pressure-Limiting*) | Parte superior del módulo del sistema respiratorio, junto al interruptor Bolsa/Ventilador y al manómetro de presión de vía aérea. | Regula y limita la presión máxima dentro del circuito durante la ventilación manual o espontánea, permitiendo la salida controlada del exceso de gas hacia el sistema de evacuación (AGSS) para evitar barotrauma. |
| **c. Recipiente absorbente de CO₂** | Parte inferior del ensamblaje del sistema respiratorio (costado izquierdo frontal), debajo del bloque del fuelle. | Contiene cal sodada (material absorbente) que elimina químicamente el CO₂ exhalado por el paciente en el circuito circular, permitiendo la reinhalación segura de los gases frescos y anestésicos sin riesgo de hipercapnia. |
| **d. Fuelle** | Parte superior del módulo del sistema respiratorio (lado izquierdo), alojado dentro de una campana transparente graduada. | Actúa como interfaz neumática entre el gas impulsor del ventilador y el gas del paciente para suministrar el volumen corriente en ventilación mecánica. Al ser ascendente, también sirve como indicador visual de fugas o desconexiones si no logra elevarse completamente durante la espiración. |

<img width="719" height="1600" alt="image" src="https://github.com/user-attachments/assets/7c8766b1-c15f-4ba8-ada7-5445b27d4cb8" />
<img width="719" height="1600" alt="image" src="https://github.com/user-attachments/assets/aa4b3462-5309-4bdc-a562-4bd28cff3101" />
<img width="719" height="1600" alt="image" src="https://github.com/user-attachments/assets/47c005ad-469f-44ae-bdbf-7e620c0b6fc6" />

---

### 2. Si el ventilador muestra el mensaje “batería en uso” y el paciente se encuentra conectado a la máquina, ¿qué acción debería ejecutarse?

El mensaje **“batería en uso”** indica que la máquina perdió la alimentación eléctrica de corriente alterna (CA) y está operando con su batería interna de respaldo. Ante esta situación se debe:

- **Verificar inmediatamente la alimentación de CA:** Comprobar que el cable de poder esté bien conectado a la toma de corriente, revisar el interruptor principal del equipo y confirmar si hubo un corte de energía en la red del quirófano.
- **Mantener la ventilación y vigilar el nivel de carga:** No desconectar al paciente de forma brusca. La batería interna proporciona una autonomía temporal (aproximadamente 90 minutos con una batería nueva completamente cargada, o hasta 150 minutos con dos baterías) mientras se restablece el suministro eléctrico.
- **Preparar ventilación de respaldo:** Si la energía de CA no se restablece antes de que la batería alcance un nivel crítico, el operador debe estar listo para cambiar a **ventilación manual** mediante el interruptor Bolsa/Ventilador o utilizar un resucitador manual (bolsa autoinflable) con una fuente alterna de oxígeno.

---

### 3. ¿Con qué frecuencia debería reemplazarse el recipiente absorbente de CO₂?

El absorbente de CO₂ (cal sodada) debe inspeccionarse antes de cada procedimiento quirúrgico y reemplazarse cuando ocurra cualquiera de las siguientes condiciones:

- **Cambio de color del indicador:** Cuando aproximadamente **dos tercios (2/3)** del contenido del recipiente hayan cambiado de color (por ejemplo, de blanco a violeta/púrpura), siguiendo siempre la recomendación del fabricante de la cal sodada.
- **Aumento de CO₂ inspirado ($FiCO_2$):** Si el monitor de capnografía registra la presencia o elevación de CO₂ inspirado, lo cual confirma que el absorbente está agotado (este es el criterio más fiable, ya que el color puede revertirse parcialmente cuando el equipo queda en reposo).
- **Desecación o inactividad prolongada:** Si el equipo permaneció sin uso por un tiempo prolongado o con flujo continuo de gas que haya secado el absorbente, ya que la cal sodada seca puede reaccionar exotérmicamente con los agentes anestésicos volátiles y generar monóxido de carbono u otros compuestos tóxicos.

---

### 4. ¿Cuál es el procedimiento para verificar si hay fuga en el cilindro de alta presión?

Para comprobar la estanqueidad del sistema de alta presión (cilindros de respaldo de O₂ o N₂O) en la WATO EX-20 se sigue este procedimiento:

1. **Desconectar** las mangueras de suministro de gas de la red central (tuberías de pared) para aislar los cilindros.
2. **Cerrar** completamente todas las válvulas de control de flujo (flujómetros).
3. **Abrir lentamente** la válvula del cilindro que se va a evaluar y registrar la lectura en su manómetro correspondiente (verificando que tenga presión suficiente para la prueba).
4. **Cerrar** por completo la válvula del cilindro.
5. **Observar el manómetro** durante **1 minuto**.
6. **Evaluar el resultado:** La presión debe permanecer estable. Si se observa una caída significativa de presión (superior a **50 psi / ~0.35 MPa** en 1 minuto para O₂, o una pérdida evidente en el manómetro), existe una fuga en el sistema de alta presión (usualmente en el empaque/sello del yugo o en las conexiones). En ese caso se debe reemplazar el sello, ajustar nuevamente el cilindro y repetir la prueba; si la fuga persiste, el equipo no debe ponerse en servicio.

---

### 5. ¿Influye el contar o no con el sensor de O₂ al hacer la prueba sobre el sistema de control de flujo? ¿De qué forma?

**Sí influye**, ya que determina si es posible verificar de manera electrónica y cuantitativa la concentración real de oxígeno suministrada y el sistema de protección contra mezclas hipóxicas:

- **Con sensor de O₂ instalado y calibrado:** Al realizar la prueba del sistema de control de flujo (donde se evalúa el libre desplazamiento de los flotadores y el enlace proporcional $O_2 / N_2O$ que impide entregar menos del 25 % de $O_2$), el sensor permite **confirmar en pantalla** que la concentración inspirada de oxígeno ($FiO_2$) se mantiene por encima del límite seguro ($\ge 25\%$) al variar los flujos, además de comprobar que las alarmas de baja concentración de oxígeno se activen correctamente.
- **Sin sensor de O₂ (o deshabilitado):** No es posible medir electrónicamente la concentración real de oxígeno entregada al circuito ni probar las alarmas de $FiO_2$ baja. La verificación queda limitada únicamente a una **inspección visual y mecánica** de las escalas de los rotámetros, por lo que en uso clínico sería obligatorio emplear un monitor de oxígeno externo para garantizar la seguridad del paciente.

---

### 6. ¿Para qué se requiere el sistema de presión negativa?

En la máquina de anestesia WATO EX-20, el sistema de presión negativa cumple dos propósitos principales:

1. **Prueba de fugas del sistema de baja presión:** Durante la verificación preoperatoria se conecta un **bulbo o pera de succión de presión negativa** a la salida común de gas fresco (CGO). Al comprimir el bulbo se genera vacío en el circuito de baja presión (flujómetros, vaporizador y conductos hacia la CGO); si el bulbo permanece colapsado durante al menos **10 segundos** sin volver a inflarse, se confirma que no hay fugas en esta sección.
2. **Evacuación de gases anestésicos residuales (AGSS) y succión clínica:** Durante la operación en quirófano, la presión negativa (vacío) permite extraer de forma segura los gases anestésicos exhalados y liberados por la válvula APL y el ventilador a través del sistema AGSS, evitando la contaminación del quirófano y la exposición ocupacional del personal de salud (además de alimentar módulos de aspiración de secreciones si el equipo dispone de ellos).
<h1 align="center"><i><b>𝐀𝐧á𝐥𝐢𝐬𝐢𝐬 𝐝𝐞 𝐫𝐞𝐬𝐮𝐥𝐭𝐚𝐝𝐨𝐬</b></i></h1>
 
### Análisis 1. Fallas que pueden presentarse en los subsistemas de la máquina de anestesia y sus causas
 
El capítulo 5 (*Troubleshooting*) del manual de servicio de las WATO EX-20/30/35 [9] agrupa las fallas en alarmas técnicas, problemas del circuito neumático y problemas de hardware y eléctricos. A continuación se resumen las fallas más representativas de cada subsistema:
 
| Subsistema | Fallas típicas | Causas principales |
| :--- | :--- | :--- |
| **Suministro de gases y gas impulsor** (alta presión) | Alarmas “Fallo suministro O₂” y “Presión gas impulsor baja”; fugas; manómetro de tubería inexacto o fluctuante. | Presión de la red o del cilindro insuficiente (la alarma de suministro de O₂ se activa por debajo de unos 200 kPa); mangueras, sellos o conectores rápidos dañados; filtros o tubos obstruidos; interruptor de presión defectuoso o mal ajustado. |
| **Sistema de suministro de anestésico** (flujómetros, vaporizador, flujo rápido de O₂) | Fugas en el vaporizador o en el botón de flujo rápido; flotador inexacto o atascado; enlace O₂/N₂O inefectivo; el N₂O no se corta cuando falla el O₂. | Vaporizador mal montado o con sellos dañados; colector del vaporizador averiado; flujómetro dañado; válvula de corte O₂–N₂O averiada; sellos internos del interruptor del sistema deteriorados. |
| **Sistema respiratorio / circuito del paciente** | Fugas durante la ventilación manual o mecánica; lectura errónea de la concentración de O₂; lecturas erróneas del manómetro o del sensor de flujo. | Recipiente de CO₂ mal instalado o con sellos dañados; fuelle o campana mal montados o rotos; tapa de válvulas mal colocada; vaso colector de agua flojo; tubos del paciente dañados; agua sobre el sensor de O₂ o dentro del sensor de flujo; sensor de O₂ sin calibrar o agotado. |
| **Ventilador y medición de volumen** | “VT no alcanzado”, “Pinsp no alcanzada”, volumen corriente inexacto, “Paciente desconectado?”, presión sostenida en vía aérea. | Fugas en el circuito con bajo flujo de gas fresco; sensor de flujo mal instalado, húmedo, sucio o con la membrana deformada; deriva del cero del sensor de presión; límite de presión (Plimit) ajustado muy bajo; fallas de las válvulas inspiratoria, PEEP o de seguridad. |
| **Alimentación eléctrica y electrónica** | “Batería en uso”, “Voltaje batería bajo”, apagado por agotamiento de batería; pantalla apagada; la máquina no enciende; ventilación detenida; teclado o perilla sin respuesta; alarmas sin sonido; fallas de comunicación. | Cable de CA desconectado o batería deteriorada; fusibles quemados; transformador de aislamiento o fuente CA-CC averiados; cables internos sueltos; software o hardware de la tarjeta de potencia o de monitoreo defectuoso; tarjeta de botones o altavoz dañados. |
| **Módulos opcionales** (CO₂, calefactor del circuito) | Línea de muestreo ocluida, sin trampa de agua, error de cero o de calibración; falla del calentador. | Humedad u obstrucción en la línea de muestreo; trampa de agua mal conectada; módulo descalibrado; termistor o resistencia calefactora dañados. |
 
En general, las causas se pueden agrupar en tres categorías: **(1)** errores de montaje o de conexión por parte del usuario (piezas mal asentadas, mangueras sueltas, cable de alimentación desconectado); **(2)** desgaste de consumibles y piezas blandas (sellos, empaques, membranas, sensor de O₂, cal sodada, batería), y **(3)** fallas de componentes electrónicos o neumáticos internos (tarjetas, válvulas, interruptores de presión), que son las menos frecuentes y requieren servicio técnico.
 
### Análisis 2. Subsistemas ordenados según el número de fallas asociadas
 
Para ordenar los subsistemas se contaron las entradas (filas) de las tablas de solución de problemas del capítulo 5 del manual de servicio [9]. Las cifras son aproximadas, porque algunas filas agrupan varias alarmas relacionadas.
 
| Puesto | Subsistema (sección del manual) | N.º aprox. de fallas/alarmas |
| :---: | :--- | :---: |
| 1 | Unidad principal: ventilador, sensores y control (5.2.1) | 40 |
| 2 | Hardware y sistema eléctrico: alimentación, batería, pantalla, teclado, red (5.5) | 30 |
| 3 | Circuito del paciente / sistema respiratorio (5.3.4) | 26 |
| 4 | Módulo de CO₂ (5.2.3)\* | 18 |
| 5 | Sistema de suministro de anestésico: flujómetros, vaporizador, flujo rápido de O₂ (5.3.3) | 13 |
| 6 | Exactitud del volumen corriente: sensores de flujo (5.3.5) | 11 |
| 7 | Suministro de gases y gas impulsor (5.3.2) | 8 |
| 8 | Módulo calefactor (5.2.4)\* | 4 |
| 9 | Módulo de control auxiliar (5.2.2) | 3 |
 
\* Módulos opcionales que no necesariamente están presentes en la configuración básica de la WATO EX-20.
 
**Interpretación:** el subsistema con más fallas registradas es la unidad principal del ventilador, porque concentra la mayoría de los sensores (presión, flujo, O₂), las válvulas y las alarmas de supervisión. Le siguen el sistema eléctrico y el circuito del paciente. Si se suman las fallas del circuito del paciente (26) y las de exactitud del volumen corriente (11), que en la práctica dependen del mismo conjunto de piezas desmontables, el **sistema respiratorio** se convierte en la parte de la máquina con más fallas asociadas. Esto coincide con que es el subsistema que más se desmonta, limpia y esteriliza, y por tanto el más expuesto a errores de montaje y desgaste de sellos. Además, 17 de sus 26 fallas son **fugas**.
 
<h1 align="center"><i><b>𝐏𝐫𝐞𝐠𝐮𝐧𝐭𝐚𝐬 𝐩𝐚𝐫𝐚 𝐥𝐚 𝐝𝐢𝐬𝐜𝐮𝐬𝐢ó𝐧</b></i></h1>
 
### Pregunta 1. ¿Qué tipos de anestésicos son los más usados en cirugía?
 
En la práctica actual la anestesia general es *balanceada*: se combinan varios fármacos, cada uno con un efecto específico (hipnosis, analgesia y relajación muscular), para usar dosis menores de cada uno y reducir sus efectos adversos [13]. Los grupos más usados son:
 
| Grupo | Fármacos más usados | Uso principal |
| :--- | :--- | :--- |
| **Anestésicos inhalatorios** | Sevoflurano (el más usado, también en niños por su olor poco irritante), desflurano, isoflurano y óxido nitroso como coadyuvante. | Mantenimiento de la anestesia general; el sevoflurano también se usa para la inducción inhalatoria. Se administran a través del vaporizador de la máquina. |
| **Anestésicos intravenosos (hipnóticos)** | Propofol (el más usado para la inducción y en la anestesia total intravenosa), ketamina y etomidato. El tiopental está prácticamente en desuso. | Inducción de la anestesia general, sedación y mantenimiento intravenoso. |
| **Opioides** | Fentanilo, remifentanilo y sufentanilo. | Analgesia durante y después de la cirugía. |
| **Relajantes neuromusculares** | Rocuronio, cisatracurio y succinilcolina (para intubación rápida). | Relajación muscular para la intubación y el campo quirúrgico. |
| **Benzodiacepinas** | Midazolam. | Premedicación, ansiolisis y sedación. |
| **Anestésicos locales** | Lidocaína, bupivacaína y ropivacaína. | Anestesia local, bloqueos de nervios periféricos y anestesia espinal y epidural. |
 
### Pregunta 2. ¿Qué diferencias plantea el modelo EX-35 con respecto al EX-20?
 
Ambos modelos son de la misma familia WATO de Mindray y comparten la arquitectura básica: flujómetros mecánicos para O₂, N₂O y aire, hasta dos vaporizadores, sistema respiratorio compacto y un ventilador controlado electrónicamente y accionado neumáticamente [9], [11]. La EX-35 es un modelo de gama superior, con estas diferencias principales:
 
| Característica | WATO EX-20 | WATO EX-35 |
| :--- | :--- | :--- |
| **Pantalla** | TFT a color de 7", manejada con teclas y perilla [11]. | Pantalla táctil de 10,4" (1024 × 768) [10], [12]. |
| **Modos de ventilación** | VCV, modo presión (P), SIMV y manual [11]. | Manual/espontáneo, VCV, PCV, SIMV-VC, SIMV-PC y presión de soporte (PSV) con ventilación de respaldo por apnea [10]. |
| **Volumen corriente mínimo** | 40 mL [11]. | 20 mL en modo volumen y 5 mL en modo presión; apta desde neonatos hasta adultos [10]. |
| **PEEP** | La ficha técnica solo la reporta como parámetro monitorizado [11]. | PEEP electrónica integrada, ajustable de 3 a 30 cmH₂O [10]. |
| **Pausa inspiratoria (TIP:TI)** | Apagada o de 5 % a 60 %, en pasos de 5 % [11]. | Apagada o de 5 % a 60 %, en pasos de 1 % [10]. |
| **Monitoreo de gases** | Presión, volumen y O₂; módulo externo de EtCO₂ solo para la EX-30 [11]. | Módulos *plug-and-play* de CO₂ y de gases anestésicos (CO₂, N₂O, O₂ y agentes, con identificación automática y cálculo de CAM) [10], [12]. |
| **Gas impulsor** | O₂, sin función de cambio automático. | Cambio automático del gas impulsor (de O₂ a aire) si falla el suministro principal, para no interrumpir la ventilación mecánica [12]. |
| **Autonomía de batería** | Hasta 150 min con baterías auxiliares [17]. | Unos 90 min con una batería y 240 min con dos [10]. |
| **AGSS** | No especificado en la ficha consultada [11]. | Pasivo o activo de alto o bajo flujo (opcional) [10]. |
| **Tamaño y peso** | 1375 mm de alto, < 120 kg [11]. | 1410 mm de alto, < 145 kg [10]. |
 
En resumen, la EX-20 es una estación básica orientada a pacientes pediátricos y adultos y a procedimientos de rutina, mientras que la EX-35 amplía los modos de ventilación (incluidos los de soporte para respiración espontánea), permite ventilar neonatos, integra la PEEP electrónica y el monitoreo de gases, y agrega funciones de seguridad como el cambio automático del gas impulsor.
 
# <h2 align="center"> CONCLUSIóN </h2>
 
La práctica permitió reconocer que la máquina de anestesia WATO EX-20 no es un equipo inaccesible, sino un conjunto organizado de subsistemas (suministro de gases, control de flujo, vaporización, sistema respiratorio, ventilador y evacuación de gases) cuyo funcionamiento correcto depende tanto del diseño del equipo como de su uso y mantenimiento. Se identificaron sus partes principales y se comprendió la función de cada una, el funcionamiento de los modos de ventilación VCV y modo presión, y la importancia de las verificaciones preoperatorias.
 
Al revisar las fallas descritas por el fabricante se concluye que **las causas más comunes no son fallas electrónicas complejas, sino problemas de montaje, conexión y mantenimiento**. La mayoría de las fallas registradas en el manual se concentran en el sistema respiratorio, donde predominan las fugas por piezas mal asentadas (recipiente de CO₂, fuelle, tapa de válvulas, sensores) o por sellos y empaques desgastados. Esto se explica porque es el subsistema que más se desmonta para limpieza y esterilización. Otra causa frecuente es la falta de mantenimiento de los consumibles: sensores de O₂ sin calibrar o agotados, sensores de flujo con humedad, cal sodada agotada o desecada y baterías deterioradas. Por último, aparecen los problemas de suministro, como presiones de gas insuficientes o el cable de alimentación desconectado, que activan alarmas como “Fallo suministro O₂” o “batería en uso”.
 
Estas causas comparten un origen humano y, por lo tanto, son en gran medida prevenibles. La prueba de fugas de alta y baja presión, la verificación del sistema respiratorio, la calibración de sensores, el cambio oportuno de la cal sodada y la revisión de la batería antes de cada procedimiento son las herramientas más efectivas para evitarlas. En este proceso, el ingeniero biomédico tiene un papel clave: capacitar al personal en el uso del equipo, ejecutar el mantenimiento preventivo según el manual del fabricante y saber interpretar las alarmas para diagnosticar fallas con rapidez, ya que cualquier error en este equipo afecta directamente la vida del paciente.

<h2 align="center">𝘽𝙞𝙗𝙡𝙞𝙤𝙜𝙧𝙖𝙛𝙞𝙖</h2>
[1] Anaesthesia. (2023, 9 marzo). https://es.patient.info/treatment-medication/anaesthesia

[2] Technology, S., & Technology, S. (2026, 18 noviembre). ¿Cuáles son los diferentes tipos de anestesia? INVAMED. https://invamed.com/es/noticias/cules-son-los-diferentes-tipos-de-anestesia

[3] Pinheiro, P. (2016, 25 enero). Tipos de anestesia: general, local, raquídea y epidural. Mdsaude. Recuperado 18 de noviembre de 2026, de https://www.mdsaude.com/es/cirugia/anestesia/

[4] Máquinas de anestesia: WATO EX-20 - Mindray. (s. f.). Mindray. https://www.mindray.com/mx/products/anesthesia/wato-ex-20 

[5] Kalstein. (s. f.). Kalstein+ | Plataforma Integral de Equipamiento Científico e Industrial. Kalstein. https://kalstein.net/es/maquina-de-anestesia-partes-y-funcion

[6] Yepes, T. (2026, 9 mayo). Máquina de anestesia: componentes, tipos y cómo elegir. GSMED. https://gsmedimaging.com/blogs/noticias-de-tecnologia-medica/maquina-de-anestesia

[7] Tsim, P., & Howatson, A. (2016). Sistemas respiratorios en anestesia (N. Bracho, Trad.). ATOTW, 333. https://resources.wfsahq.org/wp-content/uploads/333_spanish.pdf

[8] Beaulieu, P., Nathan-Denizot, N., & Feiss, P. (s. f.). Aparatos de anestesia. EMC, 39. https://www.sciencedirect.com/science/article/abs/pii/S1280470313658338

[9]

[10]
