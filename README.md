[CTAProject2022](https://github.com/Mayachiu/CTAProject2022)

サイバーエージェント Tech Accel 2022で使用しているプロジェクト

サイバーエージェント22卒のメンターの方にレビューを頂きながら、学習を進めました。[プルリクエスト](https://github.com/Mayachiu/CTAProject2022/pulls?q=is%3Apr+is%3Aclosed)

[RxSwift+MVVM](https://github.com/Mayachiu/CTAProject2022/tree/task1/MVVM)このブランチでRxSwift+MVVMへの書き換えを行っています。

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
