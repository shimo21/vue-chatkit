# vue_chatkit
chatkitを利用したチャットアプリ

## Chatkit setup
1. chatkitのアカウントを作成する
https://pusher.com/chatkit

2. chatkitでinstanceを作成

3. credientialsから必要な情報を取得

4. .env.localをリポジトリ直下に作成
```
VUE_APP_INSTANCE_LOCATOR=XXXXXXXXXXX
VUE_APP_TOKEN_URL=XXXXXXXXXXX
VUE_APP_MESSAGE_LIMIT=10
```

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Lints and fixes files
```
yarn run lint
```
