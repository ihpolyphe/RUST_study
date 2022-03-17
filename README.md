# RUST_study
個人的なRUSTの勉強。
[公式チュートリアル](https://doc.rust-jp.rs/book-ja/title-page.html)に従って順に勉強していく。

## Install
Linux or WSLなら以下。
```
$ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
$ source $HOME/.cargo/env
```

## コンパイル方法
```
rustc <file>.rs
./<file>
```

## Cargo
- cargo newを使ってプロジェクトを作成できる
- cargo buildを使ってプロジェクトをビルドできる
- cargo runを使うとプロジェクトのビルドと実行を1ステップで行える
- cargo checkを使うとバイナリを生成せずにプロジェクトをビルドして、エラーがないか確認できる

＜使い方＞
RUSTインストールして、クローン、以下実行
cd hello_cargo
cargo build

## ToDo
- RUSTのメリット(C,C++に比べて安全性の高い言語？)