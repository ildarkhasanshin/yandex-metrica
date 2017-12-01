# Yandex Metrica #

Contributors:  m_uysl   
Tags:  yandex,metrica,stats,statistics,tools,analytics,analytics tool,metrika  
Requires at least:  3.7  
Tested up to:  4.7  
Stable tag:  1.5  
License: GPLv2 (or later)  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  


Easy way to use Yandex Metrica in your WordPress site.

## Description ##

Best Metrica plugin for the using Yandex Metrica in your WordPress site.

### What is Metrica ###

Metrica is an analytics tool like as google analytics.If you didn't hear metrica yet, you can [check official metrica](http://metrica.yandex.com/) page.


### Features ###

- Easy to manage counter's  tracking options.
- Role based user tracking
- Dashboard widget that displaying metrica graphic, summary of site usage, top pages etc..
- Role based user access for the displaying dashboard widget
- Basic mode ready! If you don't want to give API access, you can try basic mode.
- i18n support: Completely translation ready!


### Translations ###

* English (en_US), built-in
* Turkish (tr_TR), native support
* Russian (ru_RU), [oleg0789](https://profiles.wordpress.org/oleg0789) and Ксения Рыбка

## Installation ##

Extract the zip file and just drop the contents in the `wp-content/plugins/` directory of your WordPress installation and then activate the Plugin from admin's Plugins page.

## Frequently Asked Questions ##

* What is metrica?
	- Metrica is a powerful analytics tool that provided by Yandex.

* Is it free?
	- Definitely, metrica service and this plugin are totally free.

* Can I see statistics on the WordPress dashboard?
	- Yes! (You have to use advanced mode, this feature needs API access)

* I can see dashboard widget but no graph?
	- Probably your counter is not working correctly, please check counter status on the official metrica website. Sometimes we can't retrieve the statistical data via API, especially on the fresh counters.

* Everything done, but metrica service doesn't work for me?
	- Yandex Metrica plugin uses wp_footer hook for the adds necessary tracking code. Please, ensure your theme has wp_footer hook?

	
## Screenshots ##

1. Select mode, basic mode for who don't want to use metrica api. But advanced mode recommended!
![Multiple Mode](https://ps.w.org/yandex-metrica/assets/screenshot-1.png)

2. Displaying graph with metrica results.
![Dashboard widget](https://ps.w.org/yandex-metrica/assets/screenshot-2.png)

3. Settings page.
![Settings page](https://ps.w.org/yandex-metrica/assets/screenshot-3.png)


## Changelog ##

### 1.5 ###
  - Metrica API upgraded, fixes api related problems
  - `sslverify` parameter set to true
  - UI improvements
  - Informer widget address update
  - Widget: showing visitors fix. Props Эльвира Капитонова
  - requires at least WordPress 3.7
  
### 1.4.3 ###
  - minor bug fix about HTTP request
  
### 1.4.2 ###
  - minor bug fixes
  
### 1.4.1 ###
  - array-multisort bug fix. Props Николай Астраханцев

### 1.4 ###
  - Text Domain changed
  - Nonces added to settings page
  - Wrong option name fixed. Props [romapad](https://github.com/romapad)

### 1.3 ###
 - Updated metrica tracking code
 - New hash tracking option added

### 1.2 ###
 - Improved error checking for API request
 - Possible connectivity case added
 - Minor tweaks

#### 1.1.2 ####
 - Russian language pack added. Props Ксения Рыбка and oleg0789
 - API connectivity check improved
 - Minor fixes

#### 1.1.1 ####
 - Dashboard widget daily order fixed
 
### 1.1 ###
 - Dashboard widget UI improvements
 - Bug fixes

#### 1.0.2 ####
 - Capability checking before display temporary dashboard widget
 
#### 1.0.1 ####
 - Closure function removed
 - Typo fix
 
### 1.0 ###
 - Metrica API integration
 - Backward compatibility mode
 - Tracking by user role
 - Dashboard widget
 - New widget, informer widget still exist
 - Better localization
 - Performance improvements
 - Special thanks to Yandex Team for all support.

#### 0.1.3 ####
 - Minor bug fixes
 
#### 0.1.2 ####
 - Bug fix - about options

#### 0.1.1 ####
 - bug fix - header output

#### 0.1 ####
 - Initial release.

## Upgrade Notice ##

### 1.0 ###

Including major changes, recommended update!

### 1.5 ###

Metrica api upgraded, if you get authentication related problems reset plugin settings and connect to API again (that will generate new token)