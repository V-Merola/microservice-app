# Microservice-app
Questa repository contiene un'applicazione completa basata su architettura a microservizi. Ogni funzionalità dell'applicazione è suddivisa in microservizi indipendenti, ciascuno con la propria repository. 
Questo progetto dimostra l'uso di tecnologie come Spring Boot, Spring Cloud, JWT, e vari pattern architetturali legati ai microservizi.
### Tecnologie usate:
- Spring Boot: Per lo sviluppo dei microservizi.
- Spring Cloud Eureka: Per la gestione del Service Discovery e delle configurazioni centralizzate.
- Spring Security con JWT: Per la gestione dell'autenticazione.
- Spring Cloud Gateway: Per la gestione delle API Gateway
- Spring Cloud Config Server: Per la gestione delle configurazioni
- Spring Boot Admin: Per monitoraggio e logging (Actuator - Micrometer)
  
## Architettura dell'applicazione:
L'applicazione è composta dai seguenti microservizi:

1. [**Authentication API**](https://github.com/V-Merola/authentication-api)
   ###### Gestisce l'autenticazione e la sicurezza tramite token JWT.
   [**Flutter Frontend Authentication**](https://github.com/V-Merola/authentication-api-frontendF)
   
3. [**User Microservice**](https://github.com/V-Merola/user-ms)
   ###### Si occupa della gestione degli utenti e dei profili.
   
4. [**API Gateway**](https://github.com/V-Merola/api-gateway)
   ###### Funziona come punto di accesso unificato, smistando le richieste tra i vari microservizi.

5. [**Service Discovery**](https://github.com/V-Merola/discovery-ms)
   ###### Gestione della registrazione e scoperta dei microservizi tramite Eureka.

6. [**Event Microservice**](https://github.com/V-Merola/event-ms)
   ###### Gestisce la creazione di eventi sportivi e l'organizzazione automatica di squadre e calendari

7. [**Config Server**](https://github.com/V-Merola/ConfigServer)
   ###### Fornisce configurazioni centralizzate per i microservizi, permettendo una gestione unificata delle impostazioni.

8. [**Config Repo**](https://github.com/V-Merola/config-repo)
   ###### Fornisce repository con file di configurazione

9. [**Logging Monitoring**](https://github.com/V-Merola/logging-monitoring-ms)
   ###### Fornisce monitoraggio tramite Spring Admin Dashboard

