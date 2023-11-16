# Imagem do Kali customizada para eu usar como Live USB 

https://www.kali.org/docs/development/live-build-a-custom-kali-iso/
https://live-team.pages.debian.net/live-manual/html/live-manual/customizing-contents.en.html

```bash
sudo apt install -y git live-build simple-cdd cdebootstrap curl

./build.sh --verbose --variant custom --no-clean
```

```bash
 sudo mount -i -o remount,exec,dev /media/kali/Extra
```
