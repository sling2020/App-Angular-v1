FROM nginx:alpine
RUN rm -rf /usr/share/nginx/html/*
COPY app1/browser /usr/share/nginx/html 
EXPOSE  4200
COPY nginx.conf /etc/nginx/nginx.conf
CMD ["nginx", "-g", "daemon off;"]