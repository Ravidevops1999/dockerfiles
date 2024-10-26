FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/Ravidevops1999/Ansible/refs/heads/main/vars_file.yaml /usr/share/nginx/html/index.html
RUN chmod +r index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]