
# _git_ `❯❮❯`
> A git aliases plugin for [Fisher][fisher-link],
mirroring the aliases from the  [Prezto Git Module][prezto-git-module-link]
and inspired the [Fish git plugin][fish-git-link].

[![MIT License](https://img.shields.io/badge/license-MIT-007EC7.svg?style=flat-square)](/LICENSE)


## Install

fisher:
```fish
fisher install sparetimecoders/fish-git-plugin
```

## Default branch name

`plugin-git` respects `init.defaultBranch` setting that was [introduced in git 2.28](https://github.blog/2020-07-27-highlights-from-git-2-28/#introducing-init-defaultbranch).
The order for resolving the default branch name is as follows:

1. `init.defaultBranch` if it is set and the branch exists
2. `main` if it exists
3. `master` as fallback

# License

[MIT][mit] © [Peter Svensson][author] et [al][contributors]


[mit]:            https://opensource.org/licenses/MIT
[author]:         https://github.com/peter-svensson
[fisher-link]:    https://github.com/jorgebucaran/fisher
[prezto-git-module-link]: https://github.com/sorin-ionescu/prezto/tree/master/modules/git
[fish-git-link]: https://github.com/jhillyerd/plugin-git
