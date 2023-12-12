# Descriure opcions per la integració d'aplicacions de finances i operacions amb Microsoft Power Platform
Les versions actuals de les aplicacions de finances i operacions estan allotjades a Azure, cosa que ajuda a augmentar l'àmbit d'integració
d'aquests productes. Aquestes aplicacions es poden connectar a altres productes allotjats a Azure. També es poden connectar a les 
aplicacions locals mitjaçant una porta d'enllaç. A continuació explorarem les capacitats d'integració d'aplicacions de finances i operacions 
amb Microsoft Power Platform.

## Microsoft Power Platform
Proporciona un conjunt d'aplicacions amb capacitats per a aplicacions de finances i operacions. Les característiques com la doble
escriptura i l'entitat virtual poden establir una integració directa entre Microsoft Dataverse i les entitats de dades de les aplicacions
de finances i operacions.

Es composa d'eines com aplicacions de llenç, Power Automate i Power BI. Totes aquestes eines es poden integrar individualment amb
aplicacions de finances i operacions.

## Integració amb Dataverse
Dataverse és l'opció d'emmagatzematge de dades predeterminada per a Microsoft Power Platform, on es poden emmagatzemar de forma segura
totes les dades de l'empresa en format tabular, mantenint les relacions entre claus i taules. Les aplicacions de finances i operacions
emmagatzemen dades a AzureSQL. Tot i aixó, podem integrar aplicacions de finances i operacions amb Dataverse mitjançant el marc d'entitats 
de dades. Hi ha diverses tecnologies involucrades per aconseguir aquesta integració.

### Doble escriptura
Plataforma d'integració estàndard que proporciona una interacció pràcticament a temps real entre Dataverse i les aplicacions de finances
i operacions. Proporciona una capacitat d'integració bidireccional acoplada de forma estreta, resultant una experiència fàcil d'utilitzar
a totes les aplicacions.

La infraestructura de doble escriptura segueix un principi de sense codi/poc codi, fet que minimitza l'esforç de l'enginyeria per assignar 
taules estàndards o personalitzades entre aplicacions. La doble escriptura és compatible amb el mode en línia i el mode sense connexió.

### Entitat virtual
Les entitats virtuals permeten la integració de dades que es troben en sistemes externs al representar sense probles aquestes dades com a
taules de Dataverse, sense replicar dades i, sovint, sense codificació personalitzada. Els origens de dades de les aplicacions de finances
i operacions també es poden utilitzar com a origen de dades virtual al Dataverse. Es pot habilitar les operacions completes de creació,
lectura, actualització i eliminació (CRUD) des de Dataverse a les entitats virtuals de les aplicacions de finances i operacions.

Totes les entitats de OData de les aplicacions de finances i operacions estan disponibles com a entitats virtuals al Dataverse, i per tant,
també a Microsoft Power Platform. Es pot crear una aplicació basada en models utilitzant les entitats virtuals i realitzar les operacions
CRUD directament a l'origen de dades de finances i operacions des d'una aplicació basada en models.

## Integració amb aplicacions de llenç de Power Apps
Una aplicació de llenç de Power Apps és una plataforma de desenvolupament d'aplicacions sense codi de Microsoft Power Platform. Té la
capacitat de connectar-se a diversos origens de dades utilitzant els connectors integrats o personalitzats.

## Integració amb Power Automate
Servei de flux de treball en línia que automatitza les accions més habituals de les aplicacions i serveis. Power Automate té un connector
per aplicacions de finances i operacions, que ajuda a connectar totes les entitats de OData d'aplicacions de finances i operacions, i
realitza operacions de CRUD en aquestes entitats.
