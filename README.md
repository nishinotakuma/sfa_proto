# sfa_proto

## 起動方法

### packageインストール
```
cd sfa_proto
npm install
```

### Rails起動
Rails側は普通にvagrant内で起動

### ios起動
以下のコマンドでxcodeのシミュレータが自動起動。
```
cd sfa_proto
react-native run-ios
```

### androidエミュレータ起動
あらかじめ、エミュレータを起動して、以下のコマンド。
```
cd sfa_proto
react-native run-android
```

## 新規開発環境構築

- xcodeをインストール（している人は飛ばす）

https://facebook.github.io/react-native/docs/getting-started.html#xcode

- node.jsが入っていない場合はnodejsをインストール([Reactのビルド方法](https://baseconnect.docbase.io/posts/133175#nodejs%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)のnodejsインストール方法と同じ)

```zsh
cd
git clone https://github.com/creationix/nvm.git ~/.nvm
source ~/.nvm/nvm.sh
nvm --version
nvm install v7.7.2
source ~/.nvm/nvm.sh
```

- reactNativeをグローバルにインストール

```zsh
npm install -g react-native-cli
```

### androidエミュレータを使う場合
公式ドキュメントに沿ってAndroid Studioをインストールする。

https://facebook.github.io/react-native/docs/getting-started.html#java-development-kit
