Note: GitHub repository is mirrored from GitLab. To submit pull requests or report any issues, go to [https://gitlab.com/dark-themes/uniform-dark-theme-sn](https://gitlab.com/dark-themes/uniform-dark-theme-sn "Click here to access the repository.").

![Alt](./Images/logo.png "Uniform Dark+ Theme")

## Uniform Dark+ Theme

Theme inspired by Visual Studio Code's default dark theme, designed for Standard Notes. It is based off my other [theme](https://gitlab.com/dark-themes/uniform-dark-theme-vscode "Click here to access the repository.") that unifies VS Code's default dark theme.

## Preview

![Alt](./Images/preview.png "Preview of Uniform Dark+ Theme")

I enjoy VS Code's default dark theme, however for me it appeared too *boxy*. Also, I preferred a cleaner look.

Lighter colors of user interface elements were changed to match the darker color of its Editor background. I am porting that style to Standard Notes.

Included in the theme, though&#8212;as depicted in the preview image, is my favorite editor font family: [Fira Code](https://github.com/tonsky/FiraCode "Click here to access the repository for more information.").

Work in progress...

<!--## Build from Source Code

Download [Visual Studio Code](https://code.visualstudio.com/ "Click here to access the download link.") from Microsoft, and install it.

Download and install [Node.js](https://nodejs.org/en/ "Click here to access the download link.") and [Git](https://git-scm.com/downloads "Click here to access the download link.").

Also, open a terminal to download and install the Visual Studio Code Extension Manager (vsce):
```
npm install -g vsce
```

Clone the project:
```
git clone https://gitlab.com/dark-themes/uniform-dark-theme-vscode.git
```

(Recommended) Verify the project's authenticity: Look upward for "Verified," next to the commit SHA.

(Recommended) Open a terminal, and verify the project's integrity:
```
cd uniform-dark-theme-vscode
git show-ref --heads --hash
```
Check that the hash matches the commit SHA.

Open the project in Visual Studio Code, and build/package the extension:
```
vsce package \
--baseContentUrl https://gitlab.com/dark-themes/uniform-dark-theme/-/raw/master/ \
--baseImagesUrl https://gitlab.com/dark-themes/uniform-dark-theme/-/raw/master/ \
--out Archives/
```

## Usage

Select Install to do so automatically. \
Alternatively, install the extension from the VSIX file in Visual Studio Code.

Press on the cogwheel, ⚙️; select Color Theme; and choose Uniform Dark+. \
Alternatively, go to File > Preferences > Color Theme, and choose Uniform Dark+.

Known to work in Visual Studio Code 1.44.2

## Contributing

Sign into GitLab, to fork the project. \
(The repository is located at [https://gitlab.com/dark-themes/uniform-dark-theme-vscode](https://gitlab.com/dark-themes/uniform-dark-theme-vscode "Click here to access the repository.").)

Modify the color theme. \
Stage, commit and push the changes.

Return to the GitLab repository, and submit a new pull request. \
To report any issues, submit a new issue or discuss an existing one.

## History

May 4, 2020 &middot; Version 1.2.1: corrected manifest file \
May 3, 2020 &middot; Version 1.2: changed color of focusBorder \
Apr 16, 2020 &middot; Version 1.1.3: corrected images in marketplace \
Apr 16, 2020 &middot; Version 1.1.2: refined the project \
Apr 11, 2020 &middot; Version 1.1.1: corrected manifest file \
Apr 10, 2020 &middot; Version 1.1: changed tab border color \
Apr 9, 2020 &middot; Version 1: initial commit -->

For Web client to work, stylesheet is also hosted on GitLab Pages:
[https://saegl5.gitlab.io/css/stylesheet.css](https://saegl5.gitlab.io/css/stylesheet.css)

## Known Issues

- [x] ~~Theme does not work in Standard Notes 3.4.1 ([#550](https://github.com/standardnotes/desktop/issues/550))~~ - **Fixed!**<br>
- [x] ~~Theme does not work with Web client~~ - **Fixed!**<br>
- [x] ~~Desktop client has stronger font-weight after upgrading from version 3.3.5 to 3.4.1 ([#551](https://github.com/standardnotes/desktop/issues/551),[#14948](https://github.com/electron/electron/issues/14948))~~ - **Contrasted colors more**<br>
- [ ] Theme crashes Android client (related to [#56](https://github.com/standardnotes/mobile/issues/56)?)

## License

MIT

Copyright (c) 2020 Ed Silkworth