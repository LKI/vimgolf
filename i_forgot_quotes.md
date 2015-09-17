# Start file:

```
foo = a
      ab
      abc
```


# End file:

```
foo = "a"
      "ab"
      "abc"
```


# Launch Command:

```
vimgolf put 5462e3f41198b80002512673
```


# Trys:

```
$<C-V>GI"<Esc>A"<Esc>j.j.ZZ
$<C-V>GI"<Esc><C-V>G$A"<Esc>ZZ
ta<C-V>jjA"<Esc>$.ZZ
<C-V>? <CR>A"<Esc>$.ZZ
<C-V>GhA"<Esc>$.ZZ
```


# Secrets:

`G` : Go to first non-blank char on last line

`.` : Repeat last change
