# Descriure les funcionalitats i característiques de Finance
Finance s'ha dissenyat pel negoci multiempresa i multidivisa d'una organització, i supervisa el rendiment d'una empresa en temps real. Finance pot pronosticar resultats futurs i prendre decisions basades en dades per impulsar el creixement de l'organització, sense importar el tamany o el sector al que pertany.

## Comptabilitat general
El mòdul de comptabilitat general s'utilitza per definir i administrar els registres financers d'una entitat jurídica. La comptabilitat general és un registre d'entrades de dèbit i crèdit. Aquestes entrades es classifiquen utilitzant els comptes enumerats en un pla de comptes.

#### Cas d'ús
Una organització utilitza Finance per digitalitzar el seu sistema financer i comptable. Comptabilitat general és el primer mòdul que cal dissenyar. S'ha de configurar l'exercici, seguit del pla de comptes i els comptes principals. Llavors, caldrà definir les dimensions, els grups de dimensions i les estructures comptables. Finalment, cal configurar el llibre de comptabilitat, on es vincularà l'exercici, el pla de comptes i l'estructura comptable. En la configuració del llibre de comptabilitat, també cal definir la divisa i el tipus de canvi predeterminats. Totes les transaccions comptables segueixen la configuració que s'ha implementat en la configuració del llibre de comptabilitat.

## Clients
Clients es refereix al saldo de fons que un client deu per productes o serveis entregats i facturats. El valor total de tots els clients s'inclou en el balanç de situació com actius circulants. Clients s'utilitza per a controlar totes les factures de client i els pagaments entrants. Es pot crear factures de serveis si les factures no estan relacionades amb les comandes de venda. També es pot rebre pagamaents per diferents mitjants, com lletres de canvi, efectiu, xecs, targetes de crèdit i pagaments electrònics.

#### Cas d'ús
Cal comptabilitzar totes les transaccions de Clients al llibre de comptabilitat, com factures de clients i devolucions de proveïdors. El mòdul Clients pot liquidar tots els cobraments amb les transaccions de pagament. El mòdul admet diferents formes de pagament, condicions de pagament, regles de descompte per pagament anticipat, dies de pagament i calendaris.

## Proveïdors
Proveïdors fa referència a les quantitats de diners que una empresa deu als seus venedors o proveïdors per béns o serveis que s'han rebut, però que encara no s'han pagat. El valor total dels proveïdors s'inclou en el balanç de situació com a passiu. Es pot introduïr manualment factures de proveïdors o importar-les electrònicament a través de serveis d'integració. Després d'introduïr o rebre factures, aquestes es poden revisar i aprovar mitjançant un diari d'aprovació de factures. El sistema pot habilitar la conciliació de factures, les directrius de factures de proveïdor i els fluxos de treball per automatitzar el procés de revisió. Les factures que cumpleixen uns criteris determinats s'aproven automàticament i les factures restants es marquen per a ser revisades.

#### Cas d'ús
Cal comptabilitzar totes les transaccions de proveïdors en el llibre de comptabilitat, com factures de proveïdors o devolucions de clients. El mòdul Proveïdors pot liquidar tots els pagaments amb les transaccions de pagament que es facin. El mòdul admet diferents formes de pagament (com pagaments amb xec i electrònics), condicions de pagament, regles de descompte per pagament anticipat, dies de pagament i calendaris.

## Comptabilitat de costos
Comptabilitat de costos és una branca de la comptabilitat que registra, classifica, analitza i resum els costos que realitza una empresa. El mòdul Comptabilitat de costos administra els processos utilitzats en la comptabilitat de costos, com la base d'assignació, el llibre de comptabilitat de costos i el moviment, la classificació i el comportament dels costos.

#### Cas d'ús
Una empresa multinacional té operacions en quatre països, representats per quatre entitats jurídiques diferents. Disposa d'un centre de costos per gestionar les operacions dels països. El mòdul Comptabilitat de costos ajuda a comptabilitzar les opercaions diàries de les entitats jurídiques. Fa un seguiment de les despeses, les medeix i n'estudia els seus efectes, ajudant a decidir com utilitzar els recursos de manera efectiva.

## Gestió pressupostària
Aquest mòdul proporciona informació general dels components de la funcionalitat de gestió pressupostària, les eines de gestió pressupostària i les funcions d'informes. El mòdul de pressupostos de Dynamics 365 es divideix en tres seccions principals: planificació pressupostària, entrada de pressupostos i control pressupostari. La planificació pressupostària garanteix que es compleixin les directius, els procediments i els requeriments de l'organització en implantar el pressupost. Amb l'entrada de pressupostos (el pas següent), podem enregistrar els elements del pressupost en Finance i assignar-los als comptes de comptabilitat. El control pressupostari és el pas opcional amb el que es valida les transaccions financeres en Finance segons les línies pressupostàries registrades.

#### Cas d'ús
Es pot utilitzar Finance per ganatir la planificació estratègica a llarg plaç i la planificació pressuspostària anual, amb la finalitat de fer un seguiment de les transaccions financeres d'una manera que encaixi amb la jerarquia organitzativa. L'assignació del pressupost es pot configurar per els comptes principals i les dimensions definides en el pla de comptes de l'organització. També es pot aplicar el control pressupostari en les transaccions, en funció del pressupost establert. El nivell de control depèn de la cultura i el grau de maduresa de l'organització.

## Gestió d'efectiu i bancs
La gestió d'efectiu i bancs s'utilitza per a mantenir els comptes bancaris de l'entitat jurídica i els instruments financers associats a tots els comptes bancaris. Entre aquests instruments es pot trobar resguards de dipòsit, xecs lletres de canvi i pagarès. També pot conciliar extractes bancaris i imprimir les dades bancàries en informes estàndard.

#### Cas d'ús
Des d'aquest mòdul es pot mantenir comptes bancaris organitzatius i fer totes les operacions relacionades amb el banc. Si es necessita conciliar un extracte bancari amb el seu llibre de comptabilitat, Finance permet importar l'extracte i conciliar-lo automàticament des de les transaccions bancàries. En aquest mòdul, també es pot pronosticar les xifres de fluxs d'efectiu. Les dades de clients i proveïdors, conjuntament amb les condicions de pagament, poden deduïr la previsió de flux d'efectiu de l'organització.

## Actius fixes
Aquest mòdul proporciona accés a recursos que utilitzen actius fixes per a Finance. Els actius fixes són articles de valor que pertanyen a un individu o organització. Poden ser edificis, vehicles, terres i equips.

#### Cas d'ús
Diferents organitzacions tenen diferents tipus d'actius fixes per operar al seu negoci. Hi ha actius tangibles, com propietats, equips i inventari. Les organitzacions utilitzen aquests actius fixes per a produïr béns i serveis. Les organitzacions també tenen actius intangibles, que no existeixen físicament, però representen un valor monetari, com drets d'autor, marques i fons de comerç. Aquest tipus d'actius pot augmentar el valor futur d'una organització i, a vegades, poden ser més valuosos que els actius tangibles. En el mòdul d'actius fixes, es manté el perfil d'un actiu, com els detalls de compra, la valoració actual i el perfil de depreciació.

## Gestió de desepeses
La gestió de despeses permet crear un flux de treball integrat amb la finalitat d'emmagatzemar dades de mètodes de pagament, importar transaccions amb targetes de crèdit i fer un seguiment dels diners que gasten els empleats. També pot definir les directives de despeses i automatitzar el retorn de les despeses de viatge.

#### Cas d'ús
Una empresa té definides regles i directius per a diferents despeses, com viatges i alimentació. En el mòdul de Gestió de despeses, poden definir totes aquestes directius en funció de la jerarquia organitzativa. Per exemple, quan un empleat registra despeses, aquests s'ajusten a les directius introduïdes. També és possible introduïr despeses per a entitats jurídiques creuades, quan un empleat participa en un projecte que pertany a una entitat jurídica diferent i és necessari introduïr despeses per al projecte.

## Característiques normatives
Les aplicacions de finances i operacions inclouen funcions normatives per a diferents països/regions. Aquesta funció s'activa segons la direcció principal de l'entitat jurídica activa. En aquesta funcionalitat, hi ha actualitzacions normatives per adaptar-la a les noves legislacions o modificacions per a un país o regió. Les actualitzacions normatives que s'entreguen amb revisions o com a part d'una versió preliminar es poden identificar, respectivament, amb les sigles HF i amb "Versió preliminar". També envia i revisa alertes normatives. Pot comprovar les Actualitzacions reglamentaries per obtenir informació sobre els últims plans d'actualització nromativa.

#### Cas d'ús






































