```Dockerfile
FROM CHINA:latest
ENV BEIJING
WORKDIR /huijiwiki.com
RUN git clone https://github.com/Reasno/Reasno
CMD ['whoami']
```
