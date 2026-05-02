# 📘 Poezii & Proză API  
API profesional, elegant și modern pentru accesarea poeziilor și prozei din literatura română clasică.  
Conceput pentru dezvoltatori, cercetători, profesori și pasionați de cultură.

[![Status](https://img.shields.io/badge/status-live-brightgreen)]()
[![HTTPS](https://img.shields.io/badge/security-HTTPS-blue)]()
[![API Version](https://img.shields.io/badge/version-1.0.0-black)]()
[![License](https://img.shields.io/badge/license-MIT-lightgrey)]()

---

## 🔗 Acces rapid

### 🌐 🌐 URL principal (HTTPS)
https://api-poezie-si-proza.onrender.com


## 🔑 Autentificare

API-ul folosește autentificare prin **API Key**.
Include cheia în header:
x-api-key: YOUR_API_KEY


---

## 📚 Endpointuri

### Poezii
- `GET /api/poezii`
- `GET /api/poezii/:id`

### Proză
- `GET /api/proza`
- `GET /api/proza/:id`

---

## 🧪 Exemple

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

## Planuri
Free · Basic · Premium

---
### Folosirea API key‑ului
```GET /poeti?apiKey=CHEIA_TA_API```

---

## 🛡 Securitate
HTTPS activ (SSL valid)
Anti‑cloning pentru Swagger
Rate limiting
API Key per utilizator
Monitorizare trafic

---

## Despre proiect
Acest API a fost creat pentru a moderniza accesul la literatura românească clasică și pentru a o integra în aplicații educaționale, culturale și digitale moderne.
---

## 📄 Licență
Acest proiect este distribuit sub licența MIT.

---

## ❤️ Autor

Acest API a fost construit cu grijă pentru a oferi acces modern, sigur și elegant la literatura românească clasică.
Proiect dezvoltat de Maria Lavinia.

---

## Notă:  
Notă privind performanța API‑ului  
Acest serviciu rulează în prezent pe un plan gratuit Render.
Prima cerere după o perioadă de inactivitate poate avea o întârziere de aproximativ 60 de secunde, deoarece instanța este repornită automat.
După activare, toate răspunsurile sunt livrate instant.
Se Lucrează la optimizări și viitoare actualizări pentru a îmbunătăți experiența de utilizare.
