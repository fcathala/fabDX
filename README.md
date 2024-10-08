# fabDX
fabAnt ported to DX...

## Install DX
### Recommended method
* Install [NodeJS](https://nodejs.org/en/download/) first (you can also read this helpful [post](https://treehouse.github.io/installation-guides/windows/node-windows.html) on the subject)
* Install [the CLI with npm](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_install_cli.htm)

```Batch
>> npm install sfdx-cli --global
```

* [Verify Your Installation](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_install_cli.htm)

```Batch
>> node --version
v14.16.1
```

```Batch
>> sfdx --version
sfdx-cli/7.98.0 win32-x64 node-v14.16.1
```

### Homebrew (Mac only)
* Install [SFDX](https://formulae.brew.sh/cask/sfdx)

## Resources
* [Set Up Your Salesforce DX Environment](https://blogs.perficient.com/2020/12/09/set-up-your-salesforce-dx-environment/)
* [How to install Visual Studio Code, Salesforce CLI/SFDX, and Connect to Salesforce Org](https://www.youtube.com/watch?v=BT4IRLrsBlg) on YouTube!
* Display a generic help page

```Batch
>> sfdx --help
Salesforce CLI

VERSION
  sfdx-cli/7.98.0 win32-x64 node-v14.16.1

USAGE
  $ sfdx [COMMAND]

TOPICS
  alias    manage username aliases
  auth     authorize an org for use with the Salesforce CLI
  config   configure the Salesforce CLI
  force    tools for the Salesforce developer
  plugins  add/remove/create CLI plug-ins

COMMANDS
  autocomplete  display autocomplete installation instructions
  commands      list all the commands
  help          display help for sfdx
  plugins       list installed plugins
  update        update the sfdx CLI
  which         show which plugin a command is in
```

## References
* It all starts with [Salesforce's tooling page](https://developer.salesforce.com/tools) for developers (and the [CLI page](https://developer.salesforce.com/tools/sfdxcli) in particular).
* Read the Salesforce CLI [Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm) is a good start for all DX projects.
* Reading the [NPM Guide](https://docs.npmjs.com/about-npm) is also time well spent.
* Troubleshoot an installation Googling your way around or looking in [the usual tech forums](https://salesforce.stackexchange.com/questions/163795/sfdx-is-not-recognized-as-an-internal-or-external-command).
