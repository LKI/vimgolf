# Start file:

```
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

This challenge is just a simple movement and entering text at a certain place.
```


# End file:

```
*temp var1 0
*temp var2 "hi"
*temp var3 -1
*temp var4 42
*temp var5 "asdf"
*temp var6 0
*temp var7 11

Simple things we do all the time should be able to be done with very few keystrokes, but sometimes I find something I need to do makes me go, "There MUST be a better way."

New text.

This challenge is just a simple movement and entering text at a certain place.
```


# Launch Command:

```
vimgolf put 55b18bbea9c2c30d04000001
```


# Trys:

```
5jYpf6C7 11<Esc>2jo<CR>New text.<Esc>ZZ
Y}Pf1C7 11<Esc>3jO<CR>New text.<Esc>ZZ
}kYp<C-A>l11<C-A>3jO<CR>New text.<Esc>ZZ
}kYp<C-A>w11.GONew te<C-N>.<CR><Esc>ZZ
#Yp<C-A>w11.GONew te<C-N>.<CR><Esc>ZZ
```


# Secrets:

`#`     : Search bottom-top

`<C-A>` : Add by one

`<C-N>` : Complete by occursion
