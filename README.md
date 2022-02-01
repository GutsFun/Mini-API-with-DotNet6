# Mini API sous .NET 6

> 📃 Ce projet est utilisé dans le cadre d'un article disponible depuis mon blog technique :
<https://developer.gutsfun.com/mini-api-avec-net-6/>

Ce dépôt propose de découvrir le développement de Mini API à l'aide du **Framework .NET 6** de Microsoft. Il contient le code source permettant de réaliser et suivre le tutoriel de l'article en lien ci-dessus.

Le contenu du dépôt se partage en deux projets :

- Un projet ``mini-api`` proposant une API s'appuyant sur les principes amenés avec **ASP.NET Core MVC** et les nouvelles fonctionnalités de **C# 10**.
- Un projet ``macro-api`` proposant une version plus allégée de l'API ``mini-api`` et plus proche de ce qui est proposé dans l'article.

Veuillez suivre les instructions de l'[article](https://developer.gutsfun.com/mini-api-avec-net-6/) pour l'installation de l'environnement de travail qui comprends :

- Le SDK .NET 6
- L'IDE pour le développement et la compilation du code.

## Installation et exécution

### API

Pour télécharger et lancer les API il vous faut d'abord cloner la solution sur votre poste en lançant la commande suivante dans un terminal Bash ou Powershell depuis le dossier de destination :

```bash
git clone https://github.com/inpulse-tv/epX-dotnet6-mini-api.git
```

Pour exécuter les API il vous faut au préalable une version du [SDK .NET 6](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) d'intallée sur votre poste. Ensuite il suffit de lancer la commande Shell suivante à la racine du projet d'API qui vous intéresse.

```bash
dotnet run
```

Vous aurez une API consultable en local sur le port 8000 via l'URL : <http://localhost:8000>.
L'API ne propose qu'un seul endpoint : ``api/entreesdujour``

*N.B* : Il est tout à fait possible d'utiliser [Visual Studio 2022](https://visualstudio.microsoft.com/fr/vs/) pour éditer et exécuter les API.

### Base de données

Ce projet utilise comme source de données une base **sqlite3** ``pouletmayo.db``, disponible dans le dossier ``sqlite3`` de ce dépôt Git.

Pour savoir comment installer et utiliser la base **sqlite3**, veuillez suivre le tutoriel suivant : [Premiers pas sur SQL - [SQL partie.1] [n00b] [#data] [ep.3]](https://www.youtube.com/watch?v=_ALsx-CMyy8)
