# Settings for the Eclipse-kuksa organization

The sole intention of this repository is to contain the [README.md](profiles/README.md) file that
will be shown at the [eclipse-kuksa github page](https://github.com/eclipse-kuksa)!


#### Pre-commit checks
The repository has [configuration file](.pre-commit-config.yaml) with pre-commits hooks.
It executes a number of checks that typically must pass for a new Pull Request to be accepted and merged.
You must manually configure pre-commit to use the provided hooks by running `pre-commit install` from the
repository top folder.

```bash
$ pip install pre-commit
$ pre-commit install
```
