<div align="center">

 # Live server for Vim/Nvim (unofficial plugin).

 <h4>
   Little development server with live reload capability.
 </h4>

 [![GitHub](https://img.shields.io/badge/by-manzeloth-green)](https://github.com/manzeloth)
 [![npm](https://img.shields.io/badge/npm-live%20server-red)](https://www.npmjs.com/package/live-server)

</div>


---


## Installation

Install [nodejs](https://nodejs.org/en/download/) and [live-server](https://www.npmjs.com/package/live-server) npm package. Make sure you have npm in your `PATH`.

This line should work with [vim-plug](https://github.com/junegunn/vim-plug):

```vim
" live-server
Plug 'manzeloth/live-server'
```

then restart Vim/Nvim and run `:PlugInstall`.

## Usage

Type `:LiveServer start` to open a new instance of live-server in your web browser.

Type `:LiveServer stop` to close all instances of live-server.

## Credits

All credits goes to Tapio Vierros. This unofficial plugin uses [Live Server](https://www.npmjs.com/package/live-server) which is under the MIT License.
