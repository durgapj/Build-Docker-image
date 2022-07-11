FROM nginx
LABEL "project"="vprofile"
LABEL  "author"="durgapj"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vproapp.conf
