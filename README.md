Views Base URL
--------------

This module provides a site base URL token in Views. The main purpose of this
module is to create a link with absolute path through **Global:Custom text**
option.

##### Usage
- Select field formatter in view, and add **Global: Base url**
- Select **Exclude from display** option.
- Create custom link by adding a **Global: Custom text**
- Create link using replacement pattern like this:
```html
<a href="[base_url]/home">My home page</a>
```
