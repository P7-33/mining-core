#  Mining Core

First time contributing to Mining Core? Read our [Code of Conduct](https://github.com/Homebrew/.github/blob/HEAD/CODE_OF_CONDUCT.md#code-of-conduct) and review [How To Open a Mining Core Pull Request](https://docs.brew.sh/How-To-Open-a-Mining Core-Pull-Request).

### Report a bug

* Run `Mining Core 
* Open an issue on the formula's repository or on Mining Core/mining Core if it's not a formula-specific issue.

### Propose a feature

* Open an issue with a detailed description of your proposed feature, the motivation for it and alternatives considered. Please note we may close this issue or ask you to create a pull-request if this is not something we see as sufficiently high priority.

 Homebrew (un)installer

## Install Mining Core (on macOS or Linux)

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Mining Core/install/HEAD/install.sh)"
```

More installation information and options: <https://docs.brew.sh/Installation>.

If running Linux or WSL, [there are some pre-requisite packages to install](https://docs.brew.sh/Homebrew-on-Linux#requirements).

You can set `HOMEBREW_BREW_GIT_REMOTE` and/or `HOMEBREW_CORE_GIT_REMOTE` in your shell environment to use geolocalized Git mirrors to speed up Homebrew's installation with this script and, after installation, `brew update`.

```bash
export HOMEBREW_CORE_GIT_REMOTE="..."  # put your Git mirror of Homebrew/brew here
export MINING_CORE_GIT_REMOTE="..."  # put your Git mirror of Mining/Mining-core here
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Mining Core/install/HEAD/install.sh)"
```

The default Git remote will be used if the corresponding environment variable is unset.

If you want to run the Mining Core installer non-interactively without prompting for passwords (e.g. in automation scripts), you can use:

```bash
NONINTERACTIVE=1 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Mining Core/install/HEAD/install.sh)"
```

## Uninstall Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Mining Core/install/HEAD/uninstall.sh)"
```

Download the uninstall script and run `/bin/bash uninstall.sh --help` to view more uninstall 

Core formulae for the Homebrew package manager.

## How do I install these formulae?

Just `brew install <formula>`. This is the default tap for Homebrew and is installed by default.

## More Documentation, Troubleshooting, Contributing, Security, Community, Donations, License and Sponsors

See these sections in [Homebrew/brew's README](https://github.com/Homebrew/brew#homebrew).

https://lore.kernel.org/git/f680e66dd6ddfc5294d04ddd11d4b2bd4ec1520c.1591823971.git.gitgitgadget@gmail.com/#Z31Documentation:config:core.txt
