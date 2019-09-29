** fexp **

fexp is a file explorer powered by [fzf](https://github.com/junegunn/fzf)

By itself it won't do much, so you'll need to create an alias in your .bashrc like so:

```
alias cde='tput smcup; cd $(/path/to/fexp); tput rmcup'
```

That way you can explore and move around your computer.

![](output.gif)
