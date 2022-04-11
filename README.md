# moroboxai-metapackage

This mono-repo bundles the many moroboxai packages and uses [lerna](https://github.com/lerna/lerna) for providing a fast development environment.

## Setup

Checkout and build the packages:

```
git clone https://github.com/moroboxai/moroboxai-metapackage.git
cd moroboxai-metapackage
git submodule init
git submodule update
npm i
npm run bootstrap
npm run build
```

## License

Licensed under the [MIT](https://github.com/moroboxai/moroboxai-metapackage/blob/main/LICENSE) License.
