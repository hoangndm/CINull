fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios sync_device_info

```sh
[bundle exec] fastlane ios sync_device_info
```



### ios manual_sign

```sh
[bundle exec] fastlane ios manual_sign
```



### ios increment_version

```sh
[bundle exec] fastlane ios increment_version
```



### ios commit_version

```sh
[bundle exec] fastlane ios commit_version
```



### ios firebase_beta

```sh
[bundle exec] fastlane ios firebase_beta
```

Push a new beta build to Firebase App Distribution

### ios beta_sign

```sh
[bundle exec] fastlane ios beta_sign
```

[Option 2] Sync All Development (Match => Github)

### ios beta_build

```sh
[bundle exec] fastlane ios beta_build
```



### ios beta

```sh
[bundle exec] fastlane ios beta
```

Push a new beta build

### ios release_sign

```sh
[bundle exec] fastlane ios release_sign
```



### ios release_build

```sh
[bundle exec] fastlane ios release_build
```



### ios release

```sh
[bundle exec] fastlane ios release
```

Push a new release build

### ios codesigning

```sh
[bundle exec] fastlane ios codesigning
```

Code Signing

### ios build_beta

```sh
[bundle exec] fastlane ios build_beta
```

iOS Build Beta

### ios test

```sh
[bundle exec] fastlane ios test
```

iOS Testing

### ios build_release

```sh
[bundle exec] fastlane ios build_release
```

iOS Build Release

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
