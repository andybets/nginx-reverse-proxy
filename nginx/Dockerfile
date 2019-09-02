FROM nginx:1.11.3

RUN rm /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/
RUN rm /etc/nginx/conf.d/default.conf

# for non-SSL server
COPY site.conf /etc/nginx/conf.d/