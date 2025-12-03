# PakRt-VPS
this purpos to making vps for PakRt

- masuk ke vps
  [ ssh -p 17523 indomaret@0.tcp.ap.ngrok.io ]
  
- membuat mesin debian container
  1. jadikan super user
  2. buat container debian
     [ sudo docker run -it --name faza-deb --hostname faza-machine debian:latest bash ]
  3. jika mau keluar
     [ exit ]
  4. jika mau masuk ke faza-machine
     [ sudo docker start -i faza-deb ]

  - mainkan mesin anda !!
