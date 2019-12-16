![image](https://user-images.githubusercontent.com/56011102/70880319-dea05500-200b-11ea-8dbe-902d34c5349b.png)

# これは何か

自作OSです

"Hello, World"と表示します

# 実行環境

```
$ brew install nasm
$ brew install make
$ brew install qemu
```

**nasm**: アセンブラです。機械が理解できる命令プログラム(アセンブリコード)を機械が理解できる命令(バイナリコード)に置き換えてコンピューターが実行できるようにします。

**make**: コンパイルを自動化するツールです。

**qemu**: キューエミューと読みます。自作したOSは、このエミュレーターを介して実行されます。いわゆる仮想マシンです。

※makeコマンドを打つことでqemuエミュレーターが起動し、nasmによってアセンブリファイルがコンパイル実行されます

# 実行コマンド

```
$ make qemu
```

# 作業ログ記事

https://wp.suwa3.me/2019/12/14/os%e8%87%aa%e4%bd%9c/
