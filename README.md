# Learn Node Manager

## Node版本限制

在执行 `yarn` 或者 `npm` 等命令时，优先进行版本检测。

## [nvm VS n](https://fed.taobao.org/blog/taofed/do71ct/nvm-or-n/)

`nvm` 不会影响到全局 `node` 版本。它的生效期是在每一个 `shell` 沙盒内。

而所有的 `node` 版本都声明在 `~/.nvm/versions` 下。

`n` 始终是改变 `/usr/local/bin` 下的 `node` 版本，因此实际上 `n` 是影响全局 `node` 版本的。
