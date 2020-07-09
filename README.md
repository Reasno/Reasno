```Dockerfile
FROM CHINA:1990
ENV BEIJING
WORKDIR /huijiwiki.com
RUN git clone https://github.com/Reasno/Reasno
CMD ['whoami']
```
