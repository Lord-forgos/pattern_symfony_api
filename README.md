Utilisez symfony si le raccourci est connu sinon remplacer "symfony" par "php bin/"<br/><br/>

1 - Faire sa connexion à sa DB, **changer le .env DATABASE_URL**, au moins changer le nom de la base<br/>
2 - Faire un **symfony console doctrine:database:create**<br/>
3 - Créer une migration à l'aide de la commande **symfony console make:migration**
4 - Executez la migration à l'aide de la commande **symfony console doctrine:migrations:migrate**
