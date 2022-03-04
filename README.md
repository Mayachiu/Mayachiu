# CTAProject2022
[CTAProject2022](https://github.com/Mayachiu/CTAProject2022)

サイバーエージェント Tech Accel 2022で使用しているプロジェクト

サイバーエージェント22卒のメンターの方にレビューを頂きながら、学習を進めました。[プルリクエスト](https://github.com/Mayachiu/CTAProject2022/pulls?q=is%3Apr+is%3Aclosed)

[RxSwift+MVVM](https://github.com/Mayachiu/CTAProject2022/tree/task1/MVVM)このブランチでRxSwift+MVVMへの書き換えを行っています。

セットアップは
```
make setup
```
## 使用技術
- ホットペッパーAPI
- SwiftGen
- URLSession
- PKHUD(インジケーター表示のライブラリ)
- SwiftMessages(警告表示のライブラリ)
- RxSwift
- RxCocoa
- SwiftLint(差分の関係で現在未対応)
- Git

## 意識した点
- ViewはStoryboardを使わずXibで実装
- Xibの利点を活かし、デザイン部分はXib,InterdaceBuilderで実装し、文字関係の処理はSwiftGenを利用
- APIClientはライブラリを使用せずに、URLSessionで実装
- APIキーはMyAPIKey.swiftというファイルに置いてpushせずに利用
- ライブラリを利用することでアニメーションを簡易化

# 標識マスター
[標識マスター](https://apps.apple.com/us/app/%E6%A8%99%E8%AD%98%E3%83%9E%E3%82%B9%E3%82%BF%E3%83%BC-%E9%81%8B%E8%BB%A2%E5%85%8D%E8%A8%B1%E5%AF%BE%E7%AD%96%E3%81%AB%E6%9C%80%E9%81%A9%E3%81%AA%E3%82%A2%E3%83%97%E3%83%AA/id1590156979)
App Storeで1300ダウンロード

# TweetSearch
[TweetSearch](https://apps.apple.com/jp/app/tweetsearch-%E3%83%84%E3%82%A4%E3%83%BC%E3%83%88%E6%A4%9C%E7%B4%A2%E3%82%92%E7%B0%A1%E5%8D%98%E3%81%AB/id1589606489)
Twitterで拡散され、160いいね