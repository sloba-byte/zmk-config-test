For local dev:
https://zmk.dev/docs/development/setup


then from:
```sh
cd /home/straddler/Documents/git/zmk/app
```

run:
```sh
west build -b nice_nano -- -DSHIELD=my_reviung41  -DZMK_CONFIG="/home/straddler/Documents/git/zmk-config-test/config"
```
Enter bootloader mode and then:
```sh
\cp /home/straddler/Documents/git/zmk/app/build/zephyr/zmk.uf2 /media/straddler/NICENANO/ 

```

new ergogen design

https://flatfootfox.com/ergogen-part2-outlines/