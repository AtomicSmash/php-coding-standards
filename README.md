# AS PHP coding standards

This composer package handles the dependencies and config for the PHP coding standards. For all other AS coding standards, use the npm package `@atomicsmash/coding-standards`.

## To release a new version:

1. Make any changes you need to the package
2. Merge into main
3. An automated action will generate a PR called Version Packages. Review it and then merge this in.
4. An action will tag the repo which will in turn cause packagist to release a new version.
