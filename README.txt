ASSISTENTE PERSONALE — PWA

Questa è la versione web installabile su iPhone.
1) Pubblica questa cartella su un hosting HTTPS (es. GitHub Pages, Cloudflare Pages, Netlify o altro hosting statico).
2) Apri l'indirizzo con Safari su iPhone.
3) Condividi -> Aggiungi alla schermata Home -> attiva "Apri come app web" -> Aggiungi.
4) Dentro l'app apri ⚙️ e inserisci la chiave API xAI.

IMPORTANTE: questa PWA chiama l'API xAI direttamente dal browser. La chiave resta nel localStorage del browser ma, tecnicamente, è accessibile al codice client. Per una versione più sicura conviene aggiungere un backend/proxy personale.
