# README

Hacked up version of https://github.com/dgraziotin/docker-nginx-webdav-nononsense with simple nginx config from https://github.com/colleenkhenry/shaka-streamer-demo/blob/main/nginx/sites-available/default

# Running the container
```
docker-compose build
docker-compose up
```

# Streaming to the container
Configure your HTTP push output to point at your system's IP address with port 32080, and a unique path for your stream (example: http://YOUR_IP_HERE:32080/test). 
You can then view your stream by opening http://YOUR_IP_HERE:32080/test/master.m3u in your browser.