# 🛠️ Commandes utiles :

- **Générer les entités depuis la base de données :**
  ```bash
  php bin/console doctrine:mapping:import App\Entity annotation --path=src/Entity
  ```

- **Générer les getters et setters des entités :**
  ```bash
  php bin/console make:entity --regenerate App
  ```

- **Créer / modifier une entité :**
  ```bash
  php bin/console make:entity
  ```

- **Générer un controller :**
  ```bash
  php bin/console make:controller
  ```

- **Générer un controller CRUD et les formulaires et vues associées :**
  ```bash
  php bin/console make:crud
  ```

- **Générer une migration Doctrine (lier les entités à la base de données) :**
  ```bash
  php bin/console make:migration
  ```

- **Exécuter les migrations Doctrine :**
  ```bash
  php bin/console doctrine:migrations:migrate
  ```

- **Créer la base de données via Doctrine :**
  ```bash
  php bin/console doctrine:database:create
  ```

- **Démarrer un serveur de développement :**
  ```bash
  symfony serve
  ```

# 📚 Ressources :

- [Symfony documentation](https://symfony.com/doc/current/index.html)
- [Symfony Casts](https://symfonycasts.com/)
  - [Free Symfony 6 course](https://symfonycasts.com/screencast/symfony)
- [Lior Chamla](https://www.youtube.com/c/LiorCHAMLA)
  - [Tutoriels Symfony 4 et 5](https://www.youtube.com/playlist?list=PLpUhHhXoxrjdQLodxlHFY09_9XzqdPBW8)
