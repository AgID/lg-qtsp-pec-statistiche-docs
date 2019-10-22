|AGID - Agenzia per l'Italia Digitale|

**Linee Guida per la normalizzazione dei dati statistici dei servizi
erogati dai Gestori PEC, dai Conservatori e dai Prestatori di servizi
fiduciari qualificati**

Versione 1.1 del 02/10/2019

**Sommario**

`Capitolo 1 Prefazione 3 <#prefazione>`__

`Capitolo 2 Introduzione 4 <#introduzione>`__

`2.1 Scopo 4 <#scopo>`__

`2.2 Struttura 4 <#struttura>`__

`2.3 Gruppo di lavoro 4 <#gruppo-di-lavoro>`__

`2.4 Soggetti destinatari 4 <#soggetti-destinatari>`__

`Capitolo 3 Riferimenti e sigle 5 <#riferimenti-e-sigle>`__

`3.1 Riferimenti Normativi 5 <#riferimenti-normativi>`__

`3.2 Termini e definizioni 5 <#termini-e-definizioni>`__

`Capitolo 4 Contesto 6 <#contesto>`__

`Capitolo 5 Dati statistici dei servizi erogati
7 <#dati-statistici-dei-servizi-erogati>`__

`5.1 Gestori di Posta Elettronica Certificata (PEC)
7 <#gestori-di-posta-elettronica-certificata-pec>`__

`5.1.1 Dati statistici trasmessi dai Gestori PEC 7 <#_Toc20940186>`__

`5.2 Conservatori accreditati 7 <#conservatori-accreditati>`__

`5.2.1 Dati statistici trasmessi dai prestatori di servizi di
Conservazione documentale
7 <#dati-statistici-trasmessi-dai-prestatori-di-servizi-di-conservazione-documentale>`__

`5.3 Prestatori di servizi fiduciari qualificati (QTSP – eIDAS)
7 <#prestatori-di-servizi-fiduciari-qualificati-qtsp-eidas>`__

`5.3.1 Dati statistici trasmessi dai prestatori di servizi fiduciari
qualificati (QTSP)
8 <#dati-statistici-trasmessi-dai-prestatori-di-servizi-fiduciari-qualificati-qtsp>`__

`Capitolo 6 Adeguamento al nuovo sistema
9 <#adeguamento-al-nuovo-sistema>`__

`6.1 Tempistiche di adeguamento al nuovo sistema
9 <#tempistiche-di-adeguamento-al-nuovo-sistema>`__

`6.2 Disposizioni previgenti 9 <#disposizioni-previgenti>`__

`Capitolo 7 Specifiche tecniche e tracciati record
10 <#specifiche-tecniche-e-tracciati-record>`__

`7.1 Tracciati record dati statistici
10 <#tracciati-record-dati-statistici>`__

`Capitolo 8 Trasmissione dei dati statistici
11 <#trasmissione-dei-dati-statistici>`__

`8.1 Tempistiche di trasmissione dei dati statistici
11 <#tempistiche-di-trasmissione-dei-dati-statistici>`__

Prefazione
==========

Conformemente alle norme ISO/IEC Directives, Part 3 per la stesura dei
documenti tecnici la presente linea guida utilizzerà le parole chiave
«DEVE», «DEVONO», «NON DEVE», «NON DEVONO», «E” RICHIESTO», «DOVREBBE»,
«NON DOVREBBE», «RACCOMANDATO», «NON RACCOMANDATO» «PUO”» e «OPZIONALE»,
la cui interpretazione è descritta di seguito.

-  **DEVE** o **DEVONO**, indicano un requisito obbligatorio per
   rispettare la linea guida;

-  **NON DEVE** o **NON DEVONO**, indicano un assoluto divieto delle
   specifiche;

-  **DOVREBBE** o **RACCOMANDATO** o **NON DOVREBBE** o **NON
   RACCOMANDATO**, indicano che le implicazioni devono essere comprese e
   attentamente pesate prima di scegliere approcci alternativi;

-  **PUÓ** o **POSSONO** o l'aggettivo **OPZIONALE**, indica che il
   lettore può scegliere di applicare o meno senza alcun tipo di
   implicazione la specifica.

Introduzione
============

Scopo
-----

La presente **Linea guida – ha lo scopo di** normalizzazione i dati
statistici trasmessi ad Agid nell’ambito degli obblighi previsti per i
soggetti erogatori di servizi PEC, di Conservazione e di Servizi
fiduciari qualificati (QTSP), ed è redatta in ottemperanza del decreto
legislativo 7 marzo 2005, n. 82 e successive modifiche e integrazioni
(di seguito CAD) e della Determinazione AgID n. 160 del 2018 recante
«Regolamento per l’adozione di linee guida per l’attuazione del Codice
dell’Amministrazione Digitale».

Struttura
---------

La presente LG prevede l’applicazione del documento tecnico relativo ai
“Tracciati record dati statistici” che sarà pubblicato nel sito
istituzionale AgID con l’emanazione delle LG e contente le specifiche
relative al formato dei record da trasmettere:

-  **Tracciato record dati statistici Gestori PEC, Conservatori e
      Prestatori di servizi fiduciari qualificati (QTSP)** che dettaglia
      il formato record dei dati trattati nel presente documento. Il
      documento è suddiviso a sua volta nelle seguenti sezioni:

-  TR.1 - Tracciato dati statistici – Servizio PEC

-  TR.2 - Tracciato dati statistici – Indisponibilità Servizio PEC

-  TR.3 - Tracciato dati statistici – Servizio Conservazione documentale

-  TR.4 - Tracciato dati statistici – Servizi fiduciari qualificati
      (QTSP)

Gruppo di lavoro
----------------

La redazione del presente documento e del tracciato record dati
statistici è stata curata dal gruppo di lavoro AgID con la
collaborazione dei destinatari delle Linea Guida.

Soggetti destinatari
--------------------

I soggetti destinatari delle presenti linee guida sono tutti i soggetti
erogatori dei servizi oggetto delle presenti Linee Guida.

Riferimenti e sigle
===================

Riferimenti Normativi
---------------------

Sono riportati di seguito gli atti normativi di riferimento del presente
documento.

-  **[Reg. UE 910/2014]** Regolamento (UE) n.910/2014 del Parlamento e
      del Consiglio europeo, del 23 luglio 2014, noto come Regolamento
      e-IDAS (*eletronic IDentification Authentication and Signature*
      *and eletronic Trust Services*)

-  **[D.Lgs. 82/2005]** Decreto legislativo 7 marzo 2005, n. 82 recante
      “Codice dell’amministrazione digitale” noto anche con
      l’abbreviazione “CAD”

-  **[D.Lgs 217/2017]** - Disposizioni integrative e correttive al D.Lgs
      179/2016, concernente modifiche ed integrazioni al CAD […]

-  **[DPR 11 febbraio 2005 n.68]** – Regolamento recante disposizione
      per l’utilizzo della PEC;

-  **[DM 2.11.2005]** – Regole tecniche per la formazione, la
      trasmissione e la validazione, anche temporale, della PEC;

-  **[DPCM 23 febbraio 2013]** – Regole tecniche in materia di
      generazione, apposizione e verifica delle firme elettroniche
      avanzate, qualificate e digitali

-  **[DPCM 3 dicembre 2013]** – Regole tecniche in materia di sistema di
      conservazione

Termini e definizioni
---------------------

Di seguito si riportano gli ACRONIMI che verranno utilizzati nella
presente Linee Guida:

-  **[Agenzia]** Agenzia per l’Italia Digitale

-  **[AgID]** Agenzia per l’Italia Digitale

-  **[CAD]** Codice Amministrazione Digitale, D.Lgs 7 marzo 2005, n. 82

-  **[eIDAS]** electronic IDentification, Authentication and trust
   Services

-  **[QTSP]** Qualified Trust Service Provider (eIDAS)

-  **[PEC]** Posta Elettronica Certificata

-  **[LG]** Linea Guida / Linee Guida

-  **[TR]** Documento: “Tracciato record dati statistici PEC, QTSP e
   Conservatori”

Contesto
========

Il CAD, all’art.14 bis affida all’AgID, tra gli altri compiti, quello
dell’ “\ *Emanazione di linee guida contenenti regole, standard e guide
tecniche, nonché di indirizzo, vigilanza e controllo sull’attuazione e
sul rispetto delle norme di cui al presente Codice, anche attraverso
l’adozione di atti amministrativi generali, in materia di agenda
digitale, digitalizzazione della pubblica amministrazione, sicurezza
informatica, interoperabilità e cooperazione applicativa tra sistemi
informatici pubblici e quelli dell’Unione europea*\ ”;

L'AgID è dunque preposta alla promozione dell’innovazione digitale nel
Paese e dell’utilizzo delle tecnologie digitali nell'organizzazione
della pubblica amministrazione e nel rapporto tra questa, cittadini e le
imprese, nel rispetto dei principi di legalità, imparzialità e
trasparenza e secondo criteri di efficienza, economicità ed efficacia.

In quest’ottica la norma demanda all’AgID la determinazione delle linee
guida attuative delle molteplici disposizioni del codice.

L’articolo 71 del CAD, prevede che le regole tecniche e di indirizzo per
l’attuazione del Codice siano adottate con linee guida di AgID, previa
consultazione pubblica, sentiti le amministrazioni competenti e il
Garante per la protezione dei dati personali nelle materie di
competenza, e acquisito il parere della Conferenza unificata. Le Linee
guida divengono efficaci dopo la loro pubblicazione nell'apposita area
del sito istituzionale AgID, con la pubblicazione di apposito Avviso in
Gazzetta Ufficiale della Repubblica italiana. Lo stesso procedimento è
adottato per l’aggiornamento o la modifica delle Linee guida.

Con Determinazione n.160/2018 l’AgID ha emanato il “Regolamento per
l’adozione di linee guida per l’attuazione del codice
dell’amministrazione digitale” e, ai sensi dell’art.4 dello stesso, ha
istituito il Gruppo di Lavoro per l’Emanazione delle Linee Guida per la
normalizzazione dati statistici PEC, Conservatori e Prestatori di
servizi fiduciary qualificati (QTSP)”.

Dati statistici dei servizi erogati
===================================

Gestori di Posta Elettronica Certificata (PEC)
----------------------------------------------

Il Gestore di Posta Elettronica Certificata è tenuto a trasmettere
all’Agenzia attraverso il canale applicativo dedicato, i *data set* di
seguito definiti entro il mese successivo al quadrimestre di
riferimento.

Dati statistici trasmessi dai Gestori PEC
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

====== ============= ================================ ========== ================
**ID** **Tipologia** **Nome**                         **Rif. §** **Trasmissione**
                                                                
                                                      **[TR]**  
====== ============= ================================ ========== ================
P01    Dataset       Statistiche PEC                  TR.1       Quadrimestrale
P02    Dataset       Indisponibilità del servizio PEC TR.2       Quadrimestrale
====== ============= ================================ ========== ================

Conservatori accreditati
------------------------

Il Conservatore accreditato è tenuto a trasmettere all’Agenzia,
attraverso il canale applicativo dedicato, i *data set* di seguito
definiti entro il mese successivo al semestre di riferimento.

Dati statistici trasmessi dai prestatori di servizi di Conservazione documentale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

====== ============= ============================================== ========== ================
**ID** **Tipologia** **Nome**                                       **Rif. §** **Trasmissione**
                                                                              
                                                                    **[TR]**  
====== ============= ============================================== ========== ================
C01    Dataset       Statistiche servizio Conservazione documentale TR.3       Semestrale
====== ============= ============================================== ========== ================

Prestatori di servizi fiduciari qualificati (QTSP – eIDAS)
----------------------------------------------------------

Il Prestatore di servizi fiduciari qualificati (QTSP) che emette
certificati qualificati, validazioni temporali qualificate e non
qualificate, è tenuto a trasmettere all’AgID, attraverso il canale
applicativo dedicato, i *data set* di seguito definiti entro il mese
successivo al semestre di riferimento.

Dati statistici trasmessi dai prestatori di servizi fiduciari qualificati (QTSP)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

====== ============= ================ ========== ================
**ID** **Tipologia** **Nome**         **Rif. §** **Trasmissione**
                                                
                                      **[TR]**  
====== ============= ================ ========== ================
Q01    Dataset       Statistiche QTSP TR.4       Semestrale
====== ============= ================ ========== ================

Adeguamento al nuovo sistema
============================

Tempistiche di adeguamento al nuovo sistema
-------------------------------------------

Ai fini dell’entrata a regime del Sistema di rilevazione statistiche
PEC, Conservatori e Servizi fiduciari qualificati secondo le modalità
specificate nel presente documento, AgID comunicherà ai soggetti
erogatori dei rispettivi servizi, la data di attivazione della
**Piattaforma per l’acquisizione dei dati statistici** nonché i termini
temporali (non inferiore a quattro mesi) entro i quali ciascun soggetto
è tenuto all’adeguamento dei propri sistemi di raccolta e trasmissione
dei dati statistici secondo i tracciati e le modalità di invio
stabilite.

Disposizioni previgenti
-----------------------

L’invio dei dati statistici ai sensi delle presenti LG solleva gli
erogatori di servizi di PEC, Conservazione e QTSP dall’applicazione
delle previgenti disposizionei aventi oggetto l’invio di dati
stiatistici.

Specifiche tecniche e tracciati record
======================================

Tracciati record dati statistici
--------------------------------

Le schede tecniche riportate nel documento **“Tracciato record dati
statistici”** definiscono le specifiche e le caratteristiche tecniche
dei rispettivi campi che costituiscono i tracciati record delle
statistiche raccolte. Le schede riportano inoltre informazioni di
carattere generale ed esempi utili ad una migliore comprensione e
identificazione del tracciato, descrivendone la tipologia e le
caratteristiche dei campi che definiscono i dati statistici nel
dettaglio.

In nessun caso i dati trattati prevedono la raccolta e il trattamento di
dati personali di utenti o operatori coinvolti nell’erogazione del
servizio oggetto di rilevazione. Il tracciato dei dati è definito
esclusivamente per la raccolta dei dati statistici e il loro trattamento
per gli scopi istituzionali di AgID.

Trasmissione dei dati statistici
================================

Tempistiche di trasmissione dei dati statistici 
------------------------------------------------

Ai fini della raccolta dei dati statistici si deve tener conto della
suddivisione in periodi per ciascun anno solare di osservazione che, per
la periodicità semestrale, è suddiviso in due periodi di riferimento
coincidenti in due semestri come di seguito specificato:

-  **Primo semestre: dal 1 gennaio al 30 giugno di ciascun anno**;

-  **Secondo semestre: dal 1 luglio al 31 dicembre di ciascun anno.**

Per la periodicità quadrimestrale è suddiviso in tre periodi di
riferimento coincidenti nei tre quadrimestri come di seguito
specificato:

-  **Primo quadrimestre: dal 1 gennaio al 30 aprile di ciascun anno;**

-  **Secondo quadrimestre: dal 1 maggio al 31 agosto di ciascun anno;**

-  **Terzo quadrimestre: dal 1 settembre al 31 dicembre di ciascun
   anno.**

La trasmissione dei dati statistici relativi a ciascun intervallo
(semestre/quadrimestre) deve avvenire entro il mese successivo al
periodo di riferimento:

-  **Entro** il **31 luglio** e il **31 gennaio** di ciascun anno per la
      periodicità semestrale;

-  **Entro** il **31 maggio**, il **30 settembre** e il **31 gennaio**
      di ciascun anno rispettivamente per il **primo**, il **secondo** e
      il **terzo** **quadrimestre**.

.. |AGID - Agenzia per l'Italia Digitale| image:: media/image1.png
   :width: 2.76261in
   :height: 0.5849in
