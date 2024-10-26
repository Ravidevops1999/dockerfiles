FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Ravidevops1999/Ansible/refs/heads/main/vars_file.yaml /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]