# NppLSPClient
A [LSP](https://microsoft.github.io/language-server-protocol/) client plugin for Notepad++.

## Currently, Npp 8.7.7 is the minimum supported version.

***NOTE: The latest builds assume that the Folder as Workspace (faw) dialog is used.  
This means that the rootUri component of the [initialize request](https://microsoft.github.io/language-server-protocol/specifications/lsp/3.17/specification/#initializeParams) sent from the client to the server  
is set to the directory of the root item that contains the current buffer. 
~~If no faw dialog is used or the file is not part of one of the root elements, the directory of the file is used.~~***

## Installation

- Download and unpack the NppLspClient zip-archive (the NppLspClient_x*86 or 64*.zip) from https://github.com/Ekopalypse/NppLspClient/releases to the folder "Notepad++\plugins".
- Install a language server of your choice
- Configure it by calling "Open configuration" from the NppLspClient plugin menu. (You will find a more detailed description in the configuration file.)

## Usage example

- Start Notepad++
- Open a source file
- Run "Start server for current language"

See [tips](./tips.md) for more information about usage and language server setup.


## Building manually
tbd

## Release History

* 0.0.35
    * Work in progress

## Meta

Distributed under the MIT license. See ``LICENSE`` for more information.
