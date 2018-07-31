Health Bredings Managment

============
Tipologia Utenti
============

    **SUPER USER**
    
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
   

