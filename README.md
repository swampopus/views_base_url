Views Base URL
--------------

This module provides a site base URL token in Views. The main purpose of this
module is to create a link with absolute path through **Global:Custom text**
option.

## Usage
- Select field formatter in view, and add **Global: Base url**
- Select **Exclude from display** option.
- Create custom link by adding a **Global: Custom text**
- Create link using replacement pattern like this:
```
<a href="[base_url]/home">My home page</a>
```

## Installation

* Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules


## Current Maintainers

* [Richard Peacock](https://github.com/swampopus)
* Seeking additional maintainers.


## Credits

- Ported to Backdrop CMS by [Richard Peacock](https://github.com/swampopus)

This module is based on the Drupal module views_base_url-7.x-1.2

Project page: https://www.drupal.org/project/views_base_url

Drupal Maintainers:

* [mably](https://www.drupal.org/u/mably)
* [subhojit777](https://www.drupal.org/u/subhojit777)
* [rjjakes](https://www.drupal.org/u/rjjakes)
