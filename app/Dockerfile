FROM nginx:latest
LABEL MAINTAINER="<raphael.pessoa@aluno.faculdadeimpacta.com.br>"
COPY index.html /usr/share/nginx/html/
EXPOSE 80
ENTRYPOINT ["nginx", "-g", "daemon off;"]
FROM nginx:alpine

ADD app.gz /usr/share/nginx/html/

CMD ["nginx", "-g", "daemon off;"]
