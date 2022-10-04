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

 curl -X POST -H "Content-Type: text/plain" --data "de la data" https://webhook.site/6f594809-a4b4-483e-841b-0c3b0a00ed
 
 <!DOCTYPE html>
<html>
<head>
    <title>Error: Alias 6f594809-a4b4-483e-841b-0c3b0a00ed not found - Webhook.site</title>
    <link href="/assets/css/libs/bootstrap.min.css" rel="stylesheet" crossorigin="anonymous">
    <link href="/css/app.css" rel="stylesheet">
</head>
<body>
<div class="container" style="padding: 40px">
    <div class="row">
        <div class="col-sm-4 col-sm-offset-4 text-center">
            <h1>Webhook.site Error</h1>
            <p class="lead">404 Alias 6f594809-a4b4-483e-841b-0c3b0a00ed not found</p>
                        <p class="small">
                    The URL was deleted manually, or expired automatically.

    To avoid URLs expiring automatically, you can
    <a href="/register">upgrade to Webhook.site Pro or Enterprise</a>.
            </p>
                        <br>
            <p><a class="btn btn-primary" href="/" role="button">&larr; Back to Webhook.site</a></p>
            <br>
            <p class="small muted">Copyright &copy; 2022 Webhook ApS</p>
        </div>
    </div>
</div>
</body>

## Faire un appel curl en envoyant du JSON (avec les bons headers) : copier la commande exécutée et indiquer la requête et la réponse

curl -X POST https://webhook.site/6f594809-a4b4-483e-841b-0c3b0a00edfe -H 'Content-Type: application/json' -d '{"titre":"test","annee":"1294"}'

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
