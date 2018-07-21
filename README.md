# open-in-atom-cli

> Open a file in Atom from the CLI with no lags

![open-in-atom](https://user-images.githubusercontent.com/74385/43037729-87aeccec-8d43-11e8-8509-b64115de0f91.gif)

## Installation

Install the bin using npm or yarn:

```sh
npm install -g open-in-atom-cli
yarn global add open-in-atom-cli
```

Alternatively, you can just copy the shell script [`bin/atom-open`](bin/atom-open) to your PATH.

You'll also need to install the companion Atom plugin, [open-in-atom].

[open-in-atom]: https://github.com/rstacruz/open-in-atom

## Usage

Use `atom-open` instead of `atom`. It will open your files instantly, instead of waiting 5 seconds for the official Atom CLI.

```sh
# Open a file
atom-open README.md

# Open a directory
atom-open .

# Open a directory and some files under it
atom-open . README.md package.json
```

## Thanks

**open-in-atom-cli** © 2018, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[![](https://img.shields.io/github/followers/rstacruz.svg?style=social&label=@rstacruz)](https://github.com/rstacruz) &nbsp;
[![](https://img.shields.io/twitter/follow/rstacruz.svg?style=social&label=@rstacruz)](https://twitter.com/rstacruz)

[mit]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/open-in-atom-cli/contributors
