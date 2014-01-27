packagist
=========

Packagists Server

build a composer.json with content below

{
    "repositories": [ { "type": "composer", "url": "https://github.com/joomla-distro/packagist/raw/master/web/" } ],
    "require": {
    	"joomla/jui": "*",
        "joomla-distro/cms-installer-application": "*",
        "joomla/framework": "1.0.*@stable"
    }
}

run composer install
