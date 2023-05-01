# README

# Guide d'installation et de mise en place d'un projet Ruby on Rails 7 avec Devise

Ce projet est une implémentation de l'authentification dans une application Ruby on Rails 7 en utilisant la gem Devise.
Voici le [lien vers l'article](https://clean-blog-production.up.railway.app/articles/mettre-en-place-une-authentification-avec-devise-dans-ruby-on-rails) concerné.
![Capture d’écran du 2023-05-01 19-32-46](https://user-images.githubusercontent.com/85675011/235497764-1bf1ba6a-1ae0-4cc2-af88-e0263406fa98.png)


## Prérequis

- Ruby on Rails 7
- Ruby 3.1.2
- Une base de données compatible avec Rails (par exemple, PostgreSQL, MySQL ou SQLite)

## Installation

1. Cloner le projet en utilisant une URL HTTPS ou SSH
```bash
git clone https://github.com/sandri31/start_with_devise.git
```
```bash
git clone git@github.com:sandri31/start_with_devise.git
```
2. Ouvrir le projet et installer les dépendances avec
```bash
cd start_with_devise
bundle install
```
3. Créer la base de données et lancer les migrations avec
```bash
rails db:create
rails db:migrate
```
4. Lancer le serveur
```bash
rails server
```
5. Ouvrir le navigateur à l'adresse http://localhost:3000 pour accéder à l'application.

## Conclusion

Ce projet offre un exemple de mise en place de l'authentification avec Devise dans une application Ruby on Rails 7. En suivant les étapes de ce guide, vous pouvez cloner le projet, installer les dépendances, créer la base de données, lancer les migrations et le serveur pour tester l'application sur votre propre machine.
