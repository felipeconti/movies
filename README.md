# movies
Play movies


docker run -d --net=host --restart=always -v /home/pi/hd:/data --name=minidlna felipeconti/rpi-minidlna
docker run -d --net=host --restart=always -v /home/pi/hd:/data -v /home/pi/config:/config --name=deluge felipeconti/rpi-deluge
