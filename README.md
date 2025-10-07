# 🛡️ Progetto EGESIA 

## Browser Open Source Dedicato agli operatori sanitari del Servizio Sanitario Nazionale (SSN)

Referente progetto: Marco Pingitore - E-mail: marco@marcopingitore.it

<p align="center">
  <img src="assets/logo_egesia.png" alt="Logo Progetto Egesia - SSNavigator" width="250"/>
  <br>
  <i>La piattaforma di navigazione sicura per l'operatore sanitario nel SSN.</i>
</p>

---

## 💡 Visione e Missione

Il progetto **EGESIA** mira alla progettazione e realizzazione di un **browser open source** concepito come un **punto di accesso unico e centralizzato** per tutti gli operatori e professionisti del Servizio Sanitario Nazionale (SSN) e dei Servizi Sanitari Regionali (SSR). Il nome "Egesia" evoca l'idea di "guida" o "conduttore", riflettendo la nostra missione di guidare gli utenti attraverso la complessità del panorama sanitario digitale.

L'obiettivo è superare l'attuale frammentazione dei sistemi sanitari digitali , fornendo un'esperienza utente unificata, sicura e in tempo reale.

**EGESIA non è un semplice browser, ma un centro di controllo e un hub interoperabile**. Attraverso un'**unica login** (basata su SPID, CIE o credenziali professionali certificate con autenticazione a più fattori), l'utente potrà accedere in modo autorizzato a tutte le piattaforme digitali e ai dati clinici.

---

## 🎯 Obiettivi Strategici (Fase Iniziale)

Prima di avviare lo sviluppo, la Fase 1 si concentra sull'analisi approfondita con gli stakeholder (medici, infermieri, specialisti IT, amministrativi, ecc.) per definire i seguenti obiettivi chiave:

* **Sicurezza e Privacy:** Garantire la massima protezione dei dati sensibili dei pazienti, in stretta conformità con il **GDPR** e le normative nazionali in materia sanitaria.
* **Interoperabilità Universale:** Capacità di comunicare in modo fluido e standardizzato con tutti i sistemi esistenti e futuri, aderendo in particolare al **"Realm Italiano"** di **HL7 Italia per FHIR**.
* **Usabilità Intuitiva:** Progettare un'interfaccia utente chiara, accessibile e facile da usare per personale con diverse competenze informatiche (conforme W3C).
* **Funzionalità Sanitarie Specifiche:** Integrare strumenti dedicati che rispondano direttamente alle esigenze cliniche, diagnostiche e amministrative degli operatori.
* **Trasparenza Open Source:** Mantenere un approccio completamente open source per garantire l'auditabilità, la flessibilità e l'evoluzione collaborativa del software.

---

## 🛠️ Tecnologie di Base Previste

Il browser sarà costruito estendendo un progetto open source esistente (es. basato su Chromium o un framework come Electron/Tauri). Le tecnologie previste includono:

| Area | Tecnologia | Note |
| :--- | :--- | :--- |
| **Core & Backend** | **C++** | Per il motore e l'implementazione della sicurezza. |
| **Frontend & UI** | **JavaScript/TypeScript** | Per l'interfaccia utente moderna e le funzionalità web. |
| **Integrazione** | **Python** | Per script di integrazione e automazione. |
| **Standard Dati** | **HL7 FHIR** | Il cuore dell'interoperabilità, con focus sui **Profili del Realm Italiano**. |
| **Sicurezza** | **SMART on FHIR (OAuth2)** | Per l'autenticazione e l'autorizzazione granulare sui dati clinici. |

---

## 🤝 Come Contribuire

Siamo un progetto open source e accogliamo con entusiasmo contributi da sviluppatori, esperti di sicurezza, designer e professionisti sanitari. La tua esperienza è cruciale per il successo di **EGESIA**.

1.  **Dai un feedback:** Hai esperienza diretta nel SSN? Proponi funzionalità o segnala punti critici sui sistemi attuali aprendo una **Issue**.
2.  **Sviluppo:** Se sei esperto in **C++, Python, JavaScript/TypeScript** o integrazione **FHIR**, inizia a familiarizzare con i requisiti e guarda le Issue aperte etichettate con `good first issue` o `help wanted`.
3.  **Documentazione:** Aiuta a migliorare i file `README.md` e `CONTRIBUTING.md`.

**Prima di iniziare a scrivere codice, consulta il file [CONTRIBUTING.md](CONTRIBUTING.md) per le linee guida di sviluppo e il flusso di lavoro (workflow).**

---

## ⚖️ Licenza

Questo progetto è rilasciato sotto la licenza **EUPL (European Union Public Licence) v1.2**.

Vedi il file [LICENSE.md](LICENSE.md) per i dettagli completi della licenza.
