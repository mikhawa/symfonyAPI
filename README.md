# symfonyAPI
Symfony 6.3 API

## Installation

```bash
symfony new SymfonyAPI
```

## Démarrage serveur interne :
```bash
cd SymfonyAPI
symfony serve -d
```

### URL
https//120.0.0.1:8000

### Console

```bash
php bin/console
```

On optient les actions faisables depuis la console

### Installation de maker

```bash
composer require --dev symfony/maker-bundle
```

On pourra dès lors créer rapidement des parties de site via l'invite de commande

### Création d'un contrôleur

```bash
php bin/console make:controller
```

ce qui donne

```bash
Choose a name for your controller class (e.g. DeliciousGnomeController):
 > NotrePremierController

 created: src/Controller/NotrePremierController.php


  Success!


 Next: Open your new controller class and add some pages!
```