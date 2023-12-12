# Descriure les opcions de generació d'informes

Les aplicacions de finances i operacions inclouen informes de SQL Server Reporting Services (SSRS) pregenerats. Es pot imprimir informes 
en diverses ubicacions, com la pantalla, una impressora, un arxiu o un correu electrònic. Es poden utilitzar els informes SSRS per a 
crear vistes parametritzades compatibles amb la navegació d'exploració en profunditat. També es pot incrustar enllaços externs des d'un 
informe a les pàgines d'aplicacions de finances i operacions.

Es pot programar que els informes es generin de forma periòdica mitjançant treballs per lots. Els informes SSRS també permeten crear 
documents de compliment precís per a les obligacions reguladores locals. A més a més dels informes llestos per a utilitzar, es poden 
crear informes personalitzats que s'adaptin a les necessitats de la organització mitjançant l'eina SSRS i el desenvolupament X++.


## Crear informes SSRS
Per a crear un informe, cal utilitzar Microsoft Visual Studio i un desenvolupament d'aplicacions de finances i operacions. Dins del 
Visual Studio, cal crear en primer lloc un nou objecte d'informe i, després, assignar-li un conjunt de dades.

Un conjunt de dades defineix les dades que s'utilitzen a l'informe. Als paràmetres del conjunt de dades, es pot seleccionar un origen 
de dades per al conjunt de dades i el tipus d'origen de dades. El tipus d'origen de dades explica el que fa el sistema per a recuperar 
les dades de l'origen.

Els quatre tipus d'origen de dades són:
- Consulta: utilitza una consulta existent de l'arbre d'objectes d'aplicació (AOT). L'ús d'una consulta existent permet filtrar més
  ràpidament les dades en SQL per a generar informes amb agilitat, i el seu desenvolupament requereix poc codi X++. L'únic codi X++
  que s'utilitza és per als mètodes de visualització a les taules.
- Lògica de negocis: utilitza un origen de dades diferent de les aplicacions de finances i operacions. Només es pot utilitzar el tipus
  d'origen de dades lògica de negocis amb un únic informe, ja que el nom de la classe ha de coincidir amb el nom de l'informe.
- Proveïdor de dades d'informes (RDP): s'utilitza quan és necessari afegir lògica per executar l'informe. Es sol utilitzar si es
  necessiten filtres dinàmics. Una classe RDP és una classe X++. Pot aplicar criteris de filtre avançats per accedir a dades i
  processar-les per l'informe SSRS. Els paràmetres de l'informe, que s'apliquen a la interfície d'usuari, també es poden processar a
  través de la classe RDP.
- Proveïdor d'enumeració d'AX: s'utilitza per a filtrar la vista de l'informe quan el paràmetre de l'informe és un tipus d'enumeració.
  Aquests informes poden fer referència a la recopilació de valors d'enumeració. El proveïdor d'enumeració d'AX permet afegir un conjunt
  de dades vinculat a una enumeració específica i fa que l'informe mostri un valor d'enumeració específic.

Després de crear el conjunt de dades, es pot configurar el disseny de l'informe seleccionant un disseny automàtic (per a informes simples) 
o un disseny de precisió (per a informes més personalitzats). Un cop acabat l'informe, cal implementar-lo. Quan s'ha implementat, 
l'informe estarà llest per executar-se a les aplicacions de finances i operacions.


## Crear i modificar informes amb Power BI
Power BI utilitza una sèrie de serveis de software, aplicacions i altre connectors que funcionen conjuntament per integrar de forma 
cohesiva orígens de dades no relacionats i garantir que siguin aplicables i interactius. Power BI consta de diversos elements que 
funcionen de forma conjunta, el que inclou una aplicació d'escriptori de Windows, un software com a servei (SaaS) en línia i aplicacions 
mòbils. Aquests elements permeten connectar fàcilment als orígens de dades, visualitzar-los, descobrir els elements més importants i 
compartir la informació amb qui es vulgui.

Es pot utilitzar les eines de Power BI per explorar de forma interactiva les dades mitjançant la rotació de columnes, el canvi de forma 
dels gràfics, el filtratge de dades i l'ús compartit d'informes. Es pot incorporar aquests informes a un espai de treball a les aplicacions 
de finances i operacions. Power BI és especialment útil per a crear penells d'informació, informes no documentals o qualsevol informe que 
no s'hagi d'imprimir.

Els informes llestos per utilitzar de Power BI estan disponibles a la biblioteca d'actius compartits de Microsoft Dynamics Lifecycle 
Services, i es poden descarregar i implementar en un entorn.


## Crear i modificar informes amb Microsoft Excel
Excel es pot utilitzar per la planificació pressupostària, els informes financers i la visualització i anàlisis de dades transaccionals i 
d'altres tipus, com dades de clients i proveïdors. Les aplicacions de finances i operacions poden integrar-se amb un llibre Excel, que pot 
actualitzar, eliminar i afegir dades dins de les aplicacions de finances i operacions mitjançant el complement de connector de dades 
d'Excel. Aquest complement segueix el protocol d'integració basat en REST que connecta les entitats de dades de les aplicacions de finances 
i operacions a través dels punts finals de Open Data Protocol (OData).

El connector de dades d'Excel utilitza dades transaccionals configurades en temps real, on les dades es carreguen i es validen. Els 
registres corresponents apareixeran a Dynamics 365 per al seu ús immediat. És necessari descarregar el complement Microsoft Dynamics 
Office per utilitzar aquesta característica.


## Informes financers
Els professionals de les finances i els negocis utilitzen informes financers en totes les facetes de la seva activitat. Amb els informes 
de finances i operacions, aquests professionals poden crear, mantenir, implementar i veure informes financers. Aquests informes ajuden a 
dissenyar d'una manera eficaç molts altres tipus d'informes.

Els informes financers inclouen el suport de dimensions. Els segments o les dimensions del compte estan disponibles immediatament sense 
necessitat d'eines ni passos de configuració extra.

Moltes empreses executen un conjunt bàsic d'informes financers a intervals programats amb la finalitat d'adaptar-se als seus processos 
comercials. Es possible programar informes financers de manera regular; per exemple, cada dia, setmana, mes o any.
