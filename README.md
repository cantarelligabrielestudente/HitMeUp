# HitMeUp

**Le passioni in comune diventano un motivo per conoscersi dal vivo.**

## 1. Cos'è il progetto

HitMeUp è una web app di socialità di prossimità: permette di scoprire persone vicine con cui condividere passioni e attività, come gaming, musica, sport o studio. L'obiettivo è favorire nuove amicizie e rendere più semplice iniziare una conversazione dal vivo.

L'utente crea il proprio profilo e inserisce i suoi hobby. Attraverso la geolocalizzazione del dispositivo, autorizzata dall'utente, oppure un check-in nel luogo in cui si trova, l'app individua altre persone presenti nelle vicinanze con interessi in comune. Una notifica può quindi offrire uno spunto per rompere il ghiaccio e conoscersi.

Per esempio, una persona che si trova in biblioteca e cerca compagnia per studiare può scoprire un altro utente presente nello stesso luogo e interessato allo studio di gruppo.

### Il problema che vuole risolvere

HitMeUp nasce per affrontare due difficoltà:

- **Isolamento e timidezza:** utilizzare i social non significa sempre sentirsi parte di un gruppo. Incontrare persone nuove dal vivo può creare imbarazzo, soprattutto quando manca un argomento con cui iniziare.
- **Difficoltà a trovare compagni di hobby:** chi vuole fare sport, studiare o condividere una passione spesso non sa quali persone attorno a sé abbiano gli stessi interessi.

L'app vuole offrire un primo punto di contatto: una passione condivisa può diventare un motivo concreto per fare due parole e, nel tempo, costruire un'amicizia.

### A chi si rivolge

Il progetto si rivolge alle persone che desiderano ampliare il proprio giro sociale, con particolare attenzione ai giovani e agli studenti. Può essere utile a chi è timido, a chi si è trasferito in una nuova città o a chi cerca compagnia per un'attività.

### L'idea che lo distingue

Il centro del progetto è l'amicizia basata su **interessi comuni, vicinanza e spontaneità**. HitMeUp non nasce principalmente per gli incontri romantici: vuole aiutare a conoscere persone con cui condividere qualcosa nella vita quotidiana, anche senza organizzare un evento in anticipo.

### Mission

Rendere facile e naturale fare nuove amicizie dal vivo, aiutando le persone a superare l'imbarazzo iniziale e a entrare in contatto con chi condivide le stesse passioni.

### Vision

Diventare un punto di riferimento per i giovani contro l'isolamento sociale, trasformando spazi di studio, locali e luoghi della città in comunità vive, dove le passioni condivise favoriscono nuove amicizie spontanee.

### Tecnologie previste

- **HTML:** struttura delle pagine.
- **CSS:** stile grafico e adattamento dell'interfaccia ai diversi schermi.
- **JavaScript:** interazioni e comportamento dell'interfaccia.

La tecnologia per il backend, il database e la gestione delle comunicazioni tra gli utenti è ancora da definire. Questa parte dovrà gestire gli account, salvare i profili e gli interessi e individuare le corrispondenze tra le persone presenti nelle vicinanze.

## 2. Tabella

*Sezione da completare.*

## 3. User story

Le user story descrivono ciò che una persona vuole fare nell'app e il beneficio che si aspetta. Seguono la formula: **«Come [tipo di utente], voglio [azione], per [beneficio]»**.

Le storie seguenti rappresentano le funzionalità proposte per HitMeUp. Per ciascuna è indicato un criterio di accettazione, cioè una condizione verificabile per capire se funziona come previsto.

### US01 — Registrazione

Come visitatore, voglio creare un account per avere un profilo personale su HitMeUp.

**Criterio di accettazione:** inserendo dati validi e non già associati a un account, posso completare la registrazione; se ci sono errori, l'app mi indica cosa correggere.

### US02 — Accesso

Come utente registrato, voglio accedere al mio account per ritrovare il mio profilo e le mie preferenze.

**Criterio di accettazione:** con credenziali corrette accedo al mio account; con credenziali errate l'accesso viene rifiutato.

### US03 — Profilo personale

Come utente, voglio inserire e modificare la mia presentazione per far capire agli altri chi sono.

**Criterio di accettazione:** dopo aver salvato una modifica, le informazioni aggiornate compaiono nel mio profilo anche quando lo riapro.

### US04 — Interessi

Come utente, voglio selezionare e aggiornare i miei hobby per trovare persone con passioni simili alle mie.

**Criterio di accettazione:** posso aggiungere o rimuovere interessi; dopo il salvataggio, l'app utilizza la selezione aggiornata per cercare corrispondenze.

### US05 — Geolocalizzazione

Come utente, voglio scegliere se autorizzare la geolocalizzazione per cercare persone vicine utilizzando la posizione del dispositivo.

**Criterio di accettazione:** la posizione viene utilizzata solo dopo il mio consenso; se lo nego, posso comunque usare il check-in manuale.

### US06 — Check-in manuale

Come utente, voglio effettuare il check-in in un luogo per indicare dove mi trovo senza utilizzare la geolocalizzazione.

**Criterio di accettazione:** dopo aver selezionato e confermato un luogo, la ricerca considera quel luogo come riferimento; posso annullare il check-in.

### US07 — Persone con interessi comuni

Come utente, voglio vedere persone vicine che condividono almeno un mio interesse per trovare qualcuno con cui iniziare una conversazione.

**Criterio di accettazione:** ogni risultato rispetta l'area di ricerca prevista e mostra almeno un interesse in comune; se non ci sono corrispondenze, l'app lo comunica chiaramente.

### US08 — Notifiche

Come utente, voglio poter ricevere un avviso quando viene rilevata una nuova persona compatibile nelle vicinanze per accorgermi di un'occasione per fare amicizia.

**Criterio di accettazione:** con gli avvisi attivi, una nuova corrispondenza genera una notifica nell'app; posso disattivarli dalle impostazioni.

### US09 — Consultazione di un profilo

Come utente, voglio leggere la presentazione e gli interessi pubblici di una persona suggerita per trovare uno spunto con cui rompere il ghiaccio.

**Criterio di accettazione:** aprendo un risultato, vedo la presentazione, gli interessi condivisi e solo le informazioni che quella persona ha scelto di rendere visibili.

### US10 — Visibilità

Come utente, voglio poter sospendere la mia visibilità per decidere quando essere disponibile a nuove conoscenze.

**Criterio di accettazione:** quando disattivo la visibilità, il mio profilo non compare nelle nuove ricerche degli altri utenti; posso riattivarla.

### US11 — Blocco di un utente

Come utente, voglio bloccare una persona con cui non desidero avere contatti per utilizzare l'app con maggiore tranquillità.

**Criterio di accettazione:** dopo il blocco, i due profili non vengono più suggeriti l'uno all'altro e non generano notifiche reciproche.

### US12 — Segnalazione

Come utente, voglio segnalare un profilo o un comportamento inappropriato per contribuire a rendere la comunità più sicura.

**Criterio di accettazione:** posso indicare un motivo e inviare la segnalazione; il sistema la registra e conferma l'invio.

## 4. Requisiti software

*Sezione da completare: requisiti funzionali, non funzionali e di dominio.*

## 5. Analisi SWOT

L'analisi SWOT aiuta a valutare i vantaggi e i limiti del progetto, distinguendo gli aspetti interni dalle condizioni esterne. Quella seguente è una prima valutazione progettuale, da verificare durante lo sviluppo e con il confronto con gli utenti.

| | Aspetti favorevoli | Aspetti sfavorevoli |
| --- | --- | --- |
| **Fattori interni** | **Punti di forza — Strengths**<br>• Obiettivo chiaro: favorire amicizie dal vivo.<br>• Interessi comuni come spunto per iniziare una conversazione.<br>• Geolocalizzazione e check-in come modalità alternative.<br>• Idea adatta a situazioni quotidiane, come studio e tempo libero. | **Punti di debolezza — Weaknesses**<br>• Competenze sul backend e sulla comunicazione tra utenti ancora da sviluppare.<br>• Risorse e tempi limitati di un progetto scolastico.<br>• Gestione delicata di posizione, visibilità e dati personali.<br>• Necessità di organizzare la gestione delle segnalazioni. |
| **Fattori esterni** | **Opportunità — Opportunities**<br>• Possibilità di coinvolgere scuole, università, biblioteche e associazioni.<br>• Occasioni d'uso per chi arriva in una nuova città o in un nuovo ambiente.<br>• Possibili collaborazioni con luoghi dedicati a sport, studio e tempo libero.<br>• Possibilità di far conoscere l'app attraverso gruppi e comunità locali. | **Minacce — Threats**<br>• Concorrenza di social network, app per conoscere persone e piattaforme di eventi.<br>• Pochi utenti attivi nella stessa zona possono limitare le occasioni di incontro.<br>• Diffidenza verso la condivisione della posizione e gli incontri con sconosciuti.<br>• Profili falsi o comportamenti scorretti possono ridurre la fiducia nell'app. |

### Come utilizzare questa analisi

Una possibile strategia iniziale è sperimentare HitMeUp in un ambiente circoscritto, come una comunità scolastica, per raccogliere osservazioni e verificare se gli interessi comuni aiutano davvero a iniziare una conversazione. Nello sviluppo sarà necessario dedicare attenzione anche al controllo della visibilità, alla gestione della posizione e agli strumenti di blocco e segnalazione.

## 6. UML — Diagramma dei casi d'uso

*Sezione da completare.*
