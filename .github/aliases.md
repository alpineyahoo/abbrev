Here are some useful aliases:

```shell
alias beep="osascript -e 'beep'"
alias zzz='pmset sleepnow'

# aliases for sh config
alias catz='cat ~/.zshrc'
alias apndz='echo $1 >> ~/.zshrc'
alias edz='nano ~/.zshrc'
alias srcz='source ~/.zshrc'

# aliases for YouTube downloads
alias ytmp3='youtube-dl -x $(pbpaste) -f bestaudio --audio-format mp3'
alias ytmp4='youtube-dl $(pbpaste) -f best'
```

Just register them in your `~/.zshrc` (or `~/.bashrc`)
<br>
Some aliases are NOT in this list but in `abbrev` directory. Some aliases have to be exec to treat arguments.
