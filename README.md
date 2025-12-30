# liskk-dict.el

Dictionary files for [liskk.el](https://github.com/conao3/liskk.el), providing SKK-based Japanese input support in Emacs.

## Overview

This package provides pre-packaged SKK dictionary files for use with liskk.el. It includes various dictionary sets covering general vocabulary, proper nouns, geographic names, and specialized terminology.

## Requirements

- Emacs 24.4 or later

## Installation

### Using package.el

Add this repository to your package archives and install:

```elisp
(require 'package)
(add-to-list 'package-archives '("melpa" . "https://melpa.org/packages/") t)
(package-initialize)
(package-install 'liskk-dict)
```

### Manual Installation

Clone this repository and add it to your load-path:

```elisp
(add-to-list 'load-path "/path/to/liskk-dict.el")
(require 'liskk-dict)
```

## Included Dictionaries

This package bundles the following SKK dictionaries:

| Dictionary | Description |
|------------|-------------|
| SKK-JISYO.L | Large dictionary with comprehensive vocabulary |
| SKK-JISYO.M | Medium-sized dictionary |
| SKK-JISYO.S | Small dictionary for basic usage |
| SKK-JISYO.geo | Geographic names |
| SKK-JISYO.jinmei | Personal names |
| SKK-JISYO.station | Train station names |
| SKK-JISYO.propernoun | Proper nouns |
| SKK-JISYO.law | Legal terminology |
| SKK-JISYO.lisp | Lisp-related terms |

For additional dictionaries and details, see the [SKK Dictionary Project](https://skk-dev.github.io/dict/).

## Dictionary Sources

The dictionaries included in this package are converted from the official SKK dictionary project. For information about editing dictionaries or contributing upstream, refer to:

- [Manued documentation tool](https://sundayresearch.eu/hitoshi/otherprojects/manued/index-j.html)
- [Manued on GitHub](https://github.com/yamauchih/manued)

## License

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

## Author

Naoya Yamashita (conao3@gmail.com)
