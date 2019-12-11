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

## License
MIT
