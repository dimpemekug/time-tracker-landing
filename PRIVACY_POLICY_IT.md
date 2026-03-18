# Informativa sulla Privacy di Time Tracker

Ultimo aggiornamento: 2026-03-17

La presente Informativa sulla Privacy descrive come `Time Tracker` gestisce i dati.

## Sintesi

`Time Tracker` e' progettata per funzionare principalmente in locale sul dispositivo dell'utente.

- Non e' richiesto alcun account
- Non vengono utilizzati strumenti di analytics
- Non vengono utilizzati SDK pubblicitari
- Non viene effettuato alcun tracciamento dell'utente
- Lo sviluppatore non raccoglie dati personali tramite server remoti dell'app
- Non e' presente sincronizzazione cloud nel progetto attuale

## Dati trattati dall'app

L'app consente all'utente di salvare e gestire localmente informazioni relative al tracciamento del tempo e ai progetti, tra cui:

- dati dei progetti inseriti dall'utente, come nome, colore identificativo, note, date di inizio e fine, stato di archivio e impostazioni di fatturazione
- dati di fatturazione opzionali associati ai progetti, come tariffa oraria e percentuale IVA
- dati delle attivita registrate, come titolo, progetto associato, data e ora di inizio, data e ora di fine, durata, eventuali note e indicazione di totale giornaliero
- dati del timer Pomodoro, come attivita personalizzate, progetto selezionato, preferenze di notifica e stato locale del timer
- preferenze dell'app, come lingua, tema, colore principale, impostazioni di interfaccia, onboarding e altre configurazioni locali
- dati di esempio eventualmente caricati dall'utente durante l'onboarding o tramite reset del database
- file di backup in formato `JSON` generati o importati dall'utente
- file di esportazione in formato `PDF` o `CSV` generati dall'utente dalla dashboard

Queste informazioni vengono salvate localmente sul dispositivo per consentire il funzionamento dell'app.

## Raccolta dei dati

Lo sviluppatore non raccoglie, non riceve, non trasmette, non vende e non condivide automaticamente dati dell'utente tramite server remoti attraverso l'app.

I dati restano normalmente nel database locale dell'app e nello storage locale o temporaneo del dispositivo usato per funzioni di backup, esportazione e condivisione.

Se l'utente sceglie di esportare, salvare, condividere o importare un file, tale azione viene avviata manualmente dall'utente tramite funzionalita dell'app e del sistema operativo. Eventuali trasferimenti successivi dipendono esclusivamente dalla destinazione o dal servizio scelto dall'utente.

## Permessi del dispositivo

`Time Tracker` puo richiedere l'accesso a:

- notifiche locali, per mostrare stato e controlli del timer Pomodoro
- file e documenti del sistema, per importare backup `JSON` o salvare file esportati `JSON`, `PDF` e `CSV`
- foto o libreria del dispositivo su alcune piattaforme, solo se l'utente seleziona tramite il file picker un file precedentemente salvato nella libreria Foto

Alla data del 2026-03-17, il codice dell'app non mostra flussi applicativi attivi che raccolgano posizione, contatti, microfono o fotocamera. Le notifiche usate dall'app sono locali e servono esclusivamente al funzionamento del timer Pomodoro.

## Condivisione dei dati

`Time Tracker` non condivide dati dell'utente con lo sviluppatore o con terze parti per finalita di analytics, pubblicita, profilazione o tracciamento.

L'unica eccezione e' il caso in cui l'utente esporti o condivida esplicitamente un backup o un report tramite gli strumenti di condivisione o di salvataggio della piattaforma. In tal caso, il file viene inviato o memorizzato solo verso la destinazione scelta dall'utente.

## Conservazione dei dati

I dati dell'app vengono salvati localmente sul dispositivo usando lo storage applicativo locale, tra cui:

- database locale `SQLite` per progetti, attivita e impostazioni
- preferenze locali nel database dell'app per configurazioni e stato del timer Pomodoro
- directory temporanee del dispositivo per alcune operazioni di condivisione o generazione file
- posizioni di salvataggio scelte dall'utente per backup `JSON` e report `PDF` o `CSV`

I file temporanei creati per supportare esportazione o condivisione dovrebbero essere rimossi dall'app al termine dell'operazione, ma i file salvati o condivisi manualmente dall'utente restano soggetti alle regole della destinazione scelta dall'utente.

## Conservazione e cancellazione

I dati inseriti nell'app restano sul dispositivo finche l'utente non:

- modifica o elimina manualmente progetti e attivita
- importa un backup che sostituisce i dati locali correnti
- cancella progetti e attivita dal database locale
- esegue il reset del database, che puo anche ripristinare dati di esempio
- disinstalla l'app, nei limiti del comportamento del sistema operativo
- elimina manualmente i file esportati o condivisi dalle rispettive posizioni di archiviazione

Poiche lo sviluppatore non riceve ne' conserva i dati dell'app su server remoti, non puo accedere, correggere o cancellare i dati locali dell'utente per suo conto.

## Minori

`Time Tracker` non e' rivolta specificamente ai minori e non raccoglie consapevolmente dati personali di minori.

## Sicurezza

L'app si affida ai meccanismi di sicurezza forniti dal sistema operativo e dallo storage locale dell'app. Tuttavia, nessun metodo di archiviazione su dispositivo o di trasferimento file puo essere garantito come completamente sicuro, in particolare dopo che l'utente esporta, salva o condivide un file al di fuori dell'app.

## Modifiche a questa informativa

La presente Informativa sulla Privacy puo essere aggiornata nelle future versioni dell'app. L'ultima versione dovrebbe essere resa disponibile all'URL pubblico della privacy policy usato in App Store Connect e Google Play Console.

## Contatti

Sviluppatore / Editore: `dimpemekug`

Email supporto: `dimpemekug.app@gmail.com`
