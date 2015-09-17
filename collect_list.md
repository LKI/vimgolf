# Start file:

```
* item1
* item2
* item3
* item4
* item5
```


# End file:

```
item1,item2,item3,item4,item5
```


# Launch Command:

```
vimgolf put 559c30948ef59c0eb7000002
```


# Trys:

```
5J:s/ . /,/g<CR>2xZZ
dw:%s/\n. /,<CR>ZZ
<C-V>Gls,<Esc>x5gJZZ
```


# Secrets:

`<C-V>` : Visual-block mode in vim

`gJ`    : Join line without chaning space
