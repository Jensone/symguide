---
description: Internet et le web
---

# Rappel sur Internet & Web

# Pourquoi comprendre Internet et le web ?

Internet et le web sont des outils indispensables pour tout développeur. Il est important de comprendre comment ils fonctionnent pour pouvoir développer des applications web. Tout d'abord, il est important de bien les distinguer.

## Internet

1969, ARPANET voit le jour. C'est le premier réseau à transfert de paquets.

Un paquet, c'est un message découpé en petits morceaux. Ils sont envoyés séparément et peuvent emprunter des chemins différents pour arriver à destination. C'est ce qui permet de faire transiter plusieurs messages en même temps sur le réseau.

La DARPA à l'origine d'ARPANET, est une agence du département de la défense des États-Unis. Ce projet est donc à l'origine un réseau militaire, il a été utilisé pour la première fois en 1972 lors d'un test de communication entre l'université de Californie et l'université de Stanford.

Abandonné en 1990, il est à l'origine d'Internet tel que nous le connaissons aujourd'hui. C'est désormais un réseau civil et mondial.

En réalité, le web et internet sont deux choses différentes. Internet, c'est un réseau de communication. Il est composé de millions de serveurs répartis dans le monde entier dans des datacenters. Ces serveurs sont reliés entre eux par des câbles sous-marins et terrestres. La couverture par satellite représente 1 à 2% du trafic internet mondial seulement.

Pour communiquer avec un serveur, on utilise un protocole de communication. C'est un ensemble de règles qui permettent de structurer les échanges entre eux.

Le protocole le plus populaire, tu le connais déjà, c'est le protocole HTTP. C'est celui qui permet de communiquer avec les serveurs web. Pour le email, on utilise le SMTP. HTTP signifie HyperText Transfer Protocol et SMTP Simple Mail Transfer Protocol.

Le S de HTTPS signifie Secure, c'est une version sécurisée du protocole HTTP. Ça permet de chiffrer les échanges avec serveur. C'est idéal pour sécuriser les paiements en ligne par exemple.

## Le web

Dans ton quotidien, tu utilises le web tous les jours. Tu l'utilises pour lire tes emails, regarder des vidéos, faire des recherches, acheter des produits. En fait, tu utilises sans le savoir ce qu'on appelle un client web.

Le client web, c'est le navigateur. C'est lui qui va te permettre de communiquer avec les serveurs web. Il existe plusieurs navigateurs, les plus connus sont Chrome, Firefox, Safari et Edge.

## Client / Serveur

Tout d'abord c'est important de comprendre ce qu'est un serveur web. Tu entend plusieurs fois ce terme mais tu n'as pas forcément une idée précise de ce que c'est. Un serveur web c'est rien qu'un ordinateur. C'est comme celui que tu possèdes mais il a quelques particularités.

Cet ordinateur est configuré pour que tu puisses communiquer avec lui via le protocole HTTP afin d'accéder à des ressources stockées sur lui. Ton pc, lui, ne peut pas être visité par d'autres ordinateurs. Il n'est pas configuré pour ça.

Étant donné qu'un seveur ne sera utilisé que pour y héberger des ressources, il n'a pas besoin d'écran, de clavier ou de souris. De plus il est allumé et connecté à internet 24h/24 et 7j/7.

Tu sais désormais ce qu'est internet, le web et le protocole HTTP.

Maintenant on vas voir comment la communication entre le client et le serveur fonctionne.

## La communication client / serveur

Tous les appareils connectés à internet ont une adresse IP. C'est une suite de chiffres qui permet de les identifier sur le réseau. Pour communiquer avec un serveur, on utilise son adresse IP. C'est comme ça que le navigateur va savoir où envoyer la requête. Tu te doutes bien que c'est pas pratique de retenir des adresses IP. C'est pour ça qu'on utilise des noms de domaine.

Un nom de domaine, c'est une adresse web. C'est plus simple à retenir et plus pratique à utiliser. Chaque nom de domaine est associé à une adresse IP. Afin de faire le lien entre les deux, on utilise des DNS.

DNS signifie Domain Name Service. C'est comme un annuaire téléphonique, mais pour les noms de domaine et les adresses IP. Lorsque tu saisis une adresse web dans ton navigateur, il va d'abord interroger les DNS pour récupérer l'adresse IP du serveur.

Une fois qu'il a l'adresse IP, il va envoyer une requête au serveur. Cette requête te permet d'accéder à une ressource stockée sur le serveur.

Cette ressource peut être une page web, une image, une vidéo, un fichier PDF...

C'est comme cela que le client web, un navigateur, te permet de communiquer avec un serveur web. La réponse du serveur dépend de la requête envoyée par le client. Il existe plusieurs types de requêtes. Les plus connues sont GET et POST. GET permet de récupérer une ressource. POST permet de créer une ressource.

Lorsque un veux accéder à une page d'accueil par exemple, c'est une requête GET qui est envoyée au serveur pour récupérer la page.

Le serveur va alors renvoyer la page au client. Le client va interpréter le code de la page et l'afficher à l'écran. Le code de la page est composé de HTML, CSS et JavaScript. Ce sont les seuls langages que le navigateur peut interpréter.

## Conclusion

Ce petit rappel sur internet et le web est important pour comprendre comment fonctionne la communication entre le client et le serveur. C'est pour cela que nous avons vu ce rappel avant de commencer à développer avec Symfony.