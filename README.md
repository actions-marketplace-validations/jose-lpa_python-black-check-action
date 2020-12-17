# Python BlackCheck action

GitHub Action for [black](https://github.com/psf/black)

Based on the [black-check](https://github.com/jpetrucciani/black-check) from @jpetrucciani.


## Inputs

### `path`

**Optional** The path to run black on.
**Default** `"."`

### `line-length`

**Optional** Number of characters allowed per line on Black check.
**Default** 100

## Outputs

The Black command output.

## Example usages

Just use it with defaults:

```yaml
uses: jose-lpa/python-black-check-action@master
```

```yaml
# Specify a path and a max. line length allowed.
uses: jose-lpa/python-black-check-action@master
with:
  path: '.'
  line-length: 80
```
