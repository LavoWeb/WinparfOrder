# Connecteur Winparf stock

Le connecteur n'est pas encore disponible publiquement mais il est déjà en production
pour plusieurs clients.

Il permet de faire de l'import de stock via les exports natifs de Winparf. Le seul 
coût côté ERP et la mise en place de la tâche cron d'export.

Il gére les flux avec commande asynchrone (type chéque/virement), le stock réel est
calculé à chaque import.

L'import se fait en requête SQL, pour mettre à jour 10 000 produits, il faut 7min.

Pour en savoir plus : [contactez-nous](https://lumao.eu#section-contact)