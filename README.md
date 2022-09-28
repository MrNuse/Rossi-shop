# Rossi-shop E-commerce

un progetto realizzato in collaborazione con:<br>
Alessandro Torrieri<br>
Andrea Fonte<br>
Damiano Santinato<br>
Davide Nicolas Pala<br>

Il seguente progetto è così composto:

-front end realizzato con jquery html e bootstrap con l'utilizzao del framework express per realizzare i servizi res

-back end java con infrattura microservizi:

  .Servizio autenticazione per gestire tutti i dati degli utenti e generare JWT per verificare le connessione dei client e gestire i ruoli<br>
      Comprende un DB mySQL per gestire i dati
  
  .Servizio gestionale prodotti per amministrare il magazzino<br>
      Comprende un DB mySQL per gestire i prodotti
  
  .Servizio upload file integrato con Amazon aws bucket per caricare le immagini dei prodotti e mostrare i link sul front end
  
  .Servizio mail per inoltrare le mail agli utenti (attualmente solo per l'email di registrazione)
