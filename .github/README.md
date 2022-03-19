# abbrev
Save time with less typing :)
<br>
Those above are executables as aliases. You can see [aliases.md](https://github.com/alpineyahoo/abbrev/blob/main/.github/aliases.md) file for registering aliases to your shell config (`~/.zshrc`, `~/.bashrc` etc.)
## Installation (⚠️ まだ書き途中です)

```shell
# "abbrev" という名前のチャイルドディレクトリを持たないディレクトリで実行
# run in a dir not holding a dir named "abbrev"

# コマンドの意味を理解してから実行
# run after you come to understand these behaviours

$ git clone https://github.com/alpineyahoo/abbrev.git
$ cd abbrev
$ sudo rm -r .git*
$ cat aliases.txt >> ~/.zshrc
$ rm aliases.txt
$ chmod +x *
$ mv -i * /usr/local/bin # make sure /usr/local/bin is in $PATH
$ cd ..
$ rmdir abbrev
```
## 追記
`aliases.txt` の `ytmp3`, `ytmp4` を修正しました。(エイリアスにしたとき `$(pbpaste)` はクウォートしないと認識されないみたいです…)
