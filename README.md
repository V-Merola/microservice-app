# Microservice-app
Questa repository contiene un'applicazione completa basata su architettura a microservizi. Ogni funzionalità dell'applicazione è suddivisa in microservizi indipendenti, ciascuno con la propria repository, ma collegato centralmente tramite submodules. Questo progetto dimostra l'uso di tecnologie come Spring Boot, Spring Cloud, JWT, e vari pattern architetturali legati ai microservizi.

## Architettura dell'applicazione:
L'applicazione è composta dai seguenti microservizi:

1. **Authentication API**
   ###### Gestisce l'autenticazione e la sicurezza tramite JWT.
   [Link alla repository](https://github.com/V-Merola/authentication-api)

2. **User Microservice**
   ###### Si occupa della gestione degli utenti e dei profili.
   [Link alla repository](https://github.com/V-Merola/user-ms)

3. **API Gateway**
    ###### Funziona come punto di accesso unificato, smistando le richieste tra i vari microservizi.
    [Link alla repository](https://github.com/V-Merola/api-gateway)

4. **Service Discovery**
   ###### Gestione della registrazione e scoperta dei microservizi tramite Eureka.
   [Link alla repository](https://github.com/V-Merola/discovery-ms)

5. **Event Microservice**
   ###### Gestisce la creazione di eventi
   [Link alla repository](https://github.com/V-Merola/event-ms)

6. **Config Server**
   ###### Fornisce configurazioni centralizzate per i microservizi, permettendo una gestione unificata delle impostazioni.
   [Link alla repository](https://github.com/V-Merola/ConfigServer)

7. **Config Repo**
   ###### Fornisce repository con file di configurazione
   [Link alla repository](https://github.com/V-Merola/config-repo)

8. **Logging Monitoring**
   ###### Fornisce monitoraggio tramite Spring Admin Dashboard
   [Link alla repository](https://github.com/V-Merola/logging-monitoring-ms)

