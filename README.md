# minchus.github.io
Hugo generated GitHub Pages site

## Local Development

### Pre-requisites
- [Hugo](https://gohugo.io/getting-started/installing/)
- [Go](https://golang.org/doc/install)

### Initial Setup

```shell
git clone https://github.com/minchus/minchus.github.io.git
cd minchus.github.io
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update Theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

