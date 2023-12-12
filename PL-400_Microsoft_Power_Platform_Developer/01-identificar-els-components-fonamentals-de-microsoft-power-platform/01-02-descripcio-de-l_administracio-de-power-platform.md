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
