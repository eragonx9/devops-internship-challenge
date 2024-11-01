FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf
COPY ./html /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]




#Issues:

#Correct EXPOSE "80" to EXPOSE 80.
#Typo in the CMD statement (daemon of; should be daemon off;).
#htmll->html
#nginix->nginx
#latests->latest