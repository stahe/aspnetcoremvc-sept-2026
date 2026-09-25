# Introduction étape par étape au framework ASP.NET Core MVC

**Le cours est en ligne ici : [https://stahe.github.io/aspnetcoremvc-sept-2026/](https://stahe.github.io/aspnetcoremvc-sept-2026/)**

## Présentation

Ce cours apprend pas à pas à construire une application web MVC avec **ASP.NET Core MVC** (.NET 10, C#). Les pages HTML sont fabriquées par le serveur avec des vues **Razor**, sans framework JavaScript côté navigateur.

Il fait suite au cours *Introduction pas à pas au framework web NestJS* (2026) et suit exactement la même progression :

1. **28 petits exemples**, chacun centré sur une notion :
   - contrôleurs, actions et routage ;
   - modèle d'une action : liaison, conversion et validation des paramètres ;
   - vues Razor : gabarit, vues partielles, helpers et Tag Helpers ;
   - formulaires, validation et schéma Post / Redirect / Get (TempData) ;
   - internationalisation (français / anglais) ;
   - portées des données : Singleton, Scoped et Transient, cookies ;
   - cycle de vie d'une requête : middlewares, filtres, pages d'erreur ;
   - authentification par jeton JWT dans un cookie, rôles, captcha et limitation des tentatives ;
   - architecture en couches web / métier / DAO avec **Entity Framework Core** et **MySQL**.
2. **Une étude de cas complète**, *RdvMedecins* : une application de prise de rendez-vous pour un cabinet de médecins, avec trois rôles (administrateur, médecins, patients). Le cours commente chacun de ses fichiers.

Le lecteur n'a besoin d'aucun prérequis sur ASP.NET Core : chaque exemple est commenté ligne à ligne, et le cours donne l'URL exacte à tester pour chacun.

## Environnement

- SDK .NET 10
- Visual Studio Code + extension C# Dev Kit
- MySQL (par exemple avec Laragon)
- curl

## Auteur

Ce cours a été écrit par **Claude** (Anthropic), à la demande de Serge Tahé — septembre 2026.
