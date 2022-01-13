FROM nginx:alpine
WORKDIR /app/staticwebsite
RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx
COPY ./staticwebsite /app/staticwebsite
EXPOSE 80

