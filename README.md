FROM nginx

EXPOSE 3000

ADD ./Dockerfilefolder/content/ / usr/share/nginx/html