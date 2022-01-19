# Lancet

`hugo-sst-lancet` is a sensible and opinionated base theme for Hugo. it is part of a set of small, sharp themes.

## Usage

Install the module:

```bash
$ hugo mod init github.com/anarchivist/hugo-sst-lancet/go.mod
$ hugo mod get -u
```

Add the module to your config file, e.g.

```yaml
module:
  imports:
    - path: github.com/anarchivist/hugo-sst-lancet
```

## Local development

The `exampleSite` directory has some basic content (some of which is taken from the [Hugo Basic Example site](https://github.com/gohugoio/hugoBasicExample)). From this repository's working directory, you can run `hugo -s exampleSite`.
