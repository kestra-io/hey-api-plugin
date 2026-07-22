# hey-api-plugin

Release host for `@kestra-io/hey-api-plugin` — the shared Kestra SDK generator plugin and fetch runtime.

The source of truth lives in [kestra-io/kestra](https://github.com/kestra-io/kestra/tree/develop/ui/packages/hey-api-plugin) (`ui/packages/hey-api-plugin`), where it's consumed as an npm workspace by the OSS and EE UIs.

This repo has no source code — it exists only to host versioned GitHub Release tarballs, built and published by kestra-io/kestra's *Release hey-api-plugin* workflow, so that [kestra-io/client-sdk](https://github.com/kestra-io/client-sdk) can consume a release tarball URL without going through npm or needing authentication.

See the [releases](https://github.com/kestra-io/hey-api-plugin/releases) for available versions.
