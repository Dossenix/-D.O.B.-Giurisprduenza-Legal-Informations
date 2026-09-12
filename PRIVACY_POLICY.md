# Informativa privacy — D.O.B. Bot Giurisprudenza

**Bozza del 12 settembre 2026 — da completare prima dell'adozione.** Le parti indicate come da completare non sono informazioni già verificate.

## 1. Titolare e ambito

Il titolare del trattamento relativo al bot è **Mattia Dossena**. Per domande o richieste sui dati: **dob.dossenixbots@gmail.com**.

L'informativa riguarda i dati trattati dal bot nelle attività di roleplay, inclusi quelli inseriti dagli operatori su altri giocatori. Non sostituisce l'informativa di Discord o quelle relative ad altre attività del server.

## 2. Dati e provenienza

Il bot tratta, secondo le funzioni utilizzate:

- identificativi Discord di utenti, server, ruoli, canali, messaggi e interazioni; nomi visualizzati e associazioni tra account e personaggi;
- campi dei comandi, moduli e contenuti necessari ai comandi testuali; riferimenti a messaggi utilizzati per pubblicazione e recupero;
- dati dei personaggi: nome, cognome, data di nascita di gioco, Citizen ID, immagini, incarichi, stato, note e avvertimenti;
- documenti e registrazioni di roleplay, testi dei fatti, partecipanti, allegati e prove di gioco, importi virtuali, compensi e storico delle operazioni;
- metadati tecnici, errori e registri delle modifiche, con autore e data; copie di sicurezza del database;
- indirizzo email e contenuto delle richieste inviate al contatto privacy.

I dati provengono dalle API di Discord, dagli utenti e dagli operatori autorizzati. L'accesso al contenuto dei messaggi è abilitato per le funzioni del bot; ciò non significa che tutte le conversazioni del server vengano archiviate. Il codice esaminato non implementa una raccolta generalizzata della cronologia del server.

I campi relativi a identità, vicende giudiziarie e pagamenti sono destinati esclusivamente alla finzione. Non inserire dati sensibili reali o documenti d'identità. I dati di gioco collegati a un account identificabile possono comunque essere dati personali.

## 3. Finalità e basi giuridiche

Le finalità sono fornire le funzioni richieste, associare le operazioni agli utenti autorizzati, mantenere registri di gioco coerenti, gestire errori e abusi e rispondere alle richieste sui dati.

**Impostazione proposta, da validare prima dell'adozione:** il legittimo interesse del titolare e della community a organizzare il roleplay e proteggere il servizio, previa verifica di necessità e bilanciamento con i diritti degli interessati, soprattutto minori. Gli adempimenti imposti dalla legge si fondano sull'obbligo legale applicabile. Non si presume che ogni giocatore abbia concluso un contratto con il gestore né che usare il bot equivalga a prestare consenso.

Il mancato conferimento dei dati indispensabili impedisce la relativa funzione; non è necessario compilare campi facoltativi non pertinenti. Il bot effettua calcoli e controlli di permessi per il gioco; non è destinato a decisioni automatizzate con effetti giuridici o analogamente significativi nella vita reale.

## 4. Destinatari, luoghi e fornitori

I dati sono accessibili al titolare e ai soggetti effettivamente autorizzati alla gestione. Documenti e allegati vengono inviati nei canali operativi, personali o di archivio configurati: possono vederli le persone che hanno accesso a tali canali. Un canale accessibile a molti membri può rendere visibili anche i risultati del bot a quei membri.

Discord tratta messaggi, allegati e altri dati sulla propria infrastruttura secondo la propria [Privacy Policy](https://discord.com/privacy). Il contatto email utilizza Gmail, servizio di Google, secondo le condizioni e la [Privacy Policy di Google](https://policies.google.com/privacy).

Il bot è ospitato su **Wispbyte, piano Premium**, che fornisce l'infrastruttura di esecuzione e conservazione dei file del bot. Il database viene salvato sulla macchina che esegue il bot; i file caricati nei canali sono conservati anche da Discord.

**Da completare:** Paese del nodo effettivamente assegnato, ubicazione dei backup e di eventuali copie locali, soggetti con accesso all'infrastruttura e accordi sul trattamento con il provider. La [pagina commerciale di Wispbyte](https://wispbyte.com/store) indica il Canada per l'offerta di bot hosting consultata; questo non conferma da solo la posizione dell'istanza del bot.

**Da verificare prima dell'adozione:** eventuali trasferimenti fuori dallo SEE e garanzie applicabili a ciascun fornitore, indicando come ottenerne copia. Non si presume che tutti i dati restino in Italia o nell'Unione europea.

Non sono previste vendita dei dati, pubblicità personalizzata o utilizzo per addestrare modelli di intelligenza artificiale. Nel codice esaminato non risultano integrazioni pubblicitarie o servizi di IA.

## 5. Conservazione

La configurazione e il codice esaminati prevedono:

| Categoria | Funzionamento attuale |
| --- | --- |
| Allegati archiviati dal modulo Governo | Eliminazione dei messaggi d'archivio dopo 10 giorni, con controllo ogni 10 minuti mentre il bot è online. Interruzioni o errori di permessi possono ritardarla. Non comprende tutte le copie pubblicate. |
| Foto e prove degli identikit | Non rientrano nella scadenza di 10 giorni. Sono gestite con gli identikit e le procedure di cancellazione. |
| Identikit, documenti, storico e audit | Non hanno una cancellazione generale automatica a scadenza. L'eventuale soglia per gli identikit inattivi genera una segnalazione per verifica. |
| Backup automatici | Valori predefiniti: uno ogni 24 ore e conservazione delle ultime 14 copie riconosciute dalla rotazione. È un limite numerico, non una garanzia di cancellazione entro 14 giorni; copie manuali o fuori dallo schema richiedono gestione separata. |
| Log tecnici | Rotazione per dimensione: file corrente e fino a cinque archivi da circa 5 MiB ciascuno; nessuna scadenza temporale automatica. |

La scadenza di validità di un documento di gioco, la revoca, il reset di un report o l'uscita dal server non equivalgono alla cancellazione dei dati. Le copie scaricate da altri utenti non sono eliminate automaticamente dal bot.

**Da completare prima dell'adozione:** termini o criteri operativi limitati alla necessità per identikit inattivi, storico, audit, log, email e copie manuali, con procedura di revisione e cancellazione. Il funzionamento descritto non giustifica una conservazione indefinita. I dati non più necessari e quelli oggetto di richieste fondate devono essere eliminati tempestivamente secondo gli obblighi applicabili, anche alla cessazione del bot.

## 6. Richieste e diritti

Scrivere a **dob.dossenixbots@gmail.com**, indicando il proprio ID Discord e la richiesta: accesso, rettifica, cancellazione, limitazione, opposizione o portabilità nei casi previsti. È possibile esercitare questi diritti anche senza usare i comandi del bot. Non inviare password o documenti d'identità nella richiesta iniziale; eventuali verifiche saranno proporzionate.

La risposta è dovuta di regola entro un mese, salvo proroga motivata nei casi consentiti. L'eliminazione può richiedere interventi su database, messaggi, allegati, audit e backup: il solo comando di cancellazione identikit non assicura la rimozione da ogni archivio. Eventuali dati conservati per un obbligo applicabile e relative ragioni saranno comunicati all'interessato.

È possibile presentare reclamo al [Garante per la protezione dei dati personali](https://www.garanteprivacy.it/) o all'autorità competente nel proprio Stato. Quando il trattamento si basa sul consenso, questo può essere revocato senza pregiudicare la liceità del trattamento precedente.

## 7. Sicurezza e aggiornamenti

Il bot utilizza controlli di accesso basati sui ruoli, registrazione delle operazioni e backup. Queste misure non garantiscono l'assenza di incidenti. **Da verificare:** protezione della macchina, cifratura dei dati a riposo e dei backup nell'ambiente effettivo. Non si dichiara una cifratura integrale già verificata.

Le modifiche sostanziali saranno comunicate nel server e riportate in questa pagina. Per segnalazioni sulla riservatezza usare il contatto del titolare.
