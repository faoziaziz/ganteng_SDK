# Driver Untuk Cinta 

Ada beberapa case untuk driver sdk USB beberapa mode USB yang bisa digunakan :

1. VCOM ttyACM
2. Serial ttyUSB
3. 

## Requirements

for Ubuntu or Debian based

```sh
sudo apt-get update
sudo apt-get install usbutils
```

## Compile 
```sh
gcc -o build/cek src/main.c -lusb
```
