# ClubCMS distribution
Distribution package for the TYPO3 CMS based [ClubCMS](https://github.com/ulbrich-media/clubcms). 

## Production usage

Beside TYPO3s own [system requirements](https://get.typo3.org/version/10#system-requirements), this package relies on Composer and PHP 7.4.

For the first installation just move this distribution package to your webserver. Then run `composer install` to get all the dependencies. Don't forget to change the docroot of your website to the `web` folder. 

Now you just need to open your domain inside your browser and follow the installation process. 

### Alternative installation
This extension is also available trough the TYPO3 Extension Repository, see [extensions.typo3.org](https://extensions.typo3.org/extension/clubcms). 

## Development 

This repository runs out of the box with Docker based [DDEV-Local](https://github.com/drud/ddev/). Make sure you have it installed properly, so you can just launch the local dev environment with `ddev start`. 