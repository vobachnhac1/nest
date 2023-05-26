Setup detox for text mobile App
docs: https://wix.github.io/Detox/docs/introduction/getting-started/
install detox global : yarn global add detox-cli
install applesimutils (MacOS Only): brew tap wix/brew brew install applesimutils
React native install
yarn add "jest@^29" --dev
yarn add detox --dev
Now, when all the dependencies are installed, initialize Detox in your project: npx detox init
Run Detox Test
detox build --configuration ios.sim.debug
detox test --configuration ios.sim.debug
