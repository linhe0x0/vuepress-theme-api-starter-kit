# vuepress-theme-api-starter-kit

> A out-of-the-box starter kit for https://github.com/sqrthree/vuepress-theme-api.

![image](https://user-images.githubusercontent.com/8622362/40341249-9b6e8b9e-5db6-11e8-97f5-41cadc87ce51.png)

## Built With

- [Node.js](https://nodejs.org/)
- [VuePress](https://github.com/vuejs/vuepress)

## Prerequisites

There are some global dependencies you need to set up.

- [Node.js](https://nodejs.org/)
- [VuePress](https://github.com/vuejs/vuepress)
- [vuepress-theme-api](https://github.com/sqrthree/vuepress-theme-api)

## Getting Started

```bash
$ git clone https://github.com/sqrthree/vuepress-theme-api-starter-kit.git
$ cd vuepress-theme-api-starter-kit
$ yarn # OR npm install
```

### As Easy as 1, 2, 3

```bash
# Install vuepress
yarn global add vuepress # OR npm install -g vuepress

# Install theme
yarn global add vuepress-theme-api # OR npm install -g vuepress-theme-api

# Create a markdown file and write something
echo '# Hello, World.' > docs/Hello.md

# Start writing
vuepress dev docs # OR yarn run theme:dev OR npm run theme:dev

# Build to static files
vuepress build docs # OR yarn run theme:build OR npm run theme:build

# Static server
yarn run theme:serve # OR npm run theme:serve
```

## Configuration

See [vuepress-theme-api](https://github.com/sqrthree/vuepress-theme-api#vuepress-theme-api) to get more details.
