# Descripció de l'administració de Power Platform

#### Entorns de Power Platform
Amb Power Platform, els entorns s'utilitzen per emmagatzemar, administrar i compartir les dades, les aplicacions i els fluxes empresarials
d'una organització. Cada entorn permet disposar d'una base de dades de Microsoft Dataverse per utilitzar. Els entorns de Microsoft
Dataverse permeten administrar l'accés d'usuaris, la configuració de seguretat i l'emmagatzematge associat a aquesta base de dades.

Cada entorn es crea en un inquilí de Microsoft Entra ID. Només els usuaris d'aquest inquilí poden tenir accés als recursos de l'entorn. Un
entorn també està enllaçat a una ubicació geogràfica com, per exemple, Estats Units. Quan es crea una base de dades de Microsoft Dataverse
en un entorn, es crea dins dels centres de dades d'aquesta ubicació geogràfica. Qualsevol element que es crea en aquest entorn també està
enllaçat amb la ubicació del seu entorn.

Es pot crear més d'un entorn per administrar el desenvolupament de la solució i l'emmagatzematge de dades mitjançant la configuració d'un
entron per al desenvolupament, un altre per les proves i un altre pel seu ús en producció. L'entorn de desenvolupament es per a que els
desenvolupadors crein solucions. Un cop que les solucions estan llestes per a ser provades, es mouen a un entorn de proves. Un entorn a
part garanteix que tot es pugui provar sense que afecti als usuaris. Un cop que la solució està llesta, es pot moure a producció. A més a
més, es pot configurar un entorn per Europa i un altre per Àsia. Cada entorn tindrà només una o cap instància de Microsoft Dataverse.

#### Experiències administratives
Microsoft Power Platfom té un àmpli conjunt d'experiències administratives que es poden utilitzar per administrar els diferents aspectes 
d'una solució. Des del Centre d'Administració de Power Platform, es pot crear nous entorns o administrar la seguretat. Des dels portals
de creació es pot administrar Microsoft Dataverse. En funció del que es vulgui fer, hi ha una experiència administrativa específica per
fer-ho.

## Centre d'aministració de Microsoft Power Platform
El centre d'administració de Power Platform és l'experiència administrativa principal de Microsoft Power Platform. El portal permet als administradors gestionar els seus entorns i configurar moltes de les opcions principals de Power Apps, Power Automate i aplicacions d'interacció amb clients per a Dynamics 365.

En el Centre d'administració de Power Platform, la configuració s'agrupa en categories i s'hi accedeix seleccionant el vincle que apareix al costat esquerra del portal. Les categories són:

- **Inici**: proporciona informació general, com si hi ha interrupcions en els serveis, etc. Es poden afegir diferents targetes per a personalitzar millor aquesta pantalla en funció de les necessitats.
- **Entorns**: en aquesta secció s'enumeren tots els entorns de l'inquilí. S'inclouen els entorns de Microsoft Dataverse i altres entorns, com els de Dataverse for Teams.
- **Anàlisi**: en aquesta secció es proporcionen detalls analítics sobre Microsoft Power Platform, com anàlisi de Dataverse, estadístiques de flux de Power Automate i detalls de Power Apps.
- **Facturació**: el centre de facturació conté detalls relacionats amb les llicències d'usuari.
- **Configuració**: aquesta secció permet revisar i administrar la configuració en un nivell bàsic, com control·lar qui pot crear i administrar els diferents tipus d'entorns disponibles.
- **Recursos**: en aquesta secció es pot veure les estadístiques de capacitat de l'inquilí i administrar i instal·lar característiques relacionades amb aplicacions de Dynamics 365.
- **Ajuda i suport tèncic**: aquesta secció és on es pot crear noves sol·licituts de suport tècnic i administrar les que ja s'han enviat.
- **Integració de dades**: aquesta secció permet crear o afegir connexions predefinides i supervisar les connexions entre Microsoft Dataverse i altres magatzems de dades, com Salesforce o SQL Server.
- **Dades**: en aquesta secció es poden administrar els diferents orígens de dades, portes d'enllaç de dades locals i portes d'enllaç de dades de xarxa virtual associades a aquest inquilí.
- **Polítiques**: aquesta secció és on es pot administrar algunes de les directives de seguretat de dades i altres característiques de seguretat, com la Caixa de seguretat del client i l'aïllament d'inquilins.
- **Centres d'aministració**: proporciona accés directe als centres d'administració que poden afectar a les solucions de Microsoft Power Platform, com el Centre d'administració de Microsoft 365, Azure Active Directory, etc.

## Portals d'administració i creació adicionals
A més del Centre d'administració de Power Platform, hi ha diverses experiències administratives que es poden utilitzar com a part de Power Platform. Cada experiència està dissenyada per al producte amb el que es treballa. Per exemple, l'experiència principal que s'utilitza per a crear aplicacions i administrar la instància de Dataverse associada a un entorn és el portal de creació de Power Apps.

El portal de creació de Power Apps també proporciona els següents elements:
- **Taules**: permeten administrar les taules de Microsoft Dataverse implementades en l'entorn. Es pot crear taules noves i realitzar tasques com modificar els diferents formularis, vistes i relacions amb la instància de Dataverse.
- **Connexions**: permet administrar les connexions que utilitzen les aplicacions.
- **Fluxes**: proporciona accés als fluxes que s'han creat.
- **Bots de xat** proporciona accés als bots de xat que s'han creat.
- **Models de IA**: proporciona accés als models de AI Builder.
- **Solucions**: proporciona accés a les solucions que s'han implementat.
- **Targetes**: proporciona accés a les targetes creades.
- **Opcions**: permet administrar les columnes de selecció.
- **Connexions**: permet administrar els connectors.
- **Fluxes de dades**: proporciona accés als fluxes de dades-
- **Power Platform**: proporciona accés a altres portals de creació de Power Platform.

Els elements de la secció central es poden ancorar i mostrar segons sigui necessàri. Per exemple, si la organització no fa res amb Targetes, es pot ocultar aquesta secció.

























