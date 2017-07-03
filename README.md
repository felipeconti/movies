# movies
Play movies

## Run Minidlna
```sh
docker run -d --net=host --restart=always -v /home/pi/hd:/data --name=minidlna felipeconti/rpi-minidlna
```
## Run Deluge
```sh
docker run -d --net=host --restart=always -v /home/pi/hd:/data -v /home/pi/config:/config --name=deluge felipeconti/rpi-deluge
```
