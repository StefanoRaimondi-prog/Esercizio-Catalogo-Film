# 🎬 Film Manager Web App

Un'applicazione web realizzata con Angular per gestire e visualizzare film in maniera semplice ed intuitiva.

## 🚀 Introduzione
Questa applicazione consente agli utenti di visualizzare, cercare, aggiungere, modificare ed eliminare film da un database. È ideale per piccoli progetti personali o come base per applicazioni più complesse legate al cinema o all'intrattenimento.

## 📌 Funzionalità
- **Visualizzazione film**: elenco dettagliato dei film presenti nel database.
- **Ricerca rapida**: ricerca film per titolo, genere o anno.
- **CRUD completo**: possibilità di creare, aggiornare e cancellare film.
- **Dettagli film**: pagina dedicata con informazioni approfondite come cast, sinossi, valutazioni e data di rilascio.

## 🛠️ Tecnologie utilizzate
- **Framework**: Angular v19.2.3
- **TypeScript**
- **HTML/CSS**

## ⚙️ Installazione
Per avviare localmente il progetto:

1. Clona il repository:
```bash
git clone <url-repo>
```

2. Entra nella cartella del progetto:
```bash
cd film-manager
```

3. Installa le dipendenze:
```bash
npm install
```

4. Avvia l'applicazione:
```bash
ng serve
```

5. Apri il browser su:
```
http://localhost:4200
```

## 🗃️ Struttura del progetto
```
film-manager/
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   ├── film-list
│   │   │   ├── film-detail
│   │   │   ├── film-form
│   │   ├── services/
│   │   │   └── film.service.ts
│   │   ├── models/
│   │   │   └── film.model.ts
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   └── styles.css
├── angular.json
├── package.json
└── README.md
```



