# TND Func

A set of useful returning partials. 

See `functions` for instructions

## Install

```
# config.yaml
module:
  - path: github.com/theNewDynamic/hugo-module-tnd-func
```

## Use

Call for any partial in the `tnd-func` dir.

```
{{ $page = partial "tnd-func/GetPage" .Params.related_page }}
```
