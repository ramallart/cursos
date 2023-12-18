# Entorns a Microsoft Dataverse
Un entorn és una forma de crear i administrar una instància d'una base de dades de Dataverse. També permet administrar l'accés dels usuaris, la configuració de seguretat i l'emmagatzematge associat amb la base de dades de Dataverse d'aquest entorn. Un entorn també permet instal·lar aplicacions que s'han creat amb Power Apps o fluxes que s'han creat amb Power Automate en aquest entorn. Es pot crear un o molts entorns, segons les necessitats.

Cada entorn es crea amb un subscriptor de Microsoft Entra ID, i només els usuaris d'aquest subscriptor poden accedir als seus recursos. Un entorn també està vinculat a una ubicació geogràfica, per exemple, Estats Units. Quan es crea una base de dades de Dataverse en un entorn, aquesta base de dades es crea en els centres de dades d'aquesta ubicació geogràfica. Qualsevol element que es creï en aquest entorn, també està vinculat a la ubicació de l'entorn.


Es pot crear més d'un entorn per a gestionar el desenvolupament de solucions i emmagatzematge de dades. Per a fer-ho, cal configurar un entorn de desenvolupament, un altre de prova i un altre de producció. També es pot configurar un entorn basat en una ubicació geogràfica. Per exemple, es pot configurar un entorn per a Europa i un altre per a Àsia. Cada entorn tindrà una o cap instància de Dataverse.
