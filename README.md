# Makefiles

## Usage

```Makefile
-include artifacts/make/[LANGUAGE]/Makefile

artifacts/make/%:
	curl -sfL https://fetch.makefiles.dev/v1 | bash /dev/stdin $*
```
