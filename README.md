# skeleton

Squelette d'un projet

## Styles

### Dossiers pour organiser le css :
<dl>
<dt>Colors : <dd>Les couleurs en variable</dd></dt>
<dt>Base : <dd>Contient les styles de base pour les éléments HTML tels que les typographies, les couleurs de base, les styles de liens, etc.</dd></dt>
<dt>Layout : <dd>Gère la structure globale de la mise en page, telle que la grille, les positions et les espacements.</dd></dt>
<dt>Modules : <dd>Représente les composants réutilisables et indépendants, tels que les boutons, les formulaires, les menus, etc.</dd></dt>
<dt>State : <dd>Gère les états spécifiques des éléments, tels que les styles pour les états :hover, :focus, :active, etc.</dd></dt>
<dt>Theme : <dd>Gère les styles spécifiques à un thème ou à une variante d'interface utilisateur.</dd></dt>
</dl>

### Ordre des attributs d'une class css :
* Box
* Border
* Background
* Text
* Other

## Scripts
<dl>
<dt>"stan": "vendor/bin/phpstan analyse -c conf/phpstan.neon",<dd>composer require phpstan/phpstan</dd><dt>
<dt>"insights": "vendor/bin/phpinsights --config-path=conf/phpinsights.php",<dd>composer require nunomaduro/phpinsights</dd><dt>
<dt>"insights-fix": "vendor/bin/phpinsights --f composer --config-path=conf/phpinsights.php",<dd>composer require nunomaduro/phpinsights</dd><dt>
<dt>"insights-summary": "vendor/bin/phpinsights -s --config-path=conf/phpinsights.php",<dd>composer require nunomaduro/phpinsights</dd><dt>
<dt>"format": "vendor/bin/phpcs --standard=PSR12 src",<dd>composer require squizlabs/php_codesniffer</dd><dt>
<dt>"format-fix": "vendor/bin/phpcbf src",<dd>composer require squizlabs/php_codesniffer</dd><dt>
<dt>"purge": "purgecss -c conf/purgecss.config.js",<dd>npm i -g purgecss</dd><dt>
<dt>"tsc": "tsc -p conf/tsconfig.json",<dd></dd><dt>
<dt>"tests": "vendor/bin/phpunit -c conf/phpunit.xml.dist",<dd>composer require phpunit/phpunit</dd><dt>
<dt>"tests-coverage": "vendor/bin/phpunit -c conf/phpunit.xml.dist --coverage-html coverage",<dd>composer require phpunit/php-code-coverage</dd><dt>
<dt>"tests-watcher": "vendor/bin/phpunit-watcher watch -c conf/phpunit-watcher.yml"<dd>composer require spatie/phpunit-watcher</dd><dt>
</dl>
  
### Autres scripts :
<dl>
  <dt>Typescript :<dd>npm install typescript</dd></dt>
  <dt>SASS :<dd>npm i sass</dd></dt>
  </dl>
