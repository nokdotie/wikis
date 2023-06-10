# GitHub Token
Nok.ie depends on GitHub to hosts it's maven packages. This means authentication is required to pull or push dependencies. While credentials could be defined in the `build.sbt` file, we use an environment variable instead.

Create a [GitHub Personal Access Token](https://github.com/settings/tokens) with the "repo" and "write:packages" scopes. Store the generated token in an environment variable named `GITHUB_TOKEN`.
