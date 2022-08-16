# Installation :rocket:

Stable Version:

```sh
deno run -A --unstable https://dpmland.deno.dev/install stable
```

Development Version can check the features roadmap
[here](https://github.com/dpmland/dpm/pull/7):

```sh
deno run -A --unstable https://dpmland.deno.dev/install canary
```

# Windows EMOJIS Bug :bug:

Recommendation for Windows with the EMOJIS :alien: Well I found a bug with
emojis in the CLI and tried to find a solution and found this comment about this
issue and what causes this issue.

> There is an issue with Deno.stdout.write which doesn't handle unicode
> characters well. There is already an deno issue denoland/deno#6001. But i
> found a workaourund here denoland/deno#6131 (comment). You have to enable utf8
> character encoding in windows than it should work.

_Source [Here](https://github.com/c4spar/deno-cliffy/issues/113)_

And the solution proposed is added this to the top of the `profile.ps1` file can
be accessibly with this command `notepad $PROFILE` on Powershell!

```ps1
[Console]::OutputEncoding = [Text.UTF8Encoding]::UTF8
```

### Canary vs Stable

Well the canary version actually is the more updated and more features but some
of this not have documentation if you want docs use the stable in this case
however if want install the canary for test and go to the stable version you
only need run this :nerdface:

```sh
dpm upgrade stable
```

Or if you want go from stable to canary run:

```sh
dpm upgrade stable
```

---

Made with :heart: in Ecuador and the World
