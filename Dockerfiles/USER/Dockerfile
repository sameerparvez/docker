FROM almalinux:9
RUN dnf install nginx -y
RUN useradd sameer
USER sameer
CMD ["nginx", "-g", "daemon off;"]