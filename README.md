# desktop-mew (MyEtherWallet)
A Desktop wrapper of MyEtherWallet(MEW) https://www.myetherwallet.com/ using https://electronjs.org/

# This project is EXPERIMENTAL, use it at your own risk.
# THIS PROJECT DO NOT SAVE THE PRIVATE KEYS INTERNALY. YOU MUST MAKE A BACKUP OF THE KEYFILE!! ONCE YOU QUIT THE APP THE KEYS ARE GONE.
## (although would be a nice feature to save internaly)

![alt text](https://i.gyazo.com/f84d7456d5cbf62b0fe99641b7539d39.png)

![alt text](https://i.gyazo.com/65f113e99801bde7e0dae1dd0cf9d530.png)

# instalation

```sh
# download this repo
git clone https://github.com/ernaneluis/desktop-mew.git

# can use yarn or npm
yarn install

# run following this order

# 1) get latest myEtherWallet version
yarn mew:get
# 2) go the mew folder and install dependencies
yarn mew:install
# 3) get latest gulp-cli as global function
yarn gulp:get
# 4) build mew for distribution
yarn mew:build
# 5) copy necessary files to build the desktop app
yarn prebuild
# 6) after this build, the app will be located at app/MyEtherWallet-darwin-x64 just double click and use it
yarn build:mac

# build:all will build for linux, mac and windows
yarn build:all
```