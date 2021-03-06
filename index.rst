=========================
Health Bredings Managment
=========================

    Il nostro software nasce dalla volontà di sviluppare un prodotto, che permetta di controllare e gestire un allevamento in tempo reale e a distanza, in particolare monitorando la temperatura corporea dell'animale in maniera non invasiva e continua nel tempo. Lo scopo di tale sistema è ridurre il consumo degli antibiotici e al contempo di frenare il diffondersi della resistenza antimicrobica negli allevamenti.


.. image:: https://github.com/fr00ller/Mo.Te/blob/master/dashboard.png?raw=true

    
============
Utenti
============

    **AMMINISTRATORE**

    - L’utente super user ha la possibilità di visualizzare tutti i dati statistici relativi ad ogni allevamento.

    - L’utente super user può creare e/o modificare gli utenti del portale.

    - L’utente super user può creare e/o modificare le unità produttive.

    - L’utente super user può creare e/o modificare gli allevamenti.

    - L’utente super user può creare e/o modificare le anagrafiche dei capi.



    **VETERINARIO**

    - L’utente veterinario ha la possibilità di visualizzare tutti i dati statistici relativi ai suoi allevamenti.

    - L’utente veterinario può creare e/o modificare le anagrafiche dei capi per i suoi allevamenti.

    - L’utente veterinario può creare e assegnare le attività per i suoi allevamenti.

    - L’utente veterinario può visualizzare e gestire le segnalazioni dei suoi allevamenti.


    **OPERATORE**

    - L’utente operatore può visualizzare e gestire solo le attività assegnate al suo allevamento.

    - L’utente operatore può creare e/o modificare solo per il suo allevamento.

    - L’utente operatore può creare e modificare le anagrafiche capi per il suo allevamento .


    Questo modulo sarà ad uso esclusivo dell’utente amministratore  e permette  nello specifico di creare e/o modificare utenti che hanno accesso al gestionale. Per ogni singolo utente oltre ai dati anagrafici:

    - Nome.

    - Cognome.

    - Email.

    - Telefono.

    - Ruolo Aziendale. (Super User,Veterinario,Operatore)

    - Nome utente.

    - Password.

    potrà essere assegnato uno o più allevamenti su cui potrà lavorare il nuovo utente.

    Con la stessa logica possiamo all’interno di ogni allevamento definire le unità produttive che questo utente può gestire o meno.

============
Dashboard
============

   Questa è la schermata principale del programma e troviamo in modo immediato lo stato di tutti i nostri allevamenti. 

     .. important::  Gli allevamenti saranno filtrati in base al livello di accesso dell’utente e verrà mostrata questa area solo per gli utenti appartenenti al gruppo ''veterinario'' o ''amministratore''.

   Ogni allevamento è identificato da un quadrato che riporta il nome dell'allevamento e viene colorato con un colore sempre più tendente al rosso maggiore è il numero di allarmi rilevati.


   Per ogni quadrato possiamo avere un dettaglio dei parametri rilevati all'interno facendo click sopra di esso



.. image:: https://github.com/fr00ller/Mo.Te/blob/master/dash.png?raw=true
        
------

    - **Temperature**


      Viene mostrato il valore medio delle rilevazioni di temperatura nell' allevamento.


    - **Somministrazioni**


      Viene mostrato il numero di farmaci utlizzati nel periodo di tempo selezionato


    - **Attività aperte**


      Viene mostrato in forma grafica il numero di attività aperte per il periodo selezionato.


    - **Segnalazioni Aperte**


      Viene mostrato in forma grafica il numero di attività aperte per il periodo selezionato.


    - **Mortalità capi**


      Viene mostrato il tasso di mortalità medio nell'allevamento per il periodo selezionato.

-----

    Per quanto riguarda i dati visualizzati saranno presi per l’intervallo di tempo selezionato nel filtro e per l’allevamento/unità produttiva selezionata.

    Per ogni singolo allevamento o unità di produttiva sarà possibile lasciare dei commenti o annotazioni.
    
    Ogni commento viene eliminato dopo n. 3 mesi dall’inserimento.


    Con la stessa modalità descritta sopra avremo anche

    - Ultime attività aperte

    - Ultime segnalazioni fatte

    - Ultimo accesso operatori

    - Elenco temperature rilevate ordinate in modo decrescente

  


===========
Allevamenti
===========

    L’allevamento può essere creato e modificato solo dall’utente super user e identifica a livello geografico dove è collocato lo stabilimento. I campi previsti per ogni allevamento sono:

    - **Nome allevamento**

      Nome univoco che identifica l'allevamento

    - **Indirizzo**

      Indirizzo della sede legale dell'allevamento

    - **Comune**

      Comune sede legale allevamento

    - **Provincia**

      Provincia

    - **Cap**

    - **Telefono**

      Telefono sede legale allevamento.

    - **Email**

      Contatto email di riferimento dove vengono inviate le notifiche amministrative.

    - **Descrizione**

      Note descrittive sull'alevamento

    Esso viene anche  utilizzato per fornire all’utente dati aggregati nella dashboard, visualizzando con un colore più o meno tendente al rosso in base al numero di allarmi presenti. Gli allarmi che determinano lo stato dell’allevamento sono:

        - **Livelli temperatura sopra sogli. (necessario sensore Mo. Tecnhologies)**

          Vengono visualizzati il livello medio della temperatura all'interno dell'intero allevamento. Se vi sono valori sopra alla soglia verrà evidenziato dal colore.

        - **Numero segnalazioni aperte.**

          Indica il numero di segnalazioni non ancora risolte all'interno dell'intero allevamento.

        - **Tasso di mortalità.**

          Viene mostrato la percentuale media di decessi avvenuti all'interno dell'allevamento.

        - **Numero somministrazioni farmaci.**

          Indica il numero di farmi somministrati all'interno dell'allevamento.




========================
    Unità produttive
========================

    Anche questa maschera sarà ad uso esclusivo dell’utente amministratore  e permette di creare o modificare unità produttive. Per unità produttiva è inteso un sottoinsieme all’interno di un allevamento identificato dai seguenti campi:

    - **Nome.**

      Nome univoco dell'unità produttiva.

    - **Indirizzo.**
    - **Comune.**
    - **Provincia.**
    - **Cap.**

     Campi riferiti all'ubicazione geografica dell'unità produttiva.

    - Email.
    - Telefono.

    - Allevamento.

      Indica a quale allevamento appartiene l’unità produttiva

    - Tipo unità produttiva.

      Serve ad indicare la tipologia di allevamento effettuato nell'unità produttiva

    - Tipologia Animali.

    In fase di creazione di ogni unità produttiva sarà possibile creare nuovi sottoinsiemi che da adesso in poi chiameremo box. Essi sono esattamente corrispondenti allo spazio fisico dove vengono tenuti i capi e hanno i seguenti campi:

    - Nome box.

      Nome identificativo 

    - Larghezza.
    - Lunghezza.
    - Numero Capi.

    I box devono essere associati ad una ed una sola unità produttiva e vengono utilizzati per individuare più velocemente dove sono collocati fisicamente i capi all’interno dell’allevamento.

=======================
    Anagrafica capi
=======================

    Le anagrafiche dei capi sono le informazioni di base di ogni singolo capo. Ogni anagrafica può essere inserita e modificata da tutti gli utenti in base al livello di accesso come descritto sopra. Nel dettaglio i campi previsti per ogni capo sono:

    - **Codice identificativo.**
    - **Unità produttiva.**
    - **Peso alla nascita.**
    - **Data di nascita.**
    - **Codice padre.**
    - **Codice madre.**
    - **Razza.**
    - **Stato.**
    - **Descrizione.**

    Per ogni box l’operatore ha la possibilità di inserire il peso generale in modo che possa poi essere visualizzata  la curva di crescita agli utenti abilitati.
    Oltre a questo sarà possibile sempre visualizzare la scheda completa del capo e più nel dettaglio sono disponibili le seguenti informazioni:
    - Grafico temperature.
    - Grafico somministrazioni.
    - Cronologia Somministrazioni.

    Per facilitare l’inserimento di queste informazioni all’operatore sono previsti dei filtri nella lista dei capi che permettono di individuare velocemente l’animale su cui operare.I filtri a disposizione sono:
    Ricerca per codice identificativo.

    - Unità produttiva.
    - Range di date.
    - Temperatura.

==================
    Attività
==================


    Le attività sono lo strumento che viene usato dal veterinario per poter assegnare compiti ad uno specifico allevamento o unità produttiva. 


.. image:: https://github.com/fr00ller/Mo.Te/blob/master/attivita.png?raw=true



-----------------------



    Può essere creata una nuova attività utilizzando il bottone blu in alto a destra "+ Nuova Attività". 
    Nella successiva maschera possiamo selezionare una specifica unità produttiva, un box o direttamente il numero del capo per poi proseguire con il testo aggiungi che ci farà comparire la seguente schermata




.. image::  https://github.com/fr00ller/Mo.Te/blob/master/crea_attivit%C3%A0.png?raw=true


--------

    - **Capi interessati.**

       In base alla selezione fatta precedentemente ci troveremo i capi suddivisi per box. Possiamo comunque rimuovere ulteriori capi non interessati.

    - **Tipo attività (Somministrazione, Richiesta Generica).**

       Va selezionata la tipologia di attività scegliendo tra:
          
           - Somministrazione 
             
             Nel caso specifico della somministrazione sarà possibile specificare:

                 - **Nome del farmaco.**
                 - **Dose.**
                 - **Ripetizione.**
                 - **Intervallo di tempo.**


           - Richiesta Generica
           
             Nel caso specifico della richiesta generica sarà possibile specificare:

                 - **Descrizione breve**
                 - **Ripetizione.**
                 - **Intervallo di tempo.**


           
    - **Priorità.**

       Possiamo indicare l'urgenza all'operatore indicando se ha priorità **Normale** o **Urgente**

    - **Descrizione.**

       Possiamo descrivere nel dettaglio la tipologia di attività da svolgere.

    

    I filtri possibili per le attività sono:

    - Tipo di attività.

    - Range di date



======================
    Segnalazioni
======================

    Per quanto le segnalazioni possiamo definire lo strumento di comunicazione a disposizione dell’operatore. Esso infatti permette di segnalare le problematiche o eventi che accadono nell’allevamento al veterinario responsabile. In fase di creazione di una nuova segnalazione abbiamo a disposizione i seguenti campi:

    - Capi interessati.
    - Descrizione problema.
    - Allegato.
    - Le segnalazioni saranno visualizzate al veterinario di competenza e sarà possibile filtrare per i seguenti campi:
    - unità produttiva
    - nome box
    - stato
    - range di date


=======================
Flusso Operativo
=======================

    Se la segnalazione viene risolta scompare dall’elenco delle attività e delle segnalazioni ma ne teniamo comunque traccia all’interno della scheda del capo, in modo da capire lo storico delle varie problematiche avute e risolte.
e
