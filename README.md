Bugzilla (PHP Class)
============

To include in your project, add these lines to composer.json

```
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/flodolo/phpclass-bugzilla"
        }
    ],

    "require": {
        "mozillal10n/bugzilla" : "dev-master"
    },
```

Usage example (retrieve locale's component name).

```
use Bugzilla\Bugzilla as _Bugzilla;

$locale = 'fr';
echo _Bugzilla::getBugzillaLocaleField($locale);
```
