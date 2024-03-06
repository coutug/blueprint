# test-app

## Description
test-app

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] test-app`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree test-app`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init test-app
kpt live apply test-app --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
