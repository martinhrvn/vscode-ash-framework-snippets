# Ash Framework snippets
![](images/ash-logo.png)
This extension contains code snippets for [Ash Framework](https://www.ash-hq.org/) `.eex`, `.html.eex`, `.heex` and `.sface` files for [VS Code](https://code.visualstudio.com/) editor.

**Enjoy!!!**

## Snippets

Below is a list of all available snippets.

### Basic

|    Trigger |            NAME            |                                                 DESCRIPTION                                                  |
| ---------- |----------------------------|--------------------------------------------------------------------------------------------------------------|
|   `aintpk` | Ash int PK                 | `integer_primary_key :${1:name}`                                                                             |
|     `aatr` | Ash attribute              | `attribute :${1:name}, :${2:string}`                                                                         |
|    `aatrs` | Ash Attributes             | `attributes do`<br />`        ${1}`<br />`end`                                                                       |
|    `auuid` | Ash uuid PK                | `uuid_primary_key :${1:name}`                                                                                |
|     `arel` | Ash relationships          | `relationships do`<br />`     ${1}`<br />`end`                                                                    |
|      `aho` | Ash has one                | `has_one :${1:name}, ${2:Resource}`                                                                          |
|   `arespg` | Ash Resource with Postgres | `defmodule ${1:Module} do`<br />`     use Ash.Resource,`<br />`               data_layer: ${3:AshPostgres.DataLayer}`<br />`end` |
|      `apg` | Ash postgres               | `postgres do`<br />`table "${1:table}"`<br />`repo ${2:Project}.Repo`<br />`end`                             |
|     `ares` | Ash Resource               | `defmodule ${1:Module} do`<br />`     use Ash.Resource`<br />`        $2`<br />`end`                                      |
|     `aact` | Ash Actions                | `actions do`<br />`   ${1}`<br />`end`                                                                          |

## Release Notes

Please read the [CHANGELOG](CHANGELOG.md) to see what has changed in this extension over time.

## Contribution

```sh
git clone https://github.com/martinhrvn/vscode-ash-framework-snippets
```

And copy the `vscode-ash-framweork-snippets` folder into the `<user home>/.vscode/extensions` folder. Restart Code.

## License

[MIT](LICENSE.md) License

