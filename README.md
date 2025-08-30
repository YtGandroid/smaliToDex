# smaliToDex
Karena gwa pernah mau download repo asli tapi udah gaada ini gua taro sini buat jaga2


### ubah dulu diractory nya jadi dex:
misal lu ada di folde `Smali` yang didalemnya ada folder sama file smalinya `com/example/helloWorld/main.smali` berarti abis perintah `cd Smali` buat masuk ke diractorinya lu ketik perintah:
```bash
java -jar smali.jar assemble com/example/helloWorld/main.smali -o classes.dex
```

### run
```bash
dalvikvm -cp classes.dex com.example.helloWorld.main
```
