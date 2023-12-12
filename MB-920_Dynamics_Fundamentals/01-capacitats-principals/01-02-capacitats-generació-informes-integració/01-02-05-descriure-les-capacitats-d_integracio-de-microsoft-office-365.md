# Descriure les capacitats d'integració de Microsoft Office 365

Les capacitats d'integració de Microsoft Office ofereixen un entorn productiu que ajuda a realitzar la feina utilitzant productes d'Office, 
com Excel i Word. La clau d'aquesta integració és el complement de Office Microsoft Dynamics per a Excel i Word.

El complement d'Office Microsoft Dynamics utilitza el protocol de seguretat Dynamics 365 OAuth existent. Recupera els rols de seguretat de 
l'aplicació per a l'usuari actual, per a proporcionar els permisos coherents. Els usuaris que no tenen els permisos adients no podran 
descarregar dades confidencials. L'aplicació de complement permet operacions de creació, lectura, actualització i eliminació en entitats 
exposades com a públiques.

Word i Excel són les aplicacions d'anàlisi empresarial més utilitzades. Totes les aplicacions de Dynamics 365 tenen capacitats 
d'integració de Microsoft Office. Aquestes plantilles estan disponibles per a totes les entitats del sistema, com projectes, productes, 
clients, etc. També es possible afegir altres plantilles o editar les plantilles existents. 

Les plantilles de documents es troben navegant a:

> Common > Common > Office integration > Document templates.
	
	
## Microsoft Excel

Les aplicacions de finances i operacions utilitzen una aplicació denominada Complement de connector de dades d'Excel per a veure, 
actualitzar i editar dades en un llibre d'Excel. Per a poder-ho fer cal descarregar el complement d'Office de Microsoft Dynamics.

Aquesta característica està disponible a la cantonada superior dreta d'una pàgina. Obrir a Excel permet utilitzar l'entitat de dades 
que està relacionada amb l'origen principal de la pàgina. Les columnes que apareixen al llibre d'Excel es defineixen al grup de camps
AutoReport de l'entitat. També es pot afegir o eliminar camps de l'Excel utilitzant el botó disseny de l'aplicació. A més a més, es pot
filtrar les dades utilitzant el botó filtrar. L'aplicació també ofereix la possibilitat de cambiar les dades a l'Excel i publicar els
canvis de nou a les aplicacions de finances i operacions.

### Publicar dades mitjançant el complement d'Excel
Per garantir la publicació de dades valides mitjançant el complement d'Office de Microsoft Dynamics, qualsevol actualitació passa per la
validació lògica de l'entitat de dades existent. Aquesta validació garanteix la integritat de les dades i proporciona comentaris
immediats de missatges d'error rellevants si una publicació de dades no ha tingut èxit.

#### Què és una entitat de dades?
Una entitat de dades és un objecte en un model de dades. Es pot dissenyar dades dividint les coses en parts més petites que són útils per
representar les relacions de dades. Per exemple, l'entitat proveïdor té un abast i combina més de 17 taules i orígens de dades diferents 
en una sola entitat proveïdor. Durant els esdeveniments d'importació o exportació, les entitats utilitzen la lògica empresarial per a
validar i transformar les dades que es reben o s'envien. Les aplicacions de finances i operacions també permeten la creació d'entitats de 
dades personalitzades. Cada entitat de dades té una propietat denominada Habilitar API pública. Si el valor d'aquesta propietat s'estableix
en **Sí**, l'entitat de dades s'exposarà automàticament com un punt de connexió de OData. El complement de connector de dades d'Excel pot
consumir aquest punt de connexió de OData i estableix una integració sincrònica amb les aplicacions de finances i operacions.

### Obrir dades d'entitats amb Excel
Per obrir les dades de l'entitat, es pot començar des de l'Escel o des de les aplicacions de finances i operacions.

En obrir les dades de l'entitat amb Excel, es pot veure i editar les dades de forma ràpida i senzilla mitjançant el complement d'Office de
Microsoft Dynamics.

Amb el complement d'Office de Microsoft Dynamics es pot:
- Obrir les dades de l'entitat amb Excel quan es comença des de les aplicacions de finances i operacions.
- Obrir les dades de l'entitat amb Excel quan es comença des de l'Excel.
- Veure, editar i actualitzazr les dades de l'entitat amb l'Excel.
- Afegir o eliminar columnes. Es pot utilitzar el dissenyador per ajustar les columnes que el sistema afegeix automàticament al
  full de càlcul.
- Copiar dades de configuració d'un entorn a un altre utilitzant un llibre. No obstant, no n'hi ha prou amb cambiar la URL de connexió,
  ja que la memòria caché de dades del llibre continuarà tractant les dades com a dades existents. Per tant, cal utilitzar la funció Copiar
  dades de l'entorn per a publicar les dades en un nou entorn com a dades noves.

Les característiques anteriors permeten que Excel interactui amb les aplicacions de finances i operacions sense problemes a través del punt
de connexió de OData.

### Dissenyador de llibres d'Excel
Les aplicacions de finances i operacions tenen una interfície fàcil d'utilitzar per a crear plantilles d'Excel. Permet utilitzar entitats
de dades i les definicions de camp corresponents. Es pot utilitzar la pàgina Dissenyador de llibres d'Excel per a dissenyar un llibre 
d'exportració editable personalitzat que contingui una entitat i un conjunt de camps.


## Microsoft Word
Es pot utilitzar les experiències d'exportar a Word per a informes resumits. Aquestes experiències funcionen amb tecnologia de plantilles
predissenyades. Les plantilles disponibles d'Exportar a Word apareixen al menú Obrir amb Microsoft Office a la cantonada superior dreta
d'una pàgina.


























