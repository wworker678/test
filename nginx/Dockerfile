FROM nginx:latest

RUN rm /etc/nginx/nginx.conf

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 8000

# Запускаем Nginx
CMD ["nginx", "-g", "daemon off;"]