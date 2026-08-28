Obiettivo

Realizzare la tua scheda profilo professionale — il primo mattone del tuo portfolio — usando solo HTML, senza una riga di CSS, e ottenendo comunque un documento leggibile, navigabile e accessibile.

Requisiti obbligatori

Struttura

Documento HTML5 valido, lang="it", charset, viewport, title significativo, <meta name="description">.
Struttura semantica completa: <header>, <nav>, <main> (unico), almeno tre <section> con id, <aside>, <footer>.
Gerarchia delle intestazioni corretta: un solo <h1>, nessun salto di livello.
Zero <div>, tranne quelli che sai giustificare per iscritto in un commento HTML.

Contenuto 5. Un menu di navigazione in <nav> con link a frammento verso le sezioni. 6. Sezione Chi sono: due paragrafi con almeno un <strong> e un <em> usati correttamente. 7. Sezione Competenze: una <ul> con sottoliste annidate, divisa tra ciò che sai e ciò che stai imparando. 8. Sezione Percorso di studi: una <ol> in ordine cronologico, con le date in <time datetime="..."> in formato ISO. 9. Una foto (o un segnaposto) in <figure> con <figcaption> e alt scritto secondo le regole del §2.7. 10. Una <dl> con almeno quattro coppie: città, lingue, disponibilità, contatto. 11. Un <blockquote> con cite — la tua frase preferita sulla programmazione, con l'autore in <cite>. 12. In <aside>: tre link ai tuoi profili esterni (GitHub, LinkedIn, altro), che si aprono in nuova scheda in sicurezza. 13. Nel <footer>: &copy;, l'anno, un link mailto: e un <address>.

Qualità 14. Zero errori sul validatore W3C. Allega uno screenshot in docs/validazione.png. 15. Ogni testo di link deve avere senso letto fuori contesto. 16. Almeno tre attributi data-* inseriti dove ti serviranno più avanti (li userai nel Capitolo 20: pensa già a cosa ti servirà).

Consegna 17. Repository su GitHub con README.md che spiega cosa hai fatto. 18. Online su GitHub Pages o Netlify. 19. In docs/scelte.md, elenca cinque scelte semantiche che hai fatto e spiega perché hai scelto quell'elemento invece di un altro plausibile.Java e OOP da zero
Docker e setup agentico
Spring Boot + PostgreSQL (architettura MVC)
API REST full-stack, CORS
Autenticazione JWT
Modellazione dati con JPA/Hibernate
Performance (paginazione, filtri), reliability (errori, validazione)
Reporting (export Excel/Word)
Social graph (follow/unfollow), upload multimediale
Clean Code e Testing

Geo-servizi e mappe
Real-time (WebSocket, notifiche push)
Vision/OCR
RAG e memoria AI
Messaggistica ed email automatiche
Integrazione API Claude, agenti AI custom
Ottimizzazione (caching, processi asincroni)
Sicurezza (2FA, anti-SQLi, anti-XSS), GDPR
Deploy cloud, logging, monitoraggio, documentazione Swagger