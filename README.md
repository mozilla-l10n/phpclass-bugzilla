Bugzilla (PHP Class)
============

To include in your project, add these lines to composer.json

```
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/mozilla-l10n/phpclass-bugzilla"
        }
    ],

    "require": {
        "mozillal10n/bugzilla" : "dev-master"
    },
```

Usage example (retrieve locale's component name).

```
use Bugzilla\Bugzilla;

$locale = 'fr';
echo Bugzilla::getBugzillaLocaleField($locale);
```
