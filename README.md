```Dockerfile
FROM CHINA:latest
ENV BEIJING
WORKDIR /Users/bytedance
RUN git clone https://github.com/Reasno/Reasno
CMD ['whoami']
```
