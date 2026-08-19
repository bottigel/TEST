# Informativa sul trattamento dei dati personali

Applicazione **Brain Controller v4** (`com.oms.braincontrollerv4`) — versione del documento 1.0, ultimo aggiornamento 19 agosto 2026.

Questa informativa descrive quali dati tratta l'applicazione Brain Controller v4 per Android, con quali finalità e per quanto tempo, ai sensi degli articoli 13 e 14 del Regolamento (UE) 2016/679 (GDPR).

## 1. Titolare del trattamento

Luca Bottigella Email di contatto: luca.bottigella@gmail.com

Per qualunque richiesta relativa ai dati trattati dall'applicazione è possibile scrivere all'indirizzo indicato.

## 2. A chi è destinata l'applicazione

Brain Controller v4 è uno strumento di lavoro destinato a personale tecnico: manutentori, collaudatori, centri di assistenza autorizzati e utilizzatori professionali delle macchine reggiatrici dotate di centralina Brain o Brain AXIS. Non è destinata al pubblico generale né a minori di 18 anni. Senza una macchina compatibile raggiungibile via Bluetooth l'applicazione non ha funzioni operative.

## 3. Dati trattati

| Categoria | Contenuto | Finalità | Obbligatorio |
|---|---|---|---|
| Credenziali di accesso | Nome utente e ruolo assegnato. La password non viene memorizzata in chiaro. | Autenticazione e determinazione delle funzioni consentite al ruolo. | Sì |
| Identificativo del dispositivo | Identificativo tecnico del telefono o tablet su cui l'app è installata. | Distinguere da quale dispositivo è stata eseguita un'operazione sulla macchina. | Sì |
| Registro delle attività | Operazioni di modifica eseguite sulla macchina: data e ora, utente, ruolo, parametro modificato, valore precedente e successivo, esito. Vi rientrano anche accesso, disconnessione e tentativi di operazione negati. | Tracciabilità tecnica degli interventi sulla macchina, ricostruzione dei guasti, sicurezza. | Sì |
| Dati di funzionamento della macchina | Contatori di produzione e di consumo, numeri di serie delle teste di reggiatura, andamenti storici letti dalla centralina o dal tag NFC della testa. | Manutenzione predittiva e diagnostica della macchina. | Sì |
| Posizione approssimativa | Coordinate approssimative (precisione dell'ordine del chilometro) rilevate al momento della lettura dei dati della macchina. | Sapere in quale stabilimento o cantiere si trova la macchina a cui i dati si riferiscono. | **No** |

## 4. Dove finiscono i dati

**I dati restano sul dispositivo.** Vengono salvati in un archivio locale interno all'applicazione e non vengono trasmessi ad alcun server, né dal titolare né da terzi. Non sono previsti backup automatici su servizi cloud: l'applicazione ha il backup di sistema disattivato.

L'unica connessione a Internet effettuata dall'applicazione è il download dei manuali e dei video di manutenzione, che avviene tramite connessione cifrata (HTTPS) da un archivio pubblico ospitato su GitHub. In occasione di quel download il fornitore del servizio di hosting può registrare, nei propri log tecnici, l'indirizzo IP da cui la richiesta proviene. Con quella richiesta non viene inviato alcun dato dell'utente, della macchina o della posizione.

## 5. Permessi richiesti

| Permesso | Perché serve |
|---|---|
| Dispositivi nelle vicinanze (Bluetooth) | Trovare e collegarsi alla centralina della macchina. Dichiarato esplicitamente come non utilizzabile per ricavare la posizione. |
| Posizione approssimativa | Facoltativo. Associare i dati della macchina al luogo in cui la macchina si trova. |
| NFC | Leggere il tag della testa di reggiatura, funzione utilizzabile anche a macchina spenta. |
| Internet | Scaricare manuali e video di manutenzione. |

## 6. Cosa l'applicazione non fa

- Non contiene pubblicità.

- Non contiene strumenti di analisi statistica, tracciamento o profilazione di terze parti.

- Non cede né vende dati a terzi.

- Non effettua decisioni automatizzate che producano effetti giuridici sulle persone.

- Non raccoglie rubrica, fotografie, microfono, fotocamera o cronologia di navigazione.

## 7. Base giuridica

Il trattamento si fonda sul **legittimo interesse** (art. 6.1.f GDPR) a garantire la tracciabilità tecnica degli interventi eseguiti su macchinari industriali, la ricostruzione dei guasti e la sicurezza di funzionamento. La rilevazione della posizione approssimativa avviene solo previo consenso esplicito prestato tramite il permesso di sistema Android, revocabile in qualsiasi momento dalle impostazioni del dispositivo.

## 8. Conservazione

I dati restano sul dispositivo finché l'applicazione è installata. La **disinstallazione dell'applicazione elimina definitivamente** l'archivio locale, registro delle attività compreso. È inoltre prevista una cancellazione automatica delle registrazioni più vecchie di dodici mesi.

## 9. Diritti dell'interessato

Agli interessati spettano i diritti previsti dagli articoli da 15 a 22 del GDPR: accesso, rettifica, cancellazione, limitazione, opposizione e portabilità. Poiché i dati risiedono unicamente sul dispositivo, le richieste possono essere soddisfatte direttamente sul dispositivo stesso; per assistenza è possibile scrivere all'indirizzo indicato al punto 1. È inoltre riconosciuto il diritto di proporre reclamo al Garante per la protezione dei dati personali ([garanteprivacy.it](https://www.garanteprivacy.it)).

## 10. Modifiche

Questa informativa può essere aggiornata. È in valutazione l'attivazione futura di una piattaforma cloud per la raccolta centralizzata dei dati di manutenzione: prima che una simile funzione venga attivata questa informativa sarà aggiornata e agli utenti sarà data specifica evidenza della modifica all'interno dell'applicazione.

# Privacy Policy

**Brain Controller v4** (`com.oms.braincontrollerv4`) — document version 1.0, last updated 19 August 2026.

## 1. Data controller

Luca Bottigella — luca.bottigella@gmail.com

## 2. Who the app is for

Brain Controller v4 is a professional service tool for technicians, commissioning staff and authorised service centres operating industrial strapping machines fitted with a Brain or Brain AXIS controller. It is not intended for the general public or for users under 18. Without a compatible machine in Bluetooth range the app has no usable functions.

## 3. Data processed

- **Login credentials** — user name and assigned role. Passwords are not stored in clear text. Purpose: authentication and role-based access.

- **Device identifier** — a technical identifier of the phone or tablet. Purpose: identifying which device performed an operation on the machine.

- **Activity log** — write operations performed on the machine: timestamp, user, role, parameter changed, previous and new value, outcome; plus login, logout and denied attempts. Purpose: technical traceability of maintenance work, fault reconstruction, security.

- **Machine operating data** — production and consumption counters, strapping head serial numbers, historical trends read from the controller or from the head NFC tag. Purpose: predictive maintenance and diagnostics.

- **Approximate location** — optional, kilometre-level accuracy, recorded when machine data is read. Purpose: knowing which site the machine data belongs to.

Location is attached to *machine data*, never to user operations: the location field in the activity log is always empty. The location permission is optional; if denied, the app works normally and data is stored without location. No background location collection takes place.

## 4. Where the data goes

Data stays on the device, in the app's local storage, and is not transmitted to any server. System backup is disabled, so no automatic cloud copy is made. The app's only internet activity is downloading maintenance manuals and videos over HTTPS from a public repository hosted on GitHub; that hosting provider may record the requesting IP address in its technical logs. No user, machine or location data is sent with those requests.

## 5. Permissions

- **Nearby devices (Bluetooth)** — finding and connecting to the machine controller; explicitly declared as never used to derive location.

- **Approximate location** — optional; associating machine data with the site where the machine is.

- **NFC** — reading the strapping head tag, which also works with the machine powered off.

- **Internet** — downloading maintenance manuals and videos.

## 6. What the app does not do

No advertising, no third-party analytics or tracking, no profiling, no sale or disclosure of data to third parties, no automated decision-making with legal effects, no access to contacts, photos, microphone, camera or browsing history.

## 7. Legal basis

Legitimate interest (Art. 6(1)(f) GDPR) in ensuring technical traceability of work carried out on industrial machinery, fault reconstruction and operational safety. Approximate location is collected only after explicit consent given through the Android system permission, which can be withdrawn at any time in device settings.

## 8. Retention

Data remains on the device for as long as the app is installed. **Uninstalling the app permanently deletes** the local storage, including the activity log. Records older than twelve months are deleted automatically.

## 9. Your rights

Rights under Articles 15 to 22 GDPR apply: access, rectification, erasure, restriction, objection and portability. As data resides only on the device, requests can be satisfied on the device itself; for assistance write to the address in section 1. You also have the right to lodge a complaint with the Italian Data Protection Authority (garanteprivacy.it).

## 10. Changes

This policy may be updated. A future cloud platform for centralised maintenance data collection is under evaluation; before any such feature is enabled this policy will be updated and users will be notified in the app.