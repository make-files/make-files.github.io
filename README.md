# Makefiles

## Usage

```Makefile
-include artifacts/make/<LANGUAGE>/v<VERSION>/Makefile

artifacts/make/%:
	curl -sfL https://makefiles.dev/v1 | bash /dev/stdin $*
```
