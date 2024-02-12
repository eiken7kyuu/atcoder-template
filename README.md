
### REPL の実行

`stack repl` で `Main.hs` を読み込んだ REPL を起動できます:

```sh
$ stack repl a/Main.hs
```

### スクリプト実行

`Main.hs` を Stack スクリプトとして実行します:

```sh
$ stack a/Main.hs
$ ./a/Main.hs
```

### コンパイル実行

`stack run` で実行できます:

```hs
$ stack run a-exe
```


```
oj t -c "stack Main.hs"

acc submit Main.hs
```