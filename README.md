# HitMeUp

## 1. Il progetto

### Breve descrizione

HitMeUp è un progetto scolastico di una web app per fare nuove amicizie dal vivo. L’idea è aiutare a trovare persone vicine con cui condividere un hobby, studiare o fare un’attività insieme.

### Descrizione completa e contesto

Usiamo i social per parlare con tante persone, ma conoscere qualcuno dal vivo può essere più difficile. A volte vorremmo fare sport o studiare in compagnia, senza sapere chi attorno a noi abbia gli stessi interessi. Anche iniziare una conversazione può creare imbarazzo, soprattutto quando non conosciamo nessuno.

Da qui nasce HitMeUp. L’utente potrà creare un profilo, scrivere una breve presentazione e scegliere i suoi hobby, come musica, gaming, sport o studio. Attraverso la posizione del telefono, usata con il suo permesso, oppure un check-in manuale, potrà indicare il luogo in cui si trova. L’app cercherà altre persone vicine con almeno un interesse in comune e potrà avvisarlo quando ne trova una.

Per esempio, uno studente in biblioteca potrebbe scoprire che un’altra persona presente lì cerca compagnia per studiare. Sapere di avere qualcosa in comune può diventare un motivo per iniziare a parlare.

Dopo un saluto (Wave) accettato, gli utenti potranno aprire una chat e decidere se aggiungersi agli amici. HitMeUp nasce soprattutto per trovare nuovi amici e condividere attività. L’app vuole offrire una prima occasione per conoscersi, lasciando alle persone la scelta di fare il passo successivo.

### Target

HitMeUp si rivolge a chi vuole ampliare il proprio giro di amicizie, soprattutto giovani e studenti. Può essere utile a chi è timido, a chi ha cambiato scuola o città e a chi cerca qualcuno con cui condividere una passione. I luoghi a cui pensiamo sono quelli della vita quotidiana, come biblioteche, università, palestre e spazi di ritrovo.

### Competitor e differenze

Esistono già piattaforme che aiutano a conoscere persone. Abbiamo considerato questi esempi per capire meglio su cosa concentrare HitMeUp.

| Competitor | Cosa offre | Su cosa punta HitMeUp |
| --- | --- | --- |
| [Tinder](https://www.help.tinder.com/hc/en-us/articles/115004647686-Tinder-Overview) | Una piattaforma di incontri che permette di conoscere persone attraverso profili e match. | Il progetto si concentra sull’amicizia e sulla ricerca di qualcuno con cui condividere un’attività quotidiana. |
| [BFF di Bumble](https://support.bumblebff.com/hc/en-us/articles/33949872719773-Using-the-Discover-page) | Un’app dedicata alle amicizie, con profili e gruppi legati anche a interessi e posizione. | HitMeUp vuole dare particolare importanza al luogo preciso e al momento: per esempio, cercare chi è nella stessa biblioteca attraverso il check-in. |
| [Meetup](https://www.meetup.com/about/) | Una piattaforma per trovare gruppi ed eventi legati a interessi comuni. | L’idea di HitMeUp è favorire anche incontri spontanei con chi si trova già vicino, senza dover partire dalla partecipazione a un evento. |

La particolarità che vogliamo sviluppare è proprio questa: partire dal posto in cui ci si trova e da una passione condivisa per creare un’occasione di conoscenza dal vivo.


## 2. Tabella delle funzionalità

Le tabelle raccolgono 44 funzioni previste: le 24 iniziali e altre 20 per completare accesso, contatti, privacy e aiuto.

**Importanza:** Critica = necessaria per il percorso principale o per i controlli di sicurezza; Alta = importante nella prima versione; Media = da aggiungere dopo la base; Bassa = miglioramento successivo.

**Tempo:** stima di lavoro per una persona. In questa tabella **1 gg corrisponde a 4 ore di lavoro scolastico**. Le durate comprendono la realizzazione della funzione e una prima prova. Non comprendono il collaudo completo, l’integrazione finale e la preparazione dei materiali di consegna.

### Funzionalità iniziali

| ID | Azione | Chi | Importanza | Tempo |
| --- | --- | --- | --- | --- |
| F01 | Registrazione e creazione del profilo con nome, foto e hobby | Utente non registrato | Critica | 2 gg |
| F02 | Login con numero di telefono e password | Utente registrato non loggato | Critica | 1 gg |
| F03 | Modifica di profilo, foto, bio e hobby | Utente loggato | Alta | 1 gg |
| F04 | Attivazione della posizione attuale o check-in in un luogo | Utente loggato | Alta | 1,5 gg |
| F05 | Visualizzazione degli utenti vicini sulla mappa, con filtri per hobby e distanza | Utente loggato | Critica | 3 gg |
| F06 | Invio di un saluto (Wave) a una persona vicina | Utente loggato | Alta | 1 gg |
| F07 | Chat live dopo l’accettazione del saluto | Utente loggato | Alta | 3 gg |
| F08 | Segnalazione e blocco di un utente | Utente loggato | Critica | 1,5 gg |
| F09 | Visualizzazione della homepage e della spiegazione dell’app | Utente generale | Critica | 0,5 gg |
| F10 | Dashboard di moderazione per utenti e segnalazioni | Admin | Alta | 2 gg |
| F11 | Gestione dei tag di interesse e delle categorie | Admin | Media | 0,75 gg |
| F12 | Gestione del consenso GPS e indicazioni per revocarlo nel browser | Utente loggato / Browser o dispositivo | Critica | 0,75 gg |
| F13 | Accettazione o rifiuto di una richiesta di posizione esatta | Utente loggato | Critica | 1,5 gg |
| F14 | Invio, accettazione e rifiuto delle richieste di amicizia | Utente loggato | Alta | 2 gg |
| F15 | Lista degli amici e stato online, se visibile | Utente loggato | Media | 1,5 gg |
| F16 | Modalità incognito per nascondere temporaneamente posizione e presenza | Utente loggato | Critica | 1 gg |
| F17 | Ricerca avanzata per username, luogo e interessi | Utente loggato | Media | 1,5 gg |
| F18 | Moderazione di foto profilo e contenuti segnalati | Admin | Alta | 1,5 gg |
| F19 | Sospensione temporanea o ban manuale di un account | Admin | Alta | 1 gg |
| F20 | Registro delle segnalazioni e storico delle azioni di moderazione | Admin | Alta | 1 gg |
| F21 | Invio di notifiche globali e avvisi di sistema | Admin | Media | 0,75 gg |
| F22 | Lettura e accettazione dei Termini di Servizio | Utente non registrato | Critica | 0,25 gg |
| F23 | Sospensione automatica temporanea per bassa reputazione, con revisione | Sistema automatico | Media | 2 gg |
| F24 | Feedback sull’interazione e Thumbs Down | Utente loggato | Media | 1 gg |
| F25 | Logout dall’account | Utente loggato | Alta | 0,25 gg |
| F26 | Verifica del numero di telefono tramite codice | Utente in registrazione o loggato / Servizio SMS | Alta | 1,5 gg |
| F27 | Recupero della password dimenticata | Utente registrato non loggato | Alta | 1 gg |
| F28 | Cambio della password | Utente loggato | Alta | 0,5 gg |
| F29 | Cambio del numero di telefono con nuova verifica | Utente loggato | Media | 0,75 gg |
| F30 | Scelta delle informazioni visibili nel profilo e dello stato online | Utente loggato | Alta | 0,75 gg |
| F31 | Attivazione e disattivazione delle notifiche per categoria | Utente loggato | Media | 0,75 gg |
| F32 | Centro notifiche con saluti, richieste e avvisi ricevuti | Utente loggato | Media | 1 gg |
| F33 | Accettazione o rifiuto dei saluti ricevuti | Utente loggato | Alta | 0,75 gg |
| F34 | Silenziamento di una chat | Utente loggato | Bassa | 0,5 gg |
| F35 | Annullamento di una richiesta di amicizia ancora in attesa | Utente loggato | Media | 0,5 gg |
| F36 | Rimozione di una persona dalla lista amici | Utente loggato | Media | 0,5 gg |
| F37 | Richiesta della posizione esatta a un amico | Utente loggato | Media | 1 gg |
| F38 | Revoca della condivisione della posizione esatta | Utente loggato | Critica | 0,5 gg |
| F39 | Apertura della scheda di un utente e degli hobby in comune | Utente loggato | Alta | 0,5 gg |
| F40 | Fine del check-in quando si lascia un luogo | Utente loggato | Alta | 0,5 gg |
| F41 | Consultazione dello stato delle proprie segnalazioni | Utente loggato | Media | 0,75 gg |
| F42 | Cancellazione del proprio account con conferma | Utente loggato | Alta | 1 gg |
| F43 | Richiesta di revisione di una sospensione | Utente sospeso | Media | 1 gg |
| F44 | Pagina di aiuto e domande frequenti | Utente generale | Bassa | 0,5 gg |

**Totale delle 44 funzioni: 47,5 gg, cioè 190 ore stimate.** La base con priorità Critica richiede 12 gg; le funzioni con priorità Alta aggiungono 20,75 gg. Le funzioni Media e Bassa possono essere distribuite negli sviluppi successivi. Il totale è una stima delle funzioni elencate, non una scadenza garantita.


### Regole per far funzionare insieme le funzioni

- **Saluti e chat:** un Wave non apre subito una conversazione. La chat diventa disponibile dopo l’accettazione del destinatario. La richiesta di amicizia è separata dal saluto.
- **Posizione:** la mappa mostra una zona approssimativa. La posizione esatta si può chiedere solo a un amico e si vede soltanto se accetta. Il consenso può essere revocato in qualsiasi momento.
- **GPS e check-in:** chi rifiuta il GPS può scegliere il luogo manualmente. Il permesso GPS del browser è diverso dal consenso a condividere la posizione con un altro utente. La revoca del permesso del browser si effettua nelle sue impostazioni.
- **Incognito e blocco:** chi attiva l’incognito sparisce dai suggerimenti e interrompe le condivisioni di posizione. Il blocco impedisce nuovi messaggi, richieste, saluti e suggerimenti reciproci.
- **Feedback e reputazione:** un Thumbs Down non equivale a una violazione accertata. Le regole automatiche devono controllare feedback duplicati o sospetti e applicare una soglia configurabile. Una sospensione automatica è temporanea, ha una motivazione e permette di chiedere una revisione. Il ban definitivo richiede un controllo dell’admin.
- **Segnalazioni e privacy:** l’utente vede lo stato delle proprie segnalazioni, senza conoscere dati riservati o chi ha inviato segnalazioni su di lui. Il numero di telefono serve per l’account e non compare nel profilo pubblico.
- **Presenza e stato online:** il check-in termina quando l’utente esce dal luogo o scade la presenza. Lo stato online si mostra soltanto se l’utente lo consente. Cancellare l’amicizia interrompe anche la condivisione della posizione esatta.


## 3. User story

Le user story descrivono cosa vogliono fare gli utenti attraverso il sito e perché quella funzione è utile. Ogni storia rimanda alla funzione con lo stesso numero.

### Accesso e primo utilizzo

**US01 (F01):** Come utente non registrato, voglio registrarmi e creare un profilo, per presentarmi e partecipare alle attività dell’app.

**US02 (F02):** Come utente, voglio accedere con telefono e password, per ritrovare il mio profilo e i miei contatti.

**US09 (F09):** Come visitatore, voglio capire dalla homepage come funziona HitMeUp, per decidere se voglio iscrivermi.

**US22 (F22):** Come utente non registrato, voglio leggere e accettare le regole prima di registrarmi, per sapere come utilizzare il servizio.

**US26 (F26):** Come utente, voglio verificare il mio numero con un codice, per dimostrare che il recapito indicato è mio.

**US27 (F27):** Come utente, voglio recuperare l’accesso se dimentico la password, per continuare a usare il mio account.

**US44 (F44):** Come visitatore, voglio consultare le domande frequenti, per capire le funzioni e risolvere i dubbi più comuni.

### Profilo e account

**US03 (F03):** Come utente, voglio aggiornare la mia presentazione e i miei hobby, per far vedere agli altri informazioni aggiornate.

**US25 (F25):** Come utente, voglio uscire dal mio account, per evitare che altre persone lo usino dal mio dispositivo.

**US28 (F28):** Come utente, voglio cambiare la password, per aggiornare la protezione del mio account.

**US29 (F29):** Come utente, voglio aggiornare e verificare il numero di telefono, per mantenere corretto il recapito per l’accesso.

**US30 (F30):** Come utente, voglio scegliere quali informazioni mostrare, per condividere solo ciò che desidero.

**US42 (F42):** Come utente, voglio cancellare il mio account, per smettere di utilizzare il servizio.

**US43 (F43):** Come utente sospeso, voglio chiedere una revisione della sospensione, per far controllare una decisione che ritengo sbagliata.

### Luoghi, ricerca e posizione

**US04 (F04):** Come utente, voglio indicare dove mi trovo con la posizione o il check-in, per cercare persone nel luogo giusto.

**US05 (F05):** Come utente, voglio vedere sulla mappa persone vicine con interessi comuni, per trovare qualcuno con cui condividere un’attività.

**US12 (F12):** Come utente, voglio scegliere se autorizzare il GPS e sapere come revocare il permesso, per controllare l’uso della mia posizione.

**US13 (F13):** Come utente, voglio accettare o rifiutare chi chiede la mia posizione esatta, per decidere con chi condividerla.

**US16 (F16):** Come utente, voglio nascondere temporaneamente la mia presenza, per usare l’account senza comparire sulla mappa.

**US17 (F17):** Come utente, voglio cercare per username, luogo o interesse, per trovare più facilmente un profilo compatibile.

**US37 (F37):** Come utente, voglio chiedere a un amico di condividere la posizione esatta, per trovarlo più facilmente se decide di accettare.

**US38 (F38):** Come utente, voglio interrompere la condivisione della posizione esatta, per tornare a tenerla privata quando voglio.

**US39 (F39):** Come utente, voglio leggere il profilo di una persona suggerita, per trovare un argomento con cui iniziare a parlare.

**US40 (F40):** Come utente, voglio terminare il check-in quando vado via, per non risultare ancora presente nel luogo.

### Saluti, chat e amicizie

**US06 (F06):** Come utente, voglio inviare un saluto, per far capire a una persona che vorrei conoscerla.

**US07 (F07):** Come utente, voglio scrivere nella chat dopo che il saluto è stato accettato, per iniziare una conversazione con il consenso dell’altra persona.

**US14 (F14):** Come utente, voglio gestire le richieste di amicizia, per aggiungere ai miei contatti solo le persone che scelgo.

**US15 (F15):** Come utente, voglio vedere i miei amici e chi risulta online, per sapere con chi posso parlare.

**US31 (F31):** Come utente, voglio scegliere quali notifiche ricevere, per evitare avvisi che non mi interessano.

**US32 (F32):** Come utente, voglio ritrovare gli avvisi ricevuti in un’unica pagina, per non perdere saluti e richieste.

**US33 (F33):** Come utente, voglio accettare o rifiutare un saluto, per decidere con chi iniziare una chat.

**US34 (F34):** Come utente, voglio silenziare una conversazione, per sospendere gli avvisi senza bloccare la persona.

**US35 (F35):** Come utente, voglio annullare una richiesta non ancora accettata, per ritirarla se cambio idea.

**US36 (F36):** Come utente, voglio rimuovere un contatto dagli amici, per gestire liberamente la mia lista.

### Sicurezza e moderazione

**US08 (F08):** Come utente, voglio segnalare o bloccare una persona, per interrompere contatti indesiderati e chiedere un controllo.

**US10 (F10):** Come amministratore, voglio aprire una dashboard di moderazione, per controllare i casi che richiedono un intervento.

**US11 (F11):** Come amministratore, voglio aggiungere o rimuovere categorie di hobby, per mantenere ordinati gli interessi disponibili.

**US18 (F18):** Come amministratore, voglio controllare e rimuovere contenuti inappropriati, per mantenere gli spazi dell’app utilizzabili.

**US19 (F19):** Come amministratore, voglio sospendere o bannare un account dopo un controllo, per intervenire sulle violazioni delle regole.

**US20 (F20):** Come amministratore, voglio consultare lo storico delle segnalazioni e degli interventi, per capire cosa è successo e quali decisioni sono state prese.

**US21 (F21):** Come amministratore, voglio inviare un avviso agli utenti, per comunicare informazioni importanti sull’app.

**US23 (F23):** Come amministratore, voglio che il sistema sospenda temporaneamente gli account che raggiungono la soglia prevista dopo i controlli, per rivedere il caso prima di una decisione definitiva.

**US24 (F24):** Come utente, voglio lasciare un feedback su un’interazione, per segnalare che il contatto non è stato rispettoso.

**US41 (F41):** Come utente, voglio sapere se una mia segnalazione è stata presa in carico, per seguire la richiesta senza vedere dati riservati.


## 4. Analisi SWOT di un competitor: BFF di Bumble

Abbiamo scelto **BFF di Bumble** perché è un competitor vicino all’idea di HitMeUp: si rivolge alle amicizie e permette di conoscere persone attraverso profili, interessi e posizione. Offre anche gruppi legati alle passioni condivise.

La SWOT distingue gli aspetti del prodotto dalle condizioni esterne. Le opportunità e le minacce qui sotto sono una nostra valutazione per il progetto scolastico, non dati economici dell’azienda.

| | Aspetti favorevoli | Aspetti sfavorevoli |
| --- | --- | --- |
| **Fattori interni** | **Punti di forza:** servizio dedicato alle amicizie; profili con interessi; ricerca legata alla posizione; gruppi per conoscere più persone con passioni comuni. | **Punti di debolezza:** serve un profilo completo prima di comparire o cercare persone nella sezione dedicata; il servizio non è disponibile in tutti i Paesi. Sono limiti di accesso da considerare per chi vuole iniziare a usarlo. |
| **Fattori esterni** | **Opportunità:** persone che cambiano città, scuola o lavoro e cercano nuovi contatti; possibilità di coinvolgere comunità locali e gruppi legati a un hobby. | **Minacce:** concorrenza di altre app e dei gruppi social già utilizzati; difficoltà ad attirare abbastanza utenti nella stessa zona; diffidenza verso i contatti con sconosciuti. |

### Cosa ci serve capire per HitMeUp

BFF usa già interessi e posizione: queste caratteristiche, da sole, non rendono nuova la nostra idea. Per HitMeUp vogliamo concentrarci sul luogo preciso e sulla disponibilità in quel momento, con un check-in facile da avviare e terminare. Per esempio, scoprire chi è nella stessa biblioteca e cerca compagnia per studiare.

La prima versione dovrà anche evitare di diventare troppo complicata. Le 44 funzioni rappresentano l’elenco completo: conviene iniziare da quelle essenziali e aggiungere le altre in seguito.


## 5. Analisi SWOT della webapp HitMeUp

Dopo aver analizzato un competitor, abbiamo valutato anche la nostra webapp. La SWOT ci aiuta a capire quali aspetti dell’idea possono funzionare, quali difficoltà dobbiamo affrontare e quali condizioni esterne possono favorire o ostacolare il progetto.

HitMeUp è ancora un progetto scolastico: i punti di forza riguardano le caratteristiche previste, da verificare con lo sviluppo e le prove con gli utenti. Le opportunità e le minacce sono possibilità da considerare, non risultati già dimostrati.

| | Aspetti favorevoli | Aspetti sfavorevoli |
| --- | --- | --- |
| **Fattori interni** | **Punti di forza (Strengths):** obiettivo chiaro, dedicato alle amicizie e alle attività dal vivo; ricerca basata su hobby, vicinanza e presenza nello stesso luogo; Wave e chat dopo l’accettazione, per facilitare il primo contatto; controlli previsti su visibilità, posizione, blocco e segnalazioni. | **Punti di debolezza (Weaknesses):** utilità legata alla presenza di abbastanza utenti attivi nello stesso luogo e momento; 44 funzioni previste, impegnative da sviluppare e provare in un progetto scolastico; necessità di gestire insieme mappa, chat e aggiornamenti della presenza; lavoro continuo per controllare le segnalazioni e verificare che i sistemi di reputazione non penalizzino utenti senza motivo. |
| **Fattori esterni** | **Opportunità (Opportunities):** persone che cambiano scuola o città e cercano nuove amicizie; possibili collaborazioni con biblioteche, università, palestre e associazioni; eventi locali in cui proporre l’app a persone già presenti nello stesso posto; passaparola tra studenti e gruppi con interessi comuni. | **Minacce (Threats):** concorrenza di piattaforme e gruppi social già conosciuti; diffidenza verso la condivisione della posizione e gli incontri con sconosciuti; tentativi di creare profili falsi, inviare messaggi indesiderati o abusare delle segnalazioni; possibili costi o limitazioni dei servizi esterni necessari per mappe e verifica tramite SMS. |

### Come usare questa analisi nel progetto

Per la prima versione vogliamo concentrarci sul percorso principale: creare un profilo, scegliere gli hobby, indicare la presenza in un luogo, trovare persone compatibili e inviare un Wave. La chat sarà disponibile dopo l’accettazione. I controlli di privacy, blocco e segnalazione dovranno accompagnare queste funzioni fin dall’inizio.

Una prima prova potrebbe svolgersi in una sola biblioteca o in un ambiente scolastico, coinvolgendo un piccolo gruppo nello stesso periodo. Questo ci permetterebbe di verificare se le persone trovano contatti utili e se capiscono facilmente come utilizzare l’app.

Durante la prova potremmo osservare quanti utenti completano il profilo, quanti trovano almeno una persona con hobby in comune, quanti Wave vengono accettati e quanti utenti tornano a usare il servizio. Anche i problemi segnalati e i tempi di gestione ci aiuterebbero a scegliere cosa migliorare prima di aggiungere altre funzioni.
