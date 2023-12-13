# Descriure les funcionalitats i característiques de Finance
Finance s'ha dissenyat pel negoci multiempresa i multidivisa d'una organització, i supervisa el rendiment d'una empresa en temps real.
Finance pot pronosticar resultats futurs i prendre decisions basades en dades per impulsar el creixement de l'organització, sense importar
el tamany o el sector al que pertany.

## Comptabilitat general
El mòdul de comptabilitat general s'utilitza per definir i administrar els registres financers d'una entitat jurídica. La comptabilitat
general és un registre d'entrades de dèbit i crèdit. Aquestes entrades es classifiquen utilitzant els comptes enumerats en un pla de
comptes.

#### Cas d'ús
Una organització utilitza Finance per digitalitzar el seu sistema financer i comptable. Comptabilitat general és el primer mòdul que cal 
dissenyar. S'ha de configurar l'exercici, seguit del pla de comptes i els comptes principals. Llavors, caldrà definir les dimensions, els
grups de dimensions i les estructures comptables. Finalment, cal configurar el llibre de comptabilitat, on es vincularà l'exercici, el pla
de comptes i l'estructura comptable. En la configuració del llibre de comptabilitat, també cal definir la divisa i el tipus de canvi
predeterminats. Totes les transaccions comptables segueixen la configuració que s'ha implementat en la configuració del llibre de
comptabilitat.

## Clients
Clients es refereix al saldo de fons que un client deu per productes o serveis entregats i facturats. El valor total de tots els clients
s'inclou en el balanç de situació com actius circulants. Clients s'utilitza per a controlar totes les factures de client i els pagaments
entrants. Es pot crear factures de serveis si les factures no estan relacionades amb les comandes de venda. També es pot rebre pagamaents
per diferents mitjants, com lletres de canvi, efectiu, xecs, targetes de crèdit i pagaments electrònics.

#### Cas d'ús
Cal comptabilitzar totes les transaccions de Clients al llibre de comptabilitat, com factures de clients i devolucions de proveïdors. El
mòdul Clients pot liquidar tots els cobraments amb les transaccions de pagament. El mòdul admet diferents formes de pagament, condicions
de pagament, regles de descompte per pagament anticipat, dies de pagament i calendaris.

## Proveïdors
Proveïdors fa referència a les quantitats de diners que una empresa deu als seus venedors o proveïdors per béns o serveis que s'han rebut,
però que encara no s'han pagat. El valor total dels proveïdors s'inclou en el balanç de situació com a passiu. Es pot introduïr manualment
factures de proveïdors o importar-les electrònicament a través de serveis d'integració. Després d'introduïr o rebre factures, aquestes es
poden revisar i aprovar mitjançant un diari d'aprovació de factures. El sistema pot habilitar la conciliació de factures, les directrius
de factures de proveïdor i els fluxos de treball per automatitzar el procés de revisió. Les factures que cumpleixen uns criteris
determinats s'aproven automàticament i les factures restants es marquen per a ser revisades.

#### Cas d'ús
Cal comptabilitzar totes les transaccions de proveïdors en el llibre de comptabilitat, com factures de proveïdors o devolucions de clients.
El mòdul Proveïdors pot liquidar tots els pagaments amb les transaccions de pagament que es facin. El mòdul admet diferents formes de 
pagament (com pagaments amb xec i electrònics), condicions de pagament, regles de descompte per pagament anticipat, dies de pagament i
calendaris.






















