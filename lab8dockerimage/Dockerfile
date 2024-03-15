FROM nginx:1.25.3-alpine
# lastest version of nginx using alpine linux as base


# port to expose
EXPOSE 80
ENV MyName="Nate"
WORKDIR /app
# working path for application inside container

COPY src/html /usr/share/nginx/html
# copy the files for html from our working directory to the directory that

CMD [ "nginx", "-g", "daemon off;"]
# exec form