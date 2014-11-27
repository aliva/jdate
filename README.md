# jdate

a simple python script to have `date` command for jalali dates in command line

## install

```
pip install jdate
```

## usage

I wanted to implement date command (a linux command) for jalali date.
I didn't implemented all options (just the base options I needed at the time)
if you want other options please create an issue or send a pull request

```
jdate
#Cha Aza 05 21:38:10  1393
```

you can use time formats, (for a list of availabe time foramtters check `man date`)

```
jdate +FORMAT

jdate +%Y-%m-%d
# 1393-09-05
```



