# PingPong Module
[![Build Status](https://scrutinizer-ci.com/g/WildPHP/module-pingpong/badges/build.png?b=master)](https://scrutinizer-ci.com/g/WildPHP/module-pingpong/build-status/master)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/WildPHP/module-pingpong/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/WildPHP/module-pingpong/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/wildphp/module-pingpong/v/stable)](https://packagist.org/packages/wildphp/module-pingpong)
[![Latest Unstable Version](https://poser.pugx.org/wildphp/module-pingpong/v/unstable)](https://packagist.org/packages/wildphp/module-)
[![Total Downloads](https://poser.pugx.org/wildphp/module-pingpong/downloads)](https://packagist.org/packages/wildphp/module-pingpong)

This module watches for PING requests from the server and responds appropriately.

## System Requirements
If your setup can run the main bot, it can run this module as well.

## Installation
To install this module, we will use `composer`:

composer require wildphp/module-pingpong

That will install all required files for the module. In order to activate the module, add the following line to your `config.neon`, section `modules`:

	- WildPHP/Modules/PingPong/PingPong

Make sure to include a tab character in front. The bot will run the module the next time it is started.

## License
This module is licensed under the GNU General Public License, version 3. Please see `LICENSE` to read it.
