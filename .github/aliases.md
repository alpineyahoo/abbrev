Here are some useful aliases:

```shell
alias beep="osascript -e 'beep'"
alias zzz='pmset sleepnow'

# aliases for sh config
alias catz='cat ~/.zshrc'
alias apndz='echo $1 >> ~/.zshrc'
alias edz='nano ~/.zshrc'
alias srcz='source ~/.zshrc'

# aliases for YouTube downloads --------
alias ytmp3='youtube-dl $(pbpaste) -x -f bestaudio --audio-format mp3'
# install ffmpeg before use (requires ffmpeg/avconv and ffprobe/avprobe)
alias ytmp4='youtube-dl $(pbpaste) -f best'
# copy the desired YouTube video URL and execute this command in directory like Downloads folder for example
# --------------------------------------
```

Just register them in your `~/.zshrc` (or `~/.bashrc`)
<br>
Some aliases are NOT in this list but in `abbrev` directory. Some aliases have to be exec to treat arguments.
