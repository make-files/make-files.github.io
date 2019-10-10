# Makefiles

## Usage

```Makefile
-include .makefiles/pkg/<PACKAGE>/v<VERSION>/Makefile

.makefiles/%:
	curl -sfL https://makefiles.dev/v1 | bash /dev/stdin "$@"
```
