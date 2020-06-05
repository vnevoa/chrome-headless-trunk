# Scalingo Buildpack for Chromium Headless Trunk

Using the binary from the Chromium snapshot bucket

```
$ docker run -it --rm -p=0.0.0.0:9222:9222 --name=chrome-headless -v /tmp/chromedata/:/data vnevoa/chrome-headless-trunk
```

Forked from
- [Alpeware](https://github.com/alpeware/docker-chrome-headless)

