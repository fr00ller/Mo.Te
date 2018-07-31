Health Bredings Managment

============
Tipologia Utenti
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
    - L’utente veterinario può creare e assegnare le attività per i suoi allevamenti
    - L’utente veterinario può visualizzare e gestire le segnalazioni dei suoi allevamenti.
    
    
    **OPERATORE**
    
    - L’utente operatore può visualizzare e gestire solo le attività assegnate al suo allevamento.
    - L’utente operatore può creare e/o modificare solo per il suo allevamento.
    - L’utente operatore può creare e modificare le anagrafiche capi per il suo allevamento .


    Questo modulo sarà ad uso esclusivo dell’utente super user e permette  nello specifico di creare e/o modificare utenti che hanno accesso al gestionale. Per ogni singolo utente oltre ai dati anagrafici:
    - Nome.
    - Cognome.
    - Email.
    - Telefono.
    - Ruolo Aziendale. (Super User,Veterinario,Operatore)
    - Nome utente.
    - Password.

    potrà essere assegnato uno o più allevamenti su cui potrà lavorare il nuovo utente.
    Con la stessa logica possiamo all’interno di ogni allevamento definire le unità produttive che questo utente può gestire o meno.
    
===========
Allevamenti
===========

    L’allevamento può essere creato e modificato solo dall’utente super user e identifica a livello geografico dove è collocato lo stabilimento. I campi previsti per ogni allevamento sono:

    - Nome allevamento.
    - Indirizzo.
    - Comune.
    - Provincia.
    - Cap.
    - Telefono.
    - Email.
    - Descrizione.
    
    Esso viene anche  utilizzato per fornire all’utente dati aggregati nella dashboard, visualizzando con un colore più o meno tendente al rosso in base al numero di allarmi presenti. Gli allarmi che determinano lo stato dell’allevamento sono:

        - Livelli temperatura sopra soglia. (quando avremo le rilevazioni)
        - Numero segnalazioni aperte.
        - Tasso di mortalità.
        - Numero somministrazioni farmaci.
    
    
    Ci deve essere fornito per ogni indicatore sopra elencato la soglia per cui viene generato un allarme all’interno dell’allevamento. Ad esempio: Tasso di mortalità > 0 e < 15% genera allarme giallo,  > 20% allarme rosso.
    
    
    


Dashboard
============

    Modulo dedicato alla visualizzazione dei dati in forma statistica e grafica. I dati saranno filtrati in base al livello di accesso dell’utente e verrà mostrata questa area solo gli utenti appartenenti al gruppo veterinario o super user.
    Saranno presenti tutti gli allevamenti e le attività produttive e per ognuna di esse avremo i seguenti grafici:


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
    
    Con la stessa modalità descritta sopra avremo anche
    
    - Ultime attività aperte
    
    - Ultime segnalazioni fatte 
    
    - Ultimo accesso operatori
    
    - Elenco temperature rilevate ordinate in modo decrescente
    
    Per quanto riguarda i dati visualizzati saranno presi per l’intervallo di tempo selezionato nel filtro e per l’allevamento/unità produttiva selezionata. 
    Per ogni singolo allevamento o unità di produttiva sarà possibile lasciare dei commenti o annotazioni.
    Essi vengono eliminati dopo 03 mesi dall’inserimento.
   
    ================
    UNITÀ PRODUTTIVE
    ================
    Anche questa maschera sarà ad uso esclusivo dell’utente super user e permette di creare o modificare unità produttive. Per unità produttiva è inteso un sottoinsieme all’interno di un allevamento identificato dai seguenti campi:
    
    - Nome.
    - Indirizzo.
    - Comune.
    - Provincia.
    - Cap.
    - Email.
    - Telefono.
    - Allevamento. ( indica a quale allevamento appartiene l’unità produttiva)
    - Tipo allevamento. (Ingrasso,Parto,etc…)
    - Tipologia Animali.
    
    In fase di creazione di ogni unità produttiva sarà possibile creare nuovi sottoinsiemi che da adesso in poi chiameremo box. Essi sono esattamente corrispondenti allo spazio fisico dove vengono tenuti i capi e hanno i seguenti campi:
    
    - Nome box.
    - Larghezza.
    - Lunghezza.
    - Numero Capi.
    
    I box devono essere associati ad una ed una sola unità produttiva e vengono utilizzati per individuare più velocemente dove sono collocati fisicamente i capi all’interno dell’allevamento.
    
    ==================
    ANAGRAFICA CAPI
    ==================
    
    Questa è sicuramente una delle parti centrali del programma in quanto andiamo a definire le informazioni di base di ogni singolo capo. Essa può essere inserita e modificata da tutti gli utenti in base al livello di accesso come descritto sopra. Nel dettaglio i campi previsti per ogni capo sono:
    Codice identificativo.
    Unità produttiva.
    Peso alla nascita.
    Data di nascita.
    Codice padre.
    Codice madre.
    Razza.
    Stato.
    Descrizione.
    Per ogni box l’operatore ha la possibilità di inserire il peso generale in modo che possa poi essere visualizzata  la curva di crescita agli utenti abilitati.
    Oltre a questo sarà possibile sempre visualizzare la scheda completa del capo e più nel dettaglio sono disponibili le seguenti informazioni:
    Grafico temperature.
    Grafico somministrazioni.
    Cronologia Somministrazioni.
    Per facilitare l’inserimento di queste informazioni all’operatore sono previsti dei filtri nella lista dei capi che permettono di individuare velocemente l’animale su cui operare.I filtri a disposizione sono:
    Ricerca per codice identificativo.
    Unità produttiva.
    Range di date.
    Temperatura. 
    
    ===========
    ATTIVITÀ  
    ===========
    Sono lo strumento che viene usato dal veterinario per poter assegnare compiti ad uno specifico allevamento o unità produttiva. Più nello specifico potrà essere creata una nuova attività indicando in modo generale per tutti:
    Capi interessati.
    Tipo attività (Somministrazione, Richiesta Generica).
    Priorità.
    Descrizione.
    Nel caso specifico della somministrazione sarà possibile specificare:
    Nome del farmaco.
    Dose.
    Ripetizione.
    Intervallo di tempo.
    Esse saranno elencate a gli operatori interessati in base alla priorità indicata in fase di inserimento.
    Sarà possibile filtrare le attività per rendere più agevole la ricerca all’operatore.
    I filtri possibili per le attività sono:
    Tipo di attività.
    Range di date
    
    
    
    
    
    
    ===============
    SEGNALAZIONI
    ===============
    Per quanto le segnalazioni possiamo definire lo strumento di comunicazione a disposizione dell’operatore. Esso infatti permette di segnalare le problematiche o eventi che accadono nell’allevamento al veterinario responsabile. In fase di creazione di una nuova segnalazione abbiamo a disposizione i seguenti campi:
    
    - Capi interessati.
    - Descrizione problema.
    - Allegato.
    - Le segnalazioni saranno visualizzate al veterinario di competenza e sarà possibile filtrare per i seguenti campi:
    - unità produttiva
    - nome box
    - stato
    - range di date


FLUSSO OPERATIVO
===============



    
    Se la segnalazione viene risolta scompare dall’elenco delle attività e delle segnalazioni ma ne teniamo comunque traccia all’interno della scheda del capo, in modo da capire lo storico delle varie problematiche avute e risolte.
    
