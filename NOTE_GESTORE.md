# Note per Mattia — completamento delle bozze

Verifica documentale del 12 settembre 2026. Queste note non sono parte dei termini degli utenti.

## Informazioni confermate

- Gestore e titolare dichiarato: Mattia Dossena.
- Contatto: dob.dossenixbots@gmail.com.
- Hosting dichiarato: Wispbyte Premium; nodo e Paese dell'istanza ancora da verificare.
- Progetto gratuito di roleplay; uso attuale in una community Discord, con accesso operativo ristretto.
- Repository pubblico dedicato: `Dossenix/-D.O.B.-Giurisprduenza-Legal-Informations`.

## Passaggi ancora necessari

1. Verificare nel pannello o con l'assistenza Wispbyte il Paese del nodo Premium assegnato, backup, cifratura a riposo, accordo sul trattamento e garanzie degli eventuali trasferimenti internazionali. La pagina commerciale consultata indica Canada per il bot hosting, ma non prova la posizione dell'istanza. Verificare anche copie locali e gestione delle email in Gmail.
2. Validare la base giuridica proposta: documentare il bilanciamento per il legittimo interesse, inclusi dati inseriti da altri e utenti minori. Se il trattamento concreto richiede una base diversa, aggiornare l'informativa prima di adottarla.
3. Stabilire periodi o criteri di conservazione giustificati e applicabili; implementare o organizzare la revisione manuale. Non promettere che tutti i dati spariscono dopo 10 o 14 giorni.
4. Definire una procedura completa di accesso/cancellazione: identificare record, servizi Governo, audit, messaggi, foto, prove, backup e copie manuali; impedire che un ripristino reintroduca dati cancellati. Il comando attuale crea anche un backup prima della cancellazione e non copre tutte le tabelle Governo.
5. Verificare cifratura a riposo della macchina/database: SQLite non è cifrato dal codice. La protezione DPAPI dei backup su Windows non prova la cifratura del database principale e non è trasferibile automaticamente a Linux. I termini Discord richiedono cifratura a riposo.
6. Coinvolgere il genitore/tutore per l'accordo richiesto dai termini sviluppatori, senza dichiarare nei documenti un accordo non verificato e senza pubblicare suoi dati non necessari. Questo non lo rende automaticamente titolare.
7. Controllare che i dati identificativi e le prove siano effettivamente di gioco. Gli ID Discord restano dati personali anche se il resto è inventato.
8. Completare i campi aperti, rivedere i testi, sostituire lo stato di bozza con data di adozione e rendere l'informativa accessibile dal bot e dai canali dove si raccolgono dati, anche per le persone registrate dagli operatori.

## Pubblicazione

I file Markdown sono leggibili pubblicamente su GitHub una volta caricati. Non presentare le bozze incomplete come informative definitive nel Developer Portal.

URL dei documenti sul branch `main` (disponibili solo dopo il caricamento):

- [ToS](https://github.com/Dossenix/-D.O.B.-Giurisprduenza-Legal-Informations/blob/main/TERMS_OF_SERVICE.md)
- [Privacy](https://github.com/Dossenix/-D.O.B.-Giurisprduenza-Legal-Informations/blob/main/PRIVACY_POLICY.md)

Si possono successivamente pubblicare pagine dedicate con GitHub Pages e usare quei collegamenti nel portale. La sola pubblicazione non garantisce l'approvazione Discord. Nessuna procedura di verifica del bot è stata eseguita nella preparazione dei testi.

## Riscontri nel codice locale

| Punto | File esaminati |
| --- | --- |
| Dati identikit, audit e cancellazione parziale | `identikit_core/database.py`, `cogs/maintenance.py` |
| Dati servizi, compensi e allegati | `governo/storage.py`, `cogs/governo.py` |
| Intervalli backup predefiniti | `config.py` |
| Protezione backup Windows | `identikit_core/backup_security.py` |
| Accesso messaggi e rotazione log | `main.py` |

Sono stati esaminati codice e documentazione, senza leggere token, database degli utenti o allegati. I valori predefiniti non certificano la configurazione dell'istanza in produzione.

## Fonti normative e contrattuali

- [GDPR, testo ufficiale](https://eur-lex.europa.eu/legal-content/IT/TXT/?uri=CELEX:32016R0679): in particolare artt. 5, 6, 12–22, 32 e 44 e seguenti.
- [Discord Developer Terms](https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service): sezioni 1 e 5.
- [Privacy Discord](https://discord.com/privacy).
- [Privacy Google](https://policies.google.com/privacy).
- [Offerta Wispbyte](https://wispbyte.com/store), consultata per la localizzazione pubblicizzata, senza accesso al pannello del cliente.

I testi sono bozze preparatorie e richiedono verifica rispetto alla gestione effettiva; non sono una certificazione di conformità.
