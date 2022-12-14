---
title: Contributing
---

## Steps to contribute

Before the contribution you need check the file structure on the
[Readme Source File](./src/README.md) and follow this steps

1. Make a Fork to this repository
2. Make a branch with the feature to add
3. Use the conventional commits guide
   [more information here](https://www.conventionalcommits.org/en/v1.0.0/)
4. Make a pull request with an explanation what you change or features
5. Review your pull request :nerd_face:
6. Merge the pull request or request changes
7. Done! :smiley:

## Requirements

- If you add a new file to the file structure ensure add to the tree on the
  [Readme Source File](https://github.com/dpmland/dpm/blob/main/src/README.md)
  and add this con the header on the file:

```ts
// Copyright © 2022 Dpm Land. All Rights Reserved.
```

- Ensure check the lint and the format before the commit with this command:

```
deno task fmt
```

- Use underscores, not dashes in filenames example:

```ts
example_file.ts; // GOOD
example - file.ts; // BAD
```

- Inclusive code:

Please follow the guidelines for
[inclusive code](https://chromium.googlesource.com/chromium/src/+/master/styleguide/inclusive_code.md)

- For end any readme file you need add this at the end!

```md
---

Made with :heart: in :earth_americas:
```

And done thanks for contribute

## Format and lint!

For the formatting and lint you need run the **deno tasks** here are some
commands for make the development more easier.

```sh
deno task ## For list all tasks avaliable!
deno task fmt ## For format all files and check the lint!
deno task fmt:check ## For check the lint and formatting
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
