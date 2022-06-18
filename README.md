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

## Commands

  * `npm run build`: build all
  * `npm run build-game-sdk`: only build moroboxai-game-sdk
  * `npm run build-editor-sdk`: only build moroboxai-editor-sdk
  * `npm run build-editor-web`: only build moroboxai-editor-web
  * `npm run build-editor-react`: only build moroboxai-editor-react
  * `npm run build-editor`: build all editor packages
  * `npm run build-player-sdk`: only build moroboxai-player-sdk
  * `npm run build-player-web`: only build moroboxai-player-web
  * `npm run build-player-react`: only build moroboxai-player-react
  * `npm run build-player`: build all player packages
  * `npm run build-moroxel8ai-sdk`: only build moroxel8ai-sdk
  * `npm run build-moroxel8ai`: build all moroxel8ai packages
  * `npm run build-pong`: build @moroboxai-games/pong
  * `npm run dev-editor-web`: run a local server for testing moroboxai-editor-web
  * `npm run dev-editor-react`: run a local server for testing moroboxai-editor-react
  * `npm run dev-editor`: run a local server for testing moroboxai-editor-web
  * `npm run dev-player-web`: run a local server for testing moroboxai-player-web
  * `npm run dev-player-react`: run a local server for testing moroboxai-player-react
  * `npm run dev-player`: run a local server for testing moroboxai-player-web
  * `npm run dev-pong`: run a local server for testing @moroboxai-games/pong

## License

Licensed under the [MIT](https://github.com/moroboxai/moroboxai-metapackage/blob/main/LICENSE) License.
