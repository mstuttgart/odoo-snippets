
<h1 align="center">
  <br>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
  <img src="https://github.com/mstuttgart/vscode-odoo-snippets/blob/develop/images/icon.png"></a>
  <br>
  VSCode Odoo Snippets
  <br>
</h1>

<h4 align="center">Develop Odoo modules faster and with no Typing Errors</h4>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
    <img src="https://vsmarketplacebadge.apphb.com/version-short/mstuttgart.odoo-snippets.svg?style=flat-square&color=875A7B" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
     <img alt="Visual Studio Marketplace Installs" src="https://img.shields.io/visual-studio-marketplace/i/mstuttgart.odoo-snippets?color=875A7B&style=flat-square">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
    <img alt="Visual Studio Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/mstuttgart.odoo-snippets?color=875A7B&style=flat-square">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
      <img src="https://vsmarketplacebadge.apphb.com/rating/mstuttgart.odoo-snippets.svg?style=flat-square&color=875A7B" alt="Ratings">
  </a>
</p>

<p align="center">
  <a href="#about">About</a> |
  <a href="#installation">Installation</a> |
  <a href="#usage">Usage</a> |
  <a href="#contributing">Contributing</a> |
  <a href="#release-notes">Release Notes</a> | 
  <a href="#credits">Credits</a>
</p>

## About

This extension contains code snippets for [Odoo](https://www.odoo.com) to help you to develop Odoo modules faster and with no Typing Errors.

All snippets follow the [OCA Maintainer Guidelines](https://github.com/OCA/maintainer-tools/blob/master/CONTRIBUTING.md) and are made to Odoo version `10.0`, `11.0` and `12.0`.

To **OpenERP** snippets, please use the [TheDavidDelta's OpenERP Code Snippets](https://marketplace.visualstudio.com/items?itemName=TheDavidDelta.openerp-code-snippets) extension.

## Installation

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```
ext install mstuttgart.odoo-snippets
```

## Usage

This extension provide support to following languages (file extensions):

* Python (.py)
* XML (.xml)

Below is a list of all available snippets.

<details>
<summary>Python snippets</summary>

| Snippet    | Description                  |
| ---------- | ---------------------------- |
| `oman`     | Create Odoo Manifest         |
| `omod`     | Create New Odoo Model        |
| `omodi`    | Inherit Existing Odoo Model  |
| `owiz`     | Create New Odoo wizard       |
| `owizi`    | Inherit Existing Odoo wizard |
| `omodt`    | Create Test to Odoo Model    |
| `ofbin`    | Add new field Binary         |
| `ofbool`   | Add new field Boolean        |
| `ofchar`   | Add new field Char           |
| `ofdate`   | Add new field Date           |
| `oftime`   | Add new field DateTime       |
| `offloat`  | Add new field Float          |
| `ofhtml`   | Add new field HTML           |
| `ofint`    | Add new field Integer        |
| `oftxt`    | Add new field Text           |
| `ofsel`    | Add new field Selection      |
| `ofm2o`    | Add new field Many2one       |
| `ofm2m`    | Add new field Many2many      |
| `ofo2m`    | Add new field One2many       |
| `omcreate` | Add a method create          |
| `omwrite`  | Add a method write           |
| `omunlink` | Add a method unlink          |
| `omcomp`   | Add a method compute         |
| `omchange` | Add a method onchange        |

</details>

<details>
<summary>XML and Report snippets</summary>

| Snippet      | Description                                    |
| ------------ | ---------------------------------------------- |
| `odoo`       | Create Odoo Tag                                |
| `oform`      | Create Form View                               |
| `oformi`     | Inherit Existing Form View                     |
| `otree`      | Create Tree View                               |
| `otreei`     | Inherit Existing Tree View                     |
| `osearch`    | Create Search View                             |
| `osearchi`   | Inherit Existing Search View                   |
| `ograph`     | Create Graph View                              |
| `ographi`    | Inherit Existing Graph View                    |
| `opivot`     | Create Pivot View                              |
| `opivoti`    | Inherit Existing Pivot View                    |
| `okanban`    | Create Kanban View                             |
| `okanbani`   | Inherit Existing Kanban View                   |
| `ocalendar`  | Create Calendar View                           |
| `ocalendari` | Inherit Existing Calendar View                 |
| `ogantt`     | Create Gantt View                              |
| `ogantti`    | Inherit Existing Gantt View                    |
| `oxpath`     | Add the structure of xpath                     |
| `oxpathattr` | Add the structure of xpath to attributes       |
| `oact`       | Create new Action                              |
| `onote`      | Add notebook and page tags                     |
| `opage`      | Add new page tag                               |
| `omenur`     | Create New Menu Item in the Upper bar          |
| `omenuc`     | Create New Menu Item for Categories            |
| `omenua`     | Create New Menu Item for Actions               |
| `ocron`      | Add a ir.cron record (11.0 version)            |
| `obtn`       | Add Odoo button                                |
| `obtnbox`    | Add Button Box on View                         |
| `ogroup`     | Add group tag on View                          |
| `ofield`     | Add Field on View                              |
| `odata`      | Add data tag on View                           |
| `oreport`    | Create report record on View                   |
| `otemplate`  | Create template tag                            |
| `otemplatei` | Create template inherit tag                    |
| `otcall    ` | Add t-call tag on View                         |
| `otforeach`  | Add t-foreach tag on View                      |
| `otif`       | Add t-if tag on View                           |
| `otraw`      | Add t-raw tag on View                          |
| `otesc`      | Add t-esc tag on View                          |
| `otset`      | Add t-set tag on View                          |
| `otfield`    | Add t-field tag on View                        |
| `otimg`      | Add img tag with `t-att-src` attribute on View |

</details>

## Contributing

Please, see contributing guidelines [here](https://github.com/mstuttgart/odoo-vscode-snippets/blob/develop/CONTRIBUTING.md).

## Release Notes

See [changelog](CHANGELOG.md).

## Credits

This snippets are based in [odoo-pycharm-templates](https://github.com/mohamedmagdy/odoo-pycharm-templates) project.

Copyright (C) 2018-2021 by Michell Stuttgart
