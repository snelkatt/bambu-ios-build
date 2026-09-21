# BambuGateway iPhone build

This build-only repository compiles the public upstream source at commit
`59e0f7b1db20d0374a1c886d62d2abe2ea618396` using GitHub's macOS runner.
It contains no printer credentials or NAS configuration.

The workflow runs when first pushed to `main`, or from Actions > Build
BambuGateway IPA > Run workflow. After a successful build, download the
`BambuGateway-unsigned` artifact. Its IPA must be signed before installation
on an iPhone; it cannot be installed by simply opening it in Safari.

This workflow has been prepared but has not yet completed a build. Signing,
app groups, extensions, and push notifications still require device testing.

Upstream: https://github.com/leolobato/bambu-gateway-ios
