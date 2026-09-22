# KEC India custom code

This repository contains the WordPress custom-code snapshot for the KEC India site.

## Included

- `wp-content/themes/generatepress-cafe24/`

## Excluded

WordPress core, third-party plugins, uploads, caches, logs, local configuration, and generated migration backups are intentionally excluded.

The local `wp-content/plugins/anecydehe/` directory was not included because it contains obfuscated PHP that decodes and executes payloads with `eval()` and should be treated as a security incident, not as approved custom code.
