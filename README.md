# README
Erlang in Angarの翻訳用レポジトリです。オリジナルのREADMEは[こちら](./README.en.md)を参照してください。

# 最新版
* [2018.06.18 08:57版](https://drive.google.com/file/d/1gxJT8RvxsxpT2D4zyhqUIVZsOuHiCtps/view?usp=sharing)

# Contribution
## 雰囲気
自分一人でやるのはしんどいのでpull-requestください。
翻訳するときはオリジナルのものをコメントアウトする形でやっていきます。
詳しくは `NNN-foobar-ja.tex` で翻訳済みになっているファイルを参照してください。

## レビュー
訳がおかしいなと思ったら適宜Issueを立ててください。(TODO: Issueテンプレートの作成)

# Build
TeX Liveをとりあえずインストールしてビルド。オリジナルはpdfLaTeXを使って生成している。
Latexmkを使ってビルドできるようになっているので各々次のようにビルドする。

```console
$ make english   # -> text.pdf: original English version
$ make japanese  # -> text-ja.pdf: Japanese translation version
```

# 進捗
- [x] 000: Copyright
- [x] 001: Introduction
- [ ] 101: How to Dive into a Code Base
- [ ] 102: Building Open Source Erlang Software
- [ ] 103: Planning for Overload
- [ ] 104: Connecting to Remote Nodes
- [ ] 105: Runtime Metrics
- [ ] 106: Reading Crash Dumps
- [ ] 107: Memory Leaks
- [ ] 108: CPU and Scheduler Hogs
- [ ] 109: Tracing
- [x] 201: Conclusion