# KECC-IR-HIGHLIGHT: README

This is the README for extension `KECC-IR-HIGHLIGHT`.

> This is ***not an official*** implementation by the KECC developers and is not affiliated with KECC.

## Features

Support for language highlighting of KECC(KAIST Educational C Compiler) IR. So the theme you use is applied automatically to the `.ir` file. It does not contain themes.

[Example-VSCode Default Dark](./imgs/img1.png)

[Example-Atom One Dark](./imgs/img2.png)

## Requirements

No special requirements. Simply install the extension from the Marketplace.

If the highlighting does not work even after opening the `.ir file`, select `KECC IR` by clicking the `language mode` setting at the bottom bar.

## Extension Settings

No special settings.

## Known Issues

If the initializer for a global variable is not in a format that can be parsed as a number (`([0-9\\.]+?)(?=:|$)`), it is not recognized as a constant.

If you find any other issues or have a solution, please feel free to contact us.

## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release.