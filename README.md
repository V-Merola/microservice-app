# microservice-app
Questa repository contiene un'applicazione completa basata su architettura a microservizi. Ogni funzionalità dell'applicazione è suddivisa in microservizi indipendenti, ciascuno con la propria repository, ma collegato centralmente tramite submodules. Questo progetto dimostra l'uso di tecnologie come Spring Boot, Spring Cloud, JWT, e vari pattern architetturali legati ai microservizi.

### Architettura dell'applicazione:
L'applicazione è composta dai seguenti microservizi:

Authentication API: Gestisce l'autenticazione e la sicurezza tramite JWT.

Link alla repository
User Microservice: Si occupa della gestione degli utenti e dei profili.

Link alla repository
API Gateway: Funziona come punto di accesso unificato, smistando le richieste tra i vari microservizi.

Link alla repository
Service Discovery: Gestione della registrazione e scoperta dei microservizi tramite Eureka.

Link alla repository
Event Microservice: Gestisce gli eventi asincroni dell'applicazione.

Link alla repository
Config Server: Fornisce configurazioni centralizzate per i microservizi, permettendo una gestione unificata delle impostazioni.

Link alla repository
