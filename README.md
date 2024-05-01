
<h1 align="center">
  <br>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
  <img src="https://github.com/mstuttgart/vscode-odoo-snippets/blob/main/images/icon.png?raw=true"></a>
  <br>
  Odoo Snippets
  <br>
</h1>

<h4 align="center">Develop Odoo modules faster and with no Typing Errors</h4>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
    <img src="https://vsmarketplacebadges.dev/version-short/mstuttgart.odoo-snippets.png?style=for-the-badge&color=875A7B" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
<img alt="Visual Studio Marketplace Installs" src="https://img.shields.io/visual-studio-marketplace/i/mstuttgart.odoo-snippets?color=875A7B&style=for-the-badge">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
<img alt="Visual Studio Marketplace Downloads" src="https://img.shields.io/visual-studio-marketplace/d/mstuttgart.odoo-snippets?color=875A7B&style=for-the-badge">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=mstuttgart.odoo-snippets">
<img alt="Visual Studio Marketplace Rating" src="https://img.shields.io/visual-studio-marketplace/r/mstuttgart.odoo-snippets?color=875A7B&style=for-the-badge">
  </a>
</p>
<h4 align="center">Works on</h4>
<p align="center">
  <a href="https://neovim.io/">
     <img alt="Neovim" src="https://img.shields.io/badge/Tools-Neovim-informational?style=for-the-badge&logo=neovim&logoColor=white&color=bed5c5">
  </a>
  <a href="https://code.visualstudio.com/">
     <img alt="VsCode" src="https://img.shields.io/badge/Tools-Vscode-informational?style=for-the-badge&logo=visualstudiocode&logoColor=white&color=bed5c5">
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

This extension works on [VsCode](https://code.visualstudio.com) and [Neovim](https://neovim.io/). This add code snippets for [Odoo](https://www.odoo.com) to help you to develop Odoo modules faster and with no Typing Errors on .

All snippets follow the [OCA Maintainer Guidelines](https://github.com/OCA/maintainer-tools/blob/master/CONTRIBUTING.md) and are made to Odoo version `12.0`+.

## Installation

### VsCode

Launch *Quick Open*
  - <img src="https://www.kernel.org/theme/images/logos/favicon.png" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-linux.pdf">Linux</a> `Ctrl+P`
  - <img src="https://developer.apple.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf">macOS</a> `⌘P`
  - <img src="https://www.microsoft.com/favicon.ico" width=16 height=16/> <a href="https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf">Windows</a> `Ctrl+P`

Paste the following command and press `Enter`:

```
ext install mstuttgart.odoo-snippets
```

### Neovim

This collection of snippets should work with any snippet engine that supports loading vscode snippets. Like for example:

- [vim-vsnip](https://github.com/hrsh7th/vim-vsnip)
- [LuaSnip](https://github.com/L3MON4D3/LuaSnip)
- [coc-snippets](https://github.com/neoclide/coc-snippets)

Use your plugin manager of choice, e.g.

#### With Lazy.nvim

```lua
{
  "mstuttgart/vscode-odoo-snippets",
  event = "InsertEnter",
}
```

> [!WARNING]
> If you're using LuaSnip make sure to use `require("luasnip.loaders.from_vscode").lazy_load()`, and add
> `mstuttgart/vscode-odoo-snippets` as a dependency for LuaSnip, otherwise snippets might not
> be detected. If you don't use `lazy_load()` you might notice a slower startup-time
>
   ```lua
   {
      "L3MON4D3/LuaSnip",
      dependencies = { "mstuttgart/vscode-odoo-snippets" },
      config = function()
        require("luasnip.loaders.from_vscode").lazy_load()
      end,
   }
  ```

#### With Packer

```lua
use "rafamadriz/friendly-snippets"
```

## Usage

This extension provide support to following languages (file extensions):

* Python (.py)
* XML (.xml)
* CSV (.csv)

Use `tab` to navegate in snippet positions.

Below is a list of all available snippets.

<details>
<summary>Python snippets</summary>

| Python Snippet | Description                |
| -------------- | -------------------------- |
| `ipdb`         | Import Python ipdb command |


| Odoo Snippet | Description                            |
| ------------ | -------------------------------------- |
| `oman`       | Create Odoo Manifest                   |
| `omod`       | Create New Odoo Model                  |
| `omodi`      | Inherit Existing Odoo Model            |
| `owiz`       | Create New Odoo wizard                 |
| `owizi`      | Inherit Existing Odoo wizard           |
| `omodt`      | Create Test to Odoo Model              |
| `ofbin`      | Add new field Binary                   |
| `ofbool`     | Add new field Boolean                  |
| `ofchar`     | Add new field Char                     |
| `ofdate`     | Add new field Date                     |
| `oftime`     | Add new field DateTime                 |
| `offloat`    | Add new field Float                    |
| `ofhtml`     | Add new field HTML                     |
| `ofint`      | Add new field Integer                  |
| `oftxt`      | Add new field Text                     |
| `ofsel`      | Add new field Selection                |
| `ofm2o`      | Add new field Many2one                 |
| `ofm2m`      | Add new field Many2many                |
| `ofo2m`      | Add new field One2many                 |
| `omcreate`   | Add a method create                    |
| `omwrite`    | Add a method write                     |
| `omunlink`   | Add a method unlink                    |
| `omcomp`     | Add a method compute                   |
| `omchange`   | Add a method onchange                  |
| `ousercomp`  | Add self.user.company_id snippets      |
| `oimp`       | Add Odoo import snippets               |
| `oimpt`      | Add Import to Odoo Tests snippets      |
| `oimper`     | Add Import to Odoo Exceptions snippets |

</details>

<details>
<summary>XML snippets</summary>

| XML Snippet  | Description                              |
| ------------ | ---------------------------------------- |
| `odoo`       | Create Odoo Tag                          |
| `oform`      | Create Form View                         |
| `oformi`     | Inherit Existing Form View               |
| `otree`      | Create Tree View                         |
| `otreei`     | Inherit Existing Tree View               |
| `osearch`    | Create Search View                       |
| `osearchi`   | Inherit Existing Search View             |
| `ograph`     | Create Graph View                        |
| `ographi`    | Inherit Existing Graph View              |
| `opivot`     | Create Pivot View                        |
| `opivoti`    | Inherit Existing Pivot View              |
| `okanban`    | Create Kanban View                       |
| `okanbani`   | Inherit Existing Kanban View             |
| `ocalendar`  | Create Calendar View                     |
| `ocalendari` | Inherit Existing Calendar View           |
| `ogantt`     | Create Gantt View                        |
| `ogantti`    | Inherit Existing Gantt View              |
| `oxpath`     | Add the structure of xpath               |
| `oxpathattr` | Add the structure of xpath to attributes |
| `oact`       | Create new Action                        |
| `onote`      | Add notebook and page tags               |
| `opage`      | Add new page tag                         |
| `omenur`     | Create New Menu Item in the Upper bar    |
| `omenuc`     | Create New Menu Item for Categories      |
| `omenua`     | Create New Menu Item for Actions         |
| `ocron`      | Add a ir.cron record                     |
| `obtn`       | Add Odoo button                          |
| `obtnbox`    | Add Button Box on View                   |
| `ogroup`     | Add group tag on View                    |
| `ofield`     | Add Field on View                        |
| `odata`      | Add data tag on View                     |
| `ochatter`   | Add chatter tag on View                  |
| `oaurl`      | Create action.url tag                    |
| `oaserver`   | Create action.server tag                 |
| `oaclient`   | Create action.client tag                 |

<!-- <summary>QWeb snippets</summary> -->

| Qweb Snippet | Description                                    |
| ------------ | ---------------------------------------------- |
| `oreport`    | Create report record on View                   |
| `otemplate`  | Create template tag                            |
| `otemplatei` | Create template inherit tag                    |
| `otcall    ` | Add t-call tag on View                         |
| `otforeach`  | Add t-foreach tag on View                      |
| `otif`       | Add t-if tag on View                           |
| `otelif`     | Add t-elif tag on View                         |
| `otifelse`   | Add t-if-else tag on View                      |
| `otraw`      | Add t-raw tag on View                          |
| `otesc`      | Add t-esc tag on View                          |
| `otset`      | Add t-set tag on View                          |
| `otfield`    | Add t-field tag on View                        |
| `otimg`      | Add img tag with `t-att-src` attribute on View |

</details>

<details>
<summary>CSV snippets</summary>

| CSVSnippet          | Description                     |
| ------------------- | ------------------------------- |
| `ocolumns`          | Create columns to access groups |
| `odoo_access_entry` | Create entry to access groups   |


</details>

## Contributing

Please, see contributing guidelines [here](CONTRIBUTING.md).

## Release Notes

See [changelog](CHANGELOG.md).

## Credits

This snippets are based in [odoo-pycharm-templates](https://github.com/mohamedmagdy/odoo-pycharm-templates) project.

Copyright (C) 2018-2024 by Michell Stuttgart
