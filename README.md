# 📘 Romanian Classical Literature API 
API profesional, elegant și modern pentru accesarea poeziilor și prozei din literatura română clasică.  
Conceput pentru dezvoltatori, cercetători, profesori și pasionați de cultură.

---

## 🔗 Acces rapid

### 🌐 URL principal (HTTPS)
https://api-poezie-si-proza.onrender.com

---

## 📚 Descriere

Acest proiect oferă un API modern, construit cu **Node.js + Express**, care pune la dispoziție operele marilor autori clasici români: poezii, proză, bibliografie și imagini.

Pe lângă accesul la conținut literar, API‑ul include acum o platformă completă de abonamente, cu:
- conturi de utilizator
- chei API
- planuri Free / Basic / Premium
- Stripe Checkout
- Stripe Webhooks
- rate‑limiting în funcție de plan
- Customer Portal
- pagini bilingve (EN/RO)
- securitate avansată
Conținutul literar rămâne file‑based, ușor de extins și fără baze de date.

---

## 🔑 Autentificare

API-ul folosește autentificare prin **API Key**.
### cURL
```bash
curl https://domeniul-tau.ro/api/poezii \
  -H "x-api-key: YOUR_API_KEY"
```
### JavaScript
```
fetch("https://domeniul-tau.ro/api/poezii", {
  headers: { "x-api-key": "YOUR_API_KEY" }
})
  .then(r => r.json())
  .then(console.log);
```
---

### 📖 Acces la literatură

- Poezii clasice româneșt
- Proză și povestiri
- Bibliografie text
- Imagini ale autorilor
- Căutare după autor și titlu
- Suport complet pentru diacritice

### 📚 Endpointuri principale

### Poezii
- `GET /autor/{autor}/poezii`
- `GET /autor/{autor}/:id`
- `GET /autor/{autor}/:id/text`

### Proză
- `GET autor/{autor}/proza`
- `GET autor/{autor}/proza/:id`
- `GET autor/{autor}/proza/:id/text`

### Bibliografie
- `GET autor/{autor}/bibliografie/text`
  
### Poza autor
- `GET autor/{autor}/poza`
  
---

## 🛡 Securitate
HTTPS activ (SSL valid)
Anti‑cloning pentru Swagger
Rate limiting
API Key per utilizator
Monitorizare trafic

---

## 📄 Licență
Acest proiect este distribuit sub licența MIT.

---

### ❤️ Autor

Acest API a fost construit cu grijă pentru a oferi acces modern, sigur și elegant la literatura românească clasică.
Proiect dezvoltat de Maria Lavinia.

---

### Notă:  
Notă privind performanța API‑ului  
Acest serviciu rulează în prezent pe un plan gratuit Render.
Prima cerere după o perioadă de inactivitate poate avea o întârziere de aproximativ 60 de secunde, deoarece instanța este repornită automat.
După activare, toate răspunsurile sunt livrate instant.
Se Lucrează la optimizări și viitoare actualizări pentru a îmbunătăți experiența de utilizare.
