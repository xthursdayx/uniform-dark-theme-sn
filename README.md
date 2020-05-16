Note: GitHub repository is mirrored from GitLab. To submit pull requests or report any issues, go to [https://gitlab.com/dark-themes/uniform-dark-theme-sn](https://gitlab.com/dark-themes/uniform-dark-theme-sn "Click here to access the repository.").

![Alt](./Images/logo.png "Uniform Dark+ Theme")

## Uniform Dark+ Theme

Theme inspired by Visual Studio Code's default dark theme, designed for Standard Notes. It is based off my other [theme](https://gitlab.com/dark-themes/uniform-dark-theme-vscode "Click here to access the repository.") that unifies VS Code's default dark theme.

## Preview

![Alt](./Images/preview.png "Preview of Uniform Dark+ Theme")

I enjoy VS Code's default dark theme, however for me it appeared too *boxy*. Also, I preferred a cleaner look.

Lighter colors of user interface elements were changed to match the darker color of its Editor background. I am porting that style to Standard Notes.

Included in the theme, though&#8212;as depicted in the preview image, is my favorite editor font family: [Fira Code](https://github.com/tonsky/FiraCode "Click here to access the repository for more information.").

## Build from Source Code

Download and install [Standard Notes Desktop](https://standardnotes.org/ "Click here to access the download links."), or simply open [Standard Notes Web](https://standardnotes.org/ "Click here to access the link.").

Also, download and install [Git](https://git-scm.com/downloads "Click here to access the download link.").

Open a terminal, and clone the project:
```
git clone https://gitlab.com/dark-themes/uniform-dark-theme-sn.git
```

(Recommended) Verify the project's authenticity: Look upward for "Verified," next to the commit SHA.

(Recommended) Open a terminal, and verify the project's integrity:
```
cd uniform-dark-theme-sn
git show-ref --heads --hash
```
Check that the hash matches the commit SHA.

Generate an author link at [https://listed.to](https://listed.to/ "Click here to access the website.").

Open either Standard Notes Desktop or Web, and import and install the author link as an extension. Include the space at the end (i.e., "= "); do not omit it.

Create a note, and paste contents from **my-extension.json** into it. Then, go to Actions and select Publish to Private Link.

Obtain the **latest_url** address, which is mentioned in my-extension.json: Go to Actions, and select Open Private Link. The address will be posted in the address bar. Hold onto it. (No need to replace the latest_url address mentioned in my-extension.json.) <!--what if need update ping? maybe discuss standard notes later?-->

### Standard Notes Desktop

Open a terminal, and populate a remote empty public GitHub repository:<br>
(Up to Standard Notes 3.3.5, an empty GitLab repository had worked. 'No longer.)
```
cd uniform-dark-theme-sn
git remote rename origin old-origin
git remote add origin [empty GitHub repository URL]
git push -u origin master
```
Create and push a tag:
```
git tag -a [tag name] -m "[comment]"
git push origin [tag name]
```
Update the **download_url** address in the Standard Notes note:<br>
(again, the note into which you pasted contents from my-extension.json)<br>
`"download_url": "[GitHub repository URL]/archive/[tag name].zip"`

Go to Actions, and select Update Private Post.

Standard Notes Web does not utilize the download_url, only Desktop utilizes it.

### Standard Notes Web

Create another remote empty public GitHub repository, but name it:<br>
`[username].github.io`

Upload **stylesheet.css**

Update the **url** address in the Standard Notes note:<br>
`"url": "https://[username].github.io/stylesheet.css"`

Update Private Post, again.

Standard Notes Desktop does not utilize the url, only Web utilizes it.



<!-- New project > Create from template: Pages/Plain HTML
Project settings > Advanced > Change project path to https://gitlab.com/dark-themes/[namespace].gitlab.io
"url": "https://dark-themes.gitlab.io/[stylesheet name].css"

The raw file (i.e., [https://gitlab.com/dark-themes/uniform-dark-theme-sn/-/raw/master/stylesheet.css](https://gitlab.com/dark-themes/uniform-dark-theme-sn/-/raw/master/stylesheet.css "Click here to access the raw file.")) will not work.

Instead, stylesheet is also hosted on GitLab Pages:
[https://saegl5.gitlab.io/css/stylesheet.css](https://saegl5.gitlab.io/css/stylesheet.css) -->

Work in progress...
<!-- easier way: try plain html -->

<!--## Usage

Import and install the latest_url (i.e., the address held onto earlier) as an extension. Then, Activate the theme.

need extended?
depends if web or application
**<u>WARNING!</u>** Do NOT install this theme in Standard Notes Mobile! Not yet! The theme currently crashes Standard Notes Android, and it may crash the iOS app too. Wait until a???

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

## Known Issues

- [x] ~~Theme does not work in Standard Notes 3.4.1 ([#550](https://github.com/standardnotes/desktop/issues/550))~~ - **Fixed!**<br>
- [x] ~~Theme does not work with Web client~~ - **Fixed!**<br>
- [x] ~~Desktop client has stronger font-weight after upgrading from version 3.3.5 to 3.4.1 ([#551](https://github.com/standardnotes/desktop/issues/551),[#14948](https://github.com/electron/electron/issues/14948))~~ - **Contrasted colors more**<br>
- [ ] Theme crashes Android client (related to [#56](https://github.com/standardnotes/mobile/issues/56)?)

## License

MIT

Copyright (c) 2020 Ed Silkworth