# Servizi adoperati

## Google cloud
  Il sito Google Cloud offre agli utenti di creare una macchina virtuale remota, questo ci può permettere di creare un sito.
  Per iniziare andare sul sito [Google cloud console](https://console.cloud.google.com/) e iscriversi. Dopo di che 
  1. Recarsi nella sezione "computer engine"
  2. Andare su "istanza VM" e creare il progetto
  3. Inserire le caratteristiche desiderate:
      - CPU
      - Sistema operativo
      - Memoria
  5.  La creazione della macchina virtuale è stata conclusa
 ### Collegamento tramite SSH
  1. Scaricare PUTTY
  2. Inserire IP della macchina (visibile da Google Cloud nella sezione IP esterno), la porta è quella di default

### Collegamento SFTP
Tramite macchina virtuale installare il servizio FTP. Le credenziali che andiamo a creare le dovremmo successsivamente inserire su FileZilla. Dopo averlo scaricato:
  1. Scaricare FileZilla (ci serve per il trasferimento dei file)
  2. Inserire indirizzo IP e i seguenti dati:
     - nome utente
     - password
     - Porta default
  
  Infine per vedere il nostro sito possiamo andare su google e scrivere il nostro indirizzo IP
  
## Firebase
  Il sito Google Firebase offre la possibilità di creare un database dinamico utilizzando il lingaggio JavaScript. 
  Per iniziare recarsi sul sito [Google firebase](https://firebase.google.com/) e iscriversi se non lo si è già stato fatto in precedenza. 
  Appena l'utente si è iscritto seguire i seguenti passaggi:
   
   1. Andare su console
   2. Cliccare aggungi progettAndao
   3. Disattivare Google analytics
   4. Cliccare conferma
   5. Se è stato fatto tutto correttamente andare su
   6. Realtime database
   7. Secgliere Belgio
   8. Avviare in modalità e blocco e confermare
   
   Per collegarsi al database tramite sito web seguire i seguenti passaggi:
   1. Andare su panoramica progetto
   2. Scegliere la seguente icona
   3. Non mettere la spunta su Firebase Hosting
   4. Premere registra
   5. Copiare il codice mostrato e incollarlo sul file dove desideriamo fare il collegamento
   6. Infine premere vai alla console
