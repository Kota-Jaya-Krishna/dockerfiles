FROM almalinux:9
CMD ["ping", "google.com"]
RUN dnf install nginx -y
CMD ["nginx", "-g", "daemon off;"]