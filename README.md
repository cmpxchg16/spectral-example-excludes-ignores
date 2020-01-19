![](https://travis-ci.org/SpectralOps/spectral-example-excludes-ignores.svg?branch=master)
# Spectral Ignores and Excludes

In this example you'll see how to:

1. Ignore rules wholesale
2. Ignore a specific file under a particular rule


First, note both files in [src](src/) contain issues.

* Look at [.spectral/spectral.yaml](.spectral/spectral.yaml), and note the `rules` section with `exclude` marking the `CLD001` rule as excluded.
* Look at [.spectral/ignores.json](.spectral/ignores.json), and not the rule `CLD006`, with regards to the file `main_2.rb` is being ignored and not reported as an issue.
* Passing on [Travis CI](https://travis-ci.org/SpectralOps/spectral-example-excludes-ignores)