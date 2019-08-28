# Makefiles

## Usage

```Makefile
-include .makefiles/<LANGUAGE>/v<VERSION>/Makefile

.makefiles/%:
	curl -sfL https://makefiles.dev/v1 | bash /dev/stdin "$@"
```
