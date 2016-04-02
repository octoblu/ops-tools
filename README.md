# ops-tools

Tools for managing Octoblu ops

## Install

The easiest way to obtain these tools is through homebrew

```shell
# make the octoblu tools able install via 'brew install'
brew tap octoblu/tools

# Then install the tools
brew install majorsync minorsync vulcansync run_on_major run_on_minor

# Or if you just want a subset of them
brew install majorsync
brew install minorsync
brew install vulcansync
brew install run_on_major
brew install run_on_minor
```

## Contributing

If you update any of the tools in here, you'll need to:

1. Tag it `git tag v1.0.0`
2. Draft a new release in [ops-tools releases](https://github.com/octoblu/ops-tools/releases)
3. Update the appropriate formula in  [octoblu/homebrew-tools](https://github.com/octoblu/homebrew-tools)
4. Test out the formula:

```shell
brew update
brew install octoblu/tools/<formula>    # prefix 'octoblu/tools/' is only nescessary
                                        # in case there's an identically named
                                        # package in the base homebrew tap
```
