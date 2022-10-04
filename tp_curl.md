# TP curl - comprendre les requêtes et les réponses HTTP

Pour les questions suivantes, vous devez utiliser l'url suivante : https://webhook.site/6f594809-a4b4-483e-841b-0c3b0a00edfe

Pour tous les appels vous devez ajouter un header pour identifier votre appel parmis ceux des autres étudiants : x-student : VOTRE_NOM

## Faire un appel curl : copier la commande exécutée et indiquer la requête et la réponse
curl https://webhook.site/6f594809-a4b4-483e-841b-0c3b0a00edfe -H " bouquier"

## Quel est la version du protocole utilisé par le serveur ?

HTTP/1.1

## Quels sont les headers que l'on envoie dans la requête ? Quels sont leur sens ?

> GET /6f594809-a4b4-483e-841b-0c3b0a00edfe HTTP/1.1
> Host: webhook.site
> User-Agent: curl/7.74.0
> Accept: */*


## Quelles informations pouvez-vous trouver à propos du certificat SSL ?
 Server certificate:
*  subject: CN=webhook.site
*  start date: Jul 31 23:09:19 2022 GMT
*  expire date: Oct 29 23:09:18 2022 GMT
*  issuer: C=US; O=Let's Encrypt; CN=R3
*  SSL certificate verify ok.

## Quel est le code de la réponse ? Que signifie-t-il ?
X-Request-Id: 3b742095-f3ea-4970-8935-d65f87853e6d

## Quels headers recevez vous dans la response ? Quels sont leur sens ?
HTTP/1.1 200 OK
Server: nginx
Content-Type: text/plain; charset=UTF-8
Vary: Accept-Encoding
X-Request-Id: 29605326-32fe-45cf-a572-7ea5424b1184
X-Token-Id: 6f594809-a4b4-483e-841b-0c3b0a00edfe
Cache-Control: no-cache, private
Date: Tue, 04 Oct 2022 14:45:56 GMT
<
## Faire un appel curl en envoyant du texte brut : copier la commande exécutée et indiquer la requête et la réponse


## Faire un appel curl en envoyant du JSON (avec les bons headers) : copier la commande exécutée et indiquer la requête et la réponse


## Faire une appel curl en envoyant une basic authentication en utilisant 2 méthodes différentes : copier les commandes exécutées et indiquer la requête et la réponse à chaque fois 


## Exécuter la commande suivante avec la méthode GET puis indiquer la réponse : curl https://demo.api-platform.com/books/07dd4786-aaa7-4d08-a467-076b76f1d1b6 


## Exécuter la commande suivante avec la méthode PATCH  puis indiquer la réponse : curl https://demo.api-platform.com/top_books/1


## Quel est le code HTTP reçu ? Quel est sa signification ?


## Exécuter la commande suivante puis indiquer la réponse : curl https://demo.api-platform.com/top_books/1


## Exécuter la commande suivante puis indiquer la réponse : curl https://demo.api-platform.com/top_books/9999


## Quel est le code HTTP ? Que signifie-t-il ?


## Exécuter la requête suivante et copier la réponse : curl https://google.fr


## Quel est le code HTTP reçu ? Pouvez-vous expliquer cette réponse ?


## Comment éviter cette réponse ? Trouvez 2 solutions différentes et détaillez les.
