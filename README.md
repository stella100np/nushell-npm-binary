# nushell-npm-binary

When NPM installs packages such as Electron, Puppeteer, etc., they will download the corresponding binaries through the `postinstall` script. For unknown reasons this process may be slow or unavailable on some networks.

Also, if you use nushell, just run this in nushell

```shell
nu enr.nu
```
inspired by [antfu`s blog](https://antfu.me/posts/npm-binary-mirrors)
