FROM nginx:latest
#latests->latest
COPY nginx.conf /etc/nginx/nginx.conf
#nginix->nginx
COPY ./html /usr/share/nginx/html
#htmll->html
EXPOSE "80" 
# error 1 (80 -eighty)
CMD ["nginx", "-g", "daemon of;"]
