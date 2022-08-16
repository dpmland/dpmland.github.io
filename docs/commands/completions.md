---
title: Completions
---

# The completions command!

## Arguments for the Command :computer:

You can use this arguments on the: **completions** command

| Arguments | Description                          |
| --------- | ------------------------------------ |
| bash      | Generate shell completions for bash. |
| fish      | Generate shell completions for fish. |
| zsh       | Generate shell completions for zsh.  |

## Flags for the Command :pirate_flag:

You can use this flags on the: **completions** command

| Flags  | Description          |
| ------ | -------------------- |
| --help | The CLI Help Message |

### Configure in your shell

To enable the shell completions follow the steps bellow:

#### Bash

To enable bash completions for this program add following line to your
`~/.bashrc`:

```sh
source <(dpm completions bash)
```

#### Fish

To enable fish completions for this program add following line to your
`~/.config/fish/config.fish`:

```fish
source (dpm completions fish | psub)
```

#### Zsh

To enable zsh completions for this program add following line to your
`~/.zshrc`:

```sh
source <(dpm completions zsh)
```

## Bugs report :bug:

For report bugs or errors in the documentation make a issue on the docs repo or
in the dpm repo on the [dpmland org](https://github.com/dpmland/) and the:

- _[DPM REPO](https://github.com/dpmland/dpm)_: For bugs in the CLI
- _[DOCS REPO](https://github.com/dpmland/docs)_: For bugs in the documentation
- _[WEB REPO](https://github.com/dpmland/web)_: For bugs in the website
- _[DPMLAND.GITHUB.IO REPO](https://github.com/dpmland/dpmland.github.io)_: For
  bugs in the online website

---

Made with :heart: in Ecuador and the World
