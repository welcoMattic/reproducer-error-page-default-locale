# Symfony reproducer for error page default locale bug 

## Installation

With Symfony CLI

`composer install`

`symfony serve`

open https://127.0.0.1:8000/en_GB

=> the current locale is en_GB

open https://127.0.0.1:8000/en_GB/error

=> the current locale is fr_FR
