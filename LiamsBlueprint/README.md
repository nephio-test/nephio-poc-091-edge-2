# LiamsBlueprint

## Description
Blah

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] LiamsBlueprint`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree LiamsBlueprint`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init LiamsBlueprint
kpt live apply LiamsBlueprint --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
