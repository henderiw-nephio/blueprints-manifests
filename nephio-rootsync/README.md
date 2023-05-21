# nephio-rootsync

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] nephio-rootsync`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree nephio-rootsync`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init nephio-rootsync
kpt live apply nephio-rootsync --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
