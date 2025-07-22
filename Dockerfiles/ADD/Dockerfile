FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/ansible-roboshop-roles/refs/heads/main/inventory.ini /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]