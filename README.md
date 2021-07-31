# gitdoc-autocommit-issue-demo

This repo is to a demonstration of an issue ([issue 21](https://github.com/lostintangent/gitdoc/issues/21)) with the [GitDoc](https://github.com/lostintangent/gitdoc/) VSCode extension, namely that the `commitOnClose` setting doesn't work [as documented](https://github.com/lostintangent/gitdoc#contributed-settings):

> - `GitDoc: Commit on Close` - Specifies whether to automatically commit changes when you close VS Code. Defaults to `true`.

According to [the extension's ChangeLog](https://marketplace.visualstudio.com/items/vsls-contrib.gitdoc/changelog) this feature was added in release v0.0.7 (2021-03-07); specifically we have [commit 4b8f7f39](https://github.com/lostintangent/gitdoc/commit/4b8f7f3942a79bd52c554674361736aa09190174) (2021-03-07) in response to [issue 11](https://github.com/lostintangent/gitdoc/issues/11) (closed 2021-03-07).

## Version info

I witnessed this behavious on a fresh install of VSCode (on a Mac), where GitDoc is the only installed extension.

* MacBook Pro (13-inch, M1, 2020)
* macOS Big Sur 11.5.1
* VSCode
  - Version: 1.58.2
  - Commit: c3f126316369cd610563c75b1b1725e0679adfb3
  - Date: 2021-07-14T22:10:12.490Z
  - Electron: 12.0.13
  - Chrome: 89.0.4389.128
  - Node.js: 14.16.0
  - V8: 8.9.255.25-electron.0
  - OS: Darwin arm64 20.6.0
* GitDoc v0.0.8
