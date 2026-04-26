SETUP RAPIDO

1) Carica il progetto su Netlify.
2) In Site configuration > Environment variables aggiungi:
   - RESEND_API_KEY
   - FROM_EMAIL
   - SDAC_TO_EMAIL
3) Verifica su Resend il dominio del mittente usato in FROM_EMAIL.
4) Esegui npm install.
5) Per test locale usa: npx netlify dev

NOTE
- I prezzi sono dentro: netlify/functions/send-preventivo.js
- Il link privacy va sostituito in index.html
- La funzione invia una mail all'utente e una alla scuola, entrambe con PDF allegato.
