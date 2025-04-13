# PROTOCOLO 1: Secuenciamiento MinION

# A. Pre-tratamiento de muestras biológicas para la extracción de ácidos nucleicos: Muestras sólidas

1. Pesar entre 100 a 125 mg de la muestra. Colocar en un microtubo de 1.5 mL. Añadir 300 uL del Recovery Buffer y homogeneizar por vortex.
2. Incubar a temperatura ambiente por 15 minutos.
3. Centrifugar a 2000 RPM por 1 minuto. Colectar únicamente el sobrenadante en un microtubo de 1.5mL.
4. Evitar recolectar sólidos no disueltos y/o restos vegetales.

NOTA: Consiste en extraer y estabilizar el ADN de la muestra mediante un buffer llamado Recovery Buffer. Sin embargo, este proceso de pre-tratamiento va a depender de las diferentes muestras.

# B. Extracción de ADN

1. Añadir 500 ul del StartUp Buffer a la solución pre-tratada, y homogeneizar por vortex.
2. Incubar durante 1 hora a 68°C.
3. Cargar en un spin column. Volumen máximo de carga 700 uL.
4. Centrifugar a 13.000 RPM por 1 minuto, descartar el sobrenadante.
5. Añadir 700 ul de OH Buffer, reposar la columna por 3 minutos.
6. Centrifugar a 13.000 RPM por 1 minuto. Descartar el sobrenadante
7. Centrifugar a 13.000 RPM por 1 minuto.
8. Descartar el tubo colector y colocar la columna un microtubo de 1.5 mL.
9. Añadir 50 ul de Recovery Buffer. Reposar la columna por 3 minutos.
10. Centrifugar a 13.000 RPM por 1 minuto. Descartar el spin column.
11. Cuantificar la concentración y pureza.
12. Almacenar las muestras extraídas a -20°C.

# C. Control de calidad: Nanodrop

1. Encender el equipo de la parte posterior.
2. En la barra del menú, se encuentran todos los tipos de experimentos disponibles de acuerdo al tipo de muestra a usar.
3. En este experimento, seleccionar dsDNA o RNA, según sea el caso.
4. Dependiendo del volumen y tipo de muestra configurar en modo celda o alicuota. En este experimento utilizaremos la función por default para cuantificación en micro volumen.
5. Minuciosamente limpiar los dos pedestales con la tela anti pelusas proporcionada específicamente para el equipo.
6. Para calibrar el equipo, se emplea el reactivo Recovery Buffer respectivamente de cada método como Blanco.
7. Colocar 2 uL del Recovery Buffer sobre la superficie del lector, evitando tener contacto directo entre la superficie y la punta de la micropipeta. Bajar el pedestal y se será calibrado automáticamente el equipo
8. Limpiar ambos pedestales y colocar 2 ul de cada muestra. Bajar el pedestal y la cuantificación será realizada automáticamente

# D. Preparación de componentes para la secuenciación

1. Tome una placa de 96 pocillos que contenga códigos de barras 165. Separe un conjunto de códigos de barras (1 a 24, o según lo desee) de la placa y devuelva el resto al almacenamiento.

NOTA: Las placas de 96 pocillos están diseñadas para romperse en una sola dirección. Se pueden retirar de la placa tiras o múltiples tiras de ocho pocillos/códigos de barras a la vez.

2. Descongele los códigos de barras deseados a temperatura ambiente.

3. Centrifugue brevemente los códigos de barras en una microcentrifuga o homogenize por micropipeta para asegurarse de que el líquido esté en el fondo de los tubos y coloquelos en hielo

4. Descongelar el LongAmp Hot Start Taq 2X Master Mix, centrifugue brevemente, mezcle bien pipeteando y colóquelo en hielo.

| Reactivo | uL | Rx |
| --- | --- | --- |
| Agua | 25 | ... uL|
| Buffer 10X| 2,5 | ... uL|

5. Preparar el ADN libre de nucleadas
 a. Transfiera 10 ng de cada muestra de ADN genómico a un tubo de PCR de pared delgada de 0,2 ml.
 b. Ajustar el volumen a 15 ul con agua libre de nucleasas.
 c. Homogenize bien la mezcla para evitar cortes no deseados.

6. En cada tubo de PCR de pared fina de 0,2 ml que contenga la muestra a analizar, prepare la siguiente mezcla:

7. Asegúrese de que los componentes estén bien mezclados pipeteando y centrifugando brevemente.

8. Con puntas de pipeta limpias, perfore con cuidado la superficie de aluminio de los códigos de barras necesarios. Utilice una punta nueva para cada código de barras para evitar la contaminación cruzada. 

NOTA: Anote qué números de código de barras se analizarán para cada muestra.


9. Con una pipeta, mezcle los códigos de barras 165 pipeteando hacia arriba y hacia abajo 10 veces. Transfiera 10 µl de cada código de barras 165 a los tubos que contienen la muestra correspondiente.

10. Asegúrese de que los componentes estén bien mezclados pipeteando el contenido de los tubos 10 veces y centrifugando.

NOTA: Mezcle suavemente para minimizar la introducción de burbujas de aire en las reacciones.

11. Amplificar,programando al termociclador en las siguiente como condiciones:

12. Descongele los reactivos a temperatura ambiente, centrifugue brevemente con una microcentrífuga y mezcle con pipeta

13. Añadir 4 µl de EDTA a cada muestra con código de barras, mezclar bien con una pipeta y centrifugar brevemente.

CONSEJO: En este paso se añade EDTA para detener la reacción.

14. Incubar durante 5 minutos a temperatura ambiente.

15. Cuantifique 1 µl de cada muestra con código de barras utilizando un fluorómetro Qubit (o equivalente) para comprobar el control de calidad.

16. Agrupe todas las muestras con código de barras en proporciones equimolares en un tubo Eppendorf DNA LoBind de 1,5 ml.

17. Resuspenda las perlas AMPure XP (AXP) mediante agitación en vortex.

18. Al conjunto de muestras con código de barras, agregue una proporción de volumen de 0.6X de perlas AMPure XP (AXP) resuspendidas y mezcle mediante pipeteo:

Nota: La tabla contiene volúmenes de ejemplo para referencia. Ajuste el volumen de las perlas AMPure XP (AXP) agregadas al volumen de su grupo de muestras con código de barras para garantizar una relación de volumen de 0,6X.

19. Incubar durante 5 minutos a temperatura ambiente.

20. Prepare 2 ml de etanol fresco al 80% en agua libre de nucleasas.

21. Centrifugue brevemente la muestra (13000 rpm por 1 minuto) y el sedimento en una rejilla magnética hasta que el sobrenadante esté transparente e incoloro. Mantenga el tubo en la rejilla magnética y pipetee el sobrenadante.

22. Mantenga el tubo sobre el imán y lave las perlas con 1 ml de etanol al 80% recién preparado sin alterar el sedimento. Retire el etanol con una pipeta y deséchelo.

23. Repetir el paso anterior.

24. Centrifugar y colocar el tubo de nuevo en el imán. Retirar con una pipeta cualquier residuo de etanol. Dejar secar el agregado durante 30 s aproximadamente, sin dejar que se agriete.

25. Retire el tubo del soporte magnético y vuelva a suspender el pellet pipeteándolo en 15 µl de tampón de elución (EB). Centrifugue e incube durante 5 minutos a temperatura ambiente.

26. Precipitar las microesferas en un imán, durante al menos 1 minuto, hasta que el eluido se vuelva claro e incoloro.

27. Retire y conserve 15 µl de eluido en un tubo Eppendorf DNA LoBind limpio de 1,5 ml.
 a. Retire y conserve el eluido que contiene la biblioteca de ADN en un tubo Eppendorf DNA LoBind limpio de 1,5 ml.
 b. Desechar las perlas granuladas

28. Transfiera 5 µl de la muestra eluida a un tubo Eppendorf DNA LoBind limpio de 1,5 ml. Complete el volumen a 11 µl con tampón de elución (EB).

29. En un tubo Eppendorf DNA LoBind nuevo de 1,5 ml, diluya el adaptador rápido (RA) de la siguiente manera y pipetee la mezcla:

| Reactivo | Volumen |
| --- | --- |
| Adaptador rápido | 1,5 µl |
| Buffer adaptador | 3,5 µl |
| Total | 5 µl |


30. Agregue 1 µl del adaptador rápido (RA) diluido al ADN con código de barras.

31. Mezcle suavemente moviendo el tubo.

32. Incubar la reacción durante 5 minutos a temperatura ambiente.

FIN DEL PROCESO: La biblioteca preparada se utiliza para cargarla en la celda de flujo.

NOTA: Consérvela en hielo hasta que esté lista para cargarla.

# E. Cebado y carga de la celda de flujo MinION

1. Descongelar los viales Sequencing Buffer (SB), Library Beads (LIB) o Library Solution (LIS), -si se requiere-, y un tubo de Flow Cell Flush (FCF) a temperatura ambiente. Agitar en vortex, centrifugar y colocar en hielo.

2. Para preparar la mezcla de cebado de la celda de flujo con BSA, combine los siguientes reactivos en un tubo Eppendorf DNA LoBind nuevo de 1,5 ml. Mezcle invirtiendo el tubo y mezcle con la pipeta a temperatura ambiente:

| Reactivo | Volumen por celda |
| --- | --- |
| Flow Cell Flush (FCF) | 1170 µl |
| Bovine Serum Albumin | 5 µl |
| Flow Cell Tether | 30 µl |
| Volumen final| 1205 µl |

3. Abrir la tapa del dispositivo MinION y deslizar la celda de flujo debajo del clip. Presionar la celda de flujo con firmeza para asegurar un contacto eléctrico y térmico adecuados.

4. Para abrir el puerto de cebado de la celda de flujo, deslizar la tapa en el sentido de las agujas del reloj.

IMPORTANTE: Tenga cuidado a la hora de extraer el tampón. No retire más de 20-30 μl y asegúrese de que el tampón cubra la matriz de poros en todo momento. La introducción de burbujas de aire en la matriz puede dañar los poros de manera irreversible.

5. Tras abrir el puerto de cebado, verificar si hay una burbuja de aire bajo la tapa. Retirar una pequeña cantidad de tampón para quitar las burbujas:
 a. Ajustar una pipeta P1000 a 200 μl. 
 b. Introducir la punta de la pipeta en el puerto de cebado.
 c. Girar la rueda hasta que el indicador de volumen marque 220-230 µl o hasta que se pueda ver una pequeña cantidad de tampón entrar en la punta de la pipeta.

6. Cargar 800 µl de mezcla de cebado en el puerto de cebado, evitando introducir burbujas de aire. Esperar 5 minutos. Durante este tiempo, preparar la biblioteca para cargar siguiendo los pasos a continuación.

7. Mezclar con la pipeta, minuciosamente, el contenido del vial Library Beads (LIB).

8. En un tubo nuevo de 1,5 ml Eppendorf DNA LoBind, preparar la biblioteca de la siguiente manera:

| Reactivo | Volumen por celda |
| --- | --- |
| Buffer de secuenciación (SB) | 37,5 µl |
| Biblioteca de ADN | 12 µl |
| Library Beads (LIB) mezoladas (usto antes de usar, o Library Solution (LIS), si se requiere| 25,5 µl |
| Volume final| 75 µl |

9. Completar el cebado de la celda de flujo:
 a. Levantar suavemente la tapa del puerto de muestra SpotON.
 b. Cargar 200 µl de mezcla de cebado en el puerto de cebado (no en el puerto de

muestra SpotON), evitando introducir burbujas de aire.

10. Mezclar la biblioteca pipeteando suavemente, justo antes de cargar.

11. Añadir, gota a gota, 75 µl de la biblioteca preparada en el puerto de muestra SpotON. Procurar que cada gota fluya hacia adentro del puerto antes de añadir la siguiente.


12. Volver a colocar con cuidado, la tapa del puerto de muestra SpotON, procurando que el tapón encaje en el agujero y cerrar el puerto de cebado 





