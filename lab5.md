# THEVENIN
<div align="center">
  
  ![logo](https://user-images.githubusercontent.com/75336529/126577163-fd8dfa53-fb95-419c-b895-a78f7554faa5.png)
  
  **UNIVERSIDAD DE LAS FUERZAR ARMADAS "ESPE"**
  
  **DEPARTAMENTO DE ELECTRICA Y ELECTRONICA**
  
  **FUNDAMENTOS DE CIRCUITOS ELECTRICOS**
  
</div>

**INTEGRANTES:** 
 Chalan Dilan, Izurieta Erick, Jiménez Iván.

**CARRERA:**
 Electrónica y automatización

**NRC:**
 5406

**DOCENTE:**
Ing. Darwin Alulema

**1.-OBJETIVOS**

General

Examinar el circuito mediante Thévenin y calcular lo requerido en la carga aplicada del circuito.

Específicos

Calcular la resistencia de Thévenin para el circuito propuesto.

Demostrar el porcentaje de error presentado en el circuito equivalente de Thévenin

**2.-MARCO TEÓRICO**

![diagrama](https://user-images.githubusercontent.com/75336529/126717409-e37c83ff-4cb7-4437-8d1b-13ea427fba8c.jpeg)

**3.-EXPLICACIÓN DEL PROCEDIMIENTO**

**3.1.-Materiales y equipo**

|Cantidad| Material o equipo|
|---|---|
|2|Una fuente de voltaje DC|
|2|Multímetro digital|
|1|Resistor de 560Ω|
|1|Resistor de 4.7kΩ|
|1|Resistor de 330Ω|
|1|Resistor de 100Ω|
|1|Potenciometro de precisión 1kΩ|
|1|Protoboard|

**3.2.- Procedimiento**

3.2.1- Arme el circuito que se muestra en la figura.

![1](https://user-images.githubusercontent.com/75336529/126577072-9e3a64a9-ba82-4528-bc9b-b1ec4f96f893.png)

![p1](https://user-images.githubusercontent.com/75336529/126585793-5acd532b-255d-4a9a-9f63-7c9223a1bbed.png)

3.2.2.- Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 3.2.

![p2](https://user-images.githubusercontent.com/75336529/126585815-fe4cecdb-dcdc-47af-a45a-005b0bfe94bc.png)

![p3](https://user-images.githubusercontent.com/75336529/126585826-03c38362-3a73-4dd7-be56-2a2d6aa0b9ff.png)

3.2.3.- Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 3.1.

![p5](https://user-images.githubusercontent.com/75336529/126585851-2fee6569-c82a-4cd8-bf31-e2127fd2dd87.png)

3.2.4.- Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 3.1.

![p4](https://user-images.githubusercontent.com/75336529/126585840-bd9235d3-52af-418a-baf6-1f1840361321.png)

3.2.5.-Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 3.2.

![p6](https://user-images.githubusercontent.com/75336529/126585854-f385eeb7-2824-4267-8bc1-5d6093c2d630.png)

![p7](https://user-images.githubusercontent.com/75336529/126585858-60ee16af-2697-4337-addb-cf01c9bc86d1.png)

tabla 3.1: Valores del circuito equivalente de thevenin
|Vth|v|Rth|Ω|
|---|---|---|---|
|Calculado|5.056 |Calculado|298.855 |
|Medido|5.06 |Medido| 299|

Tabla 3.2: Comprobación del Teorema de Thévenin.
|Paranetro|Circuito|original |circuito equivalente |thevenin |
|---|---|---|---|---|
|Électrico|calculado|medido|calculado|medido|
|Voltaje(v)|3.89|3.89|3.892|3.89|
|Corriente(mA)|3.89|3.89|3.892|3.89|

**4.-RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

**4.1.-Cálculos realizados**

Calculo circuito original

![2](https://user-images.githubusercontent.com/75336529/126587079-5ddbe1d3-d8d2-46ac-87fc-824de51c36c3.png)

![c1](https://user-images.githubusercontent.com/75336529/126587129-fb5f07ce-aecc-4686-9e2a-89ad6c725a69.png)

Calculo de la resistencia de thevenin

![3](https://user-images.githubusercontent.com/75336529/126577079-fe0e8dd2-e1d9-40bc-95f3-ec871a871833.png)

![c2](https://user-images.githubusercontent.com/75336529/126578117-1a7a1d2b-129e-44e4-9eb1-866ecc01ab16.png)

![4](https://user-images.githubusercontent.com/75336529/126577063-1ed17f3b-718b-45b8-ab70-4cf11cb5ab9c.png)

![c3](https://user-images.githubusercontent.com/75336529/126578118-60587f28-23ca-45ae-ba89-77e967b7755b.png)

Calculo del voltaje de thevenin

![5](https://user-images.githubusercontent.com/75336529/126577064-9eaa95c0-d46c-47f7-a268-14104782c7c9.png)

![c4](https://user-images.githubusercontent.com/75336529/126578121-74a4d7ef-4765-4a2b-bec2-760ccd7e3315.png)

Calculo de voltaje y corriente en la resistencia 5 mediante thevenin

![6](https://user-images.githubusercontent.com/75336529/126579155-c692c08d-d2dd-4c87-a0d7-45445002a0d8.png)

![c5](https://user-images.githubusercontent.com/75336529/126578126-07192063-0084-492a-a30d-b92627d3efb1.png)

**4.2 Calculo del error**

Error en el voltaje de thevenin

![c6](https://user-images.githubusercontent.com/75336529/126578127-d3a24978-4f5c-4cc4-b299-97d21cdceaa6.png)

Error en la resistencia de thevenin

![c7](https://user-images.githubusercontent.com/75336529/126578128-d9ea241c-fc19-4290-a969-d83cd9cd2075.png)

Error en el voltaje de la resistencia 5

![c8](https://user-images.githubusercontent.com/75336529/126578109-19f01a93-45ae-4016-8e2d-450e3298c91e.png)

Error en la corriente de la resistencia 5

![c9](https://user-images.githubusercontent.com/75336529/126578110-274f891f-c40c-4d46-8d64-45cf5f99be8a.png)

**5.-VIDEO**

https://www.youtube.com/watch?v=Y9DpmE_t1yg

**6.-CONCLUSIONES**

•	Aprendimos que el teorema de THEVENIN se concluye con la ley de Ohm para calcular la corriente circulante en una de las ramas.

•	Es claro que este teorema es muy útil porque nos permite reducir una red de configuración compleja, en una de configuración sencilla.

•	Ciertamente este teorema de Thévenin establece que, si una parte de un circuito eléctrico lineal está comprendida entre dos terminales A y B, esta parte en cuestión puede sustituirse por un circuito equivalente que esté constituido únicamente por un generador de tensión en serie con una resistencia.

•	Concluimos manifestando que, para calcular la resistencia de Thévenin, se desconecta la resistencia de carga, se cortocircuitan las fuentes de tensión y se abren las fuentes de corriente.

**7.-BIBLIOGRAFIA**

Thevenin’s Theorem. (2010). Thevenin. http://hyperphysics.phy-astr.gsu.edu/hbasees/electric/thevenin.html

Becerril, J. V., & Martínez, D. E. (2004). ECUACIONES DIFERENCIALES TÉCNICAS DE SOLUCIÓN Y APLICACIONES (Primera edición). D.R.© 2004 Universidad Autónoma Metropolitana.

Teorema de ThÃ©venin. (2018). thevenin. http://www.sc.ehu.es/sbweb/electronica/elec_basica/tema1/Paginas/Pagina4.htm
