# WebServerBundle

WebServerBundle provides commands for running applications using the PHP
built-in web server. It simplifies your local development setup because you
don't have to configure a proper web server such as Apache or Nginx to run your
application.

## Installation

Add the repository to a `repositories` list in `composer.json`:

```json
{
    "require": { },
    "...": "",
    "repositories": [
        {
            "type": "vcs",
            "url": "git@github.com:cototal/web-server-bundle.git"
        }
    ]
}
```

Then require the bundle as a dev dependency

```
composer require --dev cototal/web-server-bundle
```

If this is your first time loading a repo from GitHub, you may be asked for a token. Composer will prompt you with some instructions to create one here:

```
https://github.com/settings/tokens/new?scopes=repo&description=Composer+on+computer+2020-07-25+1137
```

## Resources

* [Original Repo](https://github.com/symfony/web-server-bundle)
