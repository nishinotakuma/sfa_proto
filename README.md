# sfa_proto

## 起動方法

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

- Homebrewをインストールhttp://brew.sh/index_ja.html

ターミナルを開いて以下のコマンドを実行

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- node.jsが入っていない場合はnodejsをインストール

```zsh
brew install node
```

- watchmanをインストール(bug監視のため)

```zsh
brew install watchman
```

- reactNativeをグローバルにインストール

```zsh
npm install -g react-native-cli
```

### androidエミュレータを使う場合
公式ドキュメントに沿ってAndroid Studioをインストールする。
https://facebook.github.io/react-native/docs/getting-started.html#java-development-kit
