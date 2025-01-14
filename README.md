# chunkops.com

## Local development

### Requirements
- [Hugo (extended edition)](https://gohugo.io/getting-started/installing/)
- [Go](https://golang.org/doc/install)
- [git](https://git-scm.com)

A Visual Studio Code Dev Container configured with these dependencies is available in `.devcontainer/devcontainer.json`


### Setup

```shell
# Clone the repo
git clone https://github.com/solarith0/chunkops.com.git

# Change directory
cd chunkops.com

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

## Acknowledgments

This project uses the [Hextra](https://github.com/imfing/hextra) theme, licensed under the [MIT license](https://opensource.org/licenses/MIT), and was created using the [Hextra Starter Template](https://github.com/imfing/hextra-starter-template).

Built with Hugo, an open-source static site generator licensed under the [Apache 2.0 license](https://opensource.org/license/apache-2-0).
