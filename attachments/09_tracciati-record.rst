.. _`§A`:

Tracciato record dei dati statistici dei Gestori PEC, Conservatori e dei Prestatori di servizi fiduciari qualificati
====================================================================================================================

.. important::
  Documento tecnico - Tracciato record dati statistici

Versione 1.1 del 02/10/2019

Sommario
--------

.. toctree::
   :maxdepth: 2
   :name: Sommario
   :numbered:

`TR.1 \  Tracciato dati statistici ‒ Servizio PEC <§TR1>`__

`TR.2 \  Tracciato dati statistici ‒ Indisponibilità servizio PEC <§TR2>`__

`TR.3 \  Tracciato dati statistici ‒ Servizio Conservazione <§TR3>`__

`TR.4 \  Tracciato dati statistici ‒ Servizi fiduciari qualificati (QTSP) <§TR4>`__

.. _`§TR1`:
TR.1 Tracciato dati statistici ‒ Servizio PEC
---------------------------------------------

.. important::
   ID statistica: **P01**
   Descrizione statistica: ``Dati statistici PEC``
   Statistica aggregata: *Sì*

============= =================================================================================== ======== ========== =============== =================
**Campo**     **Descrizione**                                                                     **Tipo** **#Digit** **Esempio**     **Filtro**\  [1]_
CodGestPEC    Codice Soggetto erogatore del servizio PEC con prefisso espresso come segue:        String   TIN: 20    TIN-97735020584 Sì
                                                                                                                                     
              CF = “TIN-xxxxxxxxxxxxxxxx”                                                                  VAT: 15                   
                                                                                                                                     
              P.IVA= “VAT-xxxxxxxxxxx”                                                                     IPA: 20                   
                                                                                                                                     
              IPA= “IPA-xxxxxx…”                                                                                                     
Quadrimestre  Quadrimestre di riferimento (assoluto 1-3)                                          Num      1          1               Sì
Anno          Anno                                                                                Num      4          2019            Sì
NumDomini     Numero totale di domini                                                             Num                                
NumCaselle    Numero totale caselle                                                               Num                                
MsgUscita     Nr. di “ricevute di accettazione”                                                   Num                                
MsgIngresso   Nr. “ricevute di presa in carico” emesse in favore di altri gestori PEC per PEC2PEC Num                                
VirusIngresso Nr. Virus ricevuti da Gestore in msg PEC da consegnare a propri utenti              Num                                
VirusUscita   Nr. Virus ricevuti dai propri utenti PEC in msg da inviare                          Num                                
============= =================================================================================== ======== ========== =============== =================


.. _`§TR2`:
TR.2 Tracciato dati statistici ‒ Indisponibilità servizio PEC
-------------------------------------------------------------

.. important::
   ID statistica: **P02**
   Descrizione statistica: ``Dati statistici indisponibilità servizi PEC``
   Statistica aggregata: *Sì*

=============== ============================================================================ ======== ========== =============== =================
**Campo**       **Descrizione**                                                              **Tipo** **#Digit** **Esempio**     **Filtro**\  [2]_
CodGestPEC      Codice Soggetto erogatore del servizio PEC con prefisso espresso come segue: String   TIN: 20    TIN-97735020584 Sì
                                                                                                                                
                CF = “TIN-xxxxxxxxxxxxxxxx”                                                           VAT: 15                   
                                                                                                                                
                P.IVA= “VAT-xxxxxxxxxxx”                                                              IPA: 20                   
                                                                                                                                
                IPA= “IPA-xxxxxx…”                                                                                              
Quadrimestre    Quadrimestre di riferimento (assoluto 1-3)                                   Num      1          3               Sì
Giorno          Giorno di riferimento (assoluto 1-366)                                       Num      3          200             Sì
Anno            Anno                                                                         Num      4          2019            Sì
TipoDisservizio Tipo disservizio attribuito tra quelli previsti:                             Num      2          03              Sì
                                                                                                                                
                “01” = Pianificato                                                                                              
                                                                                                                                
                “02” = Incidente                                                                                                
                                                                                                                                
                “03” = Malfunzione                                                                                              
Durata          Durata in minuti dell’indisponibilità del servizio                           Num                 90              Sì [3]_
SLA             Rispetto degli SLA di cui all’art. 12, commi 3 e 5 del DM 2 novembre 2005;   String   1          S               Sì
                                                                                                                                
                “S”: SLA rispettati                                                                                             
                                                                                                                                
                “N”: sforamento dati SLA                                                                                        
=============== ============================================================================ ======== ========== =============== =================


.. _`§TR3`:
TR.3 Tracciato dati statistici ‒ Servizio Conservazione
-------------------------------------------------------

.. important::
   ID statistica: **C01**
   Descrizione statistica: ``Dati statistici Conservazione``
   Statistica aggregata: *Sì*

===================== ========================================================================================== ======== ========== =============== =================
**Campo**             **Descrizione**                                                                            **Tipo** **#Digit** **Esempio**     **Filtro**\  [4]_
CodConservatore          Codice Soggetto erogatore del servizio Conservazione con prefisso espresso come segue:  String   TIN: 20    TIN-97735020584 Sì
                                                                                                                                                    
                      CF = “TIN-xxxxxxxxxxxxxxxx”                                                                         VAT: 15                   
                                                                                                                                                    
                      P.IVA= “VAT-xxxxxxxxxxx”                                                                            IPA: 20                   
                                                                                                                                                    
                      IPA= “IPA-xxxxxx…”                                                                                                            
Semestre              Semestre di riferimento (assoluto 1-2)                                                     Num      1          2               Sì
Anno                  Anno                                                                                       Num      4          2019            Sì
ContrattiPA           nr. contratti attivi con le Pubbliche Amministrazioni                                      Num                                
ContrattiPrivati      nr. contratti attivi con i soggetti privati                                                Num                                
DocumentiAcquisiti    nr. totale di documenti acquisiti nel semestre                                             Num                                
MemoriaImpegnata      Totale memoria allocata per la conservazione documenti (nr. Gigabyte [5]_) a fine semestre Num                                
DisponibilitàServizio % Disponibilità del servizio agli utenti                                                   Num                                
InterruzioniServizio  Nr. interruzioni del servizio agli utenti nel periodo                                      Num                                
InterruzioneTipo1     Interruzioni del servizio Pianificate (Nr. interruzioni)                                   Num                                
InterruzioneTipo2     Interruzioni del servizio da Incident (Nr. interruzioni)                                   Num                                
InterruzioneTipo3     Interruzioni del servizio da Malfunzione (Nr. interruzioni)                                Num                                
InterruzioneMax       Durata massima dell’interruzione del servizio (Nr. minuti)                                 Num                                
TempoMedioRipristino  Tempo medio di ripristino del servizio (Nr.minuti) per interruzioni tipo 2 e Tipo 3        Num                                
===================== ========================================================================================== ======== ========== =============== =================


.. _`§TR4`:
TR.4 Tracciato dati statistici ‒ Servizi fiduciari qualificati (QTSP)
---------------------------------------------------------------------

.. important::
   ID statistica: **Q01**
   Descrizione statistica: ``Dati statistici QTSP``
   Statistica aggregata: *Sì*

============= =============================================================================================== ======== ========== =============== =================
**Campo**     **Descrizione**                                                                                 **Tipo** **#Digit** **Esempio**     **Filtro**\  [6]_
CodQTSP       Codice Soggetto erogatore del servizio fiduciario qualificato con prefisso espresso come segue: String   TIN: 20    TIN-97735020584 Sì
                                                                                                                                                 
              CF = “TIN-xxxxxxxxxxxxxxxx”                                                                              VAT: 15                   
                                                                                                                                                 
              P.IVA= “VAT-xxxxxxxxxxx”                                                                                 IPA: 20                   
                                                                                                                                                 
              IPA= “IPA-xxxxxx…”                                                                                                                 
Semestre      Semestre di riferimento (assoluto 1-2)                                                          Num      1          2               Sì
Anno          Anno                                                                                            Num      4          2019            Sì
NumActQC      Certificati qualificati di firma digitale attivi a fine periodo                                 Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumActRemQC   Certificati qualificati di firma digitale remota attivi a fine periodo                          Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumGenQC      Certificati qualificati di firma digitale generati nel periodo di riferimento                   Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumGenRemQC   Certificati qualificati di firma digitale remota generati nel periodo di riferimento            Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumRemQC      nr. firme elettroniche qualificate remote (anche automatiche) generate nel periodo              Num                                
Num1QC        nr. certificati qualificati *one-shot* emessi nel periodo di riferimento                        Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumTS         Marche temporali emesse nel periodo (Pre-eIDAS)                                                 Num                                
NumTSeIDAS    Marche temporali qualificate e-IDAS emesse nel periodo                                          Num                                
NumActSeal    Certificati qualificati di sigillo qualificato attivi a fine periodo                            Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumActRemSeal Certificati qualificati di sigillo qualificato remoto attivi a fine periodo                     Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumGenSeal    Certificati qualificati di sigillo qualificato generati nel periodo di riferimento              Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumGenRemSeal Certificati qualificati di sigillo qualificato remoto generati nel periodo di riferimento       Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumRemSeal    nr. sigilli qualificati remoti generati nel periodo di riferimento                              Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumActWebQC   Certificati qualificati per siti WEB attivi a fine periodo                                      Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
NumGenWebQC   Certificati qualificati per siti WEB generati nel periodo di riferimento                        Num                                
                                                                                                                                                 
              (al 30 giugno e 31 dicembre)                                                                                                       
============= =============================================================================================== ======== ========== =============== =================


.. [1]  La colonna “Filtro” individua i campi sui quali è possibile agire con funzionalità di filtro e ricerca.

.. [2]  La colonna “Filtro” individua i campi sui quali è possibile agire con funzionalità di filtro e ricerca.

.. [3]  Il filtro sul campo “Durata” si intende come durata minima.

.. [4]  La colonna “Filtro” individua i campi sui quali è possibile agire con funzionalità di filtro e ricerca.

.. [5]  Per GB (GigaByte) si intende 1 miliardo di byte.

.. [6]  La colonna “Filtro” individua i campi sui quali è possibile agire con funzionalità di filtro e ricerca.


.. forum_italia::
   :topic_id: 6
   :scope: document
