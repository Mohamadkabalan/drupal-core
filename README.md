# drupal-core

This repository contains an unmodified copy of [Drupal](https://www.drupal.org) 9.3.6, installed from the official `drupal/legacy-project` Composer template (the traditional layout with `core/` at the project root). It is a single snapshot commit with no custom modules, themes or configuration.

## License and credit

Drupal is © its contributors and licensed under GPL-2.0-or-later (see `LICENSE.txt` and `core/LICENSE.txt`). All code in this repository, including `vendor/`, is third-party.

## Contents

- `core/`: Drupal core 9.3.6
- `vendor/`: Composer dependencies (Symfony, Twig, Guzzle, etc.)
- `modules/`, `themes/`, `profiles/`: empty placeholders with Drupal's README files
- `sites/default/default.settings.php`: stock settings template
- `composer.json` / `composer.lock`: the `drupal/legacy-project` template requiring `drupal/core-recommended ^9.3`

## Getting a current Drupal install

Install from the official template rather than this snapshot:

```bash
composer create-project drupal/legacy-project my-site
# or the recommended layout:
composer create-project drupal/recommended-project my-site
```
