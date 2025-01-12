# Setup Varbase AI

A Drupal recipe to setup default Varbase AI needed modules, import configs and grant permissions.

Run this recipe activate Varbase AI, But without the need to enable the Varbase AI module.

> NOTE: [Setup Varbase AI](https://github.com/vardot/setup-varbase-ai) is the same as [**Default Varbase AI Recipe**](https://git.drupalcode.org/project/varbase\_ai/-/blob/1.0.x/recipes/default/recipe.yml?ref\_type=heads), But dose not need to enable the Varbase AI module.

Add the recipe using composer:
```
composer require vardot/setup-varbase-ai:~2.0
```

Change directory to `/web` or `/docroot`

Run the Drupal recipe bash script:
```
php core/scripts/drupal recipe recipes/contrib/setup-varbase-ai
```

```
drush recipe recipes/contrib/setup-varbase-ai
```
