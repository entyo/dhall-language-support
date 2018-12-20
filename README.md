# dhall-language-support

VSCode Launguage Support for [dhall-lang](https://github.com/dhall-lang/dhall-lang)

This project is generated by [Microsoft/vscode-generator-code](https://github.com/Microsoft/vscode-generator-code)

## Features

This extension is a kind of language support, but only syntax highlighting(from [SQbQxeKd3JHD8/SublimeDhall](https://github.com/SQbQxeKd3JHD8/SublimeDhall/blob/master/Dhall.sublime-syntax)) is currently supported.

![](https://i.imgur.com/Nlkvg4l.png)

Syntax highlighting itself is also WIP :bow:

## Development/Try it

This extension has no releases yet. But you can try/development this extension right now, using [vsce](https://www.npmjs.com/package/vsce)(Visual Studio Code Extension Manager).

You can install `vsce` via npm, then command `vsce package` to generate `.vsix` file, which is able to used in your VSCode.

```
npm i -g vsce
vsce package
```

To enable `.vsix` in your local VSCode, open [Command Pallete](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) then type **Install from VSIX**

![](https://i.imgur.com/LENlTj2.png)

You can check if it is installed correctly typing **Installed Extensions** in Command Pallete or simply open `.dhall` file.