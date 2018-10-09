# ESlint & phpcs-psr2 pre-commit hook

Pre-Commit hook script for PSR2 to check your PSR2 coding standard and more with ESLint and PHPCS code sniffer. Auto-fix enabled!

#### Requirements

* Node.js
* ESLint
* PHP Code Sniffer (phpcs) with PSR2

#### Usage

Go to your drupal subtheme folder (or create this one).

* 1 - Move to your Drupal project git hook folder `cd /path/to/your/project/.git/hooks`
* 2 - Download the pre-commit hook script `curl -O https://raw.githubusercontent.com/kwen8/eslint-psr2-pre-commit-hook/master/pre-commit`
* 3 - Make sure script is executable `chmod +x pre-commit`
* 4 - Edit the script with your favorite editor and setup the bin tools on the `#Setup` section222222222222
* 5 - Ready to commit!
