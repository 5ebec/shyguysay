# shyguysay
`cowsay` for Shy Guy

```
 ___________________________
( ヘイホーのAAって良いの無いよね )
 ---------------------------
                O         _____
                 o      ／____ ＼
                   。  /／    ＼_＞
                       H ⬤ ⬤  H
                      /\   o    /＼
                     (_/＼____／\__)
                       (===[]====)
                       (__)  (___)
```

```
             ______________
            ( 逆向きもあるよ )
             --------------
     _____        O
   ／ ____＼     o
 ＜_／    ＼\  。
   H  ⬤ ⬤ H
 ／\    o   /\
(__/＼____／\_)
  (====[]===)
  (___)  (__)
```

## what's cowsay
ja: [cowsay](https://ja.wikipedia.org/wiki/Cowsay)  
en: [cowsay](https://en.wikipedia.org/wiki/Cowsay)

## Usage
### macOS
almost the same for other OSes

Install cowsay:
```shell
$ brew install cowsay
```

Clone this repo:
```shell
$ git clone https://github.com/5ebec/shyguysay
```

Using the parameter `-l` shows cows folder and all available cowfiles:
```shell
$ cowsay -l
Cow files in /usr/local/Cellar/cowsay/3.04/share/cows:
beavis.zen blowfish bong bud-frogs bunny cheese cower daemon default dragon
dragon-and-cow elephant elephant-in-snake eyes flaming-sheep ghostbusters
head-in hellokitty kiss kitty koala kosh luke-koala meow milk moofasa moose
mutilated ren satanic sheep skeleton small sodomized stegosaurus stimpy
supermilker surgery telebears three-eyes turkey turtle tux udder vader
vader-koala www
```

Copy `.cow` files to cows folder:
```shell
$ cp shyguysay/*.cow /usr/local/Cellar/cowsay/3.04/share/cows
```

## Example
```shell
$ w -i | cowsay -n -f shyguy
 ___________________________________________________________________________________________________
/ 23:12  up 19:57, 5 users, load averages: 2.24 2.82 2.76                                           \
| USER     TTY      FROM              LOGIN@  IDLE WHAT                                             |
| 5ebec    s001     -                20:19       - /usr/bin/perl /usr/local/bin/cowsay -n -f shyguy |
| 5ebec    s006     -                20:01       - -zsh                                             |
| 5ebec    s000     -                 3:36    2:50 -zsh                                             |
| 5ebec    s004     -                20:01    3:11 -zsh                                             |
\ 5ebec    console  -                 3:16   19:56 -                                                /
 ---------------------------------------------------------------------------------------------------
               \      _____
                \   ／____ ＼
                   /／    ＼_＞
                   H ⬤ ⬤  H
                  /\   o    /＼
                 (_/＼____／\__)
                   (===[]====)
                   (__)  (___)  
                   
```
## License
MIT
