# reprint-solver-unidic
翻刻制約解消器用の中古和文UniDicファイル

著作権上、中古和文UniDicのファイルを翻刻制約解消器のリポジトリ(reprint-solver)に含めたくない。
そこで翻刻制約解消器が使用する中古和文UniDicのファイルをこちらのリポジトリにまとめた。

## 使用法
gzipで圧縮されたファイルをシェルスクリプトで展開してからファイルを移動する。
下記手順中のSOMEWHEREは翻刻制約解消器のリポジトリのあるディレクトリ。
```
% ./expand_unidic.sh
% mv lex.csv SOMEWHERE/reprint-solver/solver/dic/
% mv matrix.bin SOMEWHERE/reprint-solver/solver/dic/
```

