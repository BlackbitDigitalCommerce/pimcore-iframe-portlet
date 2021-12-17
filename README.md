## Iframe Portlet Bundle
Blackbit Iframe Portlet Bundle adds custom portlet with iframe. You can set the URL of the iframe in portlet settings.

## Installation
Add custom repository to your composer.json:

When you have credentials for the Blackbit composer registry, use:
```json
{
  "repositories": {
    "iframe-portlet-bundle": {
      "type": "composer",
      "url": "https://composer.blackbit.de"
    }
  }
}
```

or, if you have access to the bundle repository, use:
```json
{
  "repositories": {
    "iframe-portlet-bundle": {
      "type": "vcs",
      "url": "git@bitbucket.org:blackbitwerbung/iframe-portlet-bundle.git"
    }
  }
}
```

Then require the bundle with `composer require blackbit/iframe-portlet-bundle`
