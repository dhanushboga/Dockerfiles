FROM almalinux:9
RUN dnf install nginx -y

#there is no functionality for expose
EXPOSE 80
CMD ["nginx","-g","daemon off;"]