# Odoo Visual Code Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version-short/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)

This extension contains code snippets for [Odoo](https://www.odoo.com) to help you to develop Odoo modules faster and with no Typing Errors.

All snippets follow the [OCA Maintainer Guidelines](https://github.com/OCA/maintainer-tools/blob/master/CONTRIBUTING.md) and are made to Odoo version `10.0` and `11.0`.

## Installation

Launch VS Code Quick Open `Ctrl + p` or `Cmd + p`, paste the following command, and press enter.

```
ext install mstuttgart.odoo-snippets
```

## Supported Languages

This extension provide support to following languages (file extensions):

* Python (.py)
* XML (.xml)

## Usage

Below is a list of all available snippets.

### Python Snippets

| Snippet   | Description                     |
|-----------|---------------------------------|
| `oman`    | Create Odoo Manifest            |
| `omod`    | Create New Odoo Model           |
| `omodi`   | Inherit Existing Odoo Model     |
| `omodt`   | Create Test to Odoo Model       |
| `ofbin`   | Add new field of type Binary    |
| `ofbool`  | Add new field of type Boolean   |
| `ofchar`  | Add new field of type Char      |
| `ofdate`  | Add new field of type Date      |
| `oftime`  | Add new field of type DateTime  |
| `offloat` | Add new field of type Float     |
| `ofhtml`  | Add new field of type HTML      |
| `ofint`   | Add new field of type Integer   |
| `oftxt`   | Add new field of type Text      |
| `ofsel`   | Add new field of type Selection |
| `ofm2o`   | Add new field of type Many2one  |
| `ofm2m`   | Add new field of type Many2many |
| `ofo2m`   | Add new field of type One2many  |
| `ocreate` | Add a method create             |
| `owrite`  | Add a method write              |

### XML Snippets

| Snippet  | Description                |
| -------- | -------------------------- |
| `oform`  | Create Form View           |
| `oformi` | Inherit Existing Form View |
| `otree`  | Create Tree View           |
| `otreei` | Inherit Existing Tree View |
| `oxpath` | Add the structure of xpath |

## Credits

This snippets are based in [odoo-pycharm-templates](https://github.com/mohamedmagdy/odoo-pycharm-templates) project.

Copyright (C) 2018 by Michell Stuttgart
