# phpApiRequestCacher

REQUIREMENTS / ENVIRONMENT :
* PHP 8.3.4 (cli) (built: Mar 13 2024 11:43:12) (ZTS Visual C++ 2019 x64) Zend Engine v4.3.4, Copyright (c) Zend Technologies
* Composer version 2.7.2 2024-03-11 17:12:18

NOTE: The bellow instructions and commands assume that you are on Windows 10 and in the root directory of the project.

EXECUTION:
```ps
php.exe main.php
```

TESTING:
```ps
php.exe manual_dep\phpunit-11.1.2.phar --no-configuration --test-suffix Test.php tests\
```

DEBUG-TESTING:
```ps
php.exe manual_dep\phpunit-11.1.2.phar --no-configuration --test-suffix Test.php tests\ --display-incomplete --display-skipped --display-deprecations --display-errors --display-notices --display-warnings
```
(Optional flag --teamcity for CI/CD compatability.)

USEFUL:
Responsive PowerShell one-liner to monitor cache directory.
```ps
while ($true) {clear;gci ./cache/;Start-Sleep -Milliseconds 400}
```

