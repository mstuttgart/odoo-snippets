# Odoo Visual Code Snippets

[![Version](https://vsmarketplacebadge.apphb.com/version-short/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/mstuttgart.odoo-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets)

This extension contains code snippets for [Odoo](https://www.odoo.com) to help you to develop Odoo modules faster and with no Typing Errors.

All snippets follow the [OCA Maintainer Guidelines](https://github.com/OCA/maintainer-tools/blob/master/CONTRIBUTING.md) and are made to Odoo version `10.0` and `11.0`.

## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

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

| Snippet    | Description                 |
|------------|-----------------------------|
| `oman`     | Create Odoo Manifest        |
| `omod`     | Create New Odoo Model       |
| `omodi`    | Inherit Existing Odoo Model |
| `omodt`    | Create Test to Odoo Model   |
| `ofbin`    | Add new field Binary        |
| `ofbool`   | Add new field Boolean       |
| `ofchar`   | Add new field Char          |
| `ofdate`   | Add new field Date          |
| `oftime`   | Add new field DateTime      |
| `offloat`  | Add new field Float         |
| `ofhtml`   | Add new field HTML          |
| `ofint`    | Add new field Integer       |
| `oftxt`    | Add new field Text          |
| `ofsel`    | Add new field Selection     |
| `ofm2o`    | Add new field Many2one      |
| `ofm2m`    | Add new field Many2many     |
| `ofo2m`    | Add new field One2many      |
| `omcreate` | Add a method create         |
| `omwrite`  | Add a method write          |
| `omcomp`   | Add a method compute        |
| `omchange` | Add a method omchange       |

### XML Snippets

| Snippet    | Description                           |
|------------|---------------------------------------|
| `oform`    | Create Form View                      |
| `oformi`   | Inherit Existing Form View            |
| `otree`    | Create Tree View                      |
| `otreei`   | Inherit Existing Tree View            |
| `osearch`  | Create Search View                    |
| `osearchi` | Inherit Existing Search View          |
| `oxpath`   | Add the structure of xpath            |
| `oact`     | Create new Action                     |
| `onote`    | Add notebook and page tags            |
| `opage`    | Add new page tag                      |
| `omenur`   | Create New Menu Item in the Upper bar |
| `omenuc`   | Create New Menu Item for Categories   |
| `omenua`   | Create New Menu Item for Actions      |
| `ocron`    | Add a ir.cron record (11.0 version)   |

## Credits

This snippets are based in [odoo-pycharm-templates](https://github.com/mohamedmagdy/odoo-pycharm-templates) project.

Copyright (C) 2018 by Michell Stuttgart
